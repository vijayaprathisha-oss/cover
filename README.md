# Ex.05 Book Cover Page Design
## Date:18/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
    <head>
        <title>BOOK COVER</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <div class="header">
                <h2>NAME OF THE BOOK-CODE CRAFT</h2>
            </div>
            <div class="content">
                <p>
                <br><b>
                  Code Craft is a beginner-friendly guide that introduces the fundamentals of programming through clear explanations, logical thinking, and practical examples. It helps learners build strong coding foundations, understand how programs work, and develop the mindset needed to write clean and efficient code.  
                </b>
                </p>
            </div>
            <div class="quotes">
                <h4>
                    “Programming is not just about writing code.
                     It is about shaping ideas into logic.”
                </h4>
            </div>
            <div class="author">
                <img src="photo.jpg" width="90" height="100" align="left" hspace="10" vspace="10">
                <h3>VIJAYAPRATHISHA J (25008497)</h3>
                <p>Vijayaprathisha J, a first-year B.Tech student specializing in Artificial Intelligence and Machine Learning, is deeply passionate about programming and solving real-life problems through code. With a strong interest in logical thinking and practical application, she aims to simplify programming concepts and inspire learners to view coding as both a skill and a craft.</p>
            </div>
            <div class="footer">
                <h3>SEC PUBLISHERS</h3>
                <h3 align="right">Rs.300/-</h3>
            </div>
        </div>
    </body>
</html>

styles.css

.container
{
    background:url("bg.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height:720px;
    width:600px;
    border:4px solid cyan;
    border-radius: 10px 10px 10px 10px;
}
.header
{
    color:black;
}
h2
{
    color:yellow;
    text-align: center;
    text-decoration: underline;
}
.content
{
    font-size: 20px;
    padding-left: 20px;
    padding-right: 20px;
}
.quotes
{
    width:500px;
    height: 50px;
    background-color: antiquewhite;
    margin-left: 30px;
    padding-left:20px;
    color:hotpink
}
.author
{
    width:500px;
    height:200px;
    background-color:bisque;
    margin-left: 30px;
    padding-left:20px;
    color:cadetblue;
}
.footer
{
    width:500px;
    height:60px;
    background-color:lightslategray;
    margin-left:30px;
    padding-left:20px;
    padding-bottom:15px;
    margin-top:20px;
    color:yellow;
    bottom: 0px;    
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-18 092044.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
