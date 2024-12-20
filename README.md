# Ex03 Time Table
# Date:25-11-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
    <html>
        <head>
    
        
            <title>TIME TABLE</title>
        </head>
        <style>
            th{
                font-size: 20px;
            }
            ol li{
                font-size: 25px;
            }
        </style>
        <body>
        <center>
        <img src="/static/saveetha.png" height="100" width="500">
        </center>
        <br>
        <table align="center" width="500" collspacing="2" collspacing ="4" border="5" bgcolor="cyas">
            <caption><h2>SLOT TIME TABLE - DEEPIKA.R  (24900220)</h2></caption>
            <tr align="center">
                <th bgcolor="blue">DAY</th>
                <th bgcolor="blue">08:00 - 10:00</th>
                <th bgcolor="blue">10:00 - 12:00</th>
                <th bgcolor="blue">12:00 - 01:00</th>
                <th bgcolor="blue">01:00 - 03:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">MONDAY</th>
                
                <td bgcolor="yellow">   </td>
                <td bgcolor="yellow">Career Development</td>
                <td  rowspan="6" bgcolor="yellow">Lunch</td>
                <td bgcolor="yellow"> Web</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">TUESDAY</th>
                <td bgcolor="yellow">Communicative <br>English</td>
                <td rowspan="2" bgcolor="yellow">   </td>
                <td bgcolor="yellow">statistic and <br>Numerical</td>
  
            </tr>
            <tr align="center">
                <th bgcolor="blue">WEDNESDAY</th>
                <td bgcolor="yellow">Calcules Matrix<br> and algebra</td>
                <td bgcolor="yellow">Menter class</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">THURSDAY</th>
                <td bgcolor="yellow">Physics</td>
                <td bgcolor="yellow">Calcules Matrix<br>and algebra</td>
                <td bgcolor="yellow">Digital Electron</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">FRIDAY</th>
                <td bgcolor="yellow">Communicative <br>English</td>
                <td bgcolor="yellow">Web</td>
                <td bgcolor="yellow">Physics</td>

            </tr>
            <tr align="center">
                <th bgcolor="blue">SATURDAY</th>
                <td bgcolor="yellow">Statistic and<br> Numerical</td>
                <td bgcolor="yellow">Web</td>
                <td bgcolor="yellow">Digital Electron</td>
            </tr>
        </table>
        </center>
        <ol border="2">
            <li>Career Development Skill  (19EY708)</li>
            <li>Fundamental of Web Development  (19Al414)</li>
            <li>Communicative English  (19EN101)</li>
            <li>Statistics and Numerical Methods  (19MA211)</li>
            <li> Calculus and Matrix Algebra  (19MA201)</li>
            <li>Menter Meet (ECA-SCOFT)</li>
            <li>Physics for Quantum computing  (SH3214)</li>
            <li> Digital Electronics (19EE404)</li>

        </ol>
    </table>
    
        

    </body>
</html>
```
# OUTPUT

![image](https://github.com/user-attachments/assets/251ff08b-66e0-49b7-b232-91d042d5b7d5)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
