# Lesson 2.4: Loops

### ➰ for loops

- For loops are used to repeat code based on a set of parameters.
- They are useful for iterating over array elements.
- Key components of a for loop:
  - Initialization: Sets the loop counter.
  - Condition: Specifies how many times the loop runs.
  - Afterthought: Executes after each loop iteration.

#### Example:

```javascript
for (let i = 0; i < 4; i++) {
  console.log(i);
}
```

### ➿ forEach loops

- forEach loops allow you to execute the same code for each element in an array.
- They are simpler to use compared to for loops.
- Syntax: `arr.forEach(function(element) { /* code to execute */ });`

#### Example:

```javascript
let fruits = ["peach", "apple", "lemon"];
fruits.forEach(function(fruit) {
  console.log(`Yummmmmmm, ${fruit}!`);
});
```

## Which Loop to Use?

- Use for loops for precise conditions and more flexibility.
- Use forEach loops for straightforward iteration through the entire array.
- The choice depends on your specific needs and personal preference.

## Other Types of Loops

- There are more types of loops, such as `for of`, `for in`, `while`, and `do...while`. Explore these options as well.


Enjoy learning about loops, and don't hesitate to ask for support if needed! 😊