# Task 10: Test TaskManager

## Description

In our final task, we'll test our `TaskManager` class using Mocha.

## Walkthrough

### Step 1: Add Mocha to the project

> #### Useful Resources for this step
> - [Mocha - Getting Started](https://mochajs.org/#getting-started)

In this step, we'll add Mocha to our project.

1. Install Mocha as development dependency for your project:
    ```Javascript
      npm install --save-dev mocha
    ```
2. Create a new test directory and a test.js file to add your tests:
  - `mkdir test`
  - `$EDITOR test/test.js # or open with your favorite editor`


### Step 2: Testing TaskManager Methods

> #### Useful Resources for this step
> - [Mocha - Getting Started](https://mochajs.org/#getting-started)

In this step, we'll test some of the methods that exist on our `TaskManager` class.

1. Use what you have learnt on testing to unit test the following methods on the `TaskManager` class:
  - `addTask`
  - `deleteTask`
  - `getTaskById`
5. Add a test case that tests how the `TaskManager` is initialized, ie: the `constructor` being called when a `new TaskManager()` is initialized.

> #### Test Your Code!
> Now is a good chance to test your code:

> 1. Run your tests with `npm test`.

>  **Expected Result**
>  You should see the tests all pass, green! 

### JWD 3 - YOU DO NOT NEED DO THIS STEP - IT IS OPTIONAL 

### Step 3: Testing TaskManager Methods - CHALLENGE (OPTIONAL)

> #### Useful Resources for this step
> - [Running Mocha in the Browser](https://mochajs.org/#running-mocha-in-the-browser)

In this step, we'll test the remaining methods on our `TaskManager` class. These are much more tricky than the previous methods, so make good use of the provided [Mocha Github example](https://github.com/mochajs/mocha-examples) if you get stuck.

Make sure to adjust any examples you reference to fit your code.

1. Use what you have learnt on testing to unit test the following methods on the `TaskManager` class:
  - `render`
  - `save`
  - `load`

## Results

Run your test and make sure they all passed!

Your task should meet the assesment criteria in the **Final Project - Scorecard Rubric**.

## Example

Stuck? Check out the provided example in the [Mocha Github example](https://github.com/mochajs/mocha-examples)

