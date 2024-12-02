# EX01 Developing a Simple Webserver

# Date:11-11-2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
  ```<!DOCTYPE html>
  <html lang="en">
  <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet"href="style.css">
       <title>Device specifications</title>

  <style>
   body{
    height:100%;
    margin:20px;
    display:flex;
    text-align:center;
    justify-content: center;
    align-items: center;
 }
 .Logo{
    width:50%;
    height:100%;
    align-items: center;
    justify-content: center;
    padding: 20px;
}
 table{
     width:100%;
     height:100%;
     border-collapse:collapse;
     padding:20px;
    
    
 }


 th,td{
     border:1px solid #1b1a1afa;
     padding:10px;
     text-align:center;
    
 }

 th{
    background-color: rgb(200, 135, 49);

 }

 td{
     background-color:antiquewhite;
 }

 .Table th {
     background-color:rgb(49, 185, 200);
 }
 .Table td {
     background-color: aquamarine;
 }   
 </style>
 </head>
 <body>
 <div class="Logo">
     <center>
     <h1>DEVICE SPECIFICATION</h1>
     </center>
    <table>
        <tbody>
        <center>
          <tr>
                 <th>Device name</th>
                <td>DESKTOP-MOHHBTU</td>
             </tr>
             <tr>
                 <th>Processor</th>
                 <td>13th Gen Intel(R)Core(TM)i5-13335U 1.30GHz</td>
             </tr>
             <tr>
                 <th>Installed RAM</th>
                 <td>16.0 GB(15.7 GB usable)</td>
             </tr>
             <tr>
                 <th>Device ID</th>
                 <td>15EEEA3B2-7EF5-4DEC-903D-57782C3C005</td>
             </tr>
             <tr>
                 <th>Product ID</th>
                 <td>00342-42708-33510-AAOEM</td>
             </tr>
             <tr>
                 <th>System type</th>
                 <td>64-bit operation system,x64-based processor</td>
             </tr>
             <tr>
                 <th>Pen and touch</th>
                 <td>No pen or touch input is available for this display</td>
            </tr>
        <center>
         </tbody>
        </table>   
</body>
</html>```
          
# OUTPUT:
![Screenshot (45)](https://github.com/user-attachments/assets/b420267c-dc73-4891-a1de-98b96e8425d8)

          
# RESULT:
The program for implementing simple webserver is executed successfully.
