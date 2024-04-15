# Ex.06 Book Front Cover Page Design
## Date:15/04/2024

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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: lightcyan;
                margin-left: auto;
                margin-right: auto;
                padding: 50px;
                font-family: cursive;
                background-image: url(book.png);
                background-size: cover;
            }
            .insight{
                color: cyan;

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color: cyan;
                top: 300px;
                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Times New Roman', Times, serif;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: px;
                position: relative;
                top: 300px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 250px;
                left: 330px;
            }
            .ed{
                color: white;
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 200px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 75px;
            }
            .mypic{
                position: relative;
                top: 240px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: white">
            </div>
            <div class="booktitle">
                <h1>Programming in Python</h1>
            </div>
            <div class="subtitle">
                Become a pro in Python
            </div>
            <div class="mypic">
                <img src="mypic.jpg" width="110" height="140" >
            </div>
            <div class="id">
                <hr style="color: white">
            </div>
            <div class="author">
                <p><b>VIKAASH</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Special Edition</b>
            </div>
        </div>
   </body>
</html>
```
## OUTPUT:
![alt text](<output exp6.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
