# Ex.05 Book Front Cover Page Design
## Date:18/12/2025

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
    <title>Book Cover</title>

    <style>
        body {
            background-color:black
            font-family: Arial, sans-serif;
        }

        .cover {
            position: relative;
            width: 350px;
            height: 550px;
            margin: 40px auto;
            padding: 15px;
            box-shadow: 0 0 10px gray;
            background-image: url("c58d078a-856c-4aed-9ff9-0bf536e245f2.jpg");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: black;
}


        .cover img {
            width: 100%;
            height: 220px;
        }

        .title {
            color:black
            font-size: 24px;
            font-weight: bold;
            margin-top: 15px;
            text-align: center;
        }

        .subtitle {
            color:black
            font-size: 16px;
            color: rgb(165, 156, 156);
            text-align: center;
            margin-top: 10px;
        }

        .synopsis {
            color:black
            font-size: 15px;
            margin-top: 80px;
            text-align: left;
        }

        .author {
            color:black
            position: absolute;
            bottom: 15px;
            right: 15px;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>

<body>

<div class="cover">
    <div id="image">
        <img src="image.png" alt="Book Image">
    </div>


    <div class="title">FUNDAMENTALS OF WEB DEVELOPMENT</div>
    <div class="subtitle">Concepts and Basics</div>


    <div class="synopsis">
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Web Design</li>
        <li>Layout</li>
        <li>Styling</li>
        <li>Basics</li>
    </ul>
<div>
    <div class="author">VISWAPRIYA S</div>
</div>

</body>
</body>
</html>
```




## OUTPUT:
<img width="1899" height="1074" alt="Screenshot 2025-12-24 194201" src="https://github.com/user-attachments/assets/3c7f0110-afb0-421e-8005-f48eb48fdfe6" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
