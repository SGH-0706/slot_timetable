# Ex03 Time Table
## Date:19.11.2024

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
 <html></html>
<head>
<title>Slot Timetable</title>
<style>
	.free-slot{
		background-color:rgb(196, 255, 247);
	}
</style>
</head>
<body>
<center>
<img src="/static/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="aqua">
<caption><b>SLOT TIMETABLE - Srinithi Muthukumar (24010166)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
    <th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td class = 'free-slot'>Free</td>
	<td>Prototyping of Iot</td>
	<td class = 'free-slot'>Free</td>
	<td class = 'free-slot'>Free</td>
	<td>Physics for quantum computing</td>
    <td>Statistics and Numerical methods</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>Fundamentals of web application development</td>
	<td>Physics for quantum computing</td>
	<td>Fundamentals of web application development</td>
	<td>Fundamentals of c programming</td>
	<td>Fundamentals of c programming</td>
    <td class = 'free-slot'>Free</td>
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H   B R E A K</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>Basics EEE</td>
	<td>Statistics and Numerical methods</td>
	<td>Mentor Meet</td>
	<td>Basics EEE</td>
	<td>Career development skills</td>
    <td>Fundamentals of web application development</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td class= 'free-slot'>Free</td>
	<td class = 'free-slot'>Free</td>
	<td>Prototyping of iot</td>
	<td class = 'free-slot'>Free</td>
	<td class = 'free-slot'>Free</td>
    <td class = 'free-slot'>Free</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of web application</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EE305</td>
<td>Basics EEE</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS420</td>
<td>Prototyping of iot</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical methods</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI304</td>
<td>Fundamentals of c programming</td>
</tr>
</table>
</body>
</html>
'''


## OUTPUT
![alt text](<Screenshot 2024-11-19 232418.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
