## Ex02 Commercial Website

## Date:29-04-2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

STEP 5
Include social media links at the footer with copyright information.

STEP 6
Define global styles for fonts, colors, and layout.

STEP 7
Style the header, navigation bar, and sections.

STEP 8
Use Flexbox for layout design.

STEP 9
Add hover effects and transitions for interactivity.

STEP 10
Add Images and Media.

STEP 11
Use optimized images for a professional look.

STEP 12
Open the HTML file in a browser to check layout and functionality.

STEP 13
Fix styling issues and refine content placement.

STEP 14
Deploy the website.

STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LEARNOVA</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff0f5;
      color: #333;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ff6f61;
      padding: 20px 40px;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    nav h1 {
      color: #fff;
      font-size: 28px;
      font-weight: 800;
    }

    nav ul {
      display: flex;
      list-style: none;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      transition: opacity 0.3s ease;
    }

    nav ul li a:hover {
      opacity: 0.8;
    }

    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 70vh;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-size: 50px;
      font-weight: bolder;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    #tt {
      text-align: center;
      font-size: 32px;
      color: #6a1b9a;
      margin-bottom: 30px;
    }

    .OC {
      padding: 60px 20px;
      background-color: #f0fff0;
      border-top: 6px solid #00b894;
    }

    .course {
      display: flex;
      justify-content: center;
      align-items: stretch;
      flex-wrap: wrap;
      gap: 30px;
    }

    .course-card {
      background-color: #ffe0e9;
      border-radius: 20px;
      padding: 20px;
      max-width: 220px;
      text-align: center;
      border: 2px solid #ff6f61;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, background-color 0.3s ease;
    }

    .course-card:hover {
      background-color: #ffccd5;
      transform: translateY(-5px);
    }

    .course-card h2 {
      color: #c2185b;
      margin-bottom: 10px;
    }

    .about {
      text-align: center;
      padding: 60px 20px;
      background-color: #e1f5fe;
      border-top: 6px solid #ab47bc;
      border-radius: 0 0 15px 15px;
      box-shadow: inset 0 4px 8px rgba(0, 0, 0, 0.05);
    }

    .about h1 {
      font-size: 32px;
      color: #7b1fa2;
      margin-bottom: 20px;
    }

    .about p {
      max-width: 700px;
      margin: 0 auto;
      font-size: 18px;
      line-height: 1.6;
      color: #444;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      background-color: #ffdde1;
      border-top: 6px solid #ec407a;
    }

    footer h2 {
      color: #ad1457;
      margin-bottom: 10px;
    }

    footer p {
      color: #444;
    }
  </style>
</head>
<body>

  <nav>
    <h1>LEARNOVA</h1>
    <ul>
      <li><a href="#hero">Home</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#cc">Courses</a></li>
      <li><a href="#foot">Contact</a></li>
    </ul>
  </nav>

  <section class="hero" id="hero">
    <p>BECAUSE YOUTUBE UNIVERSITY WASNT ENOUGH.WE GOTCHU &nbsp;</p>
  </section>

  <section class="OC" id="cc">
    <h1 id="tt">OUR COURSES</h1>
    <div class="course">
      <div class="course-card">
        <h2>MODERN THINKING</h2>
        <p>Explore the fundamentals with expert guidance.</p>
      </div>
      <div class="course-card">
        <h2>PROBLEM SOLVING</h2>
        <p>Dive deeper into advanced concepts and skills of Problem Solving.</p>
      </div>
      <div class="course-card">
        <h2>How To become HEISENBERG</h2>
        <p>You cant be more perfet in Chemistry.</p>
      </div>
    </div>
  </section>

  <section class="about" id="about">
    <h1>About Us</h1>
    <p>
        Welcome to LEARNOVA where learning meets laughter, and brains grow without the boring bits.

        We're a crew of curious nerds, caffeine-fueled creators, and professional overthinkers on a mission to make learning actually fun. No droning lectures. No textbook naps. Just practical, punchy, and occasionally ridiculous courses designed to boost your skills and confuse your enemies (or impress your boss same thing, right?).
        
        Whether you want to code your first app, write the next bestseller, or finally understand what the heck blockchain is, we've got your back (and probably a pun or two).
        
        Learn weird. Learn smart. Learn with us.
    </p>
  </section>

  <footer id="foot">
    <h2>Contact Us</h2>
    <p>Email: learnova@support</p>
  </footer>

</body>
</html>
```
## OUTPUT

![Screenshot 2025-04-30 105837](https://github.com/user-attachments/assets/0de2de17-951f-49c1-ad1d-22959e28690f)

![Screenshot 2025-04-30 105851](https://github.com/user-attachments/assets/dda5d422-3e53-4b23-af9e-277411bf8a1f)

![Screenshot 2025-04-30 105905](https://github.com/user-attachments/assets/e42027a3-82d7-4f3f-861f-853f160e7f17)
