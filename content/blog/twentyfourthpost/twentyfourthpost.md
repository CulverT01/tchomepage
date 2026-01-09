---
title: Carrot Juice, Carrot Juice, Carrot Juice
description: Fifth update of programming the Card Game Player project.
date: 2024-09-24
tags:
  - card game player project
  - object orientated programming skills evidence
  - java
---

<div class="container fluid">
  <h1 class="col align-self-center">Carrot Juice, Carrot Juice, Carrot Juice</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This is the sixth update to the Card Game Player Project and the final one for now. I may return to this project a later point as there are changes I would make to make it more user-friendly, so for now it's the end, but the moment has been prepared for.<br />
    I have created 2 decks that are 30 cards big and adhere to the game's rules (2 Ace Creatures, 1 Legend Creature, 2 Ace Support Cards, 1 Legend Support Card) with a full breakdown of the decks in the updates section. I have also reconfigured all loops that display card details and have also edited the battle stage method in the App class. I think possible future changes would be to allow decks to be edited before a game and to be saved and stored somewhere, as well as having 2 separate displays so your opponent can't see your hand.<br />
    As always, the entire project is available at this GitHub repository: <a href="https://github.com/CulverT01/cardgameplayer">https://github.com/CulverT01/cardgameplayer</a>
    </p>
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Updates</h2>
    <p class="col-8"> 
    The decks are built in a separate class called DeckLoad and each deck has their own static ArrayList method which is called when the player object is constructed. Each deck has 15 Creature Cards and 15 Support Cards, with player 1's deck (set from the loadDeck1 method) containing Melee Creatures and Item Support Cards, while player 2's deck (set from the loadDeck2 method) uses only Magic Creatures and Magic Support Cards.<br/>
    Player 1's deck is shown below in these images.<br/>
    <img src="deckload_1.png" alt="Screenshot of the first 24 cards and their details for the deck of player 1 from the deck load 1 method in the deck load class"><br/>
    <img src="deckload_2.png" alt="Screenshot of the last 6 cards and their details for the deck of player 1 from the deck load 1 method in the deck load class">
    </p>
    <p class="col-8">
    Player 2's deck is shown below in these images.<br/>
    <img src="deckload_3.png" alt="Screenshot of the first 24 cards and their details for the deck of player 2 from the deck load 2 method in the deck load class"><br/>
    <img src="deckload_4.png" alt="Screenshot of the last 6 cards and their details for the deck of player 2 from the deck load 2 method in the deck load class">
    </p> 
  </div>
  <div class="row justify-content-center">
    <h2 class="row">Changes and Clarifications</h2>
    <p class="col-8">
    The loops that display card details have all been all reconfigured because the intention was to have the cards displayed in a row horizontally, but the way I had still put them down  vertically. The assumption was to fix it at some point, but it became less and less of a priority until it was abandoned and went for a more vertical display, although I might try for a more horizontal display in the future.<br/> 
    The battleStage method was changed as originally the method had the Creatures attack in the order they are stored in the frontline array, but if you wanted a certain Creature to attack later (as it had a higher attack stat and could inflict more damage at your opponent directly), then the only way was to have it to be added to the frontline array towards the back, which is not always possible, given the fact that Creature Cards are always to added to the first available position in the array, so allowing the player to choose the order in which Creatures attack is more player friendly.<br/>
    The new battleStage method is shown below.<br/>
    <img src="app_5.png" alt="Screenshot of the first part of the revised battle stage method of the app class"><br/>
    <img src="app_6.png" alt="Screenshot of the second part of the revised battle stage method of the app class">
    </p>
  </div>
</div>
