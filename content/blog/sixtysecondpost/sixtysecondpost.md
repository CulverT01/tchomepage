---
title: After Eight
description: Eleventh Update of Alternative Formula E Points Format project.
date: 2025-11-25
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">After Eight</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my twelfth update to my Alternative Formula E Points Format project. This is season is the most representative of all the seasons under Gen 2 technical regulations due the change in qualifying format. I explained the previous qualifying format and its flaw in the previous post Seventh Heaven however, the new format works a bit differently and one still currently in use (as of the eve of Season 12). Firstly, the grid is split into 2 groups with Group A comprised of drivers in the odd numbered places in the current championship standings and Group B comprised of even numbered places (the exception being round 1, where it is up to the teams to decide which driver is in which group). Both groups are let onto the track separately to qualify and have 10 minutes to set lap times (drivers must set a time within the first 5 minutes of these sessions) and the top 4 drivers in terms of lap time in a group move onto the the Duel Stages. The Duel Stages sees pairs of drivers go out onto track one at a time to set a lap with the faster driver advancing to the next stage like a knockout competition seen in the Football World Cup. The front row made up of the finalists, the second row made up of the losing semi-finalists and positions 5-8 being the losing quarter-finalists sorted by fastest lap in the quarter-finals. The rest of the grid are sorted as such: your row relates to your position the qualifying classification of your group and if the pole sitter comes your from your group, you will start from an odd number and if they didn't you will start from an even number.<br/>
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    Stoffel Vandoorne wins the championship in real life with a total of 213 points and does the same under the alternative format with 221 points instead. He becomes the 3rd driver under the alternative format to seal the championship before the final race. 2nd place goes to Mitch Evans both in real life and under the alternative format as finishes in real life with 180 points and 182 points under alternative format. This is Mitch Evan's 3rd 2nd place finish in the standings under the alternative format and means he has an average finish of 3rd (he finishes 6th in season 6) across the Gen 2 seasons, the best of anyone in that time span.<br/>
    3 drivers score less than or equal points and they are Edoardo Mortara, Antonio Giovinazzi, and Sacha Fenestraz. Edoardo scores 1 less point under the alternative format compared to real life, so has a points total of 168 instead of 169. Antonio and Sacha never record a classified finish inside the top 15(Antonio's sole finish inside the top 15 is a retirement), so score 0 points. The driver who gains the most points compared to their real life total is Pascal Wehrlein, who achieves 114 points which is a difference of 43, compared to his real life total of 71. The Porsche drivers benefit massively under this points as Andre Lotterer has the 3rd biggest increase at 35, as his real life total is 63 and while under the alternative format has a total of 98.<br/>
    There are 5 drivers who gained the most positions compared to their final standings under the current format, who are: Antonio Felix da Costa, Andre Lotterer, Sebastien Buemi, Maximilian Guenther, and Sergio Sette Camara. All shoot up a massive 1 position higher under the alternative format to finish 7th, 10th, 14th, 18th, and 19th respectively (I am not giving the points differences, we would be here forever if I did). The driver who loses the most positions compared to where they finished under Formula E's current format is Oliver Turvey, who falls a dramatic 2 places to finish 20th with a points score of 22 under the alternative format compared to a points total of 6 in real life. <br/>
    This season is the most consistent by the grid so far with the minimal differences between the 2, so the bad drivers are consistently bad (Antonio Giovinazzi, Maximilian Guenther, etc) and the good drivers are consistently good (Stoffel Vandoorne, Pascal Wehrlein, etc). That said Antonio's season isn't bad, it's downright atrocious and he is lucky that there are less time between ePrixs and more of them, because he wouldn't not have survived Gen 1 (seasons 1-4) and be fired before Rome. Also, while title was wrapped up early, for the majority of the season it was a tight battle between Stoffel and Jean-Eric Vergne (there he is again) before the New York and London double headers, which sees him score 2 points across the 4 races and slip out of title contention.<br/>
    Below are the overall Drivers' Championship standings:
    </p>
    {% image "./afepf8_drivers_p1-9.png", "Screenshot of the first 9 positions of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf8_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf8_drivers_p19-24.png", "Screenshot of the positions 19 to 24 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Trophy for Drivers</h3>
    <p class="col-8">
    The championship is won by Robin Frijns who defends his championship and wins it over class debutant Jake Dennis 247 points to 231. Robin Frijns again finishes every single race which means the last time he failed to see the finish of an ePrix was the last race of Season 6. Once again, you would expect Edoardo Mortara to be a factor but he suffers 3 retirements, which all add up (or rather don't) to another 3rd place finish despite winning the class 7 times; including 4 in a row which is so far an all time record (It was 2, currently held by all multi-time class winners in the class except: Jake Dennis, Norman Nato, Felipe Massa, and Loic Duval). In Gen 3 (seasons 9-12), Nick Cassidy is a perennial title contender for most seasons but in Gen 2 is kind of bad, with only his consistency being his saving grace in season 7 (he didn't win the Nelson Piquet Jr Trophy on outright speed). in the overall standings he is outclassed by fellow drivers: in the same team, using the same powertrain and, especially this season, those in the same class. Until Oliver Askew's late season collapse, he was behind him and it took until Oliver's 3rd DNF for him to build any sizeable advantage over Oliver.<br/>
    Below are the Customer Trophy for Drivers standings:
    </p>
    {% image "./afepf8_customer_drivers_p1-6.png", "Screenshot of the Customer Trophy for Drivers standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    The winner of the Trophy is Oliver Askew who scores 247 points over Sergio Sette Camara, who scores on 238 points to finish 2nd. For the 3rd year in a row, a driver wins the class 4 times and doesn't win the title, also for the 2nd year in a row they finish 3rd as Dan Ticktum finishes 3rd with 4 class wins and 206 points. Oliver wins the class a record 10 times and wins 4 times consecutively twice, thus giving him the record (as of season 8) of most class wins in a season and most class wins overall. As the points gap does suggest, this does go to the final round, because of Oliver's poor results in the last 6 races, Sergio is able to mount a comeback charge and would have won the title if he had finished race 1 of the London ePrix (he is not classifies as pulls into the pits on the last lap, having run out of energy), as any finishing position would have given him enough points to win over Oliver. The record 'number of Nelson Piquet Jr Trophy class starts without a class win' gets a new holder this season, as Antonio Giovinazzi does not win in any of his 15 starts (he misses the final race due to a hand injury sustained in the previous race), over-hauling Gary Paffett's previous record of 13.<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% image "./afepf8_npjt_drivers_p1-5.png", "Screenshot of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    Mercedes-EQ Formula E Team defend their teams title in real life with a points total of 319 and also win under the alternative format with a points total of 336. 2nd place, as well as all of the top 5, are the same with ROKiT Venturi Racing finish there with a points total in real life of 295 and 308 under the alternative format. All teams score more points under the alternative format than they do in real life and the only changes are: Andretti and Porsche, and Mahindra and Nissan swapping places with the latter respectively finishing ahead of the former under the alternative format. Like with the  Overall Drivers' Championship for Jean-Eric Vergne, DS Techeetah are nip and tuck with Mercedes for most of the season, but again, the performance over New York City and London ePrixs are bad enough that they fall away, but are still in title contention until the end of the penultimate race - one race further than Jean-Eric.<br/>
    Below are the overall Teams' Championship standings:
    </p>
    {% image "./afepf8_teams_p1-6.png", "Screenshot of the first 6 positions of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% image "./afepf8_teams_p7-11.png", "Screenshot of the positions 7 to 11 of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Teams' Championship </h3>
    <p class="col-8">
    ROKiT Venturi Racing claim their 2nd ever Customer Teams' Championship, with a points total of 293 and win with a round to spare. 2nd place goes to Envision Racing, who finish with a points total of 263. Venturi become the first team to win the Customer Teams' Championship and not employ the eventual Customer Trophy for Drivers winner, which makes sense when you realise that no customer team has both cars retire in the same ePrix, so all are always scoring points, and they win the class 9 times - 4 more than their nearest competitor Envision Racing.<br/>
    Below are the Customer Teams' Championship standings:
    </p>
    {% image "./afepf8_customer_teams_p1-3.png", "Screenshot of the Customer Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Mercedes-Benz wins their first and only Manufacturers' Cup with points total of 408 over DS Automobiles, who finishes with 372 points as well as sealing with a round to spare. They still would have won the Manufacturers' Cup if it had been run in Season 8, but it is a lot more dominant as they win with a crushing total of 548 and seal it with 3 rounds to spare. The reasons for this are the same for Renault back in season 3: they are the only manufacturer supplying 2 teams (themselves and ROKiT Venturi Racing), the winning manufacturer for over half the races. Despite supplying teams, Audi and BMW are not counted this season for this championship as both manufacturers pulled out of the sport at the end of last season and no longer have a presence in the sport (the safety car went from a Mini, a BMW owned car brand, to a Porsche this season), so makes no sense for them to score points in a championship they are not involved in and thus Mercedes pick up 2 extra wins as a manufacturer (Stoffel Vandoorne finishes 2nd behind both Nick Cassidy and Jake Dennis for their respective wins). Mercedes are the only manufacturers to score less points in real life compared to the alternative format and the championship positions do not change across either format.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% image "./afepf8_manufacturers_p1-8.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
</div>