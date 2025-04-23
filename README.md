# Ex03 Time Table
## Date:23/4/2025

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
        <center>
        <img src="logo.png" width="500px"
        <title></title>
        <caption><h3>SLOT TIMETABLE- ROSHINI.S(212223230174)</h3></caption>
        </center>
    </head>
    <body>
        <center>
           <table border="1">
            <tr bgcolor="lightblue">
                <td><h3>Day/Time</h3></td>
                <td><h3><center>Monday</center></h3></td>
                <td><h3><center>Tuesday</center></h3></td>
                <td><h3><center>Wednesday</center></h3></td>
                <td><h3><center>Thursday</center></h3></td>
                <td><h3><center>Friday</center></h3></td>
                <td><h3><center>Saturday</center></h3></td>
            </tr>
            <tr bgcolor="lightpink">
                <td bgcolor="lightblue"><center><h3>8-10</h3></center></td>
                <td></td>
                <td></td>
                <td></td>
                <td>Fundamentals of web application Development</td>
                <td></td>
                <td></td>
            </tr>
            <tr bgcolor="lavender">
                <td bgcolor="lightblue"><center><h3>10-12</h3></center></td>
                <td></td>
                <td>Computer architecture</td>
                <td>Reasoning ability</td>
                <td>Python Programming</td>
                <td>Python Programming</td>
                <td>Fundamentals of web application Development</td>
            </tr>
            <tr bgcolor="lavender">
                <td bgcolor="lightblue"><center><h3>12-1</h3></center></td>
                <td colspan="6"><center><h3>L U N C H</h3></center></td>
            </tr>
            <tr bgcolor="lavender">
                <td bgcolor="lightblue"><center><h3>1-3</h3></center></td>
                <td></td>
                <td></td>
                <td>Mentor Meet</td>
                <td>Computer network</td>
                <td>Computer network</td>
                <td></td>
            </tr>
                <tr bgcolor="lavender">
                    <td bgcolor="lightblue"><center><h3>3-5</h3></center></td>
                    <td>Chemistry</td>
                    <td></td>
                    <td>Computer architecture</td>
                    <td>Chemistry</td>
                    <td></td>
                    <td></td>
                </tr>
            

        </table><br>

        <table border="1">
            <tr>
                <td><h3>s.no</S></h3></td>
                <td><h3>Subject code</h3></td>
                <td><h3><center>subject name</center></h3></td>
            </tr>
            <tr>
                <td>1.</td>
                <td><center>19AI414</center></td>
                <td>Fundamental of Web application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td><center>19AI301</center></td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td><center>SH4205</center></td>
                <td> Chemistry</td>
            </tr>
            <tr>
                <td>4.</td>
                <td><center>19EY709</center></td>
                <td>Reasoning ability</td>
            </tr>
            <tr>
                <td>5.</td>
                <td><center>19CS406</center></td>
                <td>Computer network</td>
            </tr>
            <tr>
                <td>6.</td>
                <td><center>19CS305</center></td>
                <td>Computer architecture</td>
            </tr>
        </table>
        </center>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-23 184850.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
