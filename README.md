# Ex01 Portfolio
## Date:14/03/25
## NAME: HARSETHA J(212223220032)
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">MyPortfolio</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Me</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h1>My Portfolio</h1>
            <p>Creating web pages.</p>
            <div class="hero-buttons">
                <a href="#" class="btn">Explore Projects</a>
                <a href="#" class="btn secondary">Play Video</a>
            </div>
        </div>
        <div class="hero-image">
            <img src="c:\Users\admin\Downloads\IMAGE.jpg" alt="Portfolio Image">
        </div>
    </section>

</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Section</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #e8eaec;
            margin: 0;
            padding: 0;
        }
        .portfolio-container {
            max-width: 1100px;
            margin: auto;
            padding: 50px 20px;
        }
        h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .portfolio-grid {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .portfolio-item {
            background-color: #d6dde5;
            border-radius: 15px;
            width: 300px;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(25, 200, 177, 0.1);
        }
        .portfolio-item img {
            width: 60px;
            height: 60px;
            margin-bottom: 10px;
        }
        .portfolio-item .number {
            background-color: #5aace7;
            color: #2f0e8d;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin: 10px auto;
        }
        .portfolio-item h3 {
            margin: 10px 0;
        }
        .portfolio-item p {
            color: #5e17af;
        }
    </style>
</head>
<body>

    <div class="portfolio-container">
        <h2>Our Portfolio</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="c:\Users\admin\Downloads\BASIC CALCULATOR.jpg" alt="Project 1">
                <div class="number">1</div>
                <h3>BASIC CALCULATER</h3>
                <p>basic calculator project involves creating a program that can perform fundamental arithmetic operations like addition, subtraction, multiplication, and division, typically with user input and output displayed on a screen.</p>
            </div>
            <div class="portfolio-item">
                <img src="c:\Users\admin\Downloads\ONE PAGE LAYOUT.jpg" alt="Project 2">
                <div class="number">2</div>
                <h3>ONE-PAGE LAYOUT</h3>
                <p>a single-page document that concisely summarizes a project, including its purpose, key objectives, benefits, and a call to action, often used for internal or external communication.</p>
            </div>
                    front-end
                    backend
                    CSS
                    html
                    python
                    sql
                    c program
                    c++program</p>
            </div>
        </div>
    </div>

</body>
</html>








<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intellectual Property Rights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #4178bc; /* Light blue background */
            margin: 0;
            padding: 20px;
        }
        .container {
            background: rgb(73, 132, 147);
            padding: 30px;
            border-radius: 10px;
            max-width: 600px;
            margin: auto;
            box-shadow: 0px 4px 10px rgba(138, 9, 198, 0.2);
        }
        h1 {
            font-size: 24px;
        }
        h2 {
            font-size: 22px;
            text-decoration: underline;
        }
        img {
            width: 120px;
            margin: 20px 0;
        }
        p {
            font-size: 18px;
            margin: 5px 0;
        }
    </style>
</head>
<body>
</body>
</html>
```

## OUTPUT
![Screenshot (184)](https://github.com/user-attachments/assets/db0e97f5-0a7e-4bf5-8bda-f389d33f4f5f)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
