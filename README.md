# Ex-04-Timetable
## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```HTML
<!DOCTYPE html>
<html>
 
<body>
    <centre>
    <img align="centre" src="logo.png" width="700"height="100" border="10" >

    <h1 align="centre">TIME TABLE</h1>
    <table border="5" cellspacing="5" >
        <!--<caption>Timetable</caption>-->
        <tr align = "center" height="50" width="100" bgcolor="#FF5833">
            <td><b>REFERENCE NUMBER:</b></td>
            <td><b>23002136</b></td>
            <td><b>NAME</b></td>
            <td><b>PRASHANTH .K</b></td>
            <td><b>DEPARTMENT</b></td>
            <td><b>AI&DS</b></td>
        </tr>
        
        <tr bgcolor="#33FFF6">
            <td align="center" height="50"
                width="100"><br>
                <b>Day/Period</b></br>
            </td>
            <td align="center" height="50"
                width="110">
                <b>I<br>8:00-10:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>II<br>10:00-12:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>12:00-1:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>III<br>1:00-3:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>IV<br>3:00-5:00</b>
            </td>
           
        </tr>
        <tr bgcolor="#1C58A8">
            <td align="center" height="50" bgcolor="#33FFF6">
                <b>Monday</b></td>
            <td align="center" height="50"><h3>Engineering Design and Modelling</h3>
            </td>
            <td align="center" height="50"><h3>Basic Electrical,Electronics and Measurement Engineering</h3></td>
            <td rowspan="6" align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2></td>
            <td align="center" height="50">---</td>
            <td align="center" height="50">---</td>

        
            
        </tr>
        <tr bgcolor="#1C58A8">
            <td align="center" height="50" bgcolor="#33FFF6">
                <b>Tuesday</b>
            </td>
            
            <td align="center" height="50"><h3>Digital Electronics</h3></td>
            <td align="center" height="50"><h3>Probability and queueing models</h3></td>
            <td align="center" height="50"><h3>Soft skills</h3></td>
            <td align="center" height="50">---</td>
        </tr>
        <tr bgcolor="#1C58A8">
            <td align="center" height="50" bgcolor="#33FFF6">
                <b>Wednesday</b>
            </td>
            <td align="center" height="50"><h3>Digital Electronics</h3></td>
            <td align="center" height="50"><h3>Fundamental of Web Application Development</h3></td>
            <td align="center" height="50"><h3>Basic Electrical,Electronics and Measurement Engineering</h3></td>
            <td align="center" height="50">---</td>
            
        
        </tr>
        <tr bgcolor="#1C58A8" >
            <td align="center" height="50" bgcolor="#33FFF6">
                <b>Thursday</b>
            </td>
            <td align="center" height="50"><h3>Fundamental of Web Application Development</h3></td>
            <td align="center" height="50"><h3>Fundamentals and C Programming</h3></td>
            <td align="center" height="50"><h3>Probability and Queueing models</h3></td>
            <td align="center" height="50">---</td>
            
        </tr>
        <tr bgcolor="#1C58A8">
            <td align="center" height="50" bgcolor="#33FFF6">
                <b>Friday</b>
            </td>
            <td align="center" height="50">---</td>
            <td align="center" height="50"><h3>Fundamental of Web Application Development</h3></td>
            <td align="center" height="50"><h3>Fundamentals of C programming</h3></td>
            <td align="center" height="50"><h3>Engineering Design and Modelling</h3></td>
        </tr>
        
    </table>
</body>
 
</html>
```



# OUPUT
![output](<timetable screen shot.png>)

# RESULT

Thus we display the timetable of us using HTML webpage sucessfully.