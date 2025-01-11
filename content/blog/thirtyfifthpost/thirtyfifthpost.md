---
title: Podium Ceremony
description: Fourth Update of Alternative Formula E Points Format project.
date: 2025-01-07
draft: true
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Podium Ceremony</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my fourth update to my Alternative Formula E Points Format project. I have made a few quality of life improvements with update results functions and have the results of 2023/2024 (Season 10) season of Formula E using the BTCC points format along with the extra championships that the BTCC has. Having watched all of the races to keep track of who leads which lap, I think a great alteration to Formula E current points format would to be award points for leading laps. Formula E had considered something similar, as for this season the had thought of introducing a '<a href="https://www.the-race.com/formula-e/formula-e-golden-lap-plan-race-format-points/">Golden Lap</a>', where if you lead 2 specific laps that are randomly decided earlier before the ePrix, you earn bonus points. This was met with negativity from those with in the Formula E paddock and was swiftly <a href="https://www.the-race.com/formula-e/formula-e-bins-golden-lap-format-after-backlash/">dropped.</a>This is a good thing as I consider it to be a woeful idea that should have been immediately dismissed and never left the room it was discussed in, so it couldn't been leaked out to the media. Returning to earlier point about rewarding lap leading, I think drivers should score 1 point for each lap they lead, with drivers being able to score a maximium of 3 points this way. This create an incentive for the drivers to lead laps, with the limit preventing from those who dominate the harder-to-pass races, such as Tokyo or London, from scoring a lot of points. <br />
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    Under the Formula E's current point format, Pascal Wehrlein wins the title with 198 points; 6 points more than Mitch Evans who finishes 2nd with 192 points. My alternate format also has Pascal winning the title from Mitch, but with more points and a smaller gap back to Mitch in 2nd as Pascal has 202 points, while Mitch has 200. The difference between the 2 comes down to finishes as both have the same amount of bonus points, as Pascal has 3 pole positions and led a lap in 10 races, while Mitch also 3 pole positions and has a fastest lap but only led a lap in 9 races.<br/>
    Every driver bar 1 scores more points under my format than under the current format, with the biggest gainer, in terms of points being Stoffel Vandoorne, scoring 48 more points under the alternate format than he did with the current format. The driver who didn't beat their points total under my alternate format is Caio Collet, as his 2 finishes in Portland are outside the top 15 and he fails to score any bonus points, so he matches his total from under the current format. <br/>
    The driver who gained the most positions compared to their final standings under the current format is Lucas Di Grassi who gains 5 places to finish 18th under my alternate format with 47 points, as compared to 23rd with 4 points which is where he finishes under the current points format. The driver who loses the most positions compared to where they finished under Formula E's current format is Sam Bird, who falls from a 13th position in the standings with 48 points, to a 16th position in the standings with 61 points under my alternate format. <br/>
    Below is the Overall Driver Championship Standings:
    </p>
    {% image "./afepf_drivers_p1-10.png", "Screenshot of the first 10 positions of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf_drivers_p11-20.png", "Screenshot of the positions 11 to 20 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf_drivers_p21-28.png", "Screenshot of the positions 21 to 28 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Trophy for Drivers</h3>
    <p class="col-8">
    Jake Dennis handily wins this championship, sealing it with a round to spare and leads the championship from round 2, the first of the 2 Diriyah ePrixs. His teammate Norman Nato finishes 2nd, despite only winning the class once, in Monaco, he was always classified at the end of an ePrix, so always scored points. As there can only be 8 competitors in this class, finsihing and scoring points is crucial, so Norman can finish ahead of Sebastien Buemi and Robin Frijns in the Customer Trophy, despite scoring less points in overall Drivers' Championship. Another example is Sam Bird, who finishes 8th, so far off everyone else, because he failed score points 9 times, which are: 3 missed races due to injury, 5 retirements and 1 non-classified finish.<br/>
    Below is the Standings for the Customer Trophy for Drivers:
    </p>
    {% image "./afepf_customer_drivers_p1-10.png", "Screenshot of the first 10 positions of the Customer Trophy for Drivers, outputted by afepf_viewer_program.py" %}
    {% image "./afepf_customer_drivers_p11-12.png", "Screenshot of positions 11 and 12 of the Customer Trophy for Drivers, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    Sacha Fenestraz wins this championship with a round to go, thanks to strong results and a lack of non-scores with only Dan Ticktum has less non-scores than Sacha. A driver you would have expected to be winning this based on their overall points total would be Jake Hughes, however he has the joint worst non-score record in the class. This combined with some poor results means he falls to 3rd in the championship despite looking to be in a comfortable 2nd for most of the season.<br/>
    If we were to account for running this championship in earlier seasons, then we would have to remove Dan Ticktum from this championship as he would be the season 9 Nelson Piquet Jr Trophy champion. The top three don't change and everyone below Dan in the standings (bar Caio Collet, Jordan King, Kelvin van der Linde and Paul Aron) move up a place in the standings, with Caio moving up 2 to 6th, Jordan moving up 2 to 8th and Paul staying in 9th. Only Paul and Kelvin don't gain any points from Dan's exclusion as they always finished ahead of him.<br/>
    Below is the Standings for the Nelson Piquet Jr Trophy:
    </p>
    {% image "./afepf_npjt_drivers_p1-10.png", "Screenshot of the first 10 positions of the Nelson Piquet Jr Trophy, outputted by afepf_viewer_program.py" %}
    {% image "./afepf_npjt_drivers_p11.png", "Screenshot of position 11 of the Nelson Piquet Jr Trophy, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The Qualtiy of life improvements stated in the introduction are that the points for finishing position are now calculated by the program itself, so the user does not need to input the points totals for each competitor, only now having to confirm how many retirements/non-classified finishes the were from the ePrix and whether or not a team/manufacturer car retired or customer/Nelson Piquet Jr Trophy driver retired. I tried to have the program at least calculate most of the championship position changes, but Cursor objects don't seem to be ordered and any form of manipulation seemingly empties them. If you do know how I could do this, please do let me know via the Contact page on my website: <a href="https://main--toby-culverwell-01.netlify.app/contact/">here.</a> The operation option menu on the admin program now takes number input instead of text to speed up the process of selecting an operation.
    </p>
  </div>
</div>