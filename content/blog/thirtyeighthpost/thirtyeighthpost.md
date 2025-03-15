---
title: New Season
description: Fifth Update of Alternative Formula E Points Format project.
date: 2025-02-04
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">New Season</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my fifth update to my Alternative Formula E Points Format project. You can now switch between collections, operations and Formula E seasons more easily now and the program automatically checks that a competitor is eligible for a secondary championship (Customer Driver/Team, Nelson Piquet Jr Trophy Driver). I will keep track of the championships for the current Formula E season, along with updating weekly the results for older seasons starting with Season 1, with a review of the season at the end. These updates will begin from 10th February.<br />
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    The viewer and admin programs have new function called finish that asks a user if they're finished what they're doing and returns a boolean True value if yes, otherwise returns a boolean False value. For example for the viewer program, the 2 options available to users are now in while loops, along with one that surround both options, which ends if a boolean variable no longer not True. This also applies to the admin program, but with more while loops and variables due it having more options available to the user.<br/>
    Below is the afepf viewer program which evidences these changes.
    </p>
    {% image "./afepf_viewer_finish.png", "Screenshot of the function finish in afepf_viewer_program.py that takes a users input, to check if they are finished with either viewing a single competitor's details or the current standings for a championship, a Formula E season" %}
    {% image "./afepf_viewer_program_new1.png", "Screenshot of the first part of afepf_viewer_program.py that evidences the use of while loops to allow easy switching between options the user can do with the program" %}
     {% image "./afepf_viewer_program_new2.png", "Screenshot of the second part of afepf_viewer_program.py that evidences the use of while loops to allow easy switching between options the user can do with the program" %}
    <p class="col-8">
    The afepf_function program has 2 new functions that check if a driver/team is eligible for a secondary championship (Customer Driver/Team, Nelson Piquet Jr Trophy Driver) and these are the checkDriver and checkTeam respectively. The former takes 2 arguments when called (init and either 'customer' or 'npjt') and performing a search query that outputs either all driver initials for documents whose customer driver points or npjt driver points are more than equal to 0 as well as sorting in ascending order according to those points totals and stores each item in the cursor in a list. The program checks if the value that the init argument stores is in the list and if so, then it returns True otherwise it returns False. The latter function operates the same except it only takes 1 argument (init) and searches the Team collection instead of the Driver collection. The functions are called where the user is asked if the competitor they are entering the results for is a customer driver/team or npjt driver with the if statement below checking i the are equal to True instead of 'yes'.<br/>
    The 2 functions are displayed below.
    </p>
     {% image "./afepf_function_checkDriver_checkTeam.png", "Screenshot of the functions check driver and check team in afepf_functions.py that searches the driver or team collection for all initials of drivers/teams that have more than or equal to 0 customer/npjt points, stores the results in a list and checks if a passed argument is in that list and if so, returns a boolean True value else it returns a boolean False value" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    As this program was initially designed for only season 10, the database that stored the data was known as AltFePointsFormat and MongoDB prevents you from renaming a database, so it name will stay while all other databases will be named after the season for which they store the results for.
    </p>
  </div>
</div>