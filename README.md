# Ex03 Time Table
## Date:14.03.2024

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
```html
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid red;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color:cyan;
        }
    </style>
</head>
<body>

<h2>Timetable GOKUL.M 212222230037</h2>

<table>
  <tr>
    <th>Day</th>
    <th>8:00 - 10:00</th>
    <th>10:00 - 12:00</th>
    <th>12:00 - 1:00</th>
    <th>1:00 - 3:00</th>
    <th>3:00 - 5:00</th>
  
  </tr>
  <tr>
    <b><td>Monday</td></b>
    
    <td>FREE</td>
    <td>Fundamentals 0f AI</td>
    <td>Lunch</td>
    <td>Intro data science</td>
    <td>Probability</td>

  </tr>
  <tr>
    <td>Tuesday</td>
    <td>FREE</td>
    <td>DIPT</td>
    <td>Mentor Meet</td>
    <td>WEB</td>
    <td>FREE</td>

  </tr>
  <tr>
    <td>Wednesday</td>
    <td>Probability</td>
    <td>DIPT</td>
    <td>LUNCH</td>
    <td>HRM</td>
    <td>Fundamentals of AI</td>

  </tr>
  <tr>
    <td>Thursday</td>
    <td>FREE</td>
    <td>FREE</td>
    <td>LUNCH</td>
    <td>WEB</td>
    <td>OS</td>

  </tr>
  <tr>
    <td>Friday</td>
    <td>WEB</td>
    <td>FREE</td>
    <td>LUNCH</td>
    <td>HRM</td>
    <td>FREE</td>

  </tr>
  <tr>
    <td>Saturday</td>
    <td>OS</td>
    <td>FREE</td>
    <td>LUNCH</td>
    <td>FREE</td>
    <td>Intro to data science</td>
  </tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
   
    </tr>
    <tr>
    <td align="center">1.</td>
    <td align="center">19AI414</td>
    <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
    <td align="center">2.</td>
    <td align="center">19AI403</td>
    <td>Introduction to Data Science</td>
    </tr>
    <tr>
    <td align="center">3.</td>
    <td align="center">19AI405</td>
    <td>Fundamentals of Artificial Intelligence</td>
    </tr>
    <tr>
    <td align="center">4.</td>
    <td align="center">19AI406</td>
    <td>Digital Image Processing Techniques</td>
    </tr>
    <tr>
    <td align="center">5.</td>
    <td align="center"> 19MA222</td>
    <td>Probability And Queueing Models</td>
    </tr>
    <tr>
    <td align="center">6.</td>
    <td align="center">19CS405</td>
    <td>Operating System</td>
    </tr>
    <tr>
    <td align="center">7.</td>
    <td align="center">19MS156</td>
    <td>Human Resource Management and Team Building</td>
    </tr>
    </table>
    
<table>

</table>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (108).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

