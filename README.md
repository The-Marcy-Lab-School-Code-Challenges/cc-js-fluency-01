# Code Challenge: JavaScript Fluency
## Instructions

1. Clone down this assignment to AWS Cloud9. 
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Description of the Problem
**solve the following problems using higher order array methods**

1. Create a function, `halved` that takes an array of numbers and returns an new array consisting of those numbers, halved.
```js
halved([1,2,3,4]) //[.5, 1, 1.5, 2]
```

2. Create a function, `onlyPositive`, that takes an array of numbers and returns a new array consisting only of the positive numbers.
```js
onlyPositive([-1,2,3,-14]) // [2,3]
```

3. Write a function, `sum`, that takes an array of numbers and returns the sum of those numbers.
```js
sum([-1,2,3,-14]) // -10
```

3. Create a function called `strippedStrings` that takes an array of strings and returns a new array of the strings with all non-alphanumeric characters removed.
```js
strippedStrings(["hello!", "code-challenge","marcy"]) // ["hello", "codechallenge","marcy"]
```

2. Create function, `findSpecial`, that takes an array of words and returns the index of the first occurrence of the word "special". If the word "special" is not present, it should return, `-1`.
```js
findSpecial(["special", "code-challenge","special"]) // 0
```

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
