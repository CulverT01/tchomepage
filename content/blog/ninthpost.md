---
title: The DOMinator.
description: Example of working with the DOM.
date: 2024-01-06
tags: 
    - javascript
    - web skill evidence
---
<div class="container fluid">
    <div class="font-monospace">
        <h1 class="col align-self-center">The DOMinator.</h1>
        <div class="row justify-content-center">
            <p class="col-8">
            Below is some JavaScript designed to interact with the DOM to create a to-do list which filled out using a form on html page (not shown). The code allows for new html elements to created and displayed on the webpage. <br />
            This will be my last post exhibiting work I have done during my time at the The Coders Guild Skills Boot-camp for Web Design and Development, but if you're interested in them, here is a link to their website:<br />
            <a href="https://thecodersguild.org.uk/" class="fs-3">The Coders Guild</a>
            </p>
            <h3 class="row">JavaScript Code</h3>
            <pre class="col-8">
            // Store the URL of an image for each priority level.
            const priorityImages = {
            low: 'https://cdn1.iconfinder.com/data/icons/prettyoffice8/256/Flag-green.png',
            medium: 'https://cdn1.iconfinder.com/data/icons/prettyoffice8/256/Flag-yellow.png',
            high: 'https://cdn1.iconfinder.com/data/icons/prettyoffice8/256/Flag-red.png',
            };
            // Get the form by ID from the forms collection.
            const form = document.getElementById('todo');
            // Get the todo pane (the 'ul' element) to insert todos into.
            const todoPane = document.getElementsById('todo-pane');
            // Get the text input for the title.
            const titleInput = form.elements.title;
            // Get the priority select element. 
            const prioritySelect = form.elements.priority;
            // Get a *live* list of all elements with the 'todo' class.
            const allTodos = document.getElementsByClassName('todo');
            //An event listener that will
            //1. Create a new todo. The details come from the form.
            //2. Inserts it into the DOM.
            //3. Clears the title input ready to create a new todo note.
            //4. Prevents the default behaviour (e.g don't submit to a server).
            form.addEventListener('submit', (event) => {
            for (const todo of allTodos) {
                todo.classList.remove('just-created');
            };
            const newTodo = createTodo(titleInput.value, prioritySelect.value);
            todoPane.appendChild(newTodo);
            form.reset();
            event.preventDefault();
            });
            //Function that creates new todo item
            function createTodo(title, priority) {
            const newtitle = document.createTextNode(title);
            const newItem = document.createElement('div');
            newItem.appendChild(newtitle);
            const todo = document.createElement('li');
            const image = document.createElement('img');
            image.src = priorityImages(priority);
            todo.appendChild(image);
            todo.appendChild(newItem);
            todo.setAttribute('title', 'Delete');
            todo.classList.add('todo', 'just-created');
            //Add delete listener
            todo.addEventListener('click', function (event) {
                event.currentTarget.remove();
            });
            return newItem;
            }
            </pre>
        </div>
    </div>
</div>