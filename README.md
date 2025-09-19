# NAME: JAGAN JP
# REG.NO: 212224230099
# Ex03 Time Table
## Date:19-09-25
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
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="500">
</center>
<br>
<table align="center" width="100" cellspacing="4" cellpadding="5" border="2" bgcolor="Cyan">
<caption><b>SLOT TIME TABLE - JAGAN JP (212224230099)</b></caption>
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
<td>SOFTWARE ENGINEERING</td>
<td>-</td>
<td>CAREER DEVELOPMENT</td>
<td>-</td>
<td>GAME DEVELOPMENT</td>
<td>-</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>BLOCK CHAIN</td>
<td>GAME DEVELOPMENT</td>
<td>COMPUTER NETWORK</td>
<td>-</td>
<td>SOFTWARE ENGINEERING</td>
<td>BLOCK CHAIN</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>-</td>
<td>COMPUTER ARCHITECTURE</td>
<td>MENTOR MEET</td>
<td>OPERATING SYSTEM</td>
<td>PYTHON PROGRAM</td>
<td>WEB APPLICATION</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>COMPUTER ARCHITECTURE</td>
<td>-</td>
<td>PYTHON PROGRAM</td>
<td>-</td>
<td>WEB APLLICATION</td>
<td>-</td>


</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="5" border="2">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>WEB APPLICATION</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>PYTHON PROGRAM</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS408</td>
<td>SOFTWARE ENGINEERING</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19IT402</td>
<td>GAME DEVELOPMENT</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS406</td>
<td>COMPUTER NETWORKS</td>
<tr>
<td align="center">6.</td>
<td align="center">19CS305</td>
<td>COMPUTER ARCHITECTURE</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19AI457</td>
<td>BLOCK CHAIN</td>
</tr>
<tr>
<td align="center">8.</td>
<td align="center">19CS405</td>
<td>OPERATING SYSTEM</td>
</tr>

</tr>
</tr>
</tr>
</table>
</body>
</html>
```

# OUTPUT
<img width="1172" height="687" alt="Screenshot 2025-09-19 221623" src="https://github.com/user-attachments/assets/1c9e072e-800c-4b38-8e62-3dc7abc47244" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
