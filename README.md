# Ex03 Time Table
## Date:20.09.2025

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
'''
<<html>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE </b></caption>
<tr align="center">
  <th bgcolor="yellow">Day/Time</th>
  <th bgcolor="yellow">Monday</th>
  <th bgcolor="yellow">Tuesday</th>
  <th bgcolor="yellow">Wednesday</th>
  <th bgcolor="yellow">Thursday</th>
  <th bgcolor="yellow">Friday</th>
</tr>

<tr align="center">
  <th bgcolor="yellow">8-10</th>
  <td>Fundamentals of C Programming</td>
  <td>Communicative English / Physics for Quantum Computation</td>
  <td>Statistics and Numerical Methods</td>
  <td>Fundamentals of Web Application Development</td>
  <td>Principles of Chemistry in Engineering</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">10-12</th>
  <td>Free Slot</td>
  <td>Fundamentals of Web Application Development</td>
  <td>Free Slot</td>
  <td>Principles of Chemistry in Engineering</td>
  <td>Statistics and Numerical Methods</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">1-3</th>
  <td>Soft Skills</td>
  <td>Fundamentals of C Programming</td>
  <td>Free Slot</td>
  <td>Fundamentals of Web Application Development</td>
  <td>Communicative English</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">3-5</th>
  <td>Statistics and Numerical Methods</td>
  <td>Free Slot</td>
  <td>Fundamentals of Web Application Development</td>
  <td>Fundamentals of C Programming</td>
  <td>Soft Skills</td>
</tr>

</table>

</center>

</body>
</html>
'''
## OUTPUT
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/40e217f2-1ee6-485d-b65d-42d42fdb66a9" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
