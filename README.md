# Ex.06 Book Front Cover Page Design
## Date:18/12/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
<!DOCTYPE html>
<html>
<head>
   <title>CSE</title>
   <style>
       .bookpage{
           width: 400px;
           height: 600px;
           color:black;
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: ' Arial, sans-serif';
           background-image: url("https://img.freepik.com/premium-photo/futuristic-data-visualization-technology-driven-blue-seamless-pattern_964851-32010.jpg");
           background-size: cover;
       }
      
       .author{
       
           display: inline;
           position: relative;
           color:rgb(255, 255, 255);
           top:190px;
           
           font-family:Georgia;
           font-size: medium;
       }
       .booktitle{
           color:azure;
           font-family: Roquen;
           font-size: larger;
           text-align: center;
           position: relative;
           top: 30px;
       
       }
       .id {
           width:400px;
           position: relative;
           top:180px;
           
       }
       
       .ed{
           color:azure;
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;
       
       }
       </style>
       <title>Book Cover Page</title>
       </head>
       <body>
       <div class="bookpage">
           <div class="booktitle">
               <h1> <FONT color="white">INTRODUCTION OF COMPUTER SCIENCE</h1></div></FONT>
               <br>
           <div class="subtitle">
               <center><font color="white">DEVELOPE SKILL</center></font>
           </div>
           <br>
           <br>
           <br>
           <br>
           <br>
           <br>
           <div class="id">
               <hr style="color:blanchedalmond">
           </div>
           <div class="author">
              <p><b>AVANTHIKA </b></p>
           </div>
       </div>
       </body>
       
</html>



```
## OUTPUT:

![alt text](<Screenshot (5).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
