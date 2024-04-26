# Ex03 Time Table
## Date:13.03.2024

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
    <head>
        <title>SLOT TIMETABLE-KIRUTHIKA</title>
</head>
<body bgcolor="red">
    <center>
    <img src="saveethalogo.png" height="100" width="540">
    </center>
    <style>
        table, th, td {
    border: 1px solid black;
    border-radius: 10px;
  }
    </style>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption style="color:rgb(12, 243, 112)">SLOT TIMETABLE-KIRUTHIKA(212223040098)</caption>

            <tr>
               <th bgcolor="">Day/Time</th>
               <th bgcolor="blue">Monday</th>
               <th bgcolor="blue">Tuesday</th>
               <th bgcolor="blue">Wednesday</th>
               <th bgcolor="blue">Thursday</th>
               <th bgcolor="blue">Friday</th>
               <th bgcolor="blue">Saturday</th>
          </tr>
           <tr>
               <td>8:00-10:00</td>
               <td>Digital Electronics</td>
               <td>Free Slot</td>
               <td>Fundamentals of web applications</td>
               <td>Japanese</td>
               <td>Chemistry</td>
               <td>Maths</td>
          </tr>
          <tr>
               <td>10:00-12:00</td>
               <td>Free Slot</td>
               <td>fundamental of web applications</td>
               <td>Free Slot</td>
               <td>Maths</td>
               <td>Python</td>
               <td>OperatingSystem</td>
          </tr>
          <tr>
               <td>12:00-1:00</td>
               <td colspan="6" align="center" bgcolor="skyblue">Lunch</td>
          </tr>
          <tr>
               <td>1:00-3:00</td>
               <td>Fundamentals of web applications</td>
               <td>Chemistry</td>
               <td>Creative Skill</td>
               <td>Free Slot</td>
               <td>Digital Electronics</td>
               <td>Japanese</td>

          </tr>
          <tr>
               <td>3:00-5:00</td>
               <td>OperatingSystem</td>
               <td>Free Slot</td>
               <td>Japanese</td>
               <td>Python</td>
               <td>Free Slot</td>
               <td>Free Slot</td>
         
          </tr>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption style="color:rgb(243, 224, 12)">SUBJECT DETAILS</caption>
          <tr>
               <th bgcolor="blue">S.no</th>
               <th bgcolor="blue">Subject Code</th>
               <th bgcolor="blue">Subject Name</th>
               
          </tr>
          <tr>
               <td>01</td>
               <td>19EE404</td>
               <td>Digital Electronics</td>
           </tr>
            <tr>
               <td>02</td>
               <td>19AI414</td>
               <td>Python</td>
           </tr> <tr>
               <td>03</td>
               <td>19AI414</td>
               <td>Fundamentals of web</td>
           </tr>
            <tr>
               <td>04</td>
               <td>19CS405</td>
               <td>Operating System</td>
           </tr>
             <tr>
               <td>05</td>
               <td>19CY205</td>
               <td>Chemistry</td>
           </tr>
            <tr>
               <td>06</td>
               <td>19EN404</td>
               <td>Japanese</td>
           </tr>
            <tr>
               <td>07</td>
               <td>19EY615C</td>
               <td>SoftSkill</td>
           </tr>
            <tr>
               <td>08</td>
               <td>19MA222</td>
               <td>Maths</td>
           </tr>
          
</body>
</html>
```

## OUTPUT
![Uploading Screenshot 2024-04-25 112115.png…]()


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
