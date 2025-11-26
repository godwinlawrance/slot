# Ex03 Time Table
## Date: 26/11/2025
## Reference No: 25015487

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
    <title>Saveetha Engineering College - Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f7f7f7;
            text-align: center;
        }
        .container {
            width: 90%;
            margin: auto;
            margin-top: 20px;
        }
        h2 {
            color: #005daa;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }
        table, th, td {
            border: 2px solid black;
        }
        th {
            background-color: #ffde59;
            padding: 10px;
        }
        td {
            padding: 10px;
            background-color: #c7f5fc;
            font-weight: bold;
        }
        .subject-table td, .subject-table th {
            background-color: white;
        }
    </style>
</head>
<body>

    <img src="/static/logo.png" height="100" width="540">
    <h2>SLOT TIME TABLE - Godwin Lawrance L (25015487)</h2>

    <div class="container">
        <table>
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
                <th>8 - 10</th>
                <td>PYTHON</td>
                <td>FREE SLOT</td>
                <td>PYTHON</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>PYTHON</td>td>
            </tr>
            <tr>
                <th>10 - 12</th>
                <td>FWAD</td>
                <td>ENGLISH</td>
                <td>FREE SLOT</td>
                <td>PYTHON</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <th>12 - 1</th>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr>
                <th>1 - 3</th>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>ENGLISH</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <th>3 - 5</th>
                <td>ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>ENGLISH</td>
                <td>PYTHON</td>
                <td>FWAD</td>
            </tr>
        </table>

        <h2>Subject Details</h2>
        <table class="subject-table">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMING (PYTHON)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH (ENGLISH)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>ECA-M</td>
                <td>MENTOR MEET</td>
            </tr>
        </table>
    </div>

</body>
</html>
```

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0aed9adc-c1c5-41e3-8e6b-c41870fccdc5" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
