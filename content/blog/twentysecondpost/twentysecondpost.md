---
title: Five Static Noise
description: Fifth update of programming the Card Game Player project.
date: 2024-09-10
tags:
  - card game player project
  - object orientated programming skills evidence
  - java
---

<div class="container fluid">
  <h1 class="col align-self-center">Five Static Noise</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is the fifth update to the Card Game Player Project.<br />
    I have been working on the methods that allow the game to run. These methods are for: the plan stage, the battle stage, opening hand draw and playing the game. The first 2 relate to the plan and battle stages within a turn respectively, while the others relate to drawing the opening 4 cards and dealing with mulligans, and playing a game of Castle of Cards. There has been some changes to the KeyFunction class as now all of its methods are now also static and has also gained a few new methods as well: displayHand, displayField, drawFourCards and shuffleFourCards. All methods have been tested. All that's left is to create the decks, cards and players objects and then, we will be good to go!<br />
    As always, the entire project is available at this GitHub repository: <a href="https://github.com/CulverT01/cardgameplayer">https://github.com/CulverT01/cardgameplayer</a>
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    I'll first explain App's new methods then KeyFunctions. The planStage method runs a while loop that will continuously call Player class's playCardsFromHand method until either the player is finished or has no more cards in their hand. The battleStage method runs a for loop that will call CreatureCard's creatureAttack method, if the player wants that creature to attack, until either the player is finished or each creature on their frontline has had a chance to attack. OpeningHandDraw draws the the 4 initial 4 cards needed to start to game as well as following the correct mulligan procedures outlined in the Game Rules section of the design document. the playGame method puts all this together, along with code for the draw stage and end stage.
    <br />The planStage method and OpeningHandDraw methods are shown below.
    </p>
    {% image "./app_1.png", "Screenshot of the plan stage method of the app class" %}
    {% image "./app_2.png", "Screenshot of the first part of the opening hand draw method of the app class" %}
    {% image "./app_3.png", "Screenshot of the second part of the opening hand draw method of the app class" %}
    {% image "./app_4.png", "Screenshot of the third part of the opening hand draw method of the app class" %}
    <p class="col-8">
    KeyFunctions new methods do exactly what they say: displayHand method displays a player's hand, displayField method displays a player's frontline and wasteland, drawFourCards method runs a for loop that calls the player's draw function by looping 4 times, and shuffleFourCards method returns the four cards in a player's hand to the deck and then shuffles their deck.<br />
    The displayField method and shuffleFourCards methods are shown below.
    </p>
    {% image "./keyfunction_7.png", "Screenshot of the display field method method of the key function class" %}
    {% image "./keyfunction_8.png", "Screenshot of the shuffle four cards method of the key function class" %}
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The reason why all of KeyFunction's methods are now static is because I fee like it is better programming practice to not create an object used only to call its methods. As to why this wasn't implemented earlier, All of of the methods I had made before in my life hadn't used the static modifier, so I forgot what it did, so when looking it up as it was part of main in App, I learnt what it meant and quickly decided to implement in as well as making the methods in App static as well.<br />
    The draw stage and end stage don't have own methods because: a draw stage method would just be calling the player's draw method and the end stage is when the pointer for the turn player moves to the other player, so it is easier to keep that within the playGame method.
    </p>
  </div>
</div>