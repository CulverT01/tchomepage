---
title: 2 Close to Call
description: Eighth Update of Alternative Formula E Points Format project.
date: 2025-08-12
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">2 Close to Call</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my eighth update to my Alternative Formula E Points Format project. There are no programming changes in this updates, but there is a change regarding points scoring for Manufacturers' Cup as I has been scoring that championship wrong. The championship is scored similarly to the Customer Teams' Championship, except a maximum of 2 cars score points for a manufacturer entrant, which are teams which enter themselves as a manufacturer team. I have determined that a manufacturer entrant is a team who builds their own powertrain themselves or with a technical partner, so for this season this is Renault (Renault e.dams), Venturi, Virgin, Mahindra, and ABT. Despite being supplied by Venturi and would be eligible to do so under modern Formula E rules, Dragon Racing cannot contribute for Venturi towards this championship. I will update the other seasons with the correct implementation of manufacturer points scoring in the near future and will update those pages when I do so.<br/>
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a> <br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Results</h2>
    <h3 class="row">Overall Drivers' Championship</h3>
    <p class="col-8"> 
    The champion of Season 2 is Sebastien Buemi, but he isn't under the alternative format as Lucas Di Grassi takes the title. Sebastien scores 135 points under the alternative format compared to 155 in real life, while Lucas has 141 points compared to his real life total of 153, although there would have been a bigger controversy surrounding the title. In the final race, Sebastien had won the pole and his teammate was 2nd on the grid so, he looked to be able to take the title, by the slightest margins, but going into the first corner, Lucas Di Grassi (starting 3rd) would go for an impossible gap into the first corner, taking himself and Sebastien out (If he doesn't, he is no longer a racing driver). Now both were able to continue, albeit by switching immediately to their 2nd car, but cannot go the distance with one car, so both eventually retire and score no points. Now in real life, both enter the final race on equal points, so the only points the 2 could score were for the fastest lap, which Sebastien does and thus takes the title. The controversy here is that Lucas took out his only title rival out before he could try to take the title away from him. Apart from the aforementioned crash, Sebastien loses the title because the points awarded for pole and fastest lap are smaller under the alternative format (1 point each respectively) compared what was used at the time (3 points for pole, 2 for fastest lap) and Lucas does not win the pole for any race, nor does he set the fastest lap, but his worst points-scoring finish is 4th and Sebastien's is 12th.<br/>
    Only 3 drivers scores less or equal points with the alternative format compared to real life and they are are 2 title protagonists and Rene Rast, who fails to record a classified finish in his only start, so scores 0 points under both formats. The Driver who gains the most points under the alternative format is Oliver Turvey, who scores 34 more points compared what he scored in real life - 45 points under the alternative format compared to 11 in real life. This is helped by the fact there only 18 cars starting an ePrix this season and there are usually 2 or 3 retirements, so points are pretty much given if you can finish, which he does in all but 1 race.<br/>
    The drivers who gained the most positions compared to their final standings in real life are: Stephane Sarrazin, Nick Heidfeld, and Bruno Senna, who all gain 2 places to finish 4th, 8th, and 9th respectively under my alternate format as opposed to 6th, 10th, and 11th in real life. Their points totals under the alternative format are: 98, 79, and 75 respectively whereas their points totals in real life are: 70, 53, and 52 respectively. The driver who loses the most positions compared to where they finished under Formula E's current format is Loic Duval who falls 3 places to finish 11th under the alternative format compared to 8th in real life. His points total under the alternative format is 72 and compares to his real life points total of 60. Loic deserved more from this season as he suffers 3 consecutive mechanical retirements in a row from the Paris ePrix to the first race of the London ePrix, hurting his chance of finishing anywhere near his teammate (Jerome d'Ambrosio), who he matched and arguably beat in terms of pace.<br/>
    Below are the Overall Drivers' Championship standings:
    </p>
    {% image "afepf2_drivers_p1-9.png", "Screenshot of the first 9 positions of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "afepf2_drivers_p10-18.png", "Screenshot of the positions 10 to 18 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    {% image "afepf2_drivers_p19-23.png", "Screenshot of the positions 19 to 23 of the Overall Drivers' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Trophy for Drivers</h3>
    <p class="col-8">
    The inaugural Customer Trophy winner is Jerome d'Ambrosio, who wins it from Robin Frijns in the final round. Jerome records a classified finish every single race, so is always scoring points in this championship, while his 2 other title rivals (Robin Frijns and Loic Duval) both record multiple DNFs late on to widen the gap between themselves and Jerome. This will be everyone's but Robin Frijns' and Rene Rast's sole season in the championship, as when we next have customer championships in season 5, everyone else is or will be either driving for manufacturer entrants (Jerome d'Ambrosio and Ma Quinghua) or no longer in Formula E (Loic Duval, Nathanael Berthon, Simona de Silvestro, and Salvador Duran).<br/>
    Below are the Customer Trophy for Drivers standings:
    </p>
    {% image "afepf2_customer_drivers_p1-9.png", "Screenshot of the Customer Trophy for Drivers standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Nelson Piquet Jr Trophy</h3>
    <p class="col-8">
    The only full-time competitor in this championship, Robin Frijns, wins the championship with 3 races to go for a points total of 154, over the driver with the 2nd highest number of races entered, Mike Conway. Although, combining Mike's and Jacques Villeneuve's (the driver Mike replaced) points, would give a bigger total than the winning amount. This season's version only looks this bad because the contemporary eligibility of the Jack Sears Trophy (the championship in which the Nelson Piquet Jr trophy is based off of) is drivers without a single start in the BTCC and so initially only 3 drivers are eligible (Robin Frijns, Nathanael Berthon, and Jacques Villeneuve) and we lose 2 of those after the Punta del Este ePrix, but gain 1 (Mike Conway), whereas the current eligibility (1 or less podiums and/or has not won the trophy before) would include drivers such as: Antonio Felix da Costa, Nick Heidfeld, Stephane Sarrazin, Bruno Senna, Oliver Turvey (Nelson Piquet Jr's teammate), etc.<br/>
    Below are the Nelson Piquet Jr Trophy standings:
    </p>
    {% image "afepf2_npjt_drivers_p1-7.png", "Screenshot of the Nelson Piquet Jr Trophy standings, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Overall Teams' Championship</h3>
    <p class="col-8">
    Renault e.Dams wins this championship with 238 points from ABT Schaeffler Audi Sport who have 226 points. Only Renault e.Dams fail to score more than they did in real life (270 in real life), as less points for wins make a difference when you win 50% of the season. There is a change of positions in the final standings under my alternate points format compared to real life as NEXTEV swap places with Aguri to finish 8th rather than 9th like they do in real life. With the exception of Antonio Felix da Costa, Aguri's drivers don't really do that well, although the same could be easily said about Antonio as he leads the field in DNFs at 4 (technically Loic Duval and Nelson Piquet Jr have the same amount of DNFs, but some of their non-finishes happen so late that they still complete at least 90% of the race and thus are declared as classified finishers).<br/>
    Below are the Teams' Championship standings:
    </p>
    {% image "afepf2_teams_p1-9.png", "Screenshot of the Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Customer Teams' Championship</h3>
    <p class="col-8">
    Dragon Racing win the championship with 178 points over Andretti and lead for the entirety of the season, with the closest anyone getting is Andretti at race 2. This will be Dragon's and Aguri's sole seasons in the championship as Dragon will build their own powertrains or be tied to a manufacturer (as of season 11) and while Aguri will continue as a customer team in seasons 3 and 4 as Techeetah, they will be the only customer team and thus the championship will not run.<br/>
    Below are the Customer Teams' Championship standings:
    </p>
    {% image "afepf2_customer_teams_p1-3.png", "Screenshot of the Customer Teams' Championship, outputted by afepf_viewer_program.py" %}
    <h3 class="row">Manufacturers' Cup</h3>
    <p class="col-8">
    Renault wins the cup with 259 points from ABT Schaeffler, who has 243 points. There wasn't a manufacturer's cup back in season 2, but if there were, Renault would also win with 254 points from ABT, who would have 236 points. Venturi would have lost out the most in terms of positions, falling from 3rd to 5th. This is because under the BTCC rules, Dragon Racing are unable to score points for Venturi and so Venturi only has 1 driver that can perform rather than 3. There are no other changes between the 2 championships in terms of position. Also, despite being involved with Formula E teams, neither Audi nor DS Automobiles are registered manufacturer entrants, as their respective teams (ABT and Virgin Racing) have their branding across the powertrains and thus are considered manufacturers.<br/>
    Below are the Manufacturers' Cup standings:
    </p>
    {% image "afepf2_manufacturers_p1-6.png", "Screenshot of the Manufacturers' Cup standings, outputted by afepf_viewer_program.py" %}
  </div>
</div>