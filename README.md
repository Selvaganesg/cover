# Ex.06 Book Front Cover Page Design
## Date:24/4/2025

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
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Atomic Habits</title>
   <style>
           #body{
           background-color: #F5ECD5;
           width: 630px;
           height: 800px;
       }
           #sub_head{
           line-height: 0.5;
           padding: 30px;
       }
           #head_one{
           color: #E7D283;
           font-size: 150px;
           line-height: 0;
           font-family: 'Inter', sans-serif;
       }
           #head_two{
           color: #E7D283;
           font-size: 150px;
           line-height: 0.5;
           font-family: 'Inter', sans-serif;
       }
           #para{
           padding-right: 10px;
           font-size: 30px;
           display: inline-block;
       }
           #circle_one{
           width: 105px;
           height: 105px;
           background-color: red;
           border-radius: 100px;
           padding: 10px;
           display: inline-block;
       }
           #circle{
           width: 100px;
           height: 100px;
           border-radius: 100px;
           background-color: red;
           color: white;
           display: inline-block;
           border: 2px solid white;
       }
           #author{
           font-size: 60px;
           line-height: 0;
           padding-bottom: 50px;
       }
           #text{
           width: 100px;
           height: 100px;
           border-radius: 100px;
           background-color: red;
           color: white;
           padding: 10px;
           display: inline-block;
           border: 2px solid white;
       }
   
   </style>
</head>
<body>
   <center>
       <div id="body">
           <h2 id="sub_head">THE INTERNATIONAL BESTSELLER</h2>
           <h1 >Tiny Changes</h1>
           <h1>Remarkable Results</h1>
           <h1 id="head_one">Atomic</h1>
           <h1 id="head_two">Habits</h1>
           <h3 id="para">An Easy & Proven Way<br>to Build Good Habits<br>Break Bad Ones</h3>
           <div id="circle_one">
               <div id="circle">
               
                   <p>
                       OVER
                       3 MILLION
                       COPIES
                       SOLD
                   </p>
               </div>
           </div>
           <h1 id="author">James Clear</h1>
       </div>
   </center>
</body>
</html>
```

## OUTPUT:

![alt text](image-1.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
