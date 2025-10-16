---
title: Top Ten
description: Eleventh Update of Alternative Formula E Points Format project.
date: 2025-09-23
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Top Ten</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my tenth update to my Alternative Formula E Points Format project. There are some changes to the code of the afepf_functions.py file which improve the user experience from an admin point of view. The results of Formula E's Season 5 have been inputted and this season was highly competitive as we had the most drivers so far eligible to take the title at 3 (technically 4, but one is mathematically eliminated after qualifying) and at one point, the entire top 10 in the standings were within 20 points. Things are only going to get closer from here on out.<br />
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    Jean-Eric Vergne defends his title both in real life and under the alternative points format with points totals of 136 and 139 respectively. There is however, a change in who finishes 2nd as in real life it is Sebastien Buemi but under the alternative points format it is Mitch Evans instead. Sebastien scores 119 points finish 2nd in real life (122 points under the alternative points format to finish 4th), while Mitch finishes with 125 under alternative points format to come 2nd in the standings (105 points in real life to finish 5th) In fact Sebastien is eliminated from title contention after the final qualifying session as despite the domination in qualifying that the twin-motor design Nissan uses in its powertrain gives him he qualifies 3rd.<br/>
    No driver scores less points under the alternative format compared to real life, with ones who tie with their real life total being Felipe Nasr and Felix Rosenqvist as neither finish inside the points and have combined 1 classified finish (Felipe's 19th place in Mexico City). The driver who gains the most points compared to their real life total is Oliver Turvey, whose consistency nets him 41 points compared to his real life total of 7, thus giving him an difference of 34.<br/>
    The drivers who gained the most positions compared to their final standings under the current format are Mitch Evans and Oliver Turvey, as both gain 3 places to finish 2nd and 17th respectively under my alternate format with 125 and 41 points respectively compared to 5th and 20th respectively and with points totals of 105 and 7 respectively. The drivers who loses the most positions compared to where they finished under Formula E's current format are Robin Frijns, Max Guenther and Alex Lynn who all fall 3 places to standings finishes of 7th, 20th and 21st respectively; scoring points totals of 112, 29 and 21 respectively. This compares to real life where Robin finishes 4th with 106 points, Max finishes 17th with 10 points and Alex finishes 18th with 7 points. In the defence of Max and Alex, both miss multiple races (or half the season in Alex's case) while Robin either finishes inside top 5 (4 of which are podiums) or outside the top 10 (3 of which are 0 points-scoring races). We do have a new winner for the lowest classified finisher, as Sebastien Buemi takes the unenviable record with a 21st finish in the Mexico City ePrix, but he finishes 1 lap down as Nissan got the energy calculations wrong (not for the last time either) and so both of their drivers fail to finish the last lap. However, do not worry Stephane Sarrazin fans as while this season's Berlin ePrix sees only 2 retirements, Jose Maria Lopez is 46.895 seconds off the winner (Lucas Di Grassi) so your driver still finisher further behind the leader as Stephane was 1 minute and 6.954 seconds off the winner (Daniel Abt) in season 4's Berlin ePrix.<br/>
    Below are the overall Drivers' Championship standings:
    </p>
    {% image "./afepf5_drivers_p1-9.png", "Screenshot of the first 9 positions of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf5_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf5_drivers_p19-25.png", "Screenshot of the positions 19 to 25 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Trophy for Drivers</h3>
    <p class="col-8">
    The championship is won by Sam Bird who beats his teammate Robin Frijns 213 points to 196. The 2 start the season off trading 1st and 2nd places, but by the Paris ePrix (Round 8), a retirement for Sam and finishes behind Robin, allows Robin to pull a 24 point gap on him only for the same things to befall Robin, which gives him the break he needs to tie Robin going into the New York finale. There, Robin retires from the first New York City ePrix and gives Sam the advantage that Robin cannot overcome. The HWA Racelab drivers are irrelevant for the title fight as their unreliable start and general lack of pace puts them in too big of a hole to even think of recovering.<br/>
    Below are the Customer Trophy for Drivers standings:
    </p>
    {% image "./afepf5_customer_drivers_p1-4.png", "Screenshot of the Customer Trophy for Drivers, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    This is the most competitive Nelson Piquet Jr Trophy so far and probably of all time as only Season 7 is next season with anywhere close to this depth of talent. Oliver Rowland wins the class with 154 points from Felipe Massa, who scores 150 points. Felipe holds the lead going into the final round by 4 points,but his worst classified finish allows Oliver to come from behind and win the championship by 4 points. Oliver Rowland’s 3 DNFs ties him with Robin Frijns for most DNFs in a trophy-winning season (as of the end of Season 5, there could be more DNFs from NPJT champions in later seasons), but Robin’s nearest competition technically tied with him in terms of DNFs as Mike Conway missed the first 3 races. Whereas Felipe started all the races this year and has less DNFs at 2, while the previous 2 trophy-winning campaigns have combined total of 1 DNF (0 for Felix Rosenqvist and 1 for Mitch Evans).<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% image "./afepf5_npjt_drivers_p1-9.png", "Screenshot of the first 10 positions of the Nelson Piquet Jr Trophy, outputted by afepf_viewer_program.py" %}
    {% image "./afepf5_npjt_drivers_p10.png", "Screenshot of position 11 of the Nelson Piquet Jr Trophy, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    Audi Sport Abt Schaeffler win this championship with 234 points from DS Techeetah in 2nd, who finishes with 226 points. This is a change from real life as Techeetah win the overall Teams’ championship from Abt. The biggest factor in this change is that positions outside the podium places pay more under the alternative format and Techeetah scored the most podiums at 7, but only have both cars finish inside the top 10 5 times. Conversely, Abt has both cars finish in the top 10 7 times, but only score 5 podiums. All teams score more points under the alternative format as highly competitive nature of the season (brought by the pseudo-reverse qualifying format this and the next 2 seasons have) mean that most teams have races in which neither car can’t crack the top 10 despite the results results of earlier races suggesting that they should have both in the top 10. There are no other differences of position between the standings of the two points formats.<br/>
    Below are the overall Teams' Championship standings:
    </p>
    {% image "./afepf5_teams_p1-6.png", "Screenshot of the first 6 positions of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf5_teams_p7-11.png", "Screenshot of the positions 7 to 11 of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Teams' Championship </h3>
    <p class="col-8">
    Envision Virgin Racing dominate the championship, leading the standings after every single race and scoring 249 points to HWA Racelab’s 186 points. To HWA’s credit, after their dismal start that sees them have both cars retire in 2 of the first 6 races, they bounce back to take 3 class wins in the next 6 races which includes a class 1-2 in Monaco. The only problem is that Virgin win those first 6 races, of which all are class 1-2 finishes, as well as 4 more class wins in the last 7 races so they seal the title with 3 rounds to go. Admittedly, this season’s Customer Team’s Championship is a bit farcical as the performance gap between the 2 customer teams’ powertrains (Audi for Virgin and Venturi for HWA) means that HWA’s wins are more of a failure on Virgin’s part than a success on HWA’s part.<br/>
    Below are the Customer Teams' Championship standings:
    </p>
    {% image "./afepf5_customer_teams_p1-2.png", "Screenshot of the Customer Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Audi win this championship for a 2nd consecutive time over DS Automobiles for 2nd consecutive time, with a points total of 264 points for Audi and 259 points for DS. DS actually leads this championship going into the final race and while both manufacturers have cars that crash out of the race, Audi’s driver at least has the decency to do it late in the race so they are still classified at the end and can still earn manufacturer points and thus overcomes the deficit. As Formula E did not come up with a manufacturer championship until part-way through Season 10, there was no Manufacturer Championship to compare this to, but hypothetically if there was one, then Audi would also win that one as well over DS. Audi would score 315 points to DS’s 219 points and would seal the title 2 rounds early and are the only manufacturer who doesn’t outscore their hypothetical real life points total with their points total with the alternative format. There are differences of position between the standings as in hypothetical real life, Venturi finishes ahead of Mahindra and Jaguar instead of behind them (5th in hypothetical real life and 7th under the alternative format); while Penske and Nio swap places, so Penske finishes last under the alternative format and Nio does the same in hypothetical real life.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% image "./afepf5_manufacturers_p1-9.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The improvements to the user experience stated in the introduction are that the program checks if the initial you entered to add results for does exist in the collection and will not iterate further if it is not in there. Also, the program requires you to enter how many classified finishers led a lap, so it will no longer ask if a classified finisher led a lap or not. However, if you provide a string input when an integer is allowed, an error will still occur and the program will immediately end. The functions previously known as checkDriver, checkTeam, check Manufacturer all now have 'Champ' attached to the end to distinguish them from the new functions that now carry their old names.<br/>
    Below are screenshots of the new check functions and the implementation of checkDriver in the updateDriverResult function with the new lines highlighted in blue.
    </p>
    {% image "./afepf_functions_checkDriver_checkTeam_checkManufacturer.png", "Screenshot of the check Driver, check Team, check Manufacturer functions in afepf_functions.py which checks the driver, team, and manufacturer collections respectively to see if the value stored in initial is also stored in the collection and return boolean value of True if yes" %}
    {% image "./afepf_functions_updateDriverResult.png", "Screenshot of the updateDriverResult function in afepf_functions.py, which now:  asks for the number of classified finishes that led a lap so it asks about it that many times and checks if the value inputted for init is in the Driver collection and will not iterate any further if it is not" %}
  </div>
</div>