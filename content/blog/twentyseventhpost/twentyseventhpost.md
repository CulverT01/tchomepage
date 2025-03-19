---
title: Project Preseason
description: Explaining the Design of Alternative Formula E Points Format project.
date: 2024-10-24
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Project: Preseason</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    For my second programming project I have decided to build a program that uses a database to store the championship results of 2024 Formula E season using the BTCC (British Touring Car Championship) points format. <br />
    The design of the database and its tables are found in a docx file in this GitHub repository, of which key excerpts are found below: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Also, I will be away at the end of October, so the first update for this project will come on 12/11/24 rather than 05/11/24.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Overview</h2>
    <p class="col-8">
   I have always been fascinated by alternative points formats and how they differ to the current one a motorsport and one of the most unique points formats amongst the motorsport championships I follow is the BTCC, due to its multi-class structure and separate championships for Independent entrants along with the Jack Sears Trophy; a championship for drivers without an outright top 3 result in a race. I have chosen Formula E to try this points-format out for 4 reasons:</p>  
   <ol class="col-8">
   <li> There are customer teams who run a manufacturer's powertrain which are similar enough to BTCC's Independent entrants</li>
   <li> The weekend structure is similar to BTCC's (qualifying session into full-distance race)</li>
   <li> A grid size of 22 cars (2 cars per teams) is small enough to so there isn't too many tables, but there aren't too little either</li>
   <li> I can watch the races in full to keep track of who leads a lap, which is a bonus point available under BTCC's regular points format</li>
   </ol>
   <p class="col-8">
    I had considered MotoGP and NASCAR Cup Series as both have similar differing entrants that can be easily identified as having less resources (satellite teams and teams without Tier-1 manufacturer support respectively). However, both series have fundamental issues that prevent an easy integration of the points format.</p>
    <ul class="col-8">
    <li>MotoGP has sprint races which aren't at full Grand Prix distance,so would need an adaptation of the points system to accommodate</li>
    <li>I can only watch highlights of MotoGP and thus may miss a rider leading a lap</li>
    <li>NASCAR has at minimum 36 entrants for any points-paying race, which is too many rows and entrants if I ever decide to create tables for each driver</li>
    <li>NASCAR Cup races are usually 3 to 4 hours long and it would to time consuming keep track of every driver who leads a lap</li>
    </ul>
    <h3 class="row">BTCC Championship</h3>
    <p class="col-8"> 
    The British Touring Car Championship (BTCC) awards points for the top 15 in a race, along with bonus points for the driver who: wins the pole position, sets the fastest lap in the race, and leads a lap during the race. The points are awarded as such: </p>
    <ol class="col-8">
    <li> 20</li>
    <li> 17</li>
    <li> 15</li>
    <li> 13</li>
    <li> 11</li>
    <li> 10</li>
    <li> 9</li>
    <li> 8</li>
    <li> 7</li>
    <li> 6</li>
    <li> 5</li>
    <li> 4</li>
    <li> 3</li>
    <li> 2</li>
    <li> 1</li>
    </ol> 
    <p class="col-8">
    The BTCC has 6 championships: BTCC Championship for Drivers, BTCC Independents’ Trophy for Drivers, BTCC Championship for Manufacturers/Constructors, BTCC Championship for Teams, BTCC Independents’ Teams Championship, and The Jack Sears Trophy. All drivers and teams are entered into the Championship for Drivers and Teams respectively.<br/>
    Independent teams are those that have less money and resources than the Manufacturer/Constructor backed entries and use the spec engine that TOCA, the organisation that runs the BTCC, provides, while Independent drivers are those who drive for an Independent team. The drivers eligible for the Jack Sears Trophy are those who have not earned top 3 result in a race (prior to any post-race investigations) and has not won the Jacks Sears Trophy previous. 
    </p>
    <h3 class="row">Formula E Integration</h3>
    <p class="col-8"> 
    Formula E is an all-electric single seater world championship in which 6  manufacturers supply powertrains to 11 teams, thus some teams run as customer teams. The customer teams for 2024 were: Andretti Formula E, Envision Racing, NEOM McLaren Formula E Team, and ABT CUPRA Formula E Team and these teams (and drivers who drive for them) will be classed as Independent entrants. Maserati MSG Racing run the same powertrains as DS Penske albeit badged as a Maserati, so will not count as a customer team, but the parent company of the 2 brands, Stellantis, is entered into Formula E's Manufacturers' Cup and the entrants for this championship will be used in the equivalent Manufacturers/Constructors championship. No driver who would have won the Jack Sears Trophy prior to the 10th season (2023-2024) of Formula E will be excluded, but the winner from the 10th season will be for future implementations.
    </p>
    <h2 class="row">Project Aims and Technical Specifications</h2>
    <p class="col-8">
    The aim of the project is to allow users to see how a Formula E Championship would differ based on an alternative points format as the style of racing that can occur during Formula E races is akin to a peloton in cycling, where it not always best to be constantly leading, so there could be multiple drivers with extra bonus points for leading a lap.<br/>
    The project will use MongoDB as the server for the database, as it is easier to have access to a Mongo server than other database servers and Python was chosen as it another programming language that I know fairly well and can demonstrate my knowledge in.
    </p>
    <h2 class="row">Data Dictionary, E-R Diagram and Use-Case example</h2>
    <p class="col-8">
    Below are examples of: a data dictionary, a E-R diagram and a Use-Case scenario, which should illustrate further how the program would work.
    </p>
    {% image "./data_dictionary.jpg", "Screenshot of a Data Dictionary showing the initial entities of the database: Drivers, Teams, and Manufacturers" %}
    {% image "./er_diagram.png", "Screenshot of the E-R Diagram detailing the relationships between the various entities of the database" %}
    {% image "./use_case_scenario.jpg", "Screenshot of a Use-Case Scenario detailing how viewing a Teams championship would work" %}
  </div>
</div>