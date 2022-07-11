# Task 4: Task Form Inputs Validation

## Description

Implement a form that captures the fields required to create a task.


> #### Tools
> - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
> - [Bootstrap](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
> - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
      
    
## Walkthrough

### Step 1: Add a task form

In this step, we'll add a form to create a new task.

1. Add a button to submit your form.

> #### Useful Resources for this step
> - [Forms](https://getbootstrap.com/docs/4.5/components/forms/)
> - [Buttons](https://getbootstrap.com/docs/4.5/components/buttons/) 

### Step 2: Implement a JavaScript function to validate your form fields

1. Create a JavaScript file named `index.js` and include it into your `index.html` page.
2. Implement a JavaScript function named `validFormFieldInput(data)`
3. Add an ID attribute to each form field and implement the code needed to retrieve the each form field value using the following method:
      ```javascript
       const newTaskNameInput = document.querySelector('#newTaskNameInput');
       const name = newTaskNameInput.value;
      ```
4. Log your field inputs to verify that you are getting the data you need to validate.
      ```javascript
       const newTaskNameInput = document.querySelector('#newTaskNameInput');
       const name = newTaskNameInput.value;
       console.log("name:  "+name);
      ```
> #### Useful Resources for this step
> - [Forms](https://getbootstrap.com/docs/4.5/components/forms/)
> - [Query selector documentation](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)


### Step 3: Showing errors to users

1. Add a [Bootstrap alert component](https://getbootstrap.com/docs/4.5/components/alerts/) inside your form to display the errors to the users.
2. Add the logic to display or hide the error message when the form is submited.
3. Display a meaningful error when a form filed is invalid and the user clicks the submit button.
4. Add the logic to hide the error message when the user clicks the submit button and the form data is valid.
    
> #### Useful Resources for this step
> - [Bootstrap alert component](https://getbootstrap.com/docs/4.5/components/alerts/)
> - [Document.querySelector() documentation](https://www.w3schools.com/howto/howto_js_toggle_hide_show.asp)


> #### Test Your Code!
> Now is a good chance to test your code, open your `index.html` page and fill in wrong data on the form and check if the right error is shown.
> Verify also that when the form fields are correct then no error message is displayed.

## Results

We've now create your task form with the JavaScript validations to make sure the user submits correct data!

Your task should meet the assesment criteria in the **Final Project - Scorecard Rubric**.



