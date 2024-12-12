# Ex03 Time Table
# Date:28-11-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using` <table> ` tag in html.

## STEP 4
Add header row using` <th> `tag.

## STEP 5
Add your timetable using` <td> ` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
<!doctype html>
  <html>
    <head>
	   <title>table</title>
	   
	      <style>
		  
		    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color:brown;
        }
		td,table {
            background-color:blanchedalmond;
        }
    </style>
</head>
<body>
      

    
 <h2>SLOT TIME TABLE - SHRI VIMAL (24003314)</h2>
 <table>
     <thead>
         <tr>
             <th>DAY</th>
             <th>MONDAY</th>
             <th>TUESDAY</th>
             <th>WEDNESDAY</th>
             <TH>THURSDAY</TH>
             <th>FRIDAY</th>
             <th>SATURDAY</th>
			
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>8.00-10.00</th>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>CHEMISTRY</td>
                 <td>-</td>
              </tr>
            <tr>
                <th>10.00-12.00</th>
                <td>WEB</td>
                <td>DIGITAL ELECTRONIS</td>
                <td>PYTHON</td>
                <td>PROBABILITY</td>
                <td>DIGITAL</td>
                <td>CAREER DEVELOPMENT</td>
             </tr>
            <tr>
                <th>12.00-1.00</th>
                <td colspan="6">LUNCH BREAK</td>
             </tr>
           
            <tr>
                <th>1.00-3.00</th>
                <td>HUMAN VALUES</td>
                <td>CHEMISTRY</td>
                <td>MENTOR MEET</td>
                <td>WEB</td>
                <td>PYTHON</td>
                <td>PROBABILITY</td>  
            </tr>
            <tr>
              <th>3.00-5.00</th>
              
                <td colspan="5">-</td>
                <td>WEB</td>
            </tr>
              
        </table>
            
        </tbody>
         <br><br>
        <table>
           <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
           </tr>
           <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
         </tr>
         <tr>
            <td>2</td>
            <td>SH7801</td>
            <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
         </tr>
         <tr>
            <td>3</td>
            <td>19EE404</td>
            <td>DIGITAL ELECTRONICS</td>
         </tr>
         <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>CHEMISTRY</td>
         </tr>
         <tr>
            <td>5</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING</td>
         </tr>
         <tr>
            <td>6</td>
            <td>19MA222</td>
            <td>PROBABILITY AND QUEUEING MODELS</td>
         </tr>
         <tr>
            <td>7</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS</td>
         </tr>    
        </table>
    </body>
    </html>
           
           
```
# OUTPUT

![alt text](<Screenshot (2).png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
