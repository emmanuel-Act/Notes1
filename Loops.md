# JavaScript

## Loops

- The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in 
loops. It makes the code compact. It is mostly used in array.
- There are four types of loops in JavaScript: 
  1. for loop
  2. while loop
  3. do-while loop
  4. for-in loop
### JavaScript For loop
- The JavaScript for loop iterates the elements for the fixed number of times. It should be used 
if number of iteration is known. The syntax of for loop is given below. <br/>
  for (initialization; condition; increment) <br/> 
  {  <br/>
     code to be executed  <br/>
  }  <br/>
- Example:<br/>
  <script>  <br/>
  for (i=1; i<=5; i++)  <br/>
  {  <br/>
  document.write(i + "<br/>")  <br/>
  }  <br/>
  </script>  <br/>
    output: <br/>
    1<br/>
    2<br/>
    3<br/>
    4<br/>
    5<br/>
            
### JavaScript while loop
- The JavaScript while loop iterates the elements for the infinite number of times. It should be used if number of 
iteration is not known. The syntax of while loop is given below. <br/>
  while (condition)  <br/>
  {  <br/>
    code to be executed  <br/>
  }  <br/>
- Example:<br/>
  <script>  <br/>
  var i=11;  <br/>
  while (i<=15)  <br/>
  {  <br/>
  document.write(i + "<br/>");  <br/>
  i++;  <br/>
  }  <br/>
  </script>  <br/>
    output: <br/>
    11<br/>
    12<br/>
    13<br/>
    14<br/>
    15<br/>
    
### JavaScript do while loop
- The JavaScript do while loop iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false. The syntax of do while loop is given below. <br/>
  do{  <br/>
    code to be executed  <br/>
    }while (condition);  <br/>
- Example:<br/>
<script>  <br/>
  var i=21;  <br/>
  do{  <br/>
  document.write(i + "<br/>");  <br/>
  i++;  <br/>
  }while (i<=25);  <br/>
  </script>  <br/>
    output: 
    21  
    22  
    23  
    24  
    25  

### JavaScript for in loop
- The JavaScript for in loop is used to iterate the properties of an object. The syntax for it is given below.<br/>
  for (key in object) {<br/>
  // code block to be executed<br/>
  }<br/>
- Example:<br/>
  <script><br/>
  const person = {fname:"John", lname:"Doe", age:25}; <br/>

  let txt = "";<br/>
  for (let x in person) {<br/>
  txt += person[x] + " ";<br/>
  }<br/><br/>
  document.getElementById("demo").innerHTML = txt;<br/>
  
  </script><br/>
  
  output: John Doe 25
   
