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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover - PRIYADHARSHINI S N </title>
    <style>
        /* CSS stays inside the style tag */
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: white;
            font-family: 'serif', 'Times New Roman', Times, serif;
        }

        .book-cover {
            width: 450px;
            height: 650px;

            /* Vibrant modern gradient */
            background: linear-gradient(
                180deg,
                #ff00bf 0%,     /* Neon coral */
                #3c73ff 40%,    /* Hot pink */
                #6f1596 75%,    /* Purple */
                #942bc5 100%    /* Electric blue */
            );

            padding: 50px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            color: #ffffff;
            box-shadow: 0 25px 50px rgba(119, 69, 172, 0.579);
            position: relative;
        }

        .brand {
            font-size: 18px;
            font-weight: bold;
            margin: 0;
        }

        .main-title h1 {
            font-size: 38px;
            line-height: 1.1;
            margin-top: 50px;
            margin-bottom: 30px;
            font-weight: 800;
            text-transform: uppercase;
            text-shadow: 0 4px 10px rgba(102, 29, 170, 0.35);
        }

        .subtitle {
            font-size: 18px;
            line-height: 1.4;
            margin-bottom: 20px;
        }

        .footer {
            margin-top: auto;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            border-top: 1px solid rgba(54, 35, 201, 0.3);
            padding-top: 20px;
        }

        .special-edition {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 8px;
            text-transform: uppercase;
        }

        .author-name {
            font-size: 20px;
            font-weight: bold;
            margin: 0;
            text-transform: uppercase;
        }

        .author-photo {
            width: 100px;
            height: 120px;
            border: 3px solid #ffffff;
            background-color: #ffffff;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(94, 30, 206, 0.2);
        }

        .author-photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="header">
            <p class="brand">SEC</p>
        </div>
        
        <div class="main-title">
            <h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
        </div>

        <div class="subtitle">
            <p>A JOURNEY OF HOPE, GROWTH, AND PURPOSE<br>
Updated for 2025</p>

        </div>

        <div class="footer">
            <div class="footer-text">
                <p class="special-edition">SPECIAL EDITION</p>
                <p class="author-name">PRIYADHARSHINI S N  </p>
            </div>
            
        </div>
    </div>

</body>
</html>

```
## OUTPUT:
<img width="1919" height="1077" alt="Screenshot 2025-12-27 130641" src="https://github.com/user-attachments/assets/e9159f29-eafc-48c4-9a16-8c07ef004e4a" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
