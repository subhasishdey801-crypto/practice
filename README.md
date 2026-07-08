<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f9ff;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #2e8b57;
            color: white;
            padding: 20px;
        }
        nav {
            margin: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #2e8b57;
            font-weight: bold;
        }
        section {
            padding: 40px;
        }
        footer {
            background-color: #2e8b57;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .button {
            background-color: #2e8b57;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #1c5d3b;
        }
    </style>
</head>
<body>
    <header>
        <h1>🚀 Welcome to My Website</h1>
        <p>A simple homepage created by Subho</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>This is the main section of your website. You can add text, images, or links here.</p>
        <button class="button">Click Me</button>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>Write something about yourself, your project, or your business here.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: yourname@example.com</p>
        <p>Phone: +91-XXXXXXXXXX</p>
    </section>

    <footer>
        <p>© 2026 Subho | All Rights Reserved</p>
    </footer>
</body>
</html>

