---
title: Four functions and seven years ago.
description: Evidencing the understanding of JavaScript functions and control flow.
date: 2024-01-01
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Four functions and seven years ago.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
	This blog exhibts my understanding of functions as well as control flow, through the use of if/else statements. Below are 4 functions which all do different things:<br />
    Function 1 outputs an alert to the users browser when the function is run<br />
    Function 2 outputs to the console a persons first and last name which are taken as arguments in the function<br />
    Function 3 operates the same as 2, but uses a return statement instead to control the data type of the returned value<br />
    Function 4 uses an if/else if/else statement that changes what statement is outputted to the console depending on what number is passed through as an argument in the function
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
	//Function 1 
    function Sentence(){ 
        alert('Hello World');
    }
    //Calling function 1
    Sentence();
    //Function 2
    function FullName(first, last){
        console.log(`${first} ${last}`);
    }
    //Calling function 2
    FullName('Toby', 'Culverwell'); 
    //Function 3
    function FullName2(first2, last2){
        const fullName = first2 + ' ' + last2;
        return fullName;
    }
     //Calling function 3
    console.log(FullName2('Frank', 'Sinatra')); 
    //Function 4
    function TemperatureCheck(temperature){
        if (temperature < 0) {
            console.log('Stay Inside');
        }
        else if (temperature < 30) {
            console.log('Wear a coat and hat');
        }
        else if(temperature < 50){
            console.log('Wear a coat');
        }  
        else{ 
            console.log('Pants and vest are fine');
        }
    }
    //Calling function 4
    const num1 = 35;
    const num2 = 25;
    const num3 = -5;
    const num4 = 55;
    TemperatureCheck(num1);
    TemperatureCheck(num2);
    TemperatureCheck(num3);
    TemperatureCheck(num4);
    </pre>
  </div>
</div>

