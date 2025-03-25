<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RaviBharathi - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .header {
            background-color: #b2ff00;
            color: white;
            text-align: center;
            padding: 40px 0;
            font-size: 24px;
            font-weight: bold;
        }
        .header p {
            font-size: 16px;
            margin: 5px 0;
        }
        .navbar {
            display: flex;
            justify-content: center;
            background-color: red;
            padding: 10px 0;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 0 15px;
            font-size: 18px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px gray;
        }
        h2 {
            border-bottom: 2px solid red;
            padding-bottom: 5px;
        }
        .skills ul {
            list-style-type: none;
            padding: 0;
        }
        .skills li {
            background: #ddd;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .projects a {
            display: block;
            margin: 5px 0;
            color: blue;
            text-decoration: none;
        }
        .resume {
            text-align: center;
            margin-top: 20px;
        }
        .resume button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background: black;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

  <div class="header">
        <h1>RaviBharathi</h1>
        <p>BCA Student</p>
    </div>

  <div class="navbar">
        <a href="#">About</a>
        <a href="#">Education</a>
        <a href="#">Skills</a>
        <a href="#">Projects</a>
        <a href="#">Resume</a>
    </div>

  <div class="container">
        <h2>About Me</h2>
        <p>I am RaviBharathi, currently pursuing a Bachelor of Computer Applications (BCA) at Prince Shri Venkateswara Arts and Science College.</p>
    </div>

  <div class="container">
        <h2>Education</h2>
        <p>BCA - Prince Shri Venkateswara Arts and Science College</p>
    </div>

  <div class="container skills">
        <h2>Skills</h2>
        <ul>
            <li>Java</li>
            <li>C++</li>
            <li>Python</li>
            <li>Data Structures</li>
        </ul>
    </div>

  <div class="container projects">
        <h2>Projects</h2>
        <a href="#">Calculator Program (Java)</a>
    </div>

   <div class="container resume">
        <h2>Resume</h2>
        <button onclick="window.location.href='your-resume-link.pdf'">Download CV</button>
    </div>

  <div class="footer">
        © 2025 RaviBharathi
    </div>

</body>
</html>
