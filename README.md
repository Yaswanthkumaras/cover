# Ex.06 Book Front Cover Page Design
## Date:29.04.2025


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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Book Cover - The Mystery of Tomorrow</title>
  <style>
    body {
      background: #f0f0f0;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 300px;
      height: 450px;
      background-image: url('https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80');
      background-size: cover;
      background-position: center;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
      padding: 30px 20px;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.5);
      z-index: 1;
      border-radius: 12px;
    }

    .content {
      position: relative;
      z-index: 2;
    }

    .book-title {
      font-size: 36px;
      font-weight: bold;
      margin-top: 20px;
      letter-spacing: 1px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
    }

    .book-author {
      font-size: 18px;
      margin-top: 15px;
      font-style: italic;
    }

    .book-tagline {
      font-size: 16px;
      margin-bottom: 20px;
      color: #e0e0ff;
      font-style: italic;
    }

    .decoration {
      position: absolute;
      top: 20px;
      right: 20px;
      font-size: 24px;
      opacity: 0.4;
      z-index: 2;
    }

    .author-photo {
      position: absolute;
      bottom: 10px;
      right: 10px;
      width: 130px; /* Bigger width */
      height: 130px; /* Bigger height */
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
      z-index: 3;
    }
  </style>
</head>
<body>

<div class="book-cover">
  <div class="overlay"></div>
  <div class="decoration">★</div>
  <div class="content">
    <div class="book-title">The Mystery of Tomorrow</div>
    <div class="book-author">Yaswanth Kumar</div>
    <div class="book-tagline">"A Journey Beyond Time"</div>
  </div>
  <img src="C:\Users\admin\Pictures\WhatsApp Image 2025-04-29 at 11.28.51_630c8cfc.jpg" alt="Author Photo" class="author-photo">
</div>

</body>
</html>

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/2e2fcd2b-b0d4-4bac-aa9a-ba1c50cc338f)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
