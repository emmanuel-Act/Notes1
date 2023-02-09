# JavaScript

## Conditional Statements

- The JavaScript Conditional statement is used to execute the code whether condition is true or false. There are three forms of conditional statements in JavaScript. These include:<br/>
    1. If Statement
    2. If else statement
    3. If else if statement
    
### JavaScript If Statement

- It evaluates the content only if expression is true. The signature of JavaScript if statement is given below.<br/>
  if(expression){  <br/>
  //content to be evaluated <br/> 
  }  
  - The flow chart of a JavaScript if statement looks like the one below.
  
  ![Flow Chart](https://www.javatpoint.com/images/core/if1.png "If statement flow chart")
  
  - Example of if statement in JavaScript: <br/>
    <script>  <br/>
    var a=20;  <br/>
    if(a>10){  <br/>
    document.write("value of a is greater than 10");  <br/>
    }  <br/>
    </script>  
    
    ### JavaScript If...else Statement
- It evaluates the content whether condition is true of false. The syntax of JavaScript if-else statement is given below.<br/>
  if(expression){  <br/>
  //content to be evaluated if condition is true  <br/>
  }  <br/>
  else{  <br/>
  //content to be evaluated if condition is false  <br/>
  }  <br/>
  - The flow chart of a JavaScript if...else statement looks like the one below.<br/>
  
  ![Flow Chart]([https://www.javatpoint.com/images/core/if2.png "If statement flow chart"](https://th.bing.com/th/id/OIP.nHBdSnyNZ_ZW45j-AnQ73gHaId?pid=ImgDet&w=2445&h=2795&rs=1))
  
  - Example of if statement in JavaScript: <br/>
    <script>  <br/>
    var a=20;  <br/>
    if(a%2==0){  <br/>
    document.write("a is even number");  <br/>
    }  <br/>
    else{  <br/>
    document.write("a is odd number");  <br/>
    }  <br/>
    </script>
    
### JavaScript If...else if Statement
- It evaluates the content only if expression is true from several expressions. The signature of JavaScript if else if statement is given below.<br/>
    if(expression1){  <br/>
    //content to be evaluated if expression1 is true  <br/>
    }  <br/>
    else if(expression2){  <br/>
    //content to be evaluated if expression2 is true  <br/>
    }  <br/>
    else if(expression3){  <br/>
    //content to be evaluated if expression3 is true  <br/>
    }  <br/>
    else{  <br/>
    //content to be evaluated if no expression is true  <br/>
    }  
  - The flow chart of a JavaScript if...else if statement looks like the one below.<br/>
  
  - Example of if statement in JavaScript: <br/>
    <script>  <br/>
    var a=20;  <br/>
    if(a==10){  <br/>
    document.write("a is equal to 10");  <br/>
    }  <br/>
    else if(a==15){  <br/>
    document.write("a is equal to 15");  <br/>
    }  <br/>
    else if(a==20){  <br/>
    document.write("a is equal to 20");  <br/>
    }  <br/>
    else{  <br/>
    document.write("a is not equal to 10, 15 or 20");  <br/>
    }  <br/>
    </script>  

