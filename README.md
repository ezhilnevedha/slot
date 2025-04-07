# Ex03 Time Table
## Date:07.04.2025
## Reg.no: 212223230055
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
    <title>Slot Time Table - Ezhil Nevedha K</title>
</head>
<body>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - Ezhil Nevedha K(23007496)</h3>

    <table border="1">
        <tr>
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>
        <tr>
            <td bgcolor="yellow">8-10</td>
            <td bgcolor="cyan">Fund of AI</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">ADV C</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">HRM</td>
        </tr>
        <tr>
            <td bgcolor="yellow">10-12</td>
            <td bgcolor="cyan">FWAD</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">FWAD</td>
            <td bgcolor="cyan">CN</td>
            <td bgcolor="cyan">INTRO TO DS</td>
        </tr>
        <tr>
            <td bgcolor="yellow">12-1</td>
            <td colspan="5" bgcolor="cyan">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="yellow">1-3</td>
            <td bgcolor="cyan">ADV-C</td>
            <td bgcolor="cyan">HRM</td>
            <td bgcolor="cyan">MENTOR MEET</td>
            <td bgcolor="cyan">QA-1</td>
            <td bgcolor="cyan">CN</td>
        </tr>
        <tr>
            <td bgcolor="yellow">3-5</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan">FUND OF AI</td>
            <td bgcolor="cyan">INTRO TO DS</td>
            <td bgcolor="cyan">FREE SLOT</td>
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
            <td>19AI405</td>
            <td>Fundamentals of Artificial Intelligence(FUND OF AI)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI403</td>
            <td>Introduction to data Science (INTRO TO DS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19MS156</td>
            <td>Human Resource Management and Team Building (HRM)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI305</td>
            <td>Advanced C Programming (ADV-C)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CS406</td>
            <td>Computer Networks (CN)</td>
        </tr> 
        <tr>
            <td>7.</td>
            <td>19EY710</td>
            <td>Quantitative Ability -1 (QA-1)</td>
        </tr>


    </table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/fb6695f8-7c63-4892-9429-228eed784fd7)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
