<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evelyn's Kitchen</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        header, footer {
            background-color: #333;
            color: white;
            padding: 2em;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            font-family: 'Georgia', serif;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        nav ul {
            list-style-type: none;
            text-align: center;
            background-color: #444;
            margin-top: 20px;
            padding: 1em;
            position: sticky;
            top: 0;
        }

        nav ul li {
            display: inline-block;
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 5px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover, nav ul li a.active {
            background-color: #ff6347;
        }

        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 50px auto;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            margin-bottom: 30px;
        }

        h2 {
            font-size: 2.5em;
            color: #444;
            margin-bottom: 20px;
        }

        /* Contact Section */
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        .contact-form button {
            background-color: #ff6347;
            color: white;
            border: none;
            padding: 12px 30px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #e53e2f;
        }

        /* Social Media Section */
        .social-media ul {
            list-style-type: none;
            text-align: center;
            margin-top: 20px;
        }

        .social-media ul li {
            display: inline;
            margin: 0 15px;
        }

        .social-media ul li a {
            font-size: 20px;
            color: #333;
            transition: color 0.3s ease;
        }

        .social-media ul li a:hover {
            color: #ff6347;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul li {
                display: block;
                margin: 10px 0;
            }

            .gallery {
                grid-template-columns: 1fr;
            }

            header h1 {
                font-size: 2.5em;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to Evelyn's Kitchen</h1>
        <p>Authentic Filipino flavors with an American twist</p>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home" class="active">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to Evelyn's Kitchen!</h2>
        <p>Explore our delicious Filipino-American fusion cuisine, where every dish tells a story of tradition and innovation.</p>
        <p>Click the links above to discover more about our menu, our story, our gallery, and how to reach us.</p>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Evelyn's Kitchen</h2>
        <p>At Evelyn's Kitchen, we blend Filipino authenticity with American comfort, serving dishes made from the freshest ingredients. Our signature recipes, passed down from generation to generation, are sure to delight your taste buds!</p>
        <p>Our story began as a simple fundraising initiative, where we cooked for free and shared our meals with friends and family at community potlucks. The love and support we received inspired us to turn our passion into a business. Now, we deliver the flavors of our heritage to your doorstep!</p>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Menu</h2>
        <table>
            <tr>
                <th>Dish</th>
                <th>Description</th>
                <th>Price</th>
            </tr>
            <tr>
                <td>Carbonara</td>
                <td>A creamy pasta with a Filipino twist.</td>
                <td>$10.99</td>
            </tr>
            <tr>
                <td>Fried Chicken</td>
                <td>Classic crispy fried chicken.</td>
                <td>$12.99</td>
            </tr>
            <tr>
                <td>Adobo</td>
                <td>A traditional Filipino dish with tender chicken.</td>
                <td>$11.99</td>
            </tr>
            <tr>
                <td>Pancit</td>
                <td>Filipino noodle stir fry.</td>
                <td>$9.99</td>
            </tr>
            <tr>
                <td>BBQ Pork Skewers</td>
                <td>Sweet and savory grilled skewers.</td>
                <td>$8.99</td>
            </tr>
        </table>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Our Dishes</h2>
        <div class="gallery">
            <img src="https://images.immediate.co.uk/production/volatile/sites/30/2020/08/recipe-image-legacy-id-1001491_11-2e0fa5c.jpg?quality=90&amp;resize=440,400" alt="Carbonara" />
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQY3J4fKy_BP2uXF_H4dx-TtDAUuG9xOZY2nQ&amp;s" alt="Fried Chicken" />
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQisPXiTeaIqqo5KuK2ipUTLIgPFGh98nwWBw&s" alt="Adobo" />
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxpzASOIBW8YTs_0NryCBCR" alt="Pancit" />
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>Customer Feedback</h2>
        <p>"Whenever my kids and I go to other restaurant to order Carbonara, they will keep commenting that they miss Evelyn's Kitchen's Carbonara, " - Lezil</p>
        <p>"You adobo chicken is my favorite dish at the CNMI." - Victoria</p>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have questions or want to place an order? We're here to help! Reach out to us using the form below.</p>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>

        <h3>Call us</h3>
        <p>+1 (670) 287-1070 </p>
        <p>We offer delivery services within Saipan, CNMI!!</p


