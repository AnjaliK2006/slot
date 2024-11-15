# Ex03 Time Table
## Date: 15/11/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
<body>
<img src="logo.png" width="900" height="150">    
<table border="2" cellspacing="2" cellpadding="2">
    <caption>TimeTable Anjali 24900073</caption>
    <tr bgcolor="yellow">
        <th>Date/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>
    <tr>
        <td bgcolor="yellow">8-10</td>
        <td>Free Slot</td>
        <td>Web</td>
        <td>Free Slot</td>
        <td>Python</td>
        <td colspan="2">Free Slot</td>
    </tr>
    <tr>
        <td bgcolor="yellow">10-12</td>
        <td>Maths</td>
        <td>Digital Electronics</td>
        <td>Free Slot</td>
        <td>Digital Electronics</td>
        <td>English</td>
        <td>Python</td>
    </tr>
    <tr>
        <td bgcolor="yellow">12-1</td>
        <td colspan="6">Lunch Break</td> 
    </tr>
    <tr>
        <td bgcolor="yellow">1-3</td>
        <td>BEEE</td>
        <td>Maths</td>
        <td>Mentor meet</td>
        <td>English</td>
        <td colspan="2">Web</td>
     </tr>
     <tr>
        <td bgcolor="yellow">3-5</td>
        <td colspan="2">Free Slot</td>
        <td>BEEE</td>
        <td colspan="3">Free Slot</td>
     </tr>             
</table>
<br>

<table border="2" cellspacing="2" cellpadding="6">
     <caption>Course</caption>
     <tr bgcolor="purple"</tr>
         <th>S.no</th>
         <th>Course code</th>
         <th>Course Name</th>
     </tr>
     <tr> 
         <td>1</td>
         <td>19AI301</td>
         <td>Python Programming</td>
     </tr>
     <tr>
         <td>2</td>
         <td>19AI414</td>
         <td>Fundamentals of Web Application Development</td>
     </tr>
     <tr>
         <td>3</td>
         <td>19EE305</td>
         <td>Basic Electrical ,Electronics and Measurement Engineering</td>
     </tr>
     <tr> 
         <td>4</td>
         <td>19EN101</td>
         <td>Communicative English</td>
     </tr>
     <tr>
         <td>5</td>
         <td>19MA201</td>
         <td>Calculas and Matrix Algebra</td>
     </tr>
     <tr>
         <td>6</td>
         <td>19EE404</td>
         <td>Digital Eletronics</td>
     </tr>
     <tr> 
         <td>7</td>
         <td>SH7101</td>
         <td>Heritage of Tamils</td>
     </tr>
     <tr> 
         <td>8</td>
         <td>ECA-M-SCOFT</td>
         <td>Mentor Meet</td>
     </tr>
</table>
</body>
</html>
 

     

     
```

## OUTPUT
![alt text](<Screenshot 2024-11-15 145700.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
