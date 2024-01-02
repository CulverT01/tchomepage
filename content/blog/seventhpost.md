---
title: Arrays and Objects on Loop.
description: Exampling loops, arrays and objects.
date: 2024-01-04
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Arrays and Objects on Loop.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    More key elements of JavaScript are arrays, loops and objects. Arrays are like lists for JavaScript as you can store items, like food items, in them and add or remove items if need be. To output an entire list, you will have to loop through them.<br /> 
    Objects are variables that can store multiple bits of information relating to something. For example, a person can represented by an object as they will have information such as name, age, height, etc. <br />
    Below are examples of loops, arrays, objects, looping through arrays, objects with arrays, looping through objects with arrays.
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
    //Example 1
    function timesTable(number){
        for(let i = 1; i < 13; i++){
            let multiple = i * number;
            console.log(`${i} x ${number} = ${multiple}`);
        }
    }
    let number = 7;
    timesTable(number);
    </pre>
    <p class="col-8">
    More key elements of JavaScript are arrays, loops and objects. Arrays are like lists for JavaScript as you can store items, like food items, in them and add or delete items if need be. To output an entire list, you will have to loop through them.<br /> 
    Objects are variables that can store multiple bits of information relating to something. For example, a person can represented by an object as they will have information such as nationality, eye colour, weight, etc. <br />
    Below are examples of arrays, objects, loops, objects with arrays, looping through objects with arrays, looping through arrays,.
    </p>
    <h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
    //Example 2
    const favfoods = ['Cheese', 'Marmite', 'Tomato Ketchup', 'Pizza'];
        console.log(favfoods[1] + ' ');
        console.log(favfoods[0]);
    //Example 3
    console.log('Task 3');
    function allFavFoods(favfoods){
        for (let i = 0; i < favfoods.length; i++){
            console.log(`Item in position ${i} is ${favfoods[i]}. \n`);
        }
    }
    allFavFoods(favfoods);
    </pre>
    <p class="col-8">
    More key elements of JavaScript are objects, arrays and loops. Arrays are like lists for JavaScript as you can store items, like food items, in them and put in or delete items if need be. To output an entire list, you will have to loop through them.<br /> 
    Objects are variables that can store multiple bits of information relating to something. For example, a person can represented by an object as they will have information such as hometown, hair colour, favourite colour, etc. <br />
    Below are examples of objects, loops, arrays, looping through objects with arrays, looping through arrays, objects with arrays.
    </p>
    <h3 class="row">JavaScript Code</h3>
    <pre class="col-8">
    //Example 4
    const favReceipe = {
        title: 'Tomato Ketchup and Cheese Toastie',
        servings: 1,
        ingredients: [['slices of bread', '2'],['Cheese', '50g'],['Tomato Ketchup', '2tbp'],['Butter', '10g']],
        instructions: ['Spread the butter across the 2 slices of bread', 
        'Grate the cheese and sprinke it over on of the slices', 
        'Spread the Tomato Ketchup over the other slice and place it on top of the cheese slice', 
        'PLace on a medium/high grill for 5 minutes or until the cheese has melted'] 
    }
    function receipeDetails(favreceipe){
        console.log(`Title: ${favreceipe.title}. \n`);
        console.log(`servings: ${favreceipe.servings}. \n`);
        console.log(`Ingredients: \n`);
        for(let i = 0; i < favreceipe.ingredients.length; i++){
            console.log(`\t ${favreceipe.ingredients[i]}\n`);
        }
        console.log(`Instructions: \n`);
        for(let i = 0; i < favreceipe.instructions.length; i++){
            console.log(`\t ${favreceipe.instructions[i]}\n`);
        }
    }
    receipeDetails(favReceipe);
    //Example 5
    function letsCook(receipe){
        console.log(`I'm Hungry, Hey Let's cook ${receipe.title}`);
    }
    letsCook(favReceipe);
    </pre>
  </div>
</div>