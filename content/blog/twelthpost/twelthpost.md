---
title: Designs on a new project.
description: Detailing the design of the Card Game Player project.
date: 2024-07-02 
tags:
  - card game player project
  - technical skills evidence
  - java
---

<div class="container fluid">
  <h1 class="col align-self-center">Designs on a new project</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    For the first project to display my java programming skills, I decided to build a program that allows 2 players to play a card game of my own design. A more detailed explaination can be found in a pdf file on a GitHub repository where this is found <a href="">(Link Here)</a>, but I have placed key excerpts and examples from that here below.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Card Game Overview</h2>
    <p class="col-8"> 
    The card game is framed as 2 castles (the players) going into battle against each other using their armies (their decks). The win condition is to lay siege to the other castle (reduce their Defense Points to 0) and to do this direct attack with creatures must be made. A direct attack can only be made when your opponent has no creatures on their front line. The card game will be called Castles of Cards.</p>
    <h3 class="row">Card Types</h3>
    <p class="col-8">There are 2 categories of Cards: Creature Cards and Support Cards. Each category will be split up into 2 types, so there are 4 types of card. The card types are: Magic Creature, Melee Creature, Magic Support and Item Support. Some Creature cards will also be either ‘Ace’ or ‘Legend’ cards and these cards will be more powerful than most other creature cards, but with the caveat that you can only have 2 Ace Creatures and 1 Legend Creature in your Deck. Creatures will have 2 stats: Health and Attack, with Health relates how much damage a creature can take, while Attack relates how much damage it can inflict.
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Card Game Implementation</h2>
    <h3 class="row">Player Class</h3>
    <p class="col-8">
    Players of the card game will implemented as their own object class with the same name and will have 6 attributes: Name, Defence Points, Wasteland, Front Line, Hand and Deck. The data types for the attributes are: Name will be a String, Defense Points will be an Integer, Wasteland, Hand and Deck will be ArrayLists that stores the Card object and Front Line will be a 4 element Array that stores the Card object.<br/>
    The Behaviours (methods) that a Player object has are: Drawing from the Deck and Playing Cards from the Hand.
    </p>
    <h3 class="row">Card Classes</h3>
    <p class="col-8">
    There will be a parent class of Card in which the 4 card types will inherit from as child classes.<br/>
    The Card class will have the attributes Name and Card Type, with both being Strings. The Support Card class will have, in addition to the inherited attributes, Effect Description attribute which will be a String. The Creature Card class will have, in addition to inherited attributes, a Health attribute, a Attack attribute and a Skill attribute (the ‘Ace’ or ‘Legend’ aspect of a Creature). The first 2 attributes will be integers, while the Skill attribute will be a String.<br/>
    The Support Card class will have the behaviour Effect while the Creature Card will have the behaviour Attack.
    </p>
    <h3 class="row">Runner</h3>
    <p class="col-8">
    The Runner will be the java file that is used to run the program that allows the card game to be played. There will be 5 methods in the file with one of them to begin the game, while the rest relating to the 4 stages of a turn (Draw, Plan, Battle, End).
    </p>
    </div>
  <div class="row justify-content-center">
    <h2 class="row">Flowcharts and Diagrams</h2>
    <p class="col-8">
    The following images are a flowchart for the player class method Playing Cards from Hand and 2 Class diagrams which show the relationship between the Player and Card classes as well as the relationship between the Runner, the Creature Card and the Player classes.
    </p>
    <h3 class="row">Flowchart</h3>
    <div class="col-8">
    {% image "./playCardFromHandPlayerMethod.jpg", "Flowchart detailing the playing card from hand method of the Player class" %}
    </div>
    <h3 class="row">Diagrams</h3>
    <div class="col-8">
    {% image "./PlayerCardrelationAndRunnerCreatCardPlayerrelationDiagram.jpg", "Diagrams showing the relationship between the Player and Card classes as well as the relationship between the Runner, the Creature Card and the Player classes." %}
    </div>
  </div>
</div>