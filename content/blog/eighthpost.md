---
title: Arrays and Objects on Loop (Remix).
description: Example of a loop and an object.
date: 2024-01-05
tags: 
    - javascript
    - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Arrays and Objects on Loop (Remix).</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    Another 2 Examples of an object, an array and a loop. In the 1st example we have an object that can be looped through in order to calculate the total of a shopping cart, taking in account any discounts that may apply, and then outputting the result to the console.<br /> 
    The 2nd example takes the same object and stores the items whose total price (item price x item quantity) is between 2 and 5.
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
     //Example 1
    const shoppingCart = [
    { name: "loaf of bread", type: "food", quantity: 1, price: 0.85 },
    { name: "multipack beans", type: "food", quantity: 1, price: 1 },
    { name: "mushrooms", type: "food", quantity: 10, price: 0.1 },
    { name: "can of beer", type: "alcohol", quantity: 4, price: 1.1 },
    { name: "prosecco", type: "alcohol", quantity: 1, price: 8.99 },
    { name: "steak", type: "food", quantity: 2, price: 3.99 },
    { name: "blue cheese", type: "food", quantity: 1, price: 2.99 },
    { name: "candles", type: "home", quantity: 3, price: 1.99 },
    { name: "cheesecake", type: "food", quantity: 1, price: 4.99 },
    { name: "onions", type: "food", quantity: 3, price: 0.4 }
    ];
    function totalPrice(shoppingCart, type, discount){
        let total = 0;
        let discountAmount = (100 - discount) / 100;
        for (let i = 0; i < shoppingCart.length; i++){
            if (shoppingCart[i].type === type || type === 'any'){
                shoppingCart[i].price = shoppingCart[i].price * discountAmount;
            }
            total = total + (shoppingCart[i].price * shoppingCart[i].quantity);
        }
        return total; 
    } 
    let type = prompt('What type has a discount');
    let discount = prompt('What is the discount')
    let result = totalPrice(shoppingCart, type, discount);
    console.log(`Total: £${result.toFixed(2)}`);
    //Example 2
    const shoppingCart = [
    { name: "loaf of bread", type: "food", quantity: 1, price: 0.85 },
    { name: "multipack beans", type: "food", quantity: 1, price: 1 },
    { name: "mushrooms", type: "food", quantity: 10, price: 0.1 },
    { name: "can of beer", type: "alcohol", quantity: 4, price: 1.1 },
    { name: "prosecco", type: "alcohol", quantity: 1, price: 8.99 },
    { name: "steak", type: "food", quantity: 2, price: 3.99 },
    { name: "blue cheese", type: "food", quantity: 1, price: 2.99 },
    { name: "candles", type: "home", quantity: 3, price: 1.99 },
    { name: "cheesecake", type: "food", quantity: 1, price: 4.99 },
    { name: "onions", type: "food", quantity: 3, price: 0.4 }
    ];
    function betweenPrices(lowPrice, highPrice,quantity,shoppingCart){
        const arrItems = [];
        let totalPrice = 0;
        for(let i = 0;  i < shoppingCart.length; i++){
            if(quantity == true){
                totalPrice = shoppingCart[i].price * shoppingCart[i].quantity;
                if(totalPrice >= lowPrice && totalPrice <= highPrice){
                    arrItems.push(shoppingCart[i]);
                }      
            }
            else{
                if(shoppingCart[i].price >= lowPrice && shoppingCart[i].price <= highPrice){
                    arrItems.push(shoppingCart[i]);  
                }
                else{
                    console.log(`${shoppingCart[i].name} is not in between prices`);
                } 
            }
        }
        for(let j = 0; j < arrItems.length; j++){
            console.log(`${arrItems[i]}`);
        }
    }
    betweenPrices(2,5,true,shoppingCart);
    </pre>
  </div>
</div>