# Ex.05 Book Cover Page Design
## Date: 15-12-2025

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
        <title>Cover Page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>

        <div class="BackCover"> 
        <h2>About the Book</h2>
        <hr>
        <p>
            This book <mark>"Inside the Digital Mind: How Software Thinks"</mark> invites readers to look beyond screens and code to understand how software actually makes decisions. It breaks down complex ideas like algorithms, logic, data flow, and automation into simple concepts that feel almost human.
        </p>
        <p>
            By connecting everyday problem-solving with computational thinking, this book helps readers build a strong mental model of how software operates behind the scenes. 
        </p>
    

        <div class="Facts">
            "Code is not just written - it is reasoned, tested, and brought to life."
        </div>

        <div class="about-author">
            <img src="Author.jpeg">
            <div>
            <h3>Aadhavan Nagarajan</h3>
            <p>
            Aadhavan Nagarajan is a computer science enthusiast who enjoys exploring how simple logic turns into powerful digital systems. With a strong interest in programming and problem-solving, he focuses on understanding concepts deeply rather than just writing code. This book reflects his curiosity-driven learning journey and his effort to present computer science ideas in a clear and relatable way for fellow learners.
            </p>
            </div>
        </div>

        <div class="Publisher-Details">
            <span>SEC Publishers <br> Printed in India</span>
            <span class="Rate">Rs.249</span>
        </div>
        </div>
    </body>
</html>

style.css

body {
    font-family: Arial, sans-serif;
    padding: 20px;
    background-image: url(Image.png);
    background-repeat: no-repeat;
    background-position: 181px 0px;
}
.BackCover {
    background: white;
    width: 46%;
    margin: auto;
    padding: 25px;
}
h2{
    color: rgb(0, 0, 0);
}
hr 
{
    height: 2px;
    background: rgb(30, 32, 30);
    margin: 10px 0 20px 0;
}
p 
{
    line-height: 2;
    color: rgb(0, 0, 0);
}
.Facts
{
    background: rgb(52, 54, 48);
    border-left: 5px solid rgb(50, 53, 48);
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
    color: rgb(255, 255, 255);
    border-radius: 5px;
}
.about-author 
{
    display: flex;
    background: rgb(36, 41, 38);
    padding: 15px;
    border-radius: 10px;
    margin-top: 25px;
    gap: 15px;
}
.author-Image 
{
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
}
.about-author h3 {
    margin: 0 0 5px 0;
    color: rgb(255, 255, 255);
}


.about-author img {
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
}

.about-author p
{
    color: white;
}

.Publisher-Details {
    margin-top: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgb(51, 50, 50);
    color: rgb(255, 255, 255);
    padding: 12px 20px;
    border-radius: 10px;
}
.Rate
{
    font-weight: bold;
    font-size: 18px;
}
mark
{
    background-color: rgb(86, 99, 93);
}
```

## OUTPUT:

![alt text](<Screenshot (113)-1.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
