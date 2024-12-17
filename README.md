# Ex.06 Book Front Cover Page Design
## Date:17.12.24

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
    <title>Web Application And Development</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #9acd2b;
        }

        .bookpage {
            width: 350px;
            height: 650px;
            margin: 50px auto;
            padding: 20px;
            background: linear-gradient(135deg, #00f7ff, #e2d02d);
            border: 1px solid #ccc;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
        }


        .hrstyle {
            width: 80px;
            margin: 20px auto;
            border: none;
            border-top: 3px solid #555;
        }

        .booktitle {
            text-align: center;
            color: #2e4053;
            font-family: 'Courier New', Courier, monospace;
            font-size: 1.5em;
            font-weight:bold;   
            margin: 20px 0;
        }

        .subtitle {
            text-align: center;
            color: #555;
            font-size: 1em;
            font-style: italic;
            margin-bottom: 20px;
        }

        .mypic {
            text-align: center;
            margin: 20px 0;
        }

        .mypic img {
            width: 90px;
            height: 120px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .author {
            text-align: center;
            color: #1b2631;
            font-size: 1em;
            font-weight: bold;
            margin-top: 20px;
        }

        .pub {
            text-align: center;
            color: #424949;
            font-size: 0.9em;
            margin-top: 10px;
        }

        .ed {
            text-align: center;
            color: #283747;
            font-size: 1em;
            font-weight: bold;
            margin-top: 15px;
        }

        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
            font-size: 0.8em;
            color: #888;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <div class="hrstyle"></div>
        <div class="booktitle">
            Fundamentals of Web Application<br>& Development
        </div>
        <div class="subtitle">
            with html,javascript and css insights
        </div>
        <div class="mypic">
            <img src="/static/photo.jpg" alt="Author">
        </div>
        <div class="author">Vishnurathan</div>
        <div class="pub">TechVision Press</div>
        <div class="ed">2nd Edition</div>
        <div class="footer">© 2024 | All Rights Reserved</div>
    </div>
</body>

</html>
```

## OUTPUT:

![Screenshot 2024-12-17 161829](https://github.com/user-attachments/assets/ce1a4f3a-3415-447b-8430-9de74923dafc)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
