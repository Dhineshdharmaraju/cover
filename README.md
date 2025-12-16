# Ex.05 Book Cover Page Design
## Date:
14/12/2025
## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html

<html>

<head>
    <title>AI Engineering</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="book-cover">
        <div class="header">
            
        </div>
        <div class="main-content">
            <h1>AI Engineering</h1>
            <p class="description">"The book starts with an overview of AI engineering, explaining how it differs from traditional ML engineering and discussing the new AI stack. The more AI is used, the more opportunities there are for catastrophic failures, and therefore, the more important evaluation becomes. This book discusses different approaches to evaluating open-ended models, including the rapidly growing AI-as-a-judge approach."</p>
            <div class="quote-box">
                <p>AI Engineering builds upon and is complementary to Designing Machine Learning Systems</p>
            </div>
            <div class="author-section">
                <img src="12345.png">
                <div class="author-info">
                    <p class="author-name">DHINESH D</p>
                    <p class="author-bio">Dhinesh works to accelerate data analytics on GPUs at Voltron Data. Previously, she was with Snorkel AI and NVIDIA, founded an AI infrastructure startup, and taught Machine Learning Systems Design at Stanford. He's the author of the book Designing Machine Learning Systems, an Amazon bestseller in AI</p>
                </div>
            </div>
        </div>
        <div class="footer">
            <p>SEC Publisher</p>
            <p>Printed in India</p>
            <p class="price">Price: &#8377;999 only -/-</p>
        </div>
    </div>
</body>
</html>

style.css

body {
    background-color: #6a0dad69;
    display: flex;
    justify-content: center;
    align-items: center;
    
    margin: 0;
    
    color: white;
}

.book-cover {
    width: 400px;
    height: 650px;
    background-color: #6a0dad; 
    padding: 20px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.25);
    border-radius: 5px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
    
}

.header p {
    font-style: bold;
    font-size: 14px;
}

.main-content {
    flex-grow: 1;
    display: flex;
    flex-direction: column;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: 28px;
    margin-bottom: 20px;
    text-align: center;
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
    padding-bottom: 10px;
}

.description {
    font-size: 12px;
    line-height: 1.4;
    margin-bottom: 15px;
    text-align: justify;
}

.quote-box {
    background-color: rgba(255, 255, 255, 0.1);
    padding: 10px;
    border-left: 3px solid white;
    margin-bottom: 20px;
    font-style: italic;
    font-size: 11px;
}

.author-section {
    background-color: #4b0082;
    padding: 10px;
    border-radius: 5px;
    display: flex;
}

.author-name {
    font-weight: bold;
    margin-bottom: 5px;
}
.author-section img {
    width: 120px;
    height: auto;
    max-width: 100%;
    object-fit: cover;
    display: flex;
    border-radius: 4px;
}
.author-bio {
    font-size: 10px;
    line-height: 1.3;
    display: flex;
    flex-direction: column;
}

.footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 12px;
    margin-top: 15px;
    border-top: 1px solid rgba(255, 255, 255, 0.3);
    padding-top: 10px;
}

.price {
    font-weight: bold;
    color: #ffeb3b;
}
.author-info{
    margin-left: 7;
}




```

## OUTPUT:
![alt text](<dhinesh/coverapp/static/Screenshot (37).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
