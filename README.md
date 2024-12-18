###### Accelerator Track One

# JavaScript Functions Drills

For this lab, you'll practice creating and using functions in JavaScript. You'll start with simple functions and gradually work up to more complex problems involving parameters, return values, and higher-order functions.

### Instructions:
In **functions.js**, complete each prompt by writing a JavaScript function that satisfies the requirements. Make sure to **invoke each function** to run your code and verify it works as expected.

```js
function example(){
    console.log('This function prints this message, but returns undefined')
}

example()

// => This function prints this message but returns undefined
// => undefined
```

---

## Functions Without Parameters

1. **Basic Function**  
   Write a function named `greet` that prints "Hello, World!" to the console.

---

## Functions with Parameters

2. **Single Parameter Function**  
   Write a function named `greetPerson` that takes in a `name` parameter and prints "Hello, [name]!" to the console.

3. **Multiple String Parameters**  
   Write a function named `introducePerson` that takes in two parameters: `name` and `occupation`. It should print "Hi, my name is [name] and I am a [occupation]."

4. **Number Parameter**  
   Write a function named `doubleNum` that takes in a number and returns its double.

5. **Multiple Number Parameters**  
   Write a function named `addNums` that takes in two numbers and returns their sum.

6. **Mixed Parameters**  
   Write a function named `describePet` that takes in three parameters: `petName` (string), `species` (string), and `age` (number). It should print "My pet [petName] is a [age]-year-old [species]."

---

## Functions Returning Values

7. **Check Even or Odd**  
   Write a function named `isEven` that takes in a number and returns `true` if the number is even and `false` if the number is odd.

8. **Calculate Area of a Rectangle**  
   Write a function named `calculateArea` that takes in two parameters: `length` and `width`, and returns the area of the rectangle.

9. **Reverse a String**  
   Write a function named `reverseString` that takes in a string and returns the reversed version of the string.

10. **Count Vowels in a String**  
    Write a function named `countVowels` that takes in a string and returns the number of vowels in the string.

11. **Return Object from Mixed Parameters**  
   Write a function named `createPet` that takes in three parameters: `petName` (string), `species` (string), and `age` (number). It should return an **object with the keys**: 'name', 'species', 'age'.

---

## BONUS: Advanced Functionality

12. **Function with Default Parameters**  
    Write a function named `welcomeMessage` that takes in a `name` parameter and prints "Welcome, [name]!" If no name is provided, the function should default to "Guest."

13. **Function Calling Another Function**  
    Write a function named `calculateAndLog` that takes in two numbers, calls the `addNumbers` function to calculate their sum, and logs the result to the console.

14. **Arrow Function**  
    Rewrite the `doubleNumber` function as an arrow function named `doubleNum`.

15. **Higher-Order Function**  
    Write a function named `applyFunction` that takes in two parameters: a number and a callback function. It should apply the callback to the number and return the result.

    Example:
    ```javascript
    const result = applyFunction(5, doubleNum);
    console.log(result); // Should print 10
    ```

---

### Submission Instructions:
- Complete all drills in the file **functions.js**.
- Test each function to ensure it works as expected.
- Push your completed work to your repository and submit the link on Google Classroom.
- Be prepared to explain how your code works during a follow-up discussion.

Good luck and happy coding! 🚀
