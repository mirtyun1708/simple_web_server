# EX01 Developing a Simple Webserver

# Date:
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Front Cover Page</title>
    <style>
      .a{
       background-color: black;
       width: 400px;
       height: 470px;
       border: 1px;
       border-radius: 10px;
       text-align: left;
      }
     .one{
       color: aliceblue;
       font-family: 'Courier New', Courier, monospace;
       font-size: 10px;
       position: relative;
       left: 20px;
       top: 10px;
      }
      .two{
        color: greenyellow;
        position: relative;
        top: 10px;
      }
      .three{
        color: aliceblue;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 45px;
        position: relative;
        left: 20px;
        top: 20px;
      }
      .four{
        color: aliceblue;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 45px;
        position: relative;
        left: 20px;
        top: 15px;
      }
      .five{
        color: aliceblue;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 45px;
        position: relative;
        top: 15px;
        left: 20px;
      }
      .six{
        color: aliceblue;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 12px;
        position: relative;
        left: 20px;
        top: 25px;
      }
      .seven{
        color: aliceblue;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 12px;
        position: relative;
        left: 20px;
        top: 25px;
      }
      .img1{
        height: auto;
        width: 400px;
        position:relative;
        bottom: 100px;
      }
      .img2{
        height: auto;
        width:60px;
        position: relative;
        bottom: 350px;
        left: 250px;
      }
      .img3{
        height: auto;
        width: 60px;
        position: relative;
        bottom: 405px;
      }
      .hr{
        color:red;
        position: relative;
        bottom: 240px;
      }
      .q{
        color: orange;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 20px;
        position: relative;
        bottom: 270px;
        left: 20px;
      }
      .w{
        color: aliceblue;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        font-size: 30px;
        position: relative;
        bottom: 270px;
        left: 290px;
      }
      .z{
        color: aliceblue;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 20px;
        position: relative;
        bottom: 290px;
        left:20px
      }
   </style>
</head>
<body>
  <center>
  <div class="a">
   <div class="one">EXPERT INSIGHT</div>
   <div class="two"><hr color="orangered"></div>
   <div class="three">Responsive Web</div>
   <div class="four">Design With</div>
   <div class="five">HTML5 and CSS</div>
   <div class="six">Develop future-proof responsive websites</div>
   <div class="seven"> using the latest HTML5 and CSS techniques</div>
   <img src="—Pngtree—abstract gradient wave lines clipart_8816453.png" alt="Book Cover Image" class="img1">
   <img src="css.png" alt="" class="img2">
   <img src="html.png" alt="" class="img3">
   <div class="hr"><hr color="orangered"></div>
   <div class="q">Third Edition</div>
   <div class="w"><u>Packt</div>
   <div class="z">Ben Frain</div>
</center>
</body>
```
# OUTPUT:
![WhatsApp Image 2024-11-25 at 10 42 44 AM](https://github.com/user-attachments/assets/4e0d60b5-d554-44f1-a992-173dadc4f51b)

# RESULT:
The program for implementing simple webserver is executed successfully.
