# Ex03 Time Table
## Date: 22-09-2025

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

</head>

<body>
    <center>
        <img src="logo.png" width="500">
    </center>
    <table border="1" cellpadding="10" align="center" bgcolor="magenta">
        <caption>
            <h2>Slot Time-Table</h2>
        </caption>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>WEB</td>
            <td>Free</td>
            <td>Free</td>
            <td>Free</td>
            <td>WEB</td>
            <td>Free</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>Free</td>
            <td>OS</td>
            <td>ML</td>
            <td>Python</td>
            <td>Free</td>
            <td>Free</td>
        </tr>
        <tr align="center">
            <th>12-1</th>
            <td colspan="6">Lunch</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>Python</td>
            <td>Maths</td>
            <td>Mentor Meet</td>
            <td>ML</td>
            <td>Free</td>
            <td>Python</td>
        </tr>

    </table>
</body>

</html>
```

## OUTPUT

<img width="1913" height="1155" alt="image" src="https://github.com/user-attachments/assets/4261977a-a2ef-4595-90b5-03d6cf6fe467" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
