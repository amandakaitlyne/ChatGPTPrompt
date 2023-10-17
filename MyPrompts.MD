What is a class in JavaScript?

In JavaScript, a class is a blueprint for creating objects with similar properties and behaviors. It allows you to define a custom data type that can have its own properties (variables) and methods (functions). Classes are a fundamental concept in object-oriented programming (OOP).

Here's an example of how you can define a class in JavaScript:
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
  }
}
In this example, Person is a class. It has a constructor method that is called when you create a new instance of the class. In this case, it sets the name and age properties of the object. The sayHello method is a function that can be called on objects created from this class.

You can create new instances of the Person class like this:
let person1 = new Person('John Doe', 30);
let person2 = new Person('Jane Doe', 25);
person1 and person2 are now objects with the properties name and age, and they also have access to the sayHello method.

Classes provide a way to organize and structure your code, making it easier to manage and reuse code for similar types of objects. They are a key feature of object-oriented programming and are widely used in JavaScript.
