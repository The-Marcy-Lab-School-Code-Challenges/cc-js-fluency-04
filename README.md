# Code Challenge: JavaScript Fluency

## Instructions

1. Clone down this assignment to your local environment.
2. Code your solution using JavaScript in `index.js`.
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Problems

**Solve the following problems using higher order array methods**

**Test all your solutions for the questions 1-4 with the following variable:**

```
const alumni = [
{name:'Stephanie', job:'JPMorgan',language:'JavaScript', age:24},
{name:'Devonte', job:'SquareSpace',language:'JavaScript', age:26},
{name:'Enmanuel', job:'Asana',language:'JavaScript', age:23},
{name:'Cielo', job:'NYT',language:'JavaScript', age:23},
{name:'Carmen', job:'Marcy Lab School',language:'JavaScript', age:24}
]
```

1. Write a function named `updateLanguage` that takes an array of objects and updates the language property of each object to `ES6` if the language is JavaScript.
    
    ```jsx
    updateLanguage(alumni) // returns [
      { name: 'Stephanie', job: 'JPMorgan', language: 'ES6', age: 24 },
      { name: 'Devonte', job: 'SquareSpace', language: 'ES6', age: 26 },
      { name: 'Enmanuel', job: 'Asana', language: 'ES6', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'ES6', age: 23 },
      { name: 'Carmen', job: 'Marcy Lab School', language: 'ES6', age: 24 }
    ]
    ```
    
2. Write a function named `oddJob` that takes an array of objects and returns an array of objects if the job property length is an odd number.
    
    ```jsx
    oddJob(alumni) //returns [
      {
        name: 'Devonte',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 26
      },
      { name: 'Enmanuel', job: 'Asana', language: 'JavaScript', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'JavaScript', age: 23 }
    ]
    ```
    
3. Write a function named `orderedAlumni` that takes an array of objects and sorts the objects by the age property, in order of oldest to youngest.
    
    ```jsx
    orderedAlumni(alumni) // returns [
      {
        name: 'Devonte',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 26
      },
      {
        name: 'Stephanie',
        job: 'JPMorgan',
        language: 'JavaScript',
        age: 24
      },
      {
        name: 'Carmen',
        job: 'Marcy Lab School',
        language: 'JavaScript',
        age: 24
      },
      { name: 'Enmanuel', job: 'Asana', language: 'JavaScript', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'JavaScript', age: 23 }
    ]
    ```
    
4. Write a function named `averageAge` that takes an array of objects and returns the average of all the ages from each age property in each object rounded to the nearest whole number.
    
    ```jsx
    averageAge(alumni) // 24
    ```
    
5. Write a function named `ninetiesBabies` that takes an array of objects and returns an array of only the objects where the age property is larger than 21.
    
    ```jsx
    ninetiesBabies(alumni) // returns [
      {
        name: 'Devonte',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 26
      }
    ]
    ```
    
6. Write a function named `allUseJavaScript` that takes an array of objects and returns a boolean if for every object, the language property is 'JavaScript'.
    
    ```jsx
    allUseJavaScript(alumni) // returns true
    ```
