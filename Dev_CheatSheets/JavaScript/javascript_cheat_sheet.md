**JavaScript Cheat Sheet**

---

**Basics**

```js
// Single-line comment
/* Multi-line comment */

let x = 10; // mutable
const y = 20; // immutable
var z = 30; // function-scoped (avoid)

console.log("Hello, world!");
```

---

**Data Types**

- Number
- String
- Boolean
- Object
- Array
- Null
- Undefined
- Symbol
- BigInt

```js
typeof 123;        // 'number'
typeof "hi";       // 'string'
typeof true;       // 'boolean'
typeof null;       // 'object'
typeof undefined;  // 'undefined'
```

---

**Operators**

- Arithmetic: `+`, `-`, `*`, `/`, `%`, `**`
- Assignment: `=`, `+=`, `-=`, `*=`, etc.
- Comparison: `==`, `===`, `!=`, `!==`, `<`, `>`
- Logical: `&&`, `||`, `!`
- Ternary: `condition ? valueIfTrue : valueIfFalse`

---

**Control Flow**

```js
if (x > 10) {
  // code
} else if (x === 10) {
  // code
} else {
  // code
}

switch (fruit) {
  case "apple":
    break;
  default:
    break;
}

for (let i = 0; i < 5; i++) {
  console.log(i);
}

while (condition) {
  // code
}
```

---

**Functions**

```js
function greet(name) {
  return `Hello, ${name}`;
}

const add = (a, b) => a + b;
```

---

**Arrays**

```js
const fruits = new Array("apples", "oranges", "pears");
fruits[3] = "grapes"; // adds grapes to index 3
fruits.push("mangos"); // add to end
fruits.unshift("strawberries"); // add to beginning
fruits.pop(); // remove last

console.log(Array.isArray(fruits)); // check if array
console.log(fruits.indexOf("oranges")); // get index

// Loop through
fruits.forEach(fruit => console.log(fruit));
const upper = fruits.map(f => f.toUpperCase());
```

---

**Objects**

```js
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 30,
  hobbies: ["music", "movies", "sports"],
  address: {
    street: "50 Main St",
    city: "Boston",
    state: "MA"
  }
};

console.log(person.hobbies[1]); // 'movies'

const { firstName, lastName } = person;
const { city } = person.address;

person.email = "john@gmail.com";
```

---

**Array of Objects**

```js
const todos = [
  { id: 1, text: "Take out trash", isCompleted: true },
  { id: 2, text: "Meeting with boss", isCompleted: true },
  { id: 3, text: "Dentist appt", isCompleted: false },
];

console.log(todos[1].text); // 'Meeting with boss'
```

**High-Order Methods**

```js
todos.forEach(todo => console.log(todo.text));
const texts = todos.map(todo => todo.text);
const completed = todos.filter(todo => todo.isCompleted);

// Chain filter + map
const completedTexts = todos
  .filter(todo => todo.isCompleted)
  .map(todo => todo.text);
```

---

**JSON**

```js
const todoJSON = JSON.stringify(todos);
```

---

**Arrow Functions & Ternary**

```js
const sayHello = name => `Hello, ${name}`;
const result = x > 10 ? "Over 10" : "10 or less";
```

---

**DOM Manipulation**

```js
document.getElementById("id")
document.querySelector(".class")
document.createElement("div")
element.textContent = "Hello"
element.classList.add("active")
element.addEventListener("click", () => {...})
```

---

**Events**

```js
button.addEventListener("click", function () {
  alert("Button clicked!");
});
```

---

**Error Handling**

```js
try {
  // code
} catch (error) {
  console.error(error);
} finally {
  // optional cleanup
}
```

---

**Useful Methods**

- `Array.prototype.map()`, `filter()`, `reduce()`
- `Object.keys()`, `Object.values()`
- `String.prototype.includes()`, `toLowerCase()`, `split()`

---

**Debugging Tips**

- Use `console.log()`, `console.table()`
- Use browser DevTools (Sources > Breakpoints)
- `debugger;` keyword pauses script

---

**Reference Sites**

- [MDN JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
- [W3Schools JS](https://www.w3schools.com/js/)
- [Codecademy Intermediate JavaScript](https://www.codecademy.com/enrolled/courses/learn-intermediate-javascript)

