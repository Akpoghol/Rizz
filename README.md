# Rizz
Coding Hub
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }

        nav a {
            color: #fff;
            padding: 15px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background: #555;
        }

        .hero {
            background: url('https://via.placeholder.com/1600x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px #000;
        }

        .hero h1 {
            font-size: 48px;
        }

        .container {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .about,
        .services,
        .contact {
            margin-bottom: 60px;
        }

        h2 {
            margin-bottom: 20px;
            color: #333;
        }

        .services-list {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .service {
            background: #f4f4f4;
            padding: 20px;
            flex: 1 1 30%;
            min-width: 250px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            max-width: 600px;
        }

        input, textarea {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
        }

        button {
            padding: 10px;
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background: #555;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Awesome Website</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h1>Your Dream Website Starts Here</h1>
    </section>

    <div class="container">
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus hendrerit arcu sed erat molestie vehicula. Sed auctor neque eu tellus rhoncus ut eleifend nibh porttitor. Ut in nulla enim.</p>
            <p>Phasellus molestie magna non est bibendum non venenatis nisl tempor. Suspendisse dictum feugiat nisl ut dapibus. Mauris iaculis porttitor posuere.</p>
        </section>

        <section id="services" class="services">
            <h2>Our Services</h2>
            <div class="services-list">
                <div class="service">
                    <h3>Web Design</h3>
                    <p>Professional and beautiful web design services for businesses of all sizes.</p>
                </div>
                <div class="service">
                    <h3>SEO Optimization</h3>
                    <p>Improve your site's ranking on Google and reach more customers.</p>
                </div>
                <div class="service">
                    <h3>Marketing</h3>
                    <p>We create effective marketing strategies to grow your brand.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form action="#">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea rows="5" name="message" placeholder="Your Message" required></textarea>
                <
