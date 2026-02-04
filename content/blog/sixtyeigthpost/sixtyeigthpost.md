---
title: 2026 Miami ePrix Review
description: Review of 2026 Miami ePrix Review
date: 2026-02-03
tags:
  - alternative formula e points format project
  - Formula E race review
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">2026 Miami ePrix Review</h1>
  <div class="row justify-content-center">
    <p class="col-8">
   Hello all! For the double-header weekends (the first of 6 is next time out in Jeddah) each race will have its own individual blog post, and the second of which will come out on the day after the first. This means the review of the first 2026 Jeddah ePrix race will come out on the 17th February and the review of the second 2026 Jeddah ePrix race will be on the 18th. While this track has not hosted a Formula E race before, it is not new to Formula E as last year's Evo Sessions were held at this circuit. This year's Evo Sessions will be at Jeddah and will take place a day after the ePrix there.<br/>
   Also this weekend was the Formula E Rookie Free Practice session, a 40 minute session that saw 11 drivers with less than 3 starts (this means Josep Maria 'Pepe' Marti was eligible and did participate) in Formula E get time in a Formula E car. The session was topped by Zak O'Sullivan driving for Envision Racing and we could see him or one of his other fellow competitors in this session make it in Formula E, as such was the case for Nick Cassidy (Season 6), Felipe Drugovich (Season 9 and Season 10), Max Guenther (Season 4), and Nyck de Vries (Season 4 and Season 5) to name only 4 who have done this kind of move.<br/>
   The next Formula E race will be the 2026 Jeddah ePrix double-header, with race 1 on 13th February 2026 at 17:00 UTC and race 2 on 14th February at 17:00 UTC. You can find out where to watch it <a href="https://www.fiaformulae.com/en/ways-to-watch">here</a>.<br/>
   This post will also double up as the 14th update to the programming side of the project as I have made some alterations to the updateDriverResult function (see changes and clarifications section for more).
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Qualifying</h2>
    <p class="col-8">
    Before Qualifying, there were 2 notable incidents in Free Practice: the first was in Free Practice 1 and was between Antonio Felix da Costa and Nick Cassidy, as the pair raced each other from turn 6 to turn 8, banging wheels at turn 8. Neither would receive a penalty, as neither one were impeding the other as neither were on a push lap (lapping at a reasonable pace for the race or qualifying), although Lucas di Grassi would not be so fortunate. Towards the end of Free Practice 2, Lucas, (on a push lap) misses his brake point for turn 4, runs out wide and into a slow Mitch Evans, who had moved off the racing line to not impede Lucas. To further compound Lucas's woes, his car took the brunt of the damage and was found at fault of the incident, so picked up a 3 place grid penalty.<br/>
    Now to Qualifying. Group A consisted of: Nick Cassidy, Oliver Rowland, Edoardo Mortara, Nico Mueller, Sebastien Buemi, Josep Maria 'Pepe' Marti, Nyck de Vries, Norman Nato, Mitch Evans, and Lucas Di Grassi. There was an incident in the session, as Sebastien would collide with Edoardo in turn 13. Whilst preparing to do a push lap, Sebastien had gone wide through turn 13 before returning to the racing line, unaware that Edoardo was coming through turn 13 on a push lap. His punishment was a 5 place grid penalty and he would pick up a further 3 places for impeding Nyck during qualifying as well. Another driver visiting the race stewards' office for impeding a fellow competitor was Oliver as he copped a 3 lace grid penalty for impeding Lucas  (moving slowly on the racing line into the brake zone of turn 13) while the latter was on a push lap. The 4 from the group that would move onto the Duel stage were: Norman, Nick, Nyck, and Nico (all the 'N's it seems).<br/>
    Group B went next and consisted of Jake Dennis, Pascal Wehrlein, Taylor Barnard, Max Guenther, Joel Eriksson, Jean-Eric Vergne, Zane Maloney, Antonio Felix da Costa, Felipe Drugovich, and Dan Ticktum. This session is a lot cleaner than the first as no one from this group would need to see the race stewards after the session. The (relative) cold temperature in Miami meant that the best times were set towards the end as drivers would spend most of the session warming up the times and setting non-representative times, but only a few improve on their final runs, so heavy hitters like Jake, Pascal, and Jean-Eric fail to progress. The 4 that made it into Duel stage from group B were: Taylor, Antonio, Joel, and Felipe.<br/>
    The 1st Quarter-Final was between Nyck and Nick, with the former winning and the 2nd was between Nico and Norman with the former succeeding thanks to a lock up into turn 13 for the latter. Quarter-Final 3 was between Joel and Antonio, which saw the latter advance and the final Quarter-Final was between Felipe and Taylor which saw the former moving on to Semi-Final 2 by 1 thousandth of a second. Semi-Final 1 was between Nyck and Nico, which Nico won and Semi-Final 2 was between Antonio and Felipe, with the latter winning. The Final saw Nico winning his first ever pole position, thanks to a small mistake in turn 4 for Felipe.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Race</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    Mitch Evans wins the race from Nico Mueller in 2nd and Pascal Wehrlein in 3rd. It has rained between qualifying and the race, for the first time all weekend, so the race begins under safety car until lap 5 when we go green with a standing start.<br/>
    The wet weather catches a Sebastien Buemi out as he spins through turn 4 on lap 1, trying to generate temperature through his tyres, but loses no positions as he is last thanks to all his grid penalties. The lack of grip forces the drivers to be more careful and so the race is very clean, as there are only 1 penalty-worthy incident on when lap 26 Felipe Drugovich brakes too late for turn 13 and slides into the back of Antonio Felix da Costa, damaging his front wing and knocking askew the left rear wing plate of Antonio. The only other penalty handed from this race is a 5 second penalty converted to a 3 place grid penalty to Lucas Di Grassi after he failed to come a complete stop at the designated bollard after went wide at turn 7, meaning Lucas will have now started his first 4 starts this season with a grid penalty (clean up your driving, man!). To further the point about the clean racing, there was only 1 retirement, which was Dan Ticktum, with the cause probably 'handling' issues due to uncompetitive tyre pressures for the conditions.<br/> The winning move is a textbook switchback in turn 13, executed by Mitch on Nico on lap 27 and while seems like nothing happened, there were constant overtakes inside leading pack, which was as big as 7 cars at points, but the Gen 3 Evo car races more aggressively and, in my opinion, better in dry conditions, as last year the weaker races of a double-header weekend were often the wetter races.
    </p>
    <ol>
    <li> Pascal Wehrlein (+3)</li>
    <li> Jake Dennis (=0)</li>
    <li> Nico Mueller (+2)</li>
    <li> Oliver Rowland (-1)</li>
    <li> Nick Cassidy (-4)</li>
    <li> Edoardo Mortara (=0)</li>
    </ol>
    <p class="col-8">
    Only 1 driver has less points under the alternative format compared to real life and it is Nick Cassidy who has 36 points under the alternative format whereas in real life he has 40, although the drivers' championship leader under the alternative format, Pascal, has more points than his real life counterpart, Nick, but only by 1 point. Dan is the only one to match his points totals across both formats and the driver who has the most points compared to real life is Antonio, who has 11 more points under the alternative format (15) compared to real life (4). There are differences between the standings and the driver who gains the most position's under the alternative format is Nico, who gains 2 to be 3rd under alternative format compared to 5th in real life, while the driver who loses the most positions is Nick who is 5th under the alternative format, but leads the championship in real life.<br/>
    Below are the overall Drivers' Championship standings:
    </p>
    {% image "afepf12_r3_drivers_p1-7.png", "Screenshot of the first 7 positions of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "afepf12_r3_drivers_p8-14.png", "Screenshot of the positions 8 to 14 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "afepf12_r3_drivers_p15-20.png", "Screenshot of the positions 15 to 20 of the Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Trophy for Drivers</h3>
    <p class="col-8">
    The class is won by Joel Eriksson again with 2nd in class going to Sebastien Buemi for a Envision Racing 1-2 in class and 3rd to Pepe Marti. Felipe Drugovich is the early leader for the class, leading from the start all the way until lap 26, where his crash into Antonio Felix da Costa hands Joel the lead which he does not relinquish. The standings are the same as they were going into this race.<br/>
    Below are the Customer Trophy for Drivers standings:
    </p>
    {% image "afepf12_r3_customer_drivers_p1-6.png", "Screenshot of the Customer Trophy for Drivers standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    The winner of the class is Nico Mueller with 2nd going to Joel Eriksson and 3rd to Pepe Marti. Nico leads for the first 4 laps (all under safety car), but loses the lead on the exit of turn 11 to a Felipe Drugovich in Attack Mode on lap 5, but takes it back at the start of lap 8. Felipe retakes the lead into turn 1 on lap 13, but loses it through turn 13 to Nico on lap 16 and then the challenge ends there as Joel never gets close enough to mount a challenge in the same way Felipe did. Like with the Customer Trophy for Drivers, there is no change of championship position compared to before the race and Felipe still has the same amount points across both BTCC exclusive driver championships as well as being in the same position in both championships.<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% image "afepf12_r3_npjt_drivers_p1-5.png", "Screenshot of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    With the double podium, Porsche Formula E Team lead the standings under both formats with Mahindra Racing and Citroen Racing Formula E Team 2nd and 3rd respectively under the alternative format, while in real life the 2 swap places. Citroen are the only team not to score more points under the alternative format, as they tie their real life points score with theirs under the alternative format. There is 1 other change between the 2 formats in terms of the standings as Lola Yamaha ABT Formula E Team are ahead of Cupra Kiro thanks to both of their drivers finishing (although in Dan Ticktum's defence, it is not always his fault), so this means the biggest gainers in terms of championship position is Mahindra and Lola Yamaha while the biggest losers are Citroen and Kiro. The biggest gainer in terms of points is Lola Yamaha who have 16 more points under the alternative format (17) compared to real life (1).<br/>
    Below are the overall Teams' Championship standings:
    </p>
    {% image "afepf12_r3_teams_p1-5.png", "Screenshot of the first 5 positions of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    {% image "afepf12_r3_teams_p6-10.png", "Screenshot of the first positions 6 to 10 positions of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Teams' Championship </h3>
    <p class="col-8">
    Despite their best driver finish 4th in class, Andretti Formula E still lead the class with 53 points, over Envision Racing who have 52 and Cupra Kiro in 3rd with 32. The 3 drivers who had brought home the points for their team in the first 2 races (Jake Dennis, Joel Eriksson, and Pepe Marti), continue to do so in this race, although I hope this will have changed come the end of the upcoming double-header in Jeddah; for both Dan Ticktum's and Sebastien Buemi's sakes. There are no changes in terms of positions compared to before, but if the lead Envision driver can finish ahead of the lead Andretti driver, then I think we will have a change.<br/>
    Below are the Customer Teams' Championship standings:
    </p>
    {% image "afepf12_r3_customer_teams_p1-3.png", "Screenshot of the Customer Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Porsche lead the standings in Manufacturers' Cup under the alternative format with points total of 80 and also lead in real life too with a points total of 88. Stellantis are now 2nd under the alternative format with 72 points and are 2nd in real life too, but have bigger gap back to Porsche as they have 63 points in real life. 3rd under the alternative format is Nissan who have 54 points under the alternative format and 43 in real life, while Miami ePrix winners Jaguar are 3rd in real life with an alternative format points total of 45 and a real life points total of 56. Jaguar are only 5th under alternative format and thus the biggest losers in terms of championship position, while the biggest gainers are Nissan and Mahindra, as both move up 1 place to be 3rd and 4th respectively. Porsche and Jaguar are the only manufacturers to have less points under the alternative format, with Jaguar having the biggest discrepancy at 11 points. The biggest gainer in terms of points is Lola-Yamaha, whose 34 points under the alternative format is 22 points greater than their real life total of 12.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% image "afepf12_r3_manufacturers_p1-6.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
   <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    A problem with the updateDriverResult function is that it would ask, unless already told yes, if a driver at x position had scored pole position, set the fastest lap, and/or led a lap and would only ignore the latter if the driver's finishing position was that of a retiree from the race. This slowed the function down and was quite inefficient, so now the winner of the pole position, setter of the fastest lap, and number of classified finishers who led a lap are asked as well as the bonus points are updated in the database before the finishing positions are asked. The lap leader one also prevents a driver being awarded the corresponding bonus point more than once as when a driver initial is entered, the function checks to see if it is in a list that stores driver initials and if it isn't, then the bonus point is awarded, otherwise it does nothing except telling the user that they have already entered that driver's initial already. This is all kept in a while loop, that loops while the length of the list is less than the number of classified finishers who led a lap, according to the number the user will have already entered.<br/>
    The updatePoints function is still in the if statement as it was before as it is possible for a driver to be non-classified despite having a top 15 finish - e.g: Pepe Marti in this season's Sa Paulo ePrix. Not shown is the updateBonusPoints function, which is a function that creates a filter doc and an update doc to be used by the update function as there's no need for repeating lines of code as a good programming practice to refactor code.<br/>
    Below is an image of part of the updateDriverResult function, specifically where the majority of changes made are.
    {% image "afepf_functions_updateDriverResult2.png", "Screenshot of the updateDriverResult function in afepf_functions.py, which now asks for the recipients of the bonus points and updates the database accordingly" %}
  </div> 
</div>