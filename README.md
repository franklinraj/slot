# Ex03 Time Table


## Date:13-11-2024
## Name:FRANKLIN RAJ G
## Reg no:212223230058

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:

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
~~~
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - FRANKLIN RAJ G</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - FRANKLIN RAJ G(23001518)</strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="White">Day/Time</th>
            <th colspan="1" bgcolor="GREY">Monday</th>
            <th colspan="1" bgcolor="GREY">Tuesday</th>
            <th colspan="1" bgcolor="GREY">Wednesday</th>
            <th colspan="1" bgcolor="GREY">Thursday</th>
            <th colspan="1" bgcolor="GREY">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="GREY">8-10</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">C</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="GREY">10-12</th>
            <th colspan="1" bgcolor="Cyan">C</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">SOFTWARE</th>
            <th colspan="1" bgcolor="Cyan">ML</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="GREY">12-1</th>
            <th colspan="5" bgcolor="GREY">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="GREY">1-3</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">SOFTWARE</th>
            <th colspan="1" bgcolor="Cyan">MENTOR MEET</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">EMPD</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="GREY">3-5</th>
            <th colspan="1" bgcolor="Cyan">EMPD</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">TRANSFORM</th>
            <th colspan="1" bgcolor="Cyan">ML</th>
            <th colspan="1" bgcolor="Cyan">TRANSFORM</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI414</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19AI304</th>
            <th colspan="2" bgcolor="White">Fundamentals of C</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19AI410</th>
            <th colspan="2" bgcolor="White">Introduction to machine learning</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19AI303</th>
            <th colspan="2" bgcolor="White">Engineering Mechanics and Product Development(EMPD)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19CS570</th>
            <th colspan="2" bgcolor="White">Entrepreneurship and Small Business Development(ESBD)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19MA219</th>
            <th colspan="2" bgcolor="White">Transforms and Its Applications</th> 
        </tr>
    </table>
</body>
</html>


~~~


## OUTPUT:
![Screenshot 2024-11-13 212538](https://github.com/user-attachments/assets/643306b7-d982-4b12-b1fe-4b85ca82757f)




## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
