# Ex.06 Book Front Cover Page Design
# Date:
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
book design.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <link rel="stylesheet" href="bd styles.css">
</head>
<body>
    <div class="book-cover">
            <img src="C:\Users\admin\Downloads\book cover background.jpg" alt="bookcover" class="book-cover">
        <div class="content">
            <h1 class="title">The Journey Beyond</h1>
            <h2 class="subtitle">A Tale of Mystery and Adventure</h2>
        <div class="author-section">
                <img src="C:\Users\admin\Downloads\jane doe.jpg" alt="Author" class="author-image">
                <p class="author">by Jane Doe</p>
        </div>
        </div>
    </div>
</body>
</html>

bd styles.css
body {
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background-color: #f4f4f4;
    font-family: 'Arial', sans-serif;
}

.book-cover {
    position: relative;
    width: 500px;
    height: 750px;
    background-image: url("C:\Users\admin\Downloads\book cover background.jpg");
    background-size: cover;
    background-position: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    overflow: hidden;
}

.content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: white;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
    z-index: 2;
}

.title {
    font-size: 3em;
    margin: 0;
    text-decoration: black;
}

.subtitle {
    font-size: 1.2em;
    margin: 10px 0;
}

.author-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.author-image {
    width: 100px;
    height: 100px;
    border-radius: 100%;
    border: 1px solid white;
    margin-bottom: 10px;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
}

.author {
    font-size: 1em;
    font-style: italic;
}
```
# OUTPUT:

![438305145-55b2319a-0fea-4d31-985d-716af271a8ee](https://github.com/user-attachments/assets/4101d432-c049-4384-936b-43c8e88a5573)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
