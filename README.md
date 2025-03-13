# Ex03 Time Table
## Date:13/03/2025
## register: 212224240158

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
</head>
<body>
    <img src="image.png"  height="100" width="950" alt="Cannot find">
    <style>
        body{
            background-color: darkkhaki;
        }
    </style>
    
    <center><h2 style="background-color: blanchedalmond;">TIME TABLE </h2></center>
    <center><table border="2">
        <caption>SLOT TIME TABLE</caption>
        <tr>
            <th> Day/time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr style="background-color: brown;">
            <td>8-10</td>
            <td colspan="3">Free Slot</th>
            <td>phy</td>
            <td>che</td>
        </tr>
        <tr style="background-color: rgb(188, 131, 46);">
            <td>10-12</td>
            <td>GER</td>
            <td>free slot</td>
            <td colspan="2">FWAD</td>
            <td>PHY</td>
        </tr>
        <tr style="background-color: rgb(188, 131, 46);">
            <td>12-1</td>
            <td colspan="5">FREE SLOT</td>
        </tr>
        <tr style="background-color: rgb(188, 131, 46);">
            <td>1-3</td>
            <td colspan="2">FREE SLOT</td>
            <td>MATH</td>
            <td>SS</td>
            <td>c program</td>
        </tr>
        <tr style="background-color: rgb(188, 131, 46);">
            <td>3-5</td>
            <td rowspan="2">FREE SLOT</td>
            <td>GER</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
            
        </tr>

    </table></center>
    <hr>
    <center><table border="2">
        <tr>
            <td>S.NO</td>
            <td>course code</td>
            <td>course name</td>
            
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN612</td>
            <td>German Basic</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19PH206</td>
            <td>Physics for Information Technology</td>

        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and mat algebra</td>

        </tr>
    </table></center>
</body>
</html>
```
## OUTPUT

![image](https://github.com/user-attachments/assets/376c8c33-4c93-4506-beac-496157fdaf59)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
