# Ex.05 Book Front Cover Page Design
## Date: 08-02-2026

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
    <title>Web Dev Book Cover</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&family=Inter:wght@400;700;900&display=swap');

        body {
            font-family: 'Inter', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #e8eaf6;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }

        .book-cover {
            width: 320px;
            height: 480px;
            position: relative;
            box-shadow: 10px 10px 40px rgba(0, 0, 0, 0.4);
            border-radius: 8px;
            overflow: hidden;
            background-color: #1e3a8a;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            text-align: left;
            padding: 30px;
            background-image: url('webpro6/bookapp/static/Gemini_Generated_Image_6o428y6o428y6o42.png'); /* REPLACE with your image */
            background-size: cover;
            background-position: center;
        }

        .book-cover::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(30, 58, 138, 0.85);
            z-index: 1;
            border-radius: 8px;
        }

        .book-content {
            position: relative;
            z-index: 2;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .subtitle {
            font-family: 'Roboto Mono', monospace;
            font-size: 1.1em;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: #a5b4fc;
            margin-bottom: 10px;
        }

        .title-block h1 {
            font-family: 'Inter', sans-serif;
            font-size: 2.8em;
            font-weight: 900;
            line-height: 1.1;
            margin: 0 0 5px 0;
            text-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        
        .title-block h1 span {
            color: #fcd34d;
        }

        .author {
            font-family: 'Inter', sans-serif;
            font-size: 1.2em;
            font-weight: 700;
            align-self: flex-end;
            text-align: right;
            padding-bottom: 10px;
        }

        .edition {
            font-family: 'Roboto Mono', monospace;
            font-size: 0.9em;
            color: #d1d5db;
        }

    </style>
</head>
<body>

    <div class="book-cover">
        <div class="book-content">
            <div class="top-section">
                <div class="edition">Second Edition</div>
            </div>
            
            <div class="title-block">
                <div class="subtitle">The Complete Guide</div>
                <h1>Web App <span>Fundamentals</span></h1>
            </div>

            <div class="author">
                By Rohith kumar
            </div>
        </div>
    </div>

</body>
</html>

```

## OUTPUT:
<img width="1192" height="750" alt="image" src="https://github.com/user-attachments/assets/b419c27b-1e00-4e02-83bd-f9ba411d9447" />




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
