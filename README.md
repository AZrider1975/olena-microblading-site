<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olena's Microblading Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6f0;
            color: #333;
            position: relative;
            overflow-x: hidden;
        }
        header {
            background-color: #ff99c8;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ffb3d9;
            padding: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #ffd1e8;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
        }
        .cta {
            margin-top: 20px;
        }
        .cta a {
            text-decoration: none;
            color: white;
            background-color: #ff66a3;
            padding: 10px 20px;
            border-radius: 5px;
        }
        .cta a:hover {
            background-color: #e60073;
        }
        footer {
            background-color: #ff99c8;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }
        .heart {
            position: absolute;
            background-color: #ff66a3;
            width: 50px;
            height: 50px;
            transform: rotate(45deg);
            animation: float 10s infinite;
        }
        .heart:before,
        .heart:after {
            content: "";
            position: absolute;
            background-color: #ff66a3;
            border-radius: 50%;
            width: 50px;
            height: 50px;
        }
        .heart:before {
            top: -25px;
            left: 0;
        }
        .heart:after {
            left: -25px;
            top: 0;
        }
        @keyframes float {
            0% {
                transform: translateY(0) rotate(45deg);
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
            100% {
                transform: translateY(-100vh) rotate(45deg);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Olena's Microblading Services</h1>
        <p>1416 Langstonshire Lane, Morrisville, NC 27560</p>
    </header>

    <nav>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#booking">Book Now</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>Enhancing Your Natural Beauty</h1>
        <p>Professional microblading services to help you look and feel your best.</p>
        <div class="cta">
            <a href="#booking">Book an Appointment</a>
        </div>
    </div>

    <div class="hearts">
        <div class="heart" style="top: 10%; left: 20%; width: 30px; height: 30px;"></div>
        <div class="heart" style="top: 30%; left: 50%; width: 50px; height: 50px;"></div>
        <div class="heart" style="top: 60%; left: 70%; width: 40px; height: 40px;"></div>
        <div class="heart" style="top: 80%; left: 30%; width: 60px; height: 60px;"></div>
        <div class="heart" style="top: 20%; left: 80%; width: 20px; height: 20px;"></div>
    </div>

    <footer>
        <p>&copy; 2025 Olena's Microblading Services. All Rights Reserved.</p>
    </footer>
</body>
</html>

        <p>&copy; 2025 Olena's Microblading Services. All Rights Reserved.</p>
    </footer>
</body>
</html>
