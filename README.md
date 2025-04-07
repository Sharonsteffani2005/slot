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
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - SHARON STEFFANI F V</title>
</head>
<body>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - SHARON STEFFANI F(23007577)</h3>


    <table border="1" bgcolor="cyan">
        <tr>
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
            <th bgcolor="yellow">Saturday</th>
        </tr>
        <tr>
            <td bgcolor="yellow">8-10</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>BB</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td></td>
        </tr>
        <tr>
            <td bgcolor="yellow">10-12</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>CN</td>
            <td>HRM</td>
            <td></td>

        </tr>
        <tr>
            <td bgcolor="yellow">12-1</td>
            <td colspan="5">LUNCH</td>
            <td></td>
        </tr>
        <tr>
            <td bgcolor="yellow">1-3</td>
            <td>BB</td>
            <td>HRM</td>
            <td>MM</td>
            <td>FREE SLOT</td>
            <td>CN</td>
            <td></td>

        </tr>
        <tr>
            <td bgcolor="yellow">3-5</td>
            <td>DS</td>
            <td>BEE</td>
            <td>DS</td>
            <td>BEE</td>
            <td>FREE SLOT</td>
            <td></td>

        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI403</td>
            <td>Introduction to Data Science (DS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI547</td>
            <td>Blockchain for Business (BB)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS406</td>
            <td>Computer Networks (CN)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE305</td>
            <td>Basic Electricals,and Electronics and Measurement (BEE)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19MS156</td>
            <td>Human Resource Management (HRM)</td>
        </tr>
    </table>
</body>
</html>

	



```

## OUTPUT
![image](https://github.com/user-attachments/assets/3e9cf1b5-f391-4a87-9d87-b480fdf89787)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
