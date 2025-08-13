# Ex02 Commercial Website
## Date: 11.08.25

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextGen Solutions</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef1f7;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #007bff, #00c6ff);
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 10px;
        }
        nav a {
            color: #007bff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #0056b3;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: url('https://source.unsplash.com/1600x900/?technology,business') no-repeat center;
            background-size: cover;
            color: white;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .btn {
            background: #ff6600;
            color: white;
            padding: 12px 20px;
            border: none;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        .btn:hover {
            background: #cc5500;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 40px;
            text-align: center;
        }
        .service-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact {
            text-align: center;
            padding: 40px;
            background: #007bff;
            color: white;
        }
        .contact form {
            max-width: 400px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }
        .contact input, .contact textarea {
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        .contact button {
            background: #ffcc00;
            color: #333;
            padding: 12px;
            border: none;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        .contact button:hover {
            background: #ff9900;
        }
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 15px;
        }
    </style>
</head>
<body>
    <header>NextGen Solutions - Empowering Innovation</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section class="hero" id="home">
        <h1>Revolutionizing Business with Technology</h1>
        <p>We provide cutting-edge solutions to take your business to the next level.</p>
        <button class="btn" onclick="alert('Discover More!')">Get Started</button>
    </section>
    
    <section class="services" id="services">
        <div class="service-card">
            <h3>AI Solutions</h3>
            <p>Leverage artificial intelligence to automate and optimize your business operations.</p>
        </div>
        <div class="service-card">
            <h3>Cloud Computing</h3>
            <p>Seamless cloud integration to enhance scalability and efficiency.</p>
        </div>
        <div class="service-card">
            <h3>Cybersecurity</h3>
            <p>Advanced security solutions to protect your digital assets.</p>
        </div>
    </section>
    
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 NextGen Solutions. All Rights Reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
