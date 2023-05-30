# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```

## OUTPUT
![exp 7 img 1](https://github.com/SaiganeshVelu/Ex07_Web-Design/assets/127816325/8bef6ae7-eff9-4fff-affc-d9fd8af3a922)
![exp 7 img 2](https://github.com/SaiganeshVelu/Ex07_Web-Design/assets/127816325/a6a40489-1405-43fc-827c-6e5e478e201f)
![exp 7 img 3](https://github.com/SaiganeshVelu/Ex07_Web-Design/assets/127816325/19b4fa12-781c-4482-8aef-182b6311af14)
![exp 7 img 4](https://github.com/SaiganeshVelu/Ex07_Web-Design/assets/127816325/8d73ce0d-5f8a-4b8f-902e-f4886d2f19db)






## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
