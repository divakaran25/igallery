# Ex.08 Design of Interactive Image Gallery
## Date:03-01-2025

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
   <style class="css">
    body{
        background-color: blue;
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    header {
        background-color: #333;
        color: rgb(249, 1, 18);
        padding: 10px 0;
    }
    nav ul {
        list-style: none;
        padding: 0;
        display: flex;
        justify-content: center;
    }
    nav ul li {
        margin: 0 15px;
    }
     nav ul li a {
        color: rgb(12, 247, 134);
        text-decoration: none;
    }
    .gallery-container {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 10px;
        padding: 20px;
    }
    .gallery-container img {
        width: 100%;
        height: auto;
        border-radius: 8px;
    }
    footer {
        text-align: center;
        padding: 10px 0;
        background-color: #f50606;
        margin-top: 20px;
    }
</style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main id="gallery">
        <div class="gallery-container">
            <img src="c:\Users\admin\Pictures\Image 1.jpg" alt="Image 1">
            <img src="c:\Users\admin\Pictures\Image 2.jpg" alt="Image 2">
            <img src="c:\Users\admin\Pictures\Image 3.jpeg" alt="Image 3">
            <img src="c:\Users\admin\Pictures\Image 4.jpeg" alt="Image 4">
            <img src="c:\Users\admin\Pictures\Image 5.jpeg" alt="Image 5">
            <img src="c:\Users\admin\Pictures\Image 6.jpg" alt="Image 6">
            <img src="c:\Users\admin\Pictures\Image 7.jpg" alt="Image 7">
            <img src="c:\Users\admin\Pictures\Image 8.jpeg" alt="Image 8">
        </div>
    </main>
    <footer>
        <p>&copy; 2024 MY Website</p>
    </footer>
</body>
</html>

'''
## OUTPUT:
![alt text](<Screenshot 2025-01-03 221929.png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
