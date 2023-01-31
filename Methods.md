# JavaScript

## Methods

- The JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Within the function definition, this can be used to refer to the containing object as long as the function is defined within the object.
-  If a function is assigned to a property later, any reference to this will reflect the context of the new function. Also, if the object’s function is assigned to a variable and executed via the variable, this will reflect the variable’s execution context.

### Syntax
- A method of an object is called via the following syntax. 
    - objectName.methodName();
- If a method is called without parenthesis, it is being called as a property, which means it will return the function definition, not execute the method.
### What is 'this'?
- In JavaScript, the this keyword refers to an object.
- Which object depends on how this is being invoked (used or called).
- The this keyword refers to different objects depending on how it is used:
    - In an object method, this refers to the object.
    - Alone, this refers to the global object.
    - In a function, this refers to the global object.
    - In a function, in strict mode, this is undefined.
    - In an event, this refers to the element that received the event.
    - Methods like call(), apply(), and bind() can refer this to any object.
            
### Accessing Object Methods
- You can access an object method using the above syntax.
- You will typically describe fullName() as a method of the person object, and fullName as a property.
- The fullName property will execute (as a function) when it is invoked with ().
- Example: name = person.fullname();
### Adding a method to an object
- An example would be: <br/>
  person.name = function () { <br/>
    return this.firstName + " " + this.lastName; <br/>
  };
  
