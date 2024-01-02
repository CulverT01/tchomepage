---
title: Functions and Control Flow 2 - Electric Boogaloo.
description: More Evidence on the understanding of JavaScript functions and control flow.
date: 2024-01-01
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Functions and Control Flow 2 - Electric Boogaloo.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    As functions are so integral to JavaScript, I have more examples of them below, this time using a switch case statement instead of a if/else statement. The functions do as described: <br />
    Function 1 calculates the precentage of a number based on what the user inputs and outputs to the users browser<br />
    Function 2 returns a message based on what the value is of the buttonName argument variable passed through, with another argument being the size of the drink itself and that reflected in the message <br />
    Function 3 returns the answer to a calculation based on what 2 numbers and an operator (+,-,*,/) are passed through the function as arguments. 
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
        //Task 1 Function
        function percentageCalculator(number, percentage){
            let calculator = number * (percentage / 100);
            alert('Your answer is ' + calculator);
        }
        let number =  prompt('Enter a number');
        let percentage =  prompt('Enter a percentage');
        //Calling Task 1
        percentageCalculator(number, percentage);
        //Task 2 Function
        function drinkOrder(size, buttonName){
            let message;
            switch (buttonName){
                case 'cola':
                    message = 'You have ordered a ' + size + ' of Cola';
                    return message;
                case 'lemon':
                    message = 'You have ordered a ' + size + ' of Lemonade';
                    return message;
                case 'orange':
                    message = 'You have ordered a ' + size + ' of Orangeade';
                    return message;
                default:
                    return 'Incorrect type of drink';        
            }
        }
        let size = 'Medium';
        let buttonName = 'cola';
        //Calling Task 2
        console.log(drinkOrder(size,buttonName));
        //Task 3 Function
        function calculator(num1, num2, operator) {
            switch (operator) {
            case "+":
                return num1 + num2;
            case "-":
                return num1 - num2;
            case "*":
                return num1 * num2;
            case "/":
                return num1 / num2;
            default:
                return 'Invalid operator';
            }
        }
        //Calling Task 3
        console.log(calculator(5,4,'+'));
        console.log(calculator(5,4,'-'));
        console.log(calculator(5,4,'*'));
        console.log(calculator(5,4,'/'));
    </pre>
  </div>
</div>
