# Ex03 Time Table
## Name: HASMITHA V NANCY
## Register No: 212224040111
## Date:19-04-2025

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
~~~
<html>
<head>
<title> Course Schedule </title>
</head>
<body style="background-color:#dff0ec;">
<img src="logo.png" height="100" width="1450">
<br>
<br>
<table align="center" width="540" cellspacing="20" cellpadding="4"
border="5" bgcolor="#FFC2EC">
<caption><b>SCHEDULE OF ALL COURSES</b></caption>
<br>
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
<td >COMMUNICATIVE</td>
<td>UI/UX</td>
<td>ADVANCE C</td>
<td>PHYSICS</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>EVS</td>
<td>FUNDAMENTALS OF WEB</td>
<td>UI/UX</td>
<td>PROBABILITY</td>
<td>REASONING ABILITY</td>
<td>PROBABILITY</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >ADVANCE C</td>
<td>PHYSICS</td>
<td>MENTOR MEET</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB</td>

</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="6" align="center">FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center" bgcolor="Slate gray">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
    <td align="center">1.</td>
    <td align="center">19AI414</td>
    <td>FUNDAMENTALS OF WEB</td>
</tr>
<tr>
    <td align="center">2.</td>
    <td align="center">19AI304</td>
    <td>ADVANCE C</td>
</tr>
<tr>
    <td align="center">3.</td>
    <td align="center">19EN101</td>
    <td>COMMUNICATIVE</td>
</tr>
<tr>
    <td align="center">4.</td>
    <td align="center">19PH814</td>
    <td>PHYSICS</td>
</tr>
<tr>
    <td align="center">5.</td>
    <td align="center">19MA222</td>
    <td>PROBABILITY</td>
</tr>
<tr>
    <td align="center">6.</td>
    <td align="center">19EY709</td>
    <td>REASONING ABILITY</td>
</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19CY801</td>
    <td>EVS</td>
</tr>
<tr>
    <td align="center">8.</td>
    <td align="center">19CS549</td>
    <td>UI/UX</td>
 </tr>
</table>
</body>
</html>
~~~
## OUTPUT
![Screenshot 2025-04-19 145000](https://github.com/user-attachments/assets/71abb1bf-5794-4fb4-b527-1aa4965e6494)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
