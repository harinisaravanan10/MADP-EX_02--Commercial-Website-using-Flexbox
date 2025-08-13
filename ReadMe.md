# Ex02 Commercial Website
## Date:11.08.2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TastyBites - Food Paradise</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">Tasty<span>Bites</span></div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Menu</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Delicious Meals, <span>Every Day!</span></h1>
        <p>Freshly prepared dishes with love & flavor.</p>
        <a href="#" class="btn">Explore Menu</a>
    </section>

    <section class="menu-section">
        <h2>Our Special Menu</h2>
        <div class="menu-items">
            <div class="item">
                <img src="pizza.jpeg" alt="Pizza">
                <h3>Cheesy Pizza</h3>
                <p>Loaded with cheese and fresh toppings.</p>
            </div>
            <div class="item">
                <img src="burger.jpeg" alt="Burger">
                <h3>Juicy Burger</h3>
                <p>Perfectly grilled with a secret sauce.</p>
            </div>
            <div class="item">
                <img src="pasta.jpeg" alt="Pasta">
                <h3>Italian Pasta</h3>
                <p>Rich, creamy, and utterly delicious.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 TastyBites. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #fff;
    color: #333;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background: linear-gradient(90deg, #ff416c, #ff4b2b);
    color: white;
}

.logo {
    font-size: 28px;
    font-weight: bold;
}
.logo span {
    color: yellow;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}
nav a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(135deg, #ff9a9e, #fad0c4);
    color: white;
}
.hero h1 {
    font-size: 48px;
    margin-bottom: 15px;
}
.hero h1 span {
    color: yellow;
}
.hero p {
    font-size: 20px;
    margin-bottom: 25px;
}
.btn {
    padding: 12px 25px;
    background: yellow;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 8px;
}
.btn:hover {
    background: orange;
}

/* Menu Section */
.menu-section {
    padding: 50px 20px;
    text-align: center;
}
.menu-section h2 {
    font-size: 36px;
    color: #ff4b2b;
    margin-bottom: 40px;
}
.menu-items {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}
.item {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    overflow: hidden;
    width: 300px;
    transition: transform 0.3s;
}
.item:hover {
    transform: scale(1.05);
}
.item img {
    width: 100%;
    height: auto;
}
.item h3 {
    color: #ff4b2b;
    margin: 15px 0 10px;
}
.item p {
    padding: 0 15px 15px;
    font-size: 16px;
    color: #555;
}

/* Footer */
footer {
    background: linear-gradient(90deg, #ff416c, #ff4b2b);
    color: white;
    text-align: center;
    padding: 15px 0;
}
```
## OUTPUT

<img width="1907" height="1013" alt="image" src="https://github.com/user-attachments/assets/51ad221b-6d5e-49db-8e88-08ac1f68bdc5" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
