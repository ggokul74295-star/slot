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

## PROGRAM


<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>
    <center><IMG SRC="/static/logo.png" align="center" HEIGHT="110"WIDTH="900">
    <h2 align="center">Slot Timetable - HEMA D(25015922)</h2>
    
    

    <table bgcolor="cyan" border="1" align="center" height="10" width="40" celspadding="8" celspacing="8" margin-bottom: 20px>
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">8-10</th>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">10-12</th>
            <td>FREE SLOT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>FREE SLOT</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">12-1</th>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">1-3</th>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <th BGCOLOR="YELLOW">3-5</th>
            <td>Python programing</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
    </table>


    <h3>Subjects</h3>

    <table border="2" align="center" height="100" width="590" celspacing="8" celspading="8" margin-bottom="20">
       
       
        <tr>

            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>

        </tr>
        <tr>
            <th>1.</th>
            <th>19AI414</th>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <th>2.</th>
            <th>19AI301</th>
            <td>Python Programing (PP)</td>
        </tr>
        
    </table>
</body>
</html>


## OUTPUT

![WhatsApp Image 2025-09-21 at 2 25 02 PM](https://github.com/user-attachments/assets/df00bfe8-203b-4cc9-8428-b25b576d8fd0)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
