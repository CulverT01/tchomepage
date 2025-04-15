---
title: Podium Ceremony
description: Fourth Update of Alternative Formula E Points Format project.
date: 2025-01-07
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
    This is my sixth update to my Alternative Formula E Points Format project. The program is now built to handle seasons which don't have 22 starters and don't include a manufacturers championship and now has all the of the results for Season 1 (2014-2015) of Formula E. The quirk with Season 1 in real life is that this allowed for dropped scores, where a driver's worst scoring result would be ignored towards their end of season totals;  e.g: if a driver's worst scoring round resulted in a 10th place finish and thus 1 point, then that point would be ignored towards their end of season total. Only 1 driver is affected by dropped scores as only one driver scored points in all races and that Nicolas Prost, as while he wouldn't finish race 1, he did win the pole and scored 3 points because of this. I elected to ignore this as the BTCC points format then in 2014/15 and now do not include dropped scoring as well as all future Formula E seasons.<br/> 
    Also with regards to Seasons 2 (2015-2016) and 3 (2016-2017), the drivers eligible for the Nelson Piquet Jr Trophy will be 'rookie drivers' which are drivers who have never started an ePrix, as the modern (and technically current version at the time of writing) interpretation doesn't begin until 2018, so will apply for Season 4 (2017-2018) as it follows with what I have done with regards to the 2025 interpretation. The Jack Sears Trophy (the championship th Nelson Piquet Jr Trophy is based on) in 2014 was awarded to the Independent driver (which was all drivers on the 2014 grid bar 4) who made the most positions from their starting position across all races, with the winner being Dave Newsham who never once made up the most places across a meeting, but only in one meeting did he failed to make any places across the races.<br />
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Drivers' Championship</h3>
    <p class="col-8"> 
    The inaugural champion of Formula E is Nelson Piquet Jr and he remains so under the alternative format, with him scoring 144 points in real life and 148 points under the alternative format. He ends up with a bigger winning margin under the alternative format (14) than real life (1) as Sebastien Buemi's finishes give him 134 points under the alternative format and 143 under format at the time. Sebastien is one of 4 drivers who score less under the alternative format than in real life, with others being Sam Bird, Franck Montagny, and Takuma Sato. Franck only point scoring finish is a 2nd place with no bonus points and the BTCC awards 17 points for 2nd place finish while Formula E awards 18. Takuma has less points as he set the fastest lap in his only race, from which he retired, and until end of Season 3 (2016-2017), you could still score the fastest lap point even if didn't finish in the top 10. Sebastien and Sam have to chalk their lost points to retirements, as they do not finish more than those around them with it being even more painful for Sebastien as he scores 9 less under the alternative format. 2 drivers match their points totals, these being Sakon Yamamoto (he retires from his 2 races) and Lucas Di Grassi, who would've won the championship under both formats if his front wing was legal in th Berlin ePrix. The Driver who gains the most points under the alternative format is Nick Heidfeld, who scores 33 more points compared what he scored in real life. <br/>
    The drivers who gained the most positions compared to their final standings under the then format is Nick Heidfeld, Jaime Alguersuari, and Salvador Duran, who all gains 3 places to finish 9th, 10th, and 18th respectively under my alternate format with 64, 57, and 24 points respectively, as compared to 12th, 13th, and 21st respectively, (with 31, 30, and 31 points respectively) which is where they finish under the then format. The driver who loses the most positions compared to where they finished under Formula E's current format is Takuma Sato, who falls from a 24th position in the standings with 2 points, to a 34th position in the standings with 0 points under my alternate format. However, Takuma only competes in 1 race, so of the full time competitors, it is Bruno Senna, who goes from 10th to 14th despite scoring more points under the alternative format.<br/>
    Below are the Drivers' Championship standings:
    </p>
    {% image "./afepf1_drivers_p1-9.png", "Screenshot of the first 9 positions of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf1_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf1_drivers_p19-27.png", "Screenshot of the positions 19 to 27 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf1_drivers_p28-35.png", "Screenshot of the positions 28 to 35 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Teams' Championship</h3>
    <p class="col-8">
    Team e.dams Renault wins this championship with 230 points from Dragon Racing who have 211 points. Only e.dams fail to score more than they did in real life, but even then the difference is minimal as it only 2 points. There is a change of positions in the final standings under my alternate points format compared to the used format as Venturi finish ahead of both Aguri and Mahindra, thanks to its full time drivers being consistently finishing inside the points. Only 4 times under the alternative format does a Venturi car fail to finish inside the points and the team never fail to score points which is something other 2 teams can claim.<br/>
    Below are the Teams' Championship standings:
    </p>
    {% image "./afepf1_teams_p1-6.png", "Screenshot of the first 6 positions of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf1_teams_p7-10.png", "Screenshot of the positions 7 to 10 of the Teams' Championship, outputted by afepf_viewer_program.py" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The changes made mean that the update results functions only run up to the number entrants (drivers, teams and manufacturers are asked separately) for an ePrix, which the user is asked for before they can input any results. Also, as Season 1 only has 1 powertrain supplier, there is no manufacturer championship, so the code to call functions relating to manufacturers are nestled in an if statement that checks if the variable 'season' in lower case is not equal to "season 1". If 'season' does not and thus equal to "season 1", then the function is not called and if it is and thus not equal to "season 1" then the function is called. Other championships, such as Customer championships and NPJT championship, that don't factor in a season are left alone, as they would just output some whitespace and continue along the program as normal.
    </p>
  </div>
</div>