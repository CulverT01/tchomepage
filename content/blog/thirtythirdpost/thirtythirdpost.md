---
title: Chequered Flag Waves
description: Third Update of Alternative Formula E Points Format project.
date: 2024-12-10
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">Chequered Flag Waves</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is my third update to my Alternative Formula E Points Format project. So far I have made the functions that allow for view and delete documents, with functions dedicated to view the various championships of the drivers, teams and manufacturers. I have also added new fields to all documents which relate to the initials of the competitors as well as their finishes in the ePrixs. I have also created a general user program called afepf_viewer_program.py, which allows anyone to view the current standings of any of the 6 championships or a single document stored in any of the collections. I will, at later point, put out the full season results under this points format for all 6 championships on this website here. Like with the card game project, I will revisit this project later, as there are obvious changes I can and want to implement.<br />
    As always, all files and documents are found in the GitHub repository: <a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
    Please note that I have removed the username and password for the database from the admin program in the interest of security, but not from the viewer program as the user signed on there has read only permissions.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    The readDriver, readTeam, and readManufacturer functions allow the user to select a document to view and will show all the fields stored in that document.<br/>The readManufacturer function is displayed below as an example. 
    </p>
    {% image "./afepf_function_read_manufacturer.png", "Screenshot of the function read manufacturer in afepf_functions.py that takes a users input, to output all the fields for a document stored in the Manufacturer collection in the Mongo DB Atlas server, whose manufacturer initial matches the users input" %}
    <p class="col-8">
    The readDriverResult, readTeamResult, and readManufacturerResult functions allow the user view the current standings of one of the 6 championships (Drivers' Championship, Customer Trophy for Drivers, Nelson Piquet Jr Trophy, Teams' Championship, Customer Teams' Championship, Manufacturers' Cup). The program only displays the competitors in a selected championship's: name, current points total, their current position in the championship, and their current finishes in the championship. For Manufacturers the finishes will be from the 2 highest finishing cars that use the manufacturer's powertrains.<br/>
    The readDriverResult is displayed below as an example as well as the viewer program.
    </p>
     {% image "./afepf_function_read_driver_result.png", "Screenshot of the first part of the function read_driver_result in afepf_functions.py that takes an users input, to output the name, points, championship position and finishes in the class that championship is for, for all documents that are stored in the Drivers collection in the Mongo DB Atlas server that have scored at least 0 points in that championship" %}
    {% image "./afepf_viewer_program1.png", "Screenshot of the first part of the afepf_viewer_program.py that allows users to run the read functions stored in afepf_functions.py" %}
    {% image "./afepf_viewer_program2.png", "Screenshot of the second part of the afepf_viewer_program.py that allows users to run the read functions stored in afepf_functions.py" %}
     <p class="col-8">
      The deleteDriver, deleteTeam, and deleteManufacturer functions allow the user to select a document to delete and that document, with the filter being based of the ObjectId of the document which the user will have input themself.<br/>The deleteTeam function is displayed below as an example.
     </p>
     {% image "./afepf_function_delete_team.png", "Screenshot of the function delete_team in afepf_functions.py that takes an users input, to delete a document in the Teams collection in the Mongo DB Atlas server, whose Object Id matches the users input" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The creation of Driver_Initial, Team_Initial, and Manufacturer_Initial fields was done so a competitor's full name didn't need to entered to add its results from the most recent ePrix or update the single document in question and its use has extended to the functions that read a single document. The Finishes, Customer_Driver_Finishes, NPJT_Driver_Finishes, Team_Finishes, Customer_Team_Finishes, and Manufacturer_Finishes have been created to aid the user when altering the championship positions when adding in the results of a recent ePrix and working out who is ahead on countback (who has the better finishes amongst 2 more drivers with same points). This is needed as the program itself does not adjust championship position, but could in the future. Also the only way to update any of the Finishes fields is via MongoDB Atlas website, as I have yet to find the necessary code outlined in the MongoDB documentation which would allow me to update an item in array at a specific index. If you do know how, please do let me know via the Contact page on my website: <a href="https://main--toby-culverwell-01.netlify.app/contact/">here</a>
    </p>
  </div>
</div>