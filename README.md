# Ex.06 Book Front Cover Page Design
## Date:10.12.24

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

<DOCTYPE! html>
    <html>

    <head>
        <title>
            BOOK COVER
        </title>
        <link
        href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
        <style>
            p.ti {
                font-family: "Dancing Script", cursive;
                font-size: 38px;
                color: black;
                margin-left: 38%;
                top: 20%;
                width: 10%;
                position: absolute;
            }

            oth {
                font-family: Impact, sans-serif;
                font-size: 100;
                color: whitesmoke;
                text-shadow: 15px 10px rgba(0, 0, 0, 0.785);
                margin-left: 37%;
                width: 10%;
                top: 7%;
                position: absolute;
            }

            subh {
                font-family: 'Courier New', Courier, monospace;
                color: white;
                font-size: 30;
            }

            .author{
                font-family: 'Courier New', Courier, monospace;
                color: rgb(22, 66, 64);
                font-size: 40;
                position: absolute;
                margin-left: 45%;
                margin-top: 400;
                bottom: 10%;
                
            }

            su {
                font-family: 'Snell Roundhand';
                font-style: italic;
                color: whitesmoke;
                text-shadow: 5px 4px black;
                font-size: 42;
                position: absolute;
                bottom: 17%;
                margin-left: 35%;

            }

            img {
                margin-left: 35%;
                position: relative;
            }

            hr {
                bottom: 13%;
                position: absolute;
                color: white;
                width: 20%;
                left: 43%;
            }

            
        </style>
    </head>

    <body>
        <br>
        <hr color="white">
        <img src="fwad.jpg">
        <p class="ti"> <em>The shattering of a heart when being broken is the loudest quiet ever.</em></p><br>
        <oth>WAITING FOREVER</oth><br>
        <su>Every memory reminds me of you</su><br><br><br><br><br>
        <hr align="right"><br><br>
        <div class="author">S MANO SUSHSMITHA</div>
    </body>
    </html>


        



```

## OUTPUT:


![alt text](<Screenshot 2024-12-10 131216.png>)

   


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
