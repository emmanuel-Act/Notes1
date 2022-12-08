# JavaScript

## Variables

- A JavaScript variable is simply a name of storage location. There are two types of variables in JavaScript : local variable and global variable. 
- There are some rules while declaring a JavaScript variable (also known as identifiers).
  - Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
  - After first letter we can use digits (0 to 9), for example value1.
  - JavaScript variables are case sensitive, for example x and X are different variables.
- Example of JavaScript variable: <br/>
   <script>  <br/>
      var x = 10; <br/>
      var y = 20; <br/>  
      var z=x+y;  <br/>  
      document.write(z); <br/> 
    </script>    
### Local Variables
- A JavaScript local variable is declared inside block or function. It is accessible within the function or block only. For example:<br/>
  <script>  <br/>
  function abc(){  <br/>
  var x=10;//local variable <br/> 
  }  <br/>
  </script>  <br/>
  Or,<br/>
  <script>  <br/>
  If(10<13){  <br/>
  var y=20;//local variable <br/> 
  }  <br/>
  </script>  
### Global Variables
- A JavaScript global variable is accessible from any function. A variable i.e. declared outside the function or declared with window object is known as global variable. For example:<br/>
  <script>  <br/>
  var data=200;//gloabal variable  <br/>
  function a(){  <br/>
  document.writeln(data);  <br/>
  }  <br/>
  function b(){  <br/>
  document.writeln(data);  <br/>
  }  <br/>
  a();//calling JavaScript function  <br/>
  b();  <br/>
  </script>  
  
