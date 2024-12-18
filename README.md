# Ex03 Time Table
## Date:17/11/2024

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
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252"></head>
<body>
    <img src="logo.png">
        <table border="1" cellspacing="10" cellpadding="2">
            <caption>SLOT TIME TABLE -MOUNIKA M(24010589)</caption>
            <tbody><tr bgcolor="lavender">
               <th bgcolor="violet">DAY/TIME</th>
               <th>Monday</th>
               <th>Tuesday</th>
               <th>Wednesday</th>
               <th>Thursday</th>
               <th>Friday</th>
               <th>Saturday</th>
            </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">8-10</td>
                    <td>FREE SLOT</td>
                    <td>CDS</td>
                    <td>FREE SLOT</td>
                    <td>PHY</td>
                    <td>FWAD</td>
                    <td>EDM</td>
                </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">10-12</td>
                <td>EDM</td>
                <td>MATH</td>
                <td>C</td>
                <td>FREE SLOT</td>
                <td>C</td>
                <td>PHY</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">12-1</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>SCOFT MM</td>
                <td>DE</td>
                <td>FREE SLOT</td>
                <td>MATH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">3-5</td>
                <td>FREE SLOT</td>
                <td>DE</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
        </tbody></table>
        <table border="1" cellspacing="10" cellpadding="2">
            <tbody><tr bgcolor="sky blue">
                <th bgcolor="sky blue">S.NO</th>
                <th>Course code</th>
                <th>Course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGNING AND MODELLING</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENT SKILLS</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19MA201</td>
                <td>CALCULUS AND MATRIX ALGEBRA</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>SH3214</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
        </body></table>
    
</body></html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-17 210036.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
