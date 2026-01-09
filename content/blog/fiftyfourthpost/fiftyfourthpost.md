---
title: 3 Steps of the Podium
description: Ninth Update of Alternative Formula E Points Format project.
date: 2025-08-26
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">3 Steps of the Podium</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my ninth update to my Alternative Formula E Points Format project. There no real changes to talk about (both programming and implementation-wise), but in real life there was a change to the bonus points for fastest lap which would now award 1 point as opposed to the 2 it had been previously. The eligibility for this point would change for next season, as no driver on the lead lap would score the bonus point for the fastest lap. This isn't true for the standings below, as the BTCC points system (then and now) only awards the fastest lap point to the driver with the fastest lap amongst those who finished, so for the Monaco ePrix and the final 6 races, someone else scores the bonus point for fastest lap instead of the driver who did in real life. For example, Sebastien Buemi scores the fastest lap in the 2nd Berlin Race (en-route to a victory in which he leads no laps), instead of the actual scorer: Maro Engel.<br/>
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    The champion of Season 3 is Lucas Di Grassi and achieves the same under the alternative format, although he wins 1 round earlier at the conclusion. Lucas Di Grassi scores 172 points under the alternative format compared to the 181 he does in real life. 2nd place still goes to Sebastien Buemi, who scores 136 points under the alternative format compared to 157 in real life. Sebastien wins half of the races in the season but they are his only top 10 finishes all season as: he is disqualified twice (Berlin race 1 and Montreal race 1), misses New York City ePrix due more important commitments with Toyota in the World Endurance Championship, finishes 14th in Mexico City and finishes 11th in he 2nd Montreal race. Replace the 2 disqualifications with the points he would have earned (5th and 4th respectively, with no bonus points) and he still loses the championship, but delays losing the championship lead by 1 race and takes the fight to the final race of the season.<br/>
    Only 4 drivers scores less or equal points with the alternative format compared to real life and they are are 2 title protagonists (Lucas Di Grassi and Sebastien Buemi), Loic Duval, and Alex Lynn. Alex's only points come from his pole in the first New York City race and as the BTCC awards less for pole, he scores less points. Whereas for Loic Duval, the pace in the Dragon car is not there, except for 2 races where he scores a 5th and 6th which equate to 75% of his points total. The Driver who gains the most points under the alternative format is Robin Frijns, who scores 38 more points compared what he scored in real life - 62 points under the alternative format compared to 24 in real life. Robin finishes every race and fails to score points twice under the alternative format, despite finishing no higher than 6th and scoring double digit points totals twice.<br/>
    The drivers who gained the most positions compared to their final standings in real life are: Jerome d'Ambrosio, Antonio Felix da Costa, and Adam Carroll, who all gain 4 places to finish 14th, 16th, and 18th respectively under my alternate format as opposed to 18th, 20th, and 22nd in real life. Their points totals under the alternative format are: 47, 34, and 32 respectively whereas their points totals in real life are: 13, 10, and 5 respectively. The drivers who loses the most positions compared to where they finished under Formula E's current format are Loic Duval and Pierre Gasly, who both fall 5 places to finish 20th and 21st respectively under the alternative format compared to 15th and 16th in real life. Their points total under the alternative format are 28 and 22 respectively, which compares to their real life points totals of 20 and 18 respectively. While he only finishes 6th in the standings under both formats, Nicolas Prost sits 3rd in the standings for the majority of the season until his second ever DNF in the 2nd race in Montreal race drops him all those places.<br/>
    Below are the Overall Drivers' Championship standings:
    </p>
    {% "afepf3_drivers_p1-9.png", "Screenshot of the first 9 positions of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% "afepf3_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% "afepf3_drivers_p19-25.png", "Screenshot of the positions 19 to 25 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    Unlike last season, there is proper competition (3 full-time competitors and 5 cars only driven by NPJT-eligible drivers) in this Nelson Piquet Jr Trophy Championship as Felix Rosenqvist wins the championship with 203 points and a race to spare. A comfortable 2nd place is Adam Carroll, who finishes every race and thus always scores points compared to drivers who outscore him in the Overall Drivers' Championship, who don't (although in the defence of Jose Maria Lopez, he does miss New York City for the same reason as Sebastien Buemi). Next season the eligibility will change to all drivers who haven't won the trophy and have yet to score a podium on the road, but only Mitch Evans, Maro Engel, Alex Lynn, and Tom Dillmann will return, as: Jose Maria scores a podium on the road (2 in fact - Paris ePrix and Montreal race 2), Felix wins the trophy, and Adam, Esteban Gutierrez and Pierre Gasly all do not return and this will be their only seasons in Formula E.<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% "afepf3_npjt_drivers_p1-9.png", "Screenshot of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    Renault e.Dams wins this championship with 264 points from ABT Schaeffler Audi Sport who have 253 points. Only Renault e.Dams fail to score more than they did in real life (268 in real life), as less points for wins make a difference when you win 50% of the season (again). Although unlike last season, they lead the championship from start to finish despite winning last year's championship with a bigger margin (by 1 point), as their 1st half makes up for their poorer 2nd half. There is a change of positions in the final standings under my alternate points format compared to real life as Venturi swap places with Dragon to finish 8th rather than 9th like they do in real life. Dragon are only 2 points ahead of Jaguar and are saved by having more good finishes and the inconsistency of Mitch Evans and the lack of good results for Adam Carroll, Jaguar's 2 drivers.<br/>
    Below are the Teams' Championship standings:
    </p>
    {% "afepf3_teams_p1-5.png", "Screenshot of the first 5 position of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% "afepf3_teams_p6-10.png", "Screenshot of positions 6 to 10 of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Renault wins the cup again with 281 points from ABT Schaeffler, who has 270 points. There wasn't a manufacturer's cup back in season 3, but if there were, Renault would also win again with a crushing 367 points from ABT, who would have 240 points. Renault's advantage in this hypothetical championship is so great, they seal it with 2 races to spare as even when the results for the main team start to drop off, Techeetah are there to pick up the slack and prevent the brand having a bad weekend. There are some changes between the 2 standings as under alternative format, Jaguar and Venturi overhaul Penske (Dragon) to finish 7th and 8th respectively and finish with the same amount of points (the only time this happens across all championships), with Jaguar taking it on countback courtesy of a class podium scored in Mexico City. In hypothetical real life, Penske finishes 7th, Jaguar 8th and Venturi finishes 9th.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% "afepf3_manufacturers_p1-9.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
</div>