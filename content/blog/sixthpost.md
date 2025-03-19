---
title: Comments that are too Pseudocode.
description: Demonstrating Pseudocode and comments in JavaScript.
date: 2024-01-03
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Comments that are too Pseudocode.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    Have you ever looked a piece of code and wondered if it could be in a universal programming language that anyone could understand - even non-programmers?<br />
    Well Good News!! There is Pseudocode, which uses an easy to read and understand syntax to do just that and I have an example of some Pseudocode of a list of books that when iterated through will tell you  whether or not you have read the book or not below.
    </p>
    <h3 class="row">Pseudocode</h3>
    <pre class="col-8">
    Task 2: Reading List
        ARRAY = 'Dragon and Ceremony - From a Wandmaker's Perspective by Ichimei Tsukushi': Read (TRUE), 
        'Sweetness & Lightning Vol 8 by Gido Amagakure': Read (TRUE), 
        'Kuma Kuma Kuma Bear by Kumanano Vol 16': Unread (FALSE);
        FOR NUMBER Less Than the Length of ARRAY:
            IF Item NUMBER in ARRAY = Read THEN:
                PRINT 'You have already read ' Item NUMBER in ARRAY;
            ELSE:
                PRINT  'You still need to read ' Item NUMBER in ARRAY;
    </pre>
    <h3 class="row">Alternatives to Pseudocode</h3>
    <p class="col-8">
    Now if Pseudocode isn't your thing because you can't program working software with it, then there are comments which you can use to add notes to program explaining what each line of code is doing. In JavaScript a for a line to be a comment it must start with a double slash (//) and each programming language will have its own way of commenting.<br />
    As an example, I have included function 4 from 'Four functions and seven years ago' blog post, now with comments which you'll know because they all be in green.
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
    <span class="text-success">//Run function TemperatureCheck passing temperature variable as an argument</span>
    function TemperatureCheck(temperature){
        <span class="text-success">//If temperature is less than 0 then:</span>
        if (temperature < 0) {
            <span class="text-success">//Output to the console 'Stay Inside'</span>
        console.log('Stay Inside');
    }
    <span class="text-success">//Else, if temperature is less than 30 then:</span>
    else if (temperature < 30) {
            <span class="text-success">//Output to the console 'Wear a coat and hat'</span>
        console.log('Wear a coat and hat');
    }
    <span class="text-success">//Else, if temperature is less than 50 then:</span>
    else if(temperature < 50){
            <span class="text-success">//Output to the console 'Wear a coat'</span>
        console.log('Wear a coat');
    }
    <span class="text-success">//Else then:</span>  
    else{ 
        <span class="text-success">//Output to the console 'Pants and vest are fine'</span>
        console.log('Pants and vest are fine');
    }
    }
    <span class="text-success">//Set num1 as a constant with a value of 35</span>
    const num1 = 35;
    <span class="text-success">//Set num2 as a constant with a value of 25</span>
    const num2 = 25;
    <span class="text-success">//Set num3 as a constant with a value of -5</span>
    const num3 = -5;
    <span class="text-success">//Set num4 as a constant with a value of 55</span>
    const num4 = 55;
    <span class="text-success">//Call TemperatureCheck function with num1 passed as a temperature argument</span>
    TemperatureCheck(num1);
    <span class="text-success">//Call TemperatureCheck function with num2 passed as a temperature argument</span>
    TemperatureCheck(num2);
    <span class="text-success">//Call TemperatureCheck function with num3 passed as a temperature argument</span>
    TemperatureCheck(num3);
    <span class="text-success">//Call TemperatureCheck function with num4 passed as a temperature argument</span>
    TemperatureCheck(num4);
    </pre>
  </div>
</div>