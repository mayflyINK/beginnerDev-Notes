# Object-oriented Programming
#### Encapsulation
Reduce complexity and increase usability by grouping related data and functionality into a single unit called an object
  - data (variables) called properties
  - functions called methods
  
  Object examples:\
  Car
  - properties: make, model, colour
  - methods: start, stop, move
  
  localStorage
  - length
  - methods: setItem, removeItem

In procedural programming variabled and functions are decoupled. Encapsulation reduces the need for parameters in a function (that refer to variables), fewer parameters in a function make it easier to maintain?. Parameters are modelled as properties of an object, creating a single unit.

Procedural
```javascript
var baseSalary = 30_000;
var overtime = 10;
var rate = 20;

function getWage(baseSalary, overtime, rate) {
  return baseSalary + (overtime * rate);
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
#### Abstraction
- simplifies the object "interface" by allowing "hidden" properties and methods to be contained within a container object
- reduce impact of change by allowing modification of "hidden" methods and properties without effecting the object "interface" of the container object

#### Inheritance
- allows elmination of redundant code
- properties and methods can be defined once in a generic object and allow other objects to inherit these properties and methods for re-use (parent-child objects)

#### Polymorphism
- reduce "if, then, else" and "switch and case" statements

#### References
Programming with Mosh\
https://www.youtube.com/watch?v=pTB0EiLXUC8&t=17s<br/>
The Coding Train\
https://www.youtube.com/watch?v=T-HGdc8L-7w<br/>
