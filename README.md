# Ex03 Time Table
## Date:20-11-2024

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
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <center>
    <img src="c:\\Users\\admin\\Downloads\\logo.jpg">
    </center>
    <title>TIME TABLE</title>
    <center>
    <h3> SLOT TIME TABLE - Arshath Hussain (24008800)</h3>    
    </center>
    </head>    
    <style>
        body{
            font-family:
    Arial,sans-serif;
          margin:0
          padding:0
            background-colour: antiquewhite;
            border;2px solid 
        }
        table{
            border-collapse: collapse;
            margin: 20px  auto;
            background-color: cyan;
                 solid
            box-shadow: 0;
        }
        td{
            border: 20px
        solid
            padding:10px;
            text-align:
        }
    </style>
<table border="1" width="50%" height="25%">
    <tr  style="background-color: rgba(227, 127, 27, 0.955);">
    <th>Day/Time</th>
    <th> 8-10 </th>
    <th> 10-12 </th>
    <th> 12-1 </th>
    <th> 1-3 </th>
    <th> 3-5 </th>
    </tr>
    <tr> 
        <th style="background-color: yellow;"></thstyle>Monday</th>
        <td style="background-color: cyan;"> </td> 
        <td style="background-color: cyan;"> web </td>
        <td rowspan="6" style="background-color: rgb(242, 248, 248);"> Lunch </td>
        <td style="background-color: cyan;"> </td>
        <td style="background-color: cyan;"> </td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>Tuesday</th>
        <td style="background-color: cyan;"> English </td>
        <td style="background-color: cyan;"> </td>
        <td style="background-color: cyan;"> Python </td>
        <td style="background-color: cyan;"> </td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>Wesdnesday</th>
        <td style="background-color: cyan;"> Python </td>
        <td style="background-color: cyan;"> </td>
        <td style="background-color: cyan;"> Mentor Meet </td>
        <td style="background-color: cyan;"> </td>
    </tr>  
    <tr>
        <th style="background-color: yellow;"></thstyle>Thrusady</th>
        <td style="background-color: cyan;"> Physics </td>
        <td style="background-color: cyan;"> Python </td>
        <td style="background-color: cyan;"> web </td>
        <td style="background-color: cyan;"> </td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>Friday</th>
        <td style="background-color: cyan;"> English</td>
        <td style="background-color: cyan;"> Career Development </td>
        <td style="background-color: cyan;"> Physics </td>
        <td style="background-color: cyan;"> </td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>Saturday</th>
        <td style="background-color: cyan;"> </td>
        <td style="background-color: cyan;"> Python</td>
        <td style="background-color: cyan;"> </td>
        <td style="background-color: cyan;"> web</td>
    </tr>    
</table>
</head>
<body>
<table border="4px" width="300" height="400">
        <tr>
            <th> S.NO </th>
            <th> Subject Name </th>
            <th> Subject Code </th>
        </tr>
        <tr>
            <th> 1. </th>
            <td> Fundamentals of web applications </td>
            <td> 19AI414 </td>
        </tr>
        <tr>
            <th> 2. </th>
            <td> python/linear algebra </td>
            <td> 19AI301C </td>
        </tr>
        <tr>
            <th> 3. </th>
            <td> English </td>
            <td> 19EN101 </td>
        </tr>
        <tr>
            <th> 4. </th>
            <td> Physics </td>
            <td> SH3214 </td>
        </tr>
        <tr>
            <th> 5. </th>
            <td> Career Development Skills</td>
            <td> 19EY708 </td>
         </tr>
</table>
</body>
</html>
  
## OUTPUT

![Screenshot 2024-11-20 155614](https://github.com/user-attachments/assets/6fb1b3ef-05c3-41a9-ade0-a2c42a27ae21)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
