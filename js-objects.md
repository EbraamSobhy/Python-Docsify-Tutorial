# <span style="color: #00D100">JavaScript Objects</span>

### - Objects are variables too. But objects can contain many values.

## <span style="color:#00D100">Example</span>

```javascript
const person = {
  
  firstName: "John",

  lastName: "Doe",

  age: 45,

  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};
```
