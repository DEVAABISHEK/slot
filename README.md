# Ex03 Time Table
## Date:

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

## PROGRAM:
```
<html>
    <head>
        <title>My time table</title>
    </head>
    <body>
       <center> <img   src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-04-04 113015.png" height="=200" width="500"> </center>
        <hr>
        <hr>
        <table align="center" border="2" cellspacing="5" cellpadding="12" height="50" width="40" >
            <center><h3><b>TIME TABLE</b></h3></center>
            <center><h4>DEVA ABISHEK 212223110008</h4></center>
            <tr>
             <th bgcolor="EEE4B1">Day/time</th>
             <th bgcolor="FFEDD8">Monday</th>
             <th bgcolor="FFEDD8">Tuesday</th>
             <th bgcolor="FFEDD8">Wednesday</th>
             <th bgcolor="FFEDD8">Thursday</th>
             <th bgcolor="FFEDD8">Friday</th>
             <th bgcolor="FFEDD8">Saturday</th>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">8-10</td>
                <td bgcolor="67C6E3">Physics</td>
                <td bgcolor="67C6E3">Free slot</td>
                <td bgcolor="67C6E3">Web Application</td>
                <td bgcolor="67C6E3">Physics</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">Web Application</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">10-12</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">c programing</td>
                <td bgcolor="67C6E3">probability</td>
                <td bgcolor="67C6E3" align="centre">c programing</td>
                <td bgcolor="67C6E3">computer networks</td>
                <td bgcolor="67C6E3">Free slot</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">1-3</td>
                <td bgcolor="67C6E3">computer networks</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">creative skill</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">probability</td>
            </tr>
        </table>
        <hr>
        <hr>
        <table align="center" border="2" cellspacing="1" cellpadding="12" height="50" width="600">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td align="center">19AI414</td>
                <td >Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td align="center">19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of c programming</td>
            </tr>
            <tr>
                <td>4.</td>
                <td align="center">19PH214</td>
                <td>Physics</td>
            </tr>

            <tr>
                <td>5.</td>
                <td align="center">19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/DEVAABISHEK/slot/assets/150319305/e6a65299-0f04-46e1-a5e3-28d7ffb32df4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
