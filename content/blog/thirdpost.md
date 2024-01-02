---
title: Tipping the JavaScript.
description: Evidencing the understanding of JavaScript variables.
date: 2023-12-31
tags:
  - javascript
  - web skill evidence
---

<div class="container fluid">
  <h1 class="col align-self-center">Tipping the JavaScript.</h1>
  <div class="row justify-content-center">
    <p class="col-8">
	As a part of the Coders Guild Bootcamp on for Web Design and Development Skills, I studied and learnt about JavaScript. This post and the next few will demonstrate various key uses of JavaScript. Down below is a program that calculates the cost of the overall bill and from how much it originally cost and the percentage of tip that they will provide.
    </p>
	<h3 class="row">JavaScript Code</h3>
	<pre class="col-8">
	let foodCost = prompt('Enter the cost of food:');
	let tipPercent = prompt('Percentage of cost to be tipped:');
	var tipAmount = (Number(foodCost) * Number(tipPercent))/ 100;
	var totalBill = Number(foodCost) + tipAmount;
	alert('Total bill is: £' + totalBill.toFixed(2));	
	</pre>
  </div>
</div>



