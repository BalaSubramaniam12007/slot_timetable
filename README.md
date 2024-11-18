# Ex03 Time Table
## Date:18.11.2024

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
    <title>SLOT TIME TABLE - BALASUBRAMANIAM (24901213)</title>
   
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 20px auto;
            font-family: Arial, sans-serif;
        }
        
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        
        .header {
            background-color: yellow;
            font-weight: bold;
        }
        
        .slot {
            background-color: #87CEEB;
        }
        
        .lunch {
            background-color: #FFFF99;
        }
        
        .subject-table {
            margin-top: 30px;
        }
        
        .subject-table th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <<img src="logo.png" alt="Logo" style="width<img src="logo.png" alt="Logo" style="width: 640; height: 480;"><br>
    <table border="5" align="centre" cellpadding="15" >><br>
    <table border="5" align="centre" cellpadding="15" >
    <h2 style="text-align: center;">SLOT TIME TABLE - BALASUBRAMANIAM(24901213)</h2>
    
    <!-- Time Table -->
    <table>
        <tr class="header">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="header">8-10</td>
            <td class="slot" colspan="3">FREE SLOT</td>
            <td class="slot">PHY</td>
            <td class="slot">CHE</td>
            <td class="slot">Machine Learning</td>
            
        </tr>
        <tr>
            <td class="header">10-12</td>
            <td class="slot">Web Applications</td>
            <td class="slot">FREE SLOT</td>
            <td class="slot">Web Applications</td>
            <td class="slot">Probability</td>
            <td class="slot">PHY</td>
            <td class="slot">Free Slot</td>
        </tr>
        <tr>
            <td class="header">1-3</td>
            <td class="slot" colspan="2">FREE SLOT</td>
            <td class="slot">MAT</td>
            <td class="slot">MAT</td>
            <td class="slot">Statitics</td>
            <td class="slot">Web Application</td>
        </tr>
        <tr>
            <td class="header">3-5</td>
            <td class="slot" colspan="6">FREE SLOT</td>
            
        </tr>
        
    </table>

    <!-- Subject Details Table -->
    <table class="subject-table">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19A1414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>Machine Learning(ML)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Statitics (S)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY701</td>
            <td>Probability (PRO)</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT
![Screenshot 2024-11-18 074445](https://github.com/user-attachments/assets/8e3b131a-93f8-48c1-b67f-c0a54ccf47ff)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
