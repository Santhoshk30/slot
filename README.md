# Ex04 Time Table
## Date:17.11.26

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
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table border="1" align="center" cellpadding="4"  width="540"   bgcolor="cyan">
<caption><b>SLOT TIME TABLE -SANTHOSH K(26016599)</b></caption>
<tr align="center">
<th bgcolor="brown">Day/Time</th>
<th bgcolor="brown">Monday</th>
<th bgcolor="brown">Tuesday</th>
<th bgcolor="brown">Wednesday</th>
<th bgcolor="brown">Thursday</th>
<th bgcolor="brown">Friday</th>
<th bgcolor="brown">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="beige">8-9:30</th>
<td>CDS</td>
<td>Python Programming</td>
<td>FREE SLOT</td>
<td>Communicative English</td>
<td>Statistics and numerical methods</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="beige">9:30-11:15</th>
<td>B.EEE</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
<td>Statistics and numerical methods</td>
<td>Fundamentals of Web Application Development</td>
<td>Digital Electronics</td>
</tr>
<tr align="center">
<th bgcolor="beige">12-1</th>
<td colspan="5">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="beige">1:15-2:45</th>
<td>Fundamentals of Web Application Development</td>
<td>Digital Electronics</td>
<td>Python Programming</td>
<td>Japanese N5</td>
<td>Japanese N5</td>
<td>Communicative English</td>
</tr>
<tr align="center">
<th bgcolor="beige">3:00-4:30</th>
<td>Python Programming</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table border="2" align="center" cellspacing="2" cellpadding="4" >
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19MA211 </td>
<td>Statistics and numerical methods</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EY708</td>
<td>Career Development Skills(CDS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI301</td>
<td>Python Programming(PY PROGRAM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EE305</td>
<td>Basic Electrical, Electronics and Measurement Engineering(BEEME)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EN101</td>
<td>Communicative English(CE)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EE404</td>
<td>Digital Electronics</td>
</tr>
<tr>
<td align="center">8.</td>
<td align="center">19GE624</td>
<td>Japanese N5</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (40).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
