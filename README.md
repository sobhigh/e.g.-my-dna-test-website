<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DNA Testing for Iranians</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background: #575757;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .dna-background {
            background-image: url('https://via.placeholder.com/1500x500'); /* Replace with DNA image URL */
            background-size: cover;
            background-position: center;
            height: 500px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .dna-background h1 {
            font-size: 3em;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            margin-bottom: 5px;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>DNA Testing for Iranians</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#how-it-works">How It Works</a>
    <a href="#contact">Contact Us</a>
</nav>

<div id="home" class="dna-background">
    <h1>Discover Your Genetic Heritage</h1>
</div>

<div class="container">
    <div id="about" class="section">
        <h2>About Us</h2>
        <p>We provide specialized DNA testing services exclusively for Iranian people. Our mission is to help you discover your genetic heritage and connect with your roots.</p>
    </div>

    <div id="how-it-works" class="section">
        <h2>How It Works</h2>
        <ol>
            <li>Order your DNA test kit online.</li>
            <li>Receive the kit and collect your sample.</li>
            <li>Send the sample back to our lab.</li>
            <li>Get your results online within a few weeks.</li>
        </ol>
    </div>

    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </div>
</div>

<footer>
    <p>&copy; 2024 DNA Testing for Iranians. All rights reserved.</p>
</footer>

</body>
</html>
