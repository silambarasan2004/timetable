# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
Create a simple table using table tag.Come to theia ide.Create a folder assignment.
Ceate a folder time table.Create a static folder and create a folder html and inside the create a file image.

### STEP 2
Add header row using th tag
your semister time table to write in this html.
### STEP 3
Add your timetable.your time table and register no and name to write.
### STEP 4
To run this program.

# CODE
```python
<!DOCTYPE html>
<html lang="en">
    <body>
        <img src="logo.png" height="120" width="1500" alt="LOGO">
        <table border="2" cellspacing="2"
        bordercolor="black"
        bgcolor="white" align="center">
        <tr>
            <th colspan="8">TIME TABLE</th>
        </tr>
        <tr>
            <th colspan=2>Reference Number:</th>
            <th colspan=2>22008639</th>
            <th colspan=2>Name:</th>
            <th colspan=2>Silambarasan.E</th>
        </tr>
        <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th rowspan="8">lunch break</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
            <th>8</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>break</td>
            <td>Soft Skill</td>
            <td>Soft Skill</td> 
            <td>Break</td>
            <td>Coding Practice M06</td>
            <td>Coding Practice M06</td>
            <td>Break</td>
            <td>Break</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>Fundamentals of Web Application Development</td>
            <td>Fundamentals of web Application Development</td>
            <td>Coding Practice T03</td>
            <td>Coding Practice T03</td>
            <td>Break</td>
            <td>Break</td>
            <td>Computational Physics</td>
            <td>Computational Physics</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>Computational Physics</td>
            <td>Computational Physics</td>
            <td>Principles of Chemistry in Engineering</td>
            <td>Principles of Chemistry in Engineering</td>
            <td>Calculus and Matrix Algebra</td>
            <td>Calculus and Matrix Algebra</td>
            <td>Break</td>
            <td>Break</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>Problem Solving and Python Programming P1</td>
            <td>Problem Solving and Python Programming P1</td>
            <td>Fundamentals of web Application Development</td>
            <td>Fundamentals of web Application Development</td>
            <td>Calculus and Matrix Algebra</td>
            <td>Calculus and Matrix Algebra</td>
            <td>Programming in C P1</td>
            <td>Programming in C P1</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>Fundamentals of web Application Development</td>
            <td>Fundamentals of web Application Development</td>
            <td>Programming in C P1</td>
            <td>Programming in C P1</td>
            <td>Problem Solving and Python Programming P1</td>
            <td>Problem Solving and Python Programming P1</td>
            <td>Principles of Chemistry in Engineering</td>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
    </body>
</html>
```
# OUPUT
![time table](image/timetable.png)
