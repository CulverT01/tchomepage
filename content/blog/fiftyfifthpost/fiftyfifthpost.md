---
title: Eyes 4ward
description: Ninth Update of Alternative Formula E Points Format project.
date: 2025-09-09
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Eyes 4ward</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my tenth update to my Alternative Formula E Points Format project. There no real changes to talk about (both programming and implementation-wise), but in real life there was a change to for the eligibility for Jack Sears Trophy (Nelson Piquet Jr Trophy under my alternative format). Rather than be a rookie driver (competed in 0 races) at the start of the season, to be eligible you need to have not scored a podium 'on the road', so if you have podium finish but it has come from another driver/s getting a post-race penalty or disqualification, then that does not affect your eligibility. Also winning the trophy itself makes you ineligible for any future seasons. For example, Mitch Evans' sole podium (as of the end of season 4) comes from Daniel Abt being disqualified post-race from the 2nd Honk Kong ePrix of season 4, so assuming he does not win the trophy in season 4, he would still be eligible for the trophy in season 5. He is also not only driver that would probably count this way, as Loic Duval's 2 career podiums come from post-race penalties/disqualifications, although the fact he has multiple podiums might make him ineligible anyway.<br/>
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    The champion of Season 4 is Jean-Eric Vergne and achieves the same under the alternative format, with a consistency that seems him never DNF and finish once outside the top 5. Jean-Eric scores 184 points under the alternative format compared to the 198 he does in real life. 2nd place goes to Sam Bird, who scores 151 points under the alternative format compared to 143 in real life and is good enough that title goes down to the final race, whereas in real life Jean-Eric has the title sewn up by the end of the first New York City ePrix. Lucas Di Grassi does not snatch 2nd from Sam but still finishes 3rd with 140 points under the alternative points format compared to 144 points in real life.<br/>
    Only 3 drivers scores less or equal points with the alternative format compared to real life and they are Jean-Eric Vergne, Lucas Di Grassi and Neel Jani. Jean-Eric and Lucas's lost points are once again attributed to the Formula E points format at the time awarding more points for 1st and 2nd, which they finish a lot in, while Neel Jani ties his points total as his 2 finishes are both sub 15th place finishes and scores 0 points under both formats. The Driver who gains the most points under the alternative format is Antonio Felix Da Costa, who scores 40 more points compared what he scored in real life - 60 points under the alternative format compared to 20 in real life. Antonio has seemingly inherited the consistency trait that his last season teammate had, as he fails to finish once and finishes inside the top 15 in all other races.<br/>
    The drivers who gained the most positions compared to their final standings in real life are: Antonio Felix da Costa, Nicolas Prost, and Luca Filippi, who all gain 2 places to finish 13th, 17th, and 19th respectively under my alternate format as opposed to 15th, 19th, and 21nd in real life. Their points totals under the alternative format are: 60, 40, and 19 respectively whereas their points totals in real life are: 20, 8, and 1 respectively. The drivers who loses the most positions compared to where they finished under Formula E's current format are Edoardo Mortara and Tom Dillmann, who both fall 2 places to finish 15th and 20th respectively under the alternative format compared to 13th and 18th in real life. Their points total under the alternative format are 48 and 16 respectively, which compares to their real life points totals of 29 and 12 respectively. Edoardo misses races due to commitments in other race series (DTM), while Tom only does 3 races, deputising for Edoardo. This season also sees the first race with no retirements or post-race disqualifications, as the Berlin ePrix of this season sees all 20 cars make the finish and Stephane takes the dubious honour of driver with lowest classified finish of 20th (for now).<br/>
    Below are the Overall Drivers' Championship standings:
    </p>
    {% image "./afepf4_drivers_p1-9.png", "Screenshot of the first 9 positions of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf4_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf4_drivers_p19-25.png", "Screenshot of the positions 19 to 25 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    This Nelson Piquet Jr Trophy Championship is one of the most competitive ever as Year 2 driver Mitch Evans wins the championship with 178 points and seals it in the final race. 2nd place is Andre Lotterer, who comes back after poor start to the season to score 156 points. The championship probably would have been closer, if long-time trophy rival Edoardo Mortara didn't need to skip 3 races due to DTM commitments and the driver who took over 2nd place in the standings, Oliver Turvey, didn't hurt his hand in a practice crash before the first New York City ePrix. That said, the championship probably would have not been closer, if Mitch Evans didn't retire from the first New York City ePrix.<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% image "./afepf4_npjt_drivers_p1-9.png", "Screenshot of the first 9 positions of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    {% image "./afepf4_npjt_drivers_p10-12.png", "Screenshot of the positions 10 to 12 of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    Techeetah wins this championship with 263 points from Audi Sport ABT Schaeffler who have 250 points. Only Audi Sport ABT Schaeffler fail to score more than they did in real life (264 in real life) and they also win the title in real life, whereas under the alternative format they obviously don't. There is another a change of positions in the final standings under my alternate points format compared to real life as Mahindra finish behind Renault e.Dams and Jaguar Racing. Andretti still finish last, but come 1 point short and finish where they do due to lack of high finishes their rivals had, as they are the only team not score a podium.<br/>
    Below are the Teams' Championship standings:
    </p>
    {% image "./afepf4_teams_p1-5.png", "Screenshot of the first 5 position of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf4_teams_p6-10.png", "Screenshot of positions 6 to 10 of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Audi wins the cup in their first season that they build the powertrain with 275 points from DS Automobiles, who has 217 points. There wasn't a manufacturer's cup back in season 4, but if there were, Renault would win again for the 3rd time with 326 points from Audi, who would have 256 points. Renault's victory is down to the performances of Jean-Eric Vergne and Sebastien Buemi, while a resurgent Audi the 2nd half of the season, the poor performance of Nicolas Prost, and the slow start of Andre Lotterer all contribute to a smaller advantage. Renault would end up finishing 3rd under the alternative format and the only other change of position is Andretti bettering Penske to finish 8th. They tie on points with NIO, but lose out courtesy of Oliver Turvey's 2nd place in Mexico City.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% image "./afepf4_manufacturers_p1-9.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
</div>