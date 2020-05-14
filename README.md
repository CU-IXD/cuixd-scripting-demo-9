# Scripting Lesson 9 Demo Starter

Run local development using the following:

```
npm install
npm start
```

## Instructions

Let's practice adding conditional statements.

1. Declare a variable called `name` and assign a string to it containing any name you'd like.

2. Did you know that you can measure the number of characters in a string like this:

  ```js
  var name = "My name";
  var strSize = name.length;
  // strSize now contains the number 7
  ```
  
  So add this variable storing the number of characters in `name`.

3. Add a conditional statement based on the following prompt: 

> If `name` is more than 8 characters, log this message: "You have a long name!"

Did you get it to work? Try changing the value of the name you entered to see how this changes. If you enter a "long" name you should see the message. Otherwise you should not see a message. But let's make that a little smarter.

4. Modify the conditional statement to match the following prompt:

> If `name` is more than 8 characters, log this message: "You have a long name!" Otherwise log this message: "You have a pretty normal-sized name."

Did you see a difference this time? You should see a message regardless of the length, but the message should be different depending on the length. Let's go one step further.

5. Modify the conditional statement to match the following prompt:

> If `name` is more than 15 characters, log this message: "You have a REALLY long name!" Or if `name` has between 15 and 8 characters, log this message: "You have a long name!" Otherwise log this message: "You have a pretty normal-sized name."

Now let's apply what we've learned to a simple example in our application. We'll listen for the form to be submitted. When it is, we'll prevent the default action and instead, calculate the price of the order based on the user's desired quantity and the price of the shirt size they selected. 

1. Add the event listener
2. Prevent the default action 
3. Store the current value of the quantity and size fields in variables. Be sure to consider whether either or both of these need to be converted to variables.
4. Declare a placeholder variable called `sizePrice` and set it to `0` to start.

Now we need to calculate the order cost. To do this we'll need to determine the price for the size the user has selected:

> If the user has selected `xs` then the `sizePrice` should be 5; or if the user has selected `s` the `sizePrice` should be 6; or if the user selected `m` the `sizePrice` should be 7; otherwise, `sizePrice` should be 8.

5. Add a conditional statement structure that sets the appropriate value to `sizePrice`. 
6. After the correct price is set, calculate the order cost by multiplying the `sizePrice` and the quantity. Store the result in `orderTotal`.
7. Display the order total inside `#message`.

