<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Recommendations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        nav {
            background-color: #333;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin-right: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            color: #ff5733;
        }

        header {
            background-color: pink;
            color: rgb(0, 0, 0);
            padding: 20px;
            text-align: center;
        }

        section {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        img {
            width: 100%;
            max-width: 400px;
            margin: 10px 0;
            border-radius: 8px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #ff5733;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            section {
                margin: 10px;
                padding: 15px;
            }

            img {
                max-width: 100%;
            }
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
            margin-top: 20px;
        }

        footer a {
            color: #ff5733;
            text-decoration: none;
        }

    </style>
</head>
<body>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Beaches</a></li>
            <li><a href="#">Temples</a></li>
            <li><a href="#">Countries</a></li>
        </ul>
    </nav>

    <header>
        <h1>Welcome to Travel Recommendations</h1>
        <p>Your ultimate guide to discovering the best travel destinations based on your preferences.</p>
    </header>

    <section>
        <h2>About Us</h2>
        <p>At our core, we’re on a mission to transform every journey into a personalized adventure. Whether you’re dreaming of unwinding on sun-kissed beaches, stepping back in time to explore ancient temples, or immersing yourself in the rich history and culture of a new destination, we’ve got you covered.</p>
        <p>Our team is a vibrant group of travel aficionados, united by a shared passion for discovery and adventure. With our expertise and dedication, we’ll make sure your next trip isn’t just memorable—it’ll be a once-in-a-lifetime experience. Let us guide you to the places that will ignite your wanderlust and leave you with stories to tell for years to come.</p>
    </section>

    <section>
        <h2>Contact Us</h2>
        <form action="your-script.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <section>
        <h2>Beach Recommendations</h2>
        <h3>Pereybere Beach, Mauritius</h3>
        <p>Pereybere Beach in Mauritius is known for its crystal-clear turquoise waters, ideal for swimming, snorkeling, and its vibrant, relaxed atmosphere.</p>
        <img src="download.jpeg" alt="Pereybere Beach">
        <img src="download (1).jpeg" alt="Pereybere Beach">

        <h3>Mont Choisy Beach, Mauritius</h3>
        <p>Mont Choisy Beach in Mauritius is known for its long stretch of golden sand, clear blue waters, and excellent conditions for swimming, sunbathing, and water sports.</p>
        <img src="download (2).jpeg" alt="Mont Choisy Beach">
        <img src="download (3).jpeg" alt="Mont Choisy Beach">
    </section>

    <section>
        <h2>Temple Recommendations</h2>
        <h3>Angkor Wat, Cambodia</h3>
        <p>Angkor Wat is one of the largest religious monuments in the world and a UNESCO World Heritage site.</p>
        <img src="download (4).jpeg" alt="Angkor Wat">
        <img src="download (5).jpeg" alt="Angkor Wat">

        <h3>Golden Temple, India</h3>
        <p>The Golden Temple in Amritsar is a stunning spiritual site with a peaceful atmosphere.</p>
        <img src="download (6).jpeg" alt="Golden Temple">
        <img src="65022743.webp" alt="Golden Temple">
    </section>

    <section>
        <h2>Country Recommendations</h2>
        <h3>Japan</h3>
        <p>Japan is a country full of history, culture, and beautiful landscapes. From Mount Fuji to Tokyo's bustling streets, there's something for everyone.</p>
        <img src="tokyo-main.avif" alt="Tokyo Japan">
        <img src="download (7).jpeg" alt="Mount Fuji Japan">

        <h3>Italy</h3>
        <p>Italy offers stunning historical sites, delicious food, and romantic landscapes. Visit Venice, Rome, and the Amalfi Coast for a truly unforgettable experience.</p>
        <img src="venice.jpg" alt="Venice Italy">
        <img src="Colosseo_2020.jpg" alt="Colosseum Rome">
    </section>

    <footer>
        <p>&copy; 2024 Travel Recommendations. All Rights Reserved.</p>
        <p>Follow us on <a href="#">Instagram</a>, <a href="#">Twitter</a>, <a href="#">Facebook</a></p>
    </footer>

</body>
</html>
