# Ex.05 Book Front Cover Page Design
## Date:27.12.2025

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
<title>Book Cover</title>
<style>
    body {
        background:#222;
        display:flex;
        justify-content:center;
        align-items:center;
        height:100vh;
        font-family: Arial, Helvetica, sans-serif;
    }

    .book {
        width:360px;
        height:520px;
        background: linear-gradient(#0b2a4a, #061c33);
        color:white;
        position:relative;
        box-shadow:0 20px 40px rgba(0,0,0,0.7);
        overflow:hidden;
    }

    /* Red Ribbon */
    .ribbon {
        position:absolute;
        top:0;
        left:0;
        background:#d32f2f;
        color:white;
        padding:8px 12px;
        font-size:12px;
        font-weight:bold;
        transform:rotate(-45deg);
        transform-origin:left top;
        margin:-20px;
    }

    /* Globe */
    .globe {
        width:140px;
        height:140px;
        background:radial-gradient(circle at 30% 30%, #4fc3f7, #01579b);
        border-radius:50%;
        margin:40px auto 20px;
        box-shadow:0 0 25px rgba(79,195,247,0.8);
    }

    /* Screens ring */
    .screens {
        display:flex;
        justify-content:center;
        gap:8px;
        margin-bottom:20px;
    }

    .screen {
        width:28px;
        height:20px;
        background:#263238;
        border:2px solid #90caf9;
    }

    /* Title */
    .title {
        text-align:center;
        margin-top:20px;
    }

    .title h1 {
        font-size:26px;
        margin:0;
        font-weight:bold;
    }

    .title h2 {
        font-size:22px;
        margin:5px 0 0;
        font-weight:normal;
    }

    /* Authors */
    .authors {
        position:absolute;
        bottom:60px;
        width:100%;
        text-align:center;
        font-size:14px;
        color:#bbdefb;
    }

    /* Publisher */
    .publisher {
        position:absolute;
        bottom:20px;
        width:100%;
        text-align:center;
        font-size:14px;
        font-weight:bold;
        letter-spacing:1px;
    }
</style>
</head>

<body>

<div class="book">

    <div class="ribbon">NEW</div>

    <div class="globe"></div>

    <div class="screens">
        <div class="screen"></div>
        <div class="screen"></div>
        <div class="screen"></div>
        <div class="screen"></div>
        <div class="screen"></div>
    </div>

    <div class="title">
        <h1>Fundamentals of</h1>
        <h2>Web Development</h2>
    </div>

    <div class="authors">
        Randy Connolly &nbsp;|&nbsp; Ricardo Hoar
    </div>

    <div class="publisher">
        PEARSON
    </div>

</div>

</body>
</html>
```
## OUTPUT:
<img width="1910" height="1018" alt="Screenshot 2025-12-23 102238" src="https://github.com/user-attachments/assets/274b2f6d-663e-4fa3-8e1e-2b09c0a4a11b" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
