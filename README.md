# Ex04 Time Table
## Date:17/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>timetable</title>
    </head>
<body>
<center>
    <img src="logo.png" width="600" heigth="90">
</center>

<h2 align="center">SLOT TIME TABLE - LAKSHITHA M (26018363) </h2>

  <table border="2" cellspacing="5" cellpadding="6" align="center" bgcolor="yellow">

    <tr bgcolor="pink">
      <th >Day/Time</th>
      <th >Monday</th>
      <th >Tuesday</th>
      <th >Wednesday</th>
      <th >Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
    </tr>
    <tr>
      <td  bgcolor="pink">8:00 - 9:30</td>
      <td>SNM</td>
      <td>PYTHON</td>
      <td>SNM</td>
      <td>FREE SLOT</td>
      <td>MAT</td>
      <td>MAT</td>
    </tr>
    <tr>
      <td bgcolor="pink">9:45 - 11:15</td>
      <td>MAT</td>
      <td>FWAD</td>
      <td colspan="2">FREE SLOT</td>
      
      <td>FWAD</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td bgcolor="pink">11:15 - 1:15</td>
      <td colspan="8" class="lunch" align="center">L U N C H</td>
    </tr>
    <tr>
      <td  bgcolor="pink" >1:15 - 2:45</td>
      <td>FWAD</td>
      <td>EMPD</td>
      <td>EDM</td>
      <td>EDM</td>
      <td colspan="2">FREE SLOT</td>
      <td></td>
    </tr>
    <tr>
      <td  bgcolor="pink">3:00 - 4:30</td>
      <td>PYTHON</td>
      <td>FREE SLOT</td>
      <td>EMPD</td>
      <td>EMPD</td>
      <td>BEEE</td>
      <td>FREE SLOT</td>
    </tr>
  </table>
  <br>
  <table border="2"  cellspacing="5" cellpadding="10" align="center" bgcolor="pink">
    <tr bgcolor="orange">
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td >1.</td>
      <td >19MA211</td>
      <td>Statistics and Numerical Methods (SNM)</td>
    </tr>
    <tr>
      <td >2.</td>
      <td >19MA220</td>
      <td>Mathematics for AI (MAT)</td>
    </tr>
    <tr>
      <td >3.</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td >4.</td>
      <td >19AI301</td><td>Python Programming (PYTHON)</td>
    </tr>
    <tr>
      <td >5.</td>
      <td >19AI303</td>
      <td>Engineering Mechanics and Product Development</td>
    <tr>
      <td>6.</td>
       
      <td >19AI302</td>
      <td>Engineering Design and Modelling (EDM)</td>
    </tr>
    <tr>
      <td >7.</td>
      <td >19EE305</td>
      <td>Basic Electrical, Electronics and Measurement Engineering (BEEE)</td>
    </tr>
  </table>

</body>
</html>
```

## OUTPUT

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
