# Ex09 Event Registration Web Application
## Date:07.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Singing Contest</title>
<style>
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    color: white;
    text-align: center;
  }

  /* Common section styling */
  .section {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-size: cover;
    background-position: center;
    padding: 20px;
  }

  /* ---------- Section 1 ---------- */
  .section1 {
    background: linear-gradient(to bottom, #800060, #c2185b);
  }
  .section1 h1 {
    font-size: 2em;
    margin-bottom: 10px;
    font-weight: 700;
  }
  .section1 .details {
    background: rgba(255, 255, 255, 0.1);
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 20px;
  }
  .section1 .register {
    background: gold;
    color: black;
    padding: 10px 25px;
    border-radius: 30px;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
  }
  .section1 .register:hover {
    background: #ffcc00;
  }

  /* ---------- Section 2 ---------- */
  .section2 {
    background: radial-gradient(circle, #330033, #660066, #990099);
  }
  .section2 h2 {
    font-size: 2em;
    color: cyan;
    margin-bottom: 20px;
  }
  .section2 ul {
    list-style: none;
    padding: 0;
  }
  .section2 li {
    font-size: 1.3em;
    margin: 8px 0;
  }

  /* ---------- Section 3 ---------- */
  .section3 {
    background: linear-gradient(to bottom right, #111, #444);
  }
  .section3 h2 {
    font-size: 1.8em;
    margin-bottom: 25px;
    text-transform: uppercase;
  }
  .form-container {
    width: 80%;
    max-width: 400px;
  }
  .form-container input {
    width: 100%;
    padding: 12px;
    margin: 8px 0;
    border: none;
    border-radius: 5px;
    font-size: 1em;
  }

  /* ---------- Section 4 ---------- */
  .section4 {
    background: linear-gradient(to bottom right, #0047ab, #001f4d);
  }
  .section4 h2 {
    font-size: 1.5em;
    margin-bottom: 20px;
  }
  .section4 p {
    font-size: 1.2em;
    max-width: 400px;
    margin: auto;
  }
</style>
</head>
<body>

<!-- Section 1 -->
<section class="section section1">
  <h1>SINGING CONTEST</h1>
  <div class="details">
    <p><strong>Date:</strong> 07.10.2025</p>
    <p><strong>Time:</strong> 4:00 PM</p>
    <p><strong>Venue:</strong> Saveetha Engineering College</p>
  </div>
  <div class="register">REGISTER NOW</div>
</section>

<!-- Section 2 -->
<section class="section section2">
  <h2>EVENTS</h2>
  <ul>
    <li>Solo Singing</li>
    <li>Group Singing</li>
    <li>Hip-Hop</li>
    <li>Pop</li>
    <li>Rap</li>
    <li>Classical</li>
  </ul>
</section>

<!-- Section 3 -->
<section class="section section3">
  <h2>APPLICATION FORM</h2>
  <div class="form-container">
    <input type="text" placeholder="NAME">
    <input type="email" placeholder="EMAIL ID">
    <input type="text" placeholder="CONTACT NUMBER">
  </div>
</section>

<!-- Section 4 -->
<section class="section section4">
  <h2>“Let your voice be heard”</h2>
  <p>We are eagerly waiting for your participation in singing events.</p>
  <h3 style="margin-top: 30px; color: yellow;">THANK YOU</h3>
</section>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-10-06 203354.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
