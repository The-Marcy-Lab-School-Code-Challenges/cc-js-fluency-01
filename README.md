# Code Challenge: JavaScript Fluency
## Instructions

1. Clone down this assignment to AWS Cloud9. 
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Description of the Problem

1. Create a function, `halved` that takes an array of numbers and returns an new array consisting of those numbers, halved.

2. Create a function, `onlyPositive`, that takes an array of numbers and returns a new array consisting only of the positive numbers.

3. Write a function, `sum`, that takes an array of numbers and returns the sum of those numbers.

3. Create a function called `strippedStrings` that takes an array of strings and returns a new array of the strings with all non-alphanumeric characters removed.

2. Create function, `findSpecial`, that takes an array of words and returns the index of the first occurrence of the word "special". If the word "special" is not present, it should return, `-1`.

4. Create a function called `validContacts`. This function takes an array of `contact` objects (`name` and `phoneNumber` property, remember?). It should return an array of only `contact` objects that have a `phoneNumber` that is a 10-digit string.
      ```javascript
      const contacts = [
        {name: 'Reuben', phoneNumber: '9196218777'},
        {name: 'Laisha', phoneNumber: '0123334766'},
        {name: 'Cielo', phoneNumber: '764'},
        {name: 'Maya', phoneNumber: '7653324599'}
      ];

      validContacts(contacts);
      /* returns
      [
        {name: 'Reuben', phoneNumber: '9196218777'},
        {name: 'Laisha', phoneNumber: '0123334766'},
        {name: 'Maya', phoneNumber: '7653324599'}
      ]
      */
      ```

5. Create a function, `contactNames`, that takes an array of `contact` objects and returns an array of `contact` `name`s.
      ```javascript
       const contacts = [
        {name: 'Reuben', phoneNumber: '9196218777'},
        {name: 'Laisha', phoneNumber: '0123334766'},
        {name: 'Cielo', phoneNumber: '764'},
        {name: 'Maya', phoneNumber: '7653324599'}
      ];

      contactNames(contacts); // ['Reuben', 'Laisha', 'Cielo', 'Maya'];
      ```
