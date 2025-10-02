# Ex.06 Book Front Cover Page Design
# Date:1-10-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover</title>
<style>
body {
  display: flex; justify-content: center; align-items: center;
  height: 100vh; margin: 0;background: white; font-family: 'Georgia', serif;
}
.cover {
  width: 280px; height: 420px;
  background:linear-gradient(45deg, #ff0080 0%, #ff8c00 50%, #40e0d0 100%) ; white;
  display: flex; flex-direction: column; justify-content: center; align-items: center;
  text-align: center; padding: 20px; border-radius: 17px;
  box-shadow: 0 8px 15px rgba(176, 13, 157, 0.3);
  position: relative;   
}
.cover h1 { font-size: 32px; margin: 0; }
.cover h2 { font-size: 18px; margin: 10px 0; font-weight: normal; }
.cover h3 { font-size: 16px; margin: 8px 0; font-style: italic; }
.cover .author { margin-top: 30px; font-size: 16px; font-family: 'Times New Roman', serif; }

.cover .photo {
  position: absolute;
  bottom: 12px; right: 12px;
  display: flex; flex-direction: column; align-items: center;
}
.cover .photo img {
  width: 55px; height: 55px;
  border-radius: 50%;
  border: 2px solid white;
  box-shadow: 0 4px 8px rgba(0,0,0,0.4);
}
.cover .photo span {
  margin-top: 5px; font-size: 13px; font-style: italic;
}
</style>
</head>
<body>
<div class="cover">
  <h1>Fundamentals of Web Application Development</h1>
  <h2>Learning HTML & CSS</h2>
  <h3>Step by Step Guide</h3>
  
  <div class="photo">
    <img src="myphoto.jpeg" alt="Author Photo">
    <span>Shankar SB</span>
  </div>
</div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-10-02 133330.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
