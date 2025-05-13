# Ex.05 Design of Interactive Image Gallery
## Date: 13/05/2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <title>
        Interactive Image Gallery
    </title>
    <style>
        body 
        {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("back.avif");
        }

        h6 
        {
            margin-top: 20px;
            color: red;
            font-size: xx-large;
            font-style: bold;
        }

        .Gallery
         {
            display: flex;
            gap: 15px;
            max-width: 800px;
            margin-top: 20px;
            justify-content: center;
        }
    </style>

    <body>
        <h6> The Kollywood (Tamil film industry)</h6>
        <div class="Gallery">

            <img src="c:\Users\LOKESH\Downloads\D4.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="c:\Users\LOKESH\Downloads\D2.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="c:\Users\LOKESH\Downloads\D6.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="c:\Users\LOKESH\Downloads\D5.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="c:\Users\LOKESH\Downloads\D3.jpg" width="500" height="500" onclick="openImage(this.src)">
            
        </div>

        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2025-05-13 103013](https://github.com/user-attachments/assets/e7d0b583-fb36-4ecd-9e6d-a45d58b481c9)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
