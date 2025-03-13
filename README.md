## Hi there 👋
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Header */
        header {
            background: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        /* Navigation */
        nav {
            background: #444;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        /* Main Content */
        .hero {
            padding: 4rem 2rem;
            background: #f4f4f4;
            text-align: center;
        }

        .content-section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Website Name</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h2>Welcome to My Website</h2>
        <p>Your compelling tagline goes here</p>
    </div>

    <section class="content-section" id="about">
        <h2>About Us</h2>
        <p>This is where you describe your website or business.</p>
    </section>

    <section class="content-section" id="services">
        <h2>Our Services</h2>
        <div style="display: flex; gap: 1rem; margin-top: 1rem;">
            <div style="background: #f4f4f4; padding: 1rem; flex: 1;">
                <h3>Service 1</h3>
                <p>Description of your service.</p>
            </div>
            <div style="background: #f4f4f4; padding: 1rem; flex: 1;">
                <h3>Service 2</h3>
                <p>Description of your service.</p>
            </div>
        </div>
    </section>

    <section class="content-section" id="contact">
        <h2>Contact Us</h2>
        <p>Email: your@email.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 1987-2025 Your Website Name. All rights reserved.</p>
    </footer>
</body>
</html>
