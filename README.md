# landing-page-web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthy Eating Habits</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, p, ul {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: lightblue;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        .nav-links {
            list-style: none;
        }

        .nav-links li {
            display: inline;
            margin: 0 15px;
        }

        .nav-links a {
            color: #fff;
            text-decoration: none;
        }

        #hero {
            background: url('https://example.com/healthy-food.jpg') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 0;
        }

        #hero h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .cta-button {
            display: inline-block;
            background: #e67e22;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        section {
            padding: 50px;
            text-align: center;
        }

        #benefits ul {
            list-style: none;
        }

        #benefits li {
            background: #eee;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
        }

        .recipe-card {
            background: #fff;
            padding: 20px;
            margin: 10px 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">HealthyLife</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#benefits">Benefits</a></li>
                <li><a href="#recipes">Recipes</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Welcome to HealthyLife</h1>
        <p>Embrace a healthier lifestyle with our curated tips and recipes.</p>
        <a href="#about" class="cta-button">Learn More</a>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>HealthyLife is dedicated to promoting healthy eating habits through easy-to-follow guides and delicious recipes.</p>
    </section>

    <section id="benefits">
        <h2>Benefits of Healthy Eating</h2>
        <ul>
            <li>Improves overall health</li>
            <li>Boosts energy levels</li>
            <li>Supports weight management</li>
            <li>Enhances mood and mental well-being</li>
        </ul>
    </section>

    <section id="recipes">
        <h2>Our Favorite Recipes</h2>
        <div class="recipe-card">
            <h3>Avocado Salad</h3>
            <p>A refreshing and nutritious salad packed with healthy fats.</p>
        </div>
        <div class="recipe-card">
            <h3>Quinoa Bowl</h3>
            <p>A hearty bowl filled with protein-rich quinoa and fresh veggies.</p>
        </div>
    </section>

    <footer id="contact">
        <h2>Contact Us</h2>
        <p>Email: siddharthpandey2525@gmail.com</p>
        <p>Follow us on social media for daily tips and inspiration!</p>
        <p>By Siddharth Pandey</p>
    </footer>

    <script>
        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
