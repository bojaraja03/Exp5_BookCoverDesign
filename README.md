# Ex.05 Book Front Cover Page Design
## Date: 24-12-2025

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
      margin: 0;
      padding: 0;
      background-color: #ffffff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(15, 25, 45);
      border: 2px solid #333;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #ffffff;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
      color: bisque;
    }

     .image {
      flex: 1;
      margin: 30px 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
    .image img {
      max-width: 75%;
      height: auto;
      object-fit: contain;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #6c96b6;
      margin-top: 20px;
    }

    .quote{
      text-align: center;
      font-size: 18px;
      margin-top: 20px;
      color: aquamarine;
    }

    .line {
      height: 2px;
      background: #fdfcfc;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">HOUSEMAID</div>
      <div class="subtitle">"He has no idea this is just the beginning.”
      </div>
    </div>
    <div class="image">
        <img src="HOUSEMAID.jpg" length="20%" width="75%">
    </div>
    <div class="quote">
      “Those are the four most beautiful words in the English language. You can go now.”
    </div>
    <div class="author">BY GOPIKA</div>
  </div>
</body>
</html>
```

## OUTPUT:

<img width="1272" height="775" alt="Screenshot 2025-12-24 082740" src="https://github.com/user-attachments/assets/07676da8-11db-4db5-80ab-73b33b287b00" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
