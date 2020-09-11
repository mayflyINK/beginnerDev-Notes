# Object-oriented Programming
#### Encapsulation
Object
- group of variables and functions in a unit
  - variables called properties
  - functions called methods
  
  Object examples:
  Car
  - properties: make, model, colour
  - methods: start, stop, move
  
  localStorage
  - length
  - methods: setItem, removeItem

In procedural programming variabled and functions are decoupled. Encapsulation reduces the need for parameters in a function that refer to variables. Parameters are modelled as properties of an object, creating a single unit.

Procedural
```javascript
var baseSalary = 30_000;
var overtime = 10;
var rate = 20;

function getWage(baseSalary, overtime, rate) {
  return baseSalary + (overTime * rate);
  }
```
Object-oriented
 ```javascript
  var employee = {
    baseSalary: 30_000,
      overtime: 10,
      rate:20,
      getWage: function() {
        return this.baseSalary + (this.overtime * this.rate);
      }
  };
  employee.getWage();
```
