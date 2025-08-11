# <span style="color: #00D100">JavaScript Data Types</span>

### - Data types define the kind of data a variable can store.



## <span style="color:#00D100">String</span>
```javascript
let greeting = "Hello, world!";

let name = 'John Doe';

console.log(typeof greeting);
```

## <span style="color:#00D100">Number</span>
```javascript
let age = 30; // Integer

let price = 19.99; // Floating-point number

let sum = age + price; // 49.99

console.log(typeof age); // "number"
```

## <span style="color:#00D100">Boolean</span>
```javascript
let isStudent = true;

let hasLicense = false;

console.log(typeof isStudent); // "boolean"
```

## <span style="color:#00D100">Undefined</span>
```javascript
let firstName;

console.log(firstName); // undefined

console.log(typeof firstName); // "undefined"
```

## <span style="color:#00D100">Null</span>
```javascript
let car = null;

console.log(car); // null

console.log(typeof car); // "object" - This is a historical quirk in JavaScript
```

## <span style="color:#00D100">Object</span>
```javascript
const person = {
  firstName: "Jane",
  lastName: "Doe",
  age: 28,
};

console.log(typeof person); // "object"

console.log(person.firstName); // "Jane"
```

## <span style="color:#00D100">Array</span>
```javascript
const colors = ["red", "green", "blue"];

console.log(colors[0]); // "red"

console.log(typeof colors); // "object" - arrays are technically objects
```