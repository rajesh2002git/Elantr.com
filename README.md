<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ELANT-R - Innovative IoT and Electronics Solutions</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Welcome to ELANT-R</h1>
        <p>Your partner in IoT and Electronics Solutions</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in developing innovative IoT and electronics-based solutions for businesses.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <p>We provide a range of services from IoT solutions to custom embedded systems design.</p>
    </section>

    <!-- Contact Us Section with Formspree integration -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/xvgooajz" method="POST">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 ELANT-R. All rights reserved.</p>
    </footer>
</body>
</html>
