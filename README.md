# Ex.06 Book Front Cover Page Design
## Date:01-12-23

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
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url( bookcover.jpg );
                background-size: cover;
            }
            .insight {
                color: salmon;
            }
            .hr1 {
                width: 130px;
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                color:bisque;
                position: relative;
                top: 40px;  
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:antiquewhite;
                top: 130px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 190px;
                left: 280px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 230px;
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:Salmon;
                top: 230px
            }
            .pub {
                font-size: large;
                position: relative;
                top: 190px;
                left: 330px;
                color:Salmon;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                CODING CHRONICLES
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1 align="center"> A JOURNEY OF COMPUTER SCIENCE HISTORY </h1>
            </div>
            <div class="para">
                <p align="center"> "Computing is not about computers anymore. It is about living."  </p>
            </div>
            <div class="pic">
                <img src="pic.jpg" width="130" height="145" alt="">
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>STARBIYA.S</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Third Edition </b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot 2023-12-01 214440.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
