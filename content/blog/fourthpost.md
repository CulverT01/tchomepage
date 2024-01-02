---
title: Four functions and seven years ago.
description: Evidencing the understanding of JavaScript functions and control flow.
date: 2024-01-01
draft: true
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Four functions and seven years ago.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
	This blog exhibts my understanding of functions as well as control flow, through the use of if/else statements. Below are 4 functions which all do different things:<br />
    Function 1 outputs an alert to the users browser when the function is run <br />
    Function 2 outputs to the console a persons first and last name which are taken as arguments in the function <br />
    Function 3 operates the same as 2, but uses a return statement instead to control the data type of the returned value<br />
    Function 4 uses an if/else if/else statement that changes what statement is outputted to the console depending on what number is passed through as an argument in the function
    </p>
	<h3 class="row">JavaScript Code</h3>
	<p class="col-8">
	//Function 1 <br />
    function Sentence(){ <br />
        alert('Hello World');<br />
    }<br />
    //Calling function 1<br />
    Sentence();<br />
    <br />
    //Function 2<br />
    function FullName(first, last){<br />
        console.log(`${first} ${last}`);<br />
    }<br />
    //Calling function 2<br />
    FullName('Toby', 'Culverwell');<br />
    <br />
    //Function 3<br />
    function FullName2(first2, last2){<br />
        const fullName = first2 + ' ' + last2;<br />
        return fullName;<br />
    }<br />
     //Calling function 3<br />
    console.log(FullName2('Frank', 'Sinatra'));<br />
    <br />
    //Function 4<br />
    function TemperatureCheck(temperature){<br />
        if (temperature < 0) {<br />
            console.log('Stay Inside');<br />
        }<br />
        else if (temperature < 30) {<br />
            console.log('Wear a coat and hat');<br />
        }<br />
        else if(temperature < 50){<br />
            console.log('Wear a coat');<br />
        }<br />  
        else{<br /> 
            console.log('Pants and vest are fine');<br />
        }<br />
    }<br />
    //Calling function 4<br />
    const num1 = 35;<br />
    const num2 = 25;<br />
    const num3 = -5;<br />
    const num4 = 55;<br />
    TemperatureCheck(num1);<br />
    TemperatureCheck(num2);<br />
    TemperatureCheck(num3);<br />
    TemperatureCheck(num4);<br />
    </p>
  </div>
</div>

