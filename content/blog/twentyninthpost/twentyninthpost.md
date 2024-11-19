---
title: All Five Lights Are On
description: First Update of Alternative Formula E Points Format project.
date: 2024-11-12
tags:
  - alternative formula e points format project
  - procedural programming skills evidence
  - database skills evidence
  - python
---

<div class="container fluid">
  <h1 class="col align-self-center">All Five Lights Are On</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is the first update to my Alternative Formula E Points Format project. So far I have made the tables and have populated them with records. Due to how MongoDB operates, there are some differences between the inital design of the database and its implementation. This will be explained the Changes and Clarifications section.<br />
    All files and documents are found in the GitHub repository<a href="https://github.com/CulverT01/altfepointsformat">https://github.com/CulverT01/altfepointsformat</a><br/>
   Please note that I have removed the username and password for the database from the admin program in the interest of security.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    The tables (which MongoDB refers to as collections will be for the rest of this post and future ones) for Drivers, Teams, and Manufacturers have been created and populated with records (which MongoDB refers to as documents will be for the rest of this post and future ones).<br />The Manufacturers Collection in shown below as it appears in MongoDB Atlas (the cloud service in which the database is stored in). 
    </p>
    {% image "./manufactuers_collection_atlas_1.png", "Screenshot of Mongo DB Atlas website displaying first 3 documents of the Manufacturers collection" %}
    {% image "./manufactuers_collection_atlas_2.png", "Screenshot of Mongo DB Atlas website displaying last 3 documents of the Manufacturers collection" %}
    <p class="col-8">
    The collection and documents were created using the afepf_admin_program Python file, which will be updated to allow other CRUD methods to be implemented. The 'add' option requires users to enter details regarding a either a team, or a driver or a manufacturer and those details are stored into a dictionary that is then inserted into the appropriate collection as document, as a JSON document and a Python dictionary are same in appearance. The program loops, providing the user has more drivers, or teams, or manufacturers they wish to enter and ends if they don't.<br />
    Below is the code from afepf_admin_program.py which allows teams to be added to the Teams collection.
    </p>
    {% image "./afepf_admin_add_teams.png", "Screenshot of the code in afepf_admin_program.py that takes users input, stores it in a dictionary and inserts it into the Teams collection in the Mongo DB Atlas server" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    MongoDB uses the document model to store and organise data, which is schema flexible, and allows for sub-documents within documents. Sub-documents means that I can store similar attributes, for example, the Customer Points and the Customer Trophy Position attributes from the Customer Driver table, together alongside related attributes of similar tables, such as the Driver table. This means that: the Customer Driver table, NPJT Driver table, and Customer Team table, now move into both the Drivers collection and Teams collection respectively and the attribute list now looks similar to what the inital tables looked before 1st form normalisation.<br />
    Another advantage of the document model is that documents can hve different structures, thanks to its flexible schema. This means some documents can have certain attributes, while others don't and it not result in empty sets. The Design document will be updated to include the implemented design of the database.   
    </p>
  </div>
</div>