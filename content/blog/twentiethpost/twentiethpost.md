---
title: Any more 4 Any More?
description: Fourth update of programming the Card Game Player project.
date: 2024-08-27
tags:
  - card game player project
  - object orientated programming skills evidence
  - java
---

<div class="container fluid">
  <h1 class="col align-self-center">Any more 4 Any More?</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    Hello and welcome to the fourth update to the Card Game Player Project.<br/>
    This week I've been finishing changing the Support Card classes' effect method to boolean as well as making skill an attribute of Card rather than Creature Card. The next thing to make is the Runner class, so finally we can play a game of Castles of Cards. This means the methods to start and play a game as well as to play the 4 stages of a turn (one for each stage).<br/>
    As always, the entire project is available at this GitHub repository: <a href="https://github.com/CulverT01/cardgameplayer">https://github.com/CulverT01/cardgameplayer</a>
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    All Support Card classes' effect method is now boolean, so the effect can fail and the card not be wasted. Player's playCardFromHand method has also changed to reflect this change and now only sends a Support Card to the wasteland if the effect method returns true boolean value. There is also new methods for KeyFunction class, which checks the wasteland or deck to see if there is a possible target to select within that array. The examples shown below are the updated SupportCardResMa class and its test as well as the checkWasteland and checkDeck methods of KeyFunction.
    </p>
    {% image "supportcardresma_1.png", "Screenshot of the constructor and the first part of the effect behaviour method of the support card res ma class" %}
    {% image "supportcardresma_2.png", "Screenshot of the second part of the effect behaviour method of the support card res ma class" %}
    {% image "supportcardresmatest_1.png", "Screenshot of the set up for the tests, the test to check support card res mas effect behaviour method works successfully and the first part of the test to check it fails when there is no magic creatures in the wasteland" %}
    {% image "supportcardresmatest_2.png", "Screenshot of the second part of the test to check support card res mas effect behaviour method fails when there is no magic creatures in the wasteland and the test to check it fails when the frontline is full" %}
    {% image "keyfunction_5.png", "Screenshot of the check wasteland method and the first part of the check display deck method of the key function class" %}
    {% image "keyfunction_6.png", "Screenshot of the second part of the check display deck method of the key function class" %}
     
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    Examples regarding the changes to the effect method, is  with the SupportCardResMa and SupportCardResMe classes, the effect fails if there isn't a free space on a player's frontline to play it to and before it would run as normal, except the Creature selected would stay in the wasteland and the Support Card would still go to the wasteland as per Player's playCardFromHand method. All Support Cards that increase a stat (a Creature's Attack or Health, a Player's Defence Points) can only return true boolean value as the checks that would fail them have already passed in the playCardFromHand behaviour (is there a Magic/Melee Creature in your frontline) of Player.
    </p>
  </div>
</div>