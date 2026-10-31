---
title: Formula for VictorE
description: Python programming project designed to formulate the ideal drivers to nominate to score points for a manufacturer under the Alternative Formula E points format.
date: 2026-09-29
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - object orientated programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Formula for VictorE</h1>
  <div class="row justify-content-center">
    <h2 class="row">Introduction</h2>
    <p class="col-8">
    Apologies, it has been awhile as I have been working on this small project and entering the data, which takes time (I have not finished that yet but will do in the upcoming weeks). As stated in my review of race 2 of 2026 Hankook London ePrix, Stellantis' domination of the Manufacturers' Cup in Gen 3 made me decide to implement a formula of some kind to calculate who is ideal for the upcoming race and likely to score big points in said race.<br/> 
    The Manufacturer Nomination formula calculates a score based on an average of 5 numbers: a driver's average finish at the upcoming track, their current points standing (under the alternative format), average finish in the manufacturer class, their starting position for the upcoming race, and their previous race finish, and weight is given to latter 3 by doubling those numbers. The latter 3 are weighted as they are the most important stats for scoring points as: average finish in the manufacturer class likely indicates whether or not that driver could score big points for the manufacturer based on how they have run this season, starting position matters as the tight confines of some Formula E tracks means progress from the back is difficult, and previous finish suggests what the recent record has been. The other 2, while important are often more easily swayed by outside forces as average finish at a track is only as good as the number of starts made (Taylor Barnard is supposedly a guaranteed podium Jeddah based off of Season 11, but he finished 10th in both races in Season 12) and points standings can be influenced by 1 really great result compared the rest being fairly terrible results (think Season 5-6 Max Guenther, whose only top 10 finishes were top 5s and he had 5 from 21 starts). The lowest 2 scores are determine which drivers would be nominated.<br/>
    So for example: for race 1 of 2026 Berlin ePrix, Nick Cassidy's formula score would be 15.112 (average track finish = 8.9, points standing = 9, average manufacturer finish = 6.83, starting position = 5, previous finish = 17), Jean-Eric Vergne's score would be 19.754 (average track finish = 7.43, points standing = 15, average manufacturer finish = 8.17, starting position = 16, previous finish = 14), Max Guenther's score would be 18.976 (average track finish = 14.88, points standing = 14, average manufacturer finish = 9, starting position = 11, previous finish = 13), and Taylor Barnard's score would be 18.8 (average track finish = 7, points standing = 12, average manufacturer finish = 8.5, starting position = 10, previous finish = 19). The 2 nominated would be Nick and Taylor which would net Stellantis 27 points.<br/>
    As always, the entire project is available at this GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a>, although please do note that the username and password for the database have been removed as a means of security.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Implementation</h2>
    <h3 class="row">Main program</h3>
    <p class="col-8"> 
    The project uses 2 files: manufacturer_points_nomination_formula.py and mpnf_functions.py, with the former acting as the main program and the other as a function library. When one runs manufacturer_points_nomination_formula.py, you are asked which Season you want (Season 9, 10, 11, 12, or 13, although please do note Season 13 will not work until all seats are confirmed for Season 13) and connects to the appropriate database and the ManufacturerFormula collection then asked which race number of the season they wish to calculate the formula for. That race number has its value reduced by 1 so it can act as a reference to the position in a list as the data stored in the database are in arrays (with the exception of a driver's initial).<br/>
    Below is screenshot of manufacturer_points_nomination_formula.py's code
    </p>
    {% image "manufacturer_points_nomination_formula.png", "Screenshot of the main program which users use to run the to find out the which drivers should be nominated to score manufacturer points" %}
    <h3 class="row">Driver Class</h3>
    <p class="col-8"> 
    To store the data and keep it organised, a class is used. While a normal list could have been used as Python allows for lists to contain different datatypes, I have never programmed using classes in Python before so I learn something new that I can use in future projects. Another advantage of classes is the fact they can have in-built methods so the actual nomination formula can easily accessed and I don't have to make a function that does the same thing to 4 different lists. However, improvements could be made by working out how to implement getters and setters for classes in Python (assuming this is possible) would help with regards to later functions<br/>
    Below is screenshot from mpnf_functions.py, showing the code for the Driver class.
    </p>
    {% image "mpnf_functions_driver_class.png", "Screenshot of the Driver class from mpnf_functions.py file" %}
    <h3 class="row">Collect Functions</h3>
    <p class="col-8">
    The collect functions get the values from stored in certain fields within the documents of already specified collection and stores them inside a list. For example, the CollectPtsStandings function will query the ManufacturerFormula collection in a selected database retrieving all values stored in the Driver_Points_Standing field and storing those in a list via a for loop. That list is returned by the function to be used in the CreateDriver function. There are another 2 key points to mention regarding these functions: CollectAveMnfctrFin and the commented code. The CollectAveMnfctrFin function has to do a bit more as the data stored in the Driver_Manufacturer_Finish field is an array of integers, which are the the finish within the manufacturer class a driver has had that season. The function still queries the collection as the Collect functions, then calculates the average for the values stored in each individual list within the range of the value stored in the raceNo variable which has passed from the main program. So if raceNo is 5, it will add up all the values stored in positions 0-4, then divide the total by 5 and store that result as the average manufacturer finish. As for the commented-out code, when building this program, it was done so on the assumption that Porsche would also be fielding 4 manufacturer entries, although that has since <a href="https://fenotebook.com/2026/09/18/revealed-porsche-pivot-on-second-team-plan/">changed</a>. Still the program needed some way of switching between manufacturers so the SelectManufacturer function needed to exist however, its inclusion needlessly complicates the program and is only kept in case it is needed in the future.
    <br/>
    Below are screenshots from mpnf_functions.py, showing the code for the 4 Collect functions.
    </p>
    {% image "mpnf_functions_collect_functions_1.png", "Screenshot of the first 2 Collect functions that get the data from the MongoDB collection, specifically driver initials and their point standings for an upcoming race" %}
    {% image "mpnf_functions_collect_functions_2.png", "Screenshot of the second 2 Collect functions that get the data from the MongoDB collection, specifically driver's average finish at a track and their average finish in the manufacturer class" %}
    <h3 class="row">CreateDriver and FormulaSort functions</h3>
    <p class="col-8"> 
    The CreateDriver function calls the the Collect functions and then runs a while loop while x (which is initially 0) is less than the number of documents in a collection (or the number of documents that have certain values stored in the manufacturer field). In this while loop, the user is asked or the previous finish and starting position as these values are not stored in the database as these values either change on a race to race basis or are not known until the program is needed and it would needlessly complicate the program to implement a way to enter data into the collections. Then the program creates 4 new objects of the Driver class, with the values for points standing and average track finish being the item in position 'raceNo' from the list in position 'x' in the list returned from their respective Collect functions. When the loop is finished, the program calls the DriverSort function.<br/>
    The DriverSort function has the 4 Driver objects call their Formula function and then puts the values inside a list and then sorts them - smallest to biggest. The program then checks if either of the first 2 items of the newly sorted list are the value returned by the first Driver object's Formula function and outputs a confirmation if it is. This is done for the over 3 values returned by the other 3 Driver objects.
    <br/>
    Below are screenshots from mpnf_functions.py, showing the code for the CreateDriver and FormulaSort functions.
    </p>
    {% image "mpnf_functions_createdriver_formulasort.png", "Screenshot of the Create Driver and Formula Sort functions, which gathers the data collected from the collect functions and enters them 4 new Driver objects; before calling the Formula method for all 4 Driver objects, storing returned values in a list, sorting said list and outputting the 2 lowest scores." %}
    <h3 class="row">Output</h3>
    <p class="col-8"> 
    This is the output a user would see when using this program, using the example I gave in the introduction (race 1 of 2026 Berlin ePrix).
    </p>
    {% image "mpnf_output.png", "Screenshot of the output of manufacturer points nomination formula program, using the data needed to calculate which drivers would need to be nominated according to the program for race 1 of 2026 Berlin ePrix" %}
  </div>
</div>