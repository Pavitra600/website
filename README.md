# Ex.07 Restaurant Website
# Date: 26/11/24
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
/ homepage/
    <!DOCTYPE html>
    <html lang="en">
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Korean Restaurant</title>
    </head>
    <style>
        body {
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            margin: 0;
            padding: 0;
            background: url('bg resto.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #333333;
        }
    
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }
    
        header {
            background-color: #5C0066; /* Deep purple */
            color: black; /* White for contrast */
            padding: 20px 0;
            text-align: center;
            font-size: large;
        }
    
        header nav ul {
            list-style-type: none;
            padding: 0;
        }
    
        header nav ul li {
            display: inline;
            margin: 0 15px;
        }
    
        header nav ul li button {
            background: none;
            border: 2px solid #FFD700; /* Gold */
            color: #FFD700;
            padding: 5px 10px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
        }
    
        header nav ul li button:hover {
            background: #FFD700;
            color: #5C0066; /* Matches header background */
        }
    
        section {
            margin: 20px 0;
            text-align: center;
        }
    
        h2 {
            color: #C0392B; /* Red */
        }
    
        .menu-item {
            background-color: #FFE4B5; /* Light golden shade */
            margin: 10px 0;
            padding: 15px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
    
        .menu-item h3 {
            margin-right: 15px;
            color: #5C0066; /* Matches header */
        }
    
        .menu-item img {
            border-radius: 10px;
            margin-right: 10px;
            width: 100px;
            height: auto;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
    
        footer {
            background-color: #333333; /* Dark gray */
            color: #FFD700; /* Gold */
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    
        footer h2 {
            margin: 10px 0;
        }
    
        footer p {
            margin: 5px 0;
        }
    </style>
    
    <body>
        <header>
            <div class="container">
                <h1>Seoul Flavor</h1>
                <nav>
                    <ul>
                        <li>
                            <button onclick="location.href='about.html'">About</button>
                        </li>
                        <li>
                            <button onclick="location.href='contact.html'">Contact Us</button>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>
    
        <section id="about">
            <div class="container">
                <h2>Welcome to Seoul Flavor</h2>
                <p>Discover the taste of authentic Korean cuisine. Our dishes are crafted using traditional recipes and the
                    freshest ingredients to bring you the true essence of Korea.</p>
                <p>At Seoul Flavor, we invite you to embark on a culinary journey through the vibrant and diverse world of
                    Korean cuisine. Nestled in the heart of the city, our restaurant is a haven for food enthusiasts seeking
                    authentic flavors and unforgettable dining experiences.</p>
            </div>
        </section>
    
        <section id="menu">
            <div class="container">
                <h2>Our Menu</h2>
    
                <div class="menu-item">
                    <img src="bibimbap-recipe-13.jpg">
                    <h3>Bibimbap</h3>
                    <p>A vibrant mixed rice dish topped with vegetables, beef, and a fried egg, served with spicy gochujang
                        sauce.</p>
                </div>
                <div class="menu-item">
                    <img src="kimchi.jpg">
                    <h3>Kimchi</h3>
                    <p>Fermented vegetables, typically napa cabbage and radishes, seasoned with chili pepper, garlic,
                        ginger, and other spices.</p>
                </div>
                <div class="menu-item">
                    <img src="bbq.jpg">
                    <h3>Korean BBQ</h3>
                    <p>Grilled meats marinated in savory sauces, served with a variety of side dishes and dipping sauces.
                    </p>
                </div>
                <div class="menu-item">
                    <img src="vegan-japchae-683x1024-1.jpg">
                    <h3>Japchae</h3>
                    <p>Stir-fried glass noodles mixed with vegetables and marinated beef, seasoned with soy sauce and sesame
                        oil.</p>
                </div>
                <div class="menu-item">
                    <img src="best-vegan-tteokbokki-with-cocktail-sausages-and-tofu-fish-korean-inspired-thumb-3.jpg">
                    <h3>Tteokbokki</h3>
                    <p>Spicy stir-fried rice cakes cooked with fish cakes and vegetables in a sweet and spicy sauce.</p>
                </div>
                <div class="menu-item">
                    <img src="soondubu.webp">
                    <h3>Sundubu-jjigae</h3>
                    <p>Soft tofu stew made with a spicy broth, vegetables, and seafood or meat.</p>
                </div>
    
                <div class="menu-item">
                    <img src="fried rice.jpg">
                    <h3>Kimchi Fried Rice</h3>
                    <p>Stir-fried rice with kimchi, vegetables, and your choice of meat, topped with a fried egg.</p>
                </div>
    
                <div class="menu-item">
                    <img src="maandu.jpg">
                    <h3>Mandu</h3>
                    <p>Korean dumplings filled with meat and vegetables, served steamed or fried.</p>
                </div>
                <div class="menu-item">
                    <img src="patbingsu.webp">
                    <h3>Patbingsu</h3>
                    <p>A popular Korean dessert made with shaved ice, sweet red beans, fruits, 
                        and condensed milk.</p>
                </div>
    
            </div>
        </section>
    
        <footer>
            <div class="container">
                <h2>Contact Us</h2>
                <p>Email: info@seoulflavor.com</p>
                <p>Phone: 7890934356</p>
                <p>Address: 18th main road, Annanagar West, Chennai-40</p>
            </div>
        </footer>
    </body>
    
    </html>

/ about /
    <!DOCTYPE html>
    <html lang="en">
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>About Us - Seoul Flavor</title>
        <style>
            body {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                margin: 0;
                padding: 0;
                background: url('cleo-restaurant.jpg') no-repeat center center fixed;
                background-size: cover;
                color: #fff;
            }
    
            header {
                background-color: rgba(154, 0, 193, 0.85);
                color: #fff;
                padding: 20px 0;
                text-align: center;
            }
    
            header h1 {
                margin: 0;
                font-size: 2.5em;
            }
    
            .container {
                width: 80%;
                margin: 0 auto;
                padding: 20px;
                background-color: rgba(255, 255, 255, 0.8);
                border-radius: 10px;
                box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
            }
    
            section {
                margin: 20px 0;
            }
    
            h2 {
                color: #9a00c1;
                margin-bottom: 10px;
                text-align: center;
            }
    
            p {
                line-height: 1.6;
                color: #333;
            }
    
            .mission,
            .history,
            .team,
            .testimonials {
                background-color: #fff;
                margin: 20px 0;
                padding: 20px;
                border-radius: 10px;
                box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            }
    
            .team {
                display: flex;
                flex-wrap: wrap;
                justify-content: space-between;
            }
    
            .team-member {
                flex: 1 1 30%;
                text-align: center;
                margin: 10px;
            }
    
            .team-member img {
                border-radius: 50%;
                width: 120px;
                height: 120px;
                object-fit: cover;
                margin-bottom: 10px;
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
            }
    
            footer {
                background-color: rgba(154, 0, 193, 0.85);
                color: #fff;
                text-align: center;
                padding: 10px 0;
                margin-top: 20px;
            }
    
            footer a {
                color: #ffd700;
                text-decoration: none;
            }
    
            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    
    <body>
        <header>
            <h1>About Seoul Flavor</h1>
        </header>
    
        <div class="container">
            <!-- Mission Section -->
            <section class="mission">
                <h2>Our Mission</h2>
                <p>
                    At Seoul Flavor, our mission is to bring the authentic taste of Korea to your table. We are committed to
                    providing our guests with an unforgettable dining experience through exceptional service, high-quality
                    ingredients, and a passion for culinary excellence.
                </p>
            </section>
    
            <!-- History Section -->
            <section class="history">
                <h2>Our History</h2>
                <p>
                    Seoul Flavor was founded in 2015 with the vision of sharing the vibrant and diverse flavors of Korean
                    cuisine with the world. Over the years, we have become a beloved dining destination, blending
                    traditional recipes with modern flair.
                </p>
            </section>
    
            <!-- Team Section -->
            <section class="team">
                <h2>Meet Our Team</h2>
                <div class="team-member">
                    <img src="chef.resto.jpg" alt="Chef John">
                    <h3>Chef John Kim</h3>
                    <p>Executive Chef</p>
                </div>
                <div class="team-member">
                    <img src="chef2.jpeg" alt="Manager Sarah">
                    <h3>Sarah Park</h3>
                    <p>General Manager</p>
                </div>
                <div class="team-member">
                    <img src="che3.jpeg" alt="Sous Chef Lee">
                    <h3>Lee Min</h3>
                    <p>Sous Chef</p>
                </div>
            </section>
    
            <!-- Testimonials Section -->
            <section class="testimonials">
                <h2>What Our Guests Say</h2>
                <p>
                    "Seoul Flavor is the best Korean restaurant I've ever visited! The Bibimbap is amazing, and the service
                    is top-notch." – Emily R.
                </p>
                <p>
                    "I love the ambiance and the food. The Korean BBQ is a must-try!" – David L.
                </p>
            </section>
        </div>
    
        <footer>
            <p>© 2024 Seoul Flavor | <a href="index.html">Back to Home</a></p>
        </footer>
    </body>
    
    </html>

/ contact us /

    <!DOCTYPE html>
    <html lang="en">
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Contact Us - Seoul Flavor</title>
        <style>
            body {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                margin: 0;
                padding: 0;
                background-image: url('cleo-restaurant.jpg');
                background-size: cover;
                background-repeat: no-repeat;
                background-attachment: fixed;
                color: #333;
            }
    
            header {
                background-color: rgba(154, 0, 193, 0.9);
                color: #fff;
                padding: 20px 0;
                text-align: center;
            }
    
            header h1 {
                margin: 0;
                font-size: 2.5em;
            }
    
            .container {
                width: 80%;
                margin: 0 auto;
                padding: 20px;
            }
    
            h2 {
                color: #c0392b;
                margin-bottom: 10px;
                text-align: center;
            }
    
            .contact-info,
            .contact-form {
                background-color: rgba(255, 255, 255, 0.9);
                margin: 20px 0;
                padding: 20px;
                border-radius: 10px;
                box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            }
    
            .contact-info h3,
            .contact-form h3 {
                margin-top: 0;
            }
    
            .contact-info p {
                line-height: 1.6;
            }
    
            .contact-info .map {
                margin-top: 15px;
                text-align: center;
            }
    
            .map iframe {
                width: 100%;
                height: 300px;
                border: none;
                border-radius: 10px;
            }
    
            .contact-form form {
                display: flex;
                flex-direction: column;
            }
    
            .contact-form label {
                margin: 10px 0 5px;
            }
    
            .contact-form input,
            .contact-form textarea,
            .contact-form button {
                padding: 10px;
                margin-bottom: 15px;
                border: 1px solid #ddd;
                border-radius: 5px;
            }
    
            .contact-form button {
                background-color: #9a00c1;
                color: #fff;
                border: none;
                cursor: pointer;
                font-size: 1em;
            }
    
            .contact-form button:hover {
                background-color: #c0392b;
            }
    
            footer {
                background-color: rgba(154, 0, 193, 0.9);
                color: #fff;
                text-align: center;
                padding: 10px 0;
                margin-top: 20px;
            }
    
            footer a {
                color: #ffd700;
                text-decoration: none;
            }
    
            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    
    <body>
        <header>
            <h1>Contact Us</h1>
        </header>
    
        <div class="container">
            <!-- Contact Information Section -->
            <section class="contact-info">
                <h2>Get in Touch</h2>
                <h3>Contact Details</h3>
                <p>
                    Email: <a href="mailto:info@seoulflavor.com">info@seoulflavor.com</a><br>
                    Phone: <a href="tel:+917890934356">+91 7890934356</a><br>
                    Address: 18th Main Road, Anna Nagar West, Chennai - 40
                </p>
                <div class="map">
                    <h3>Our Location</h3>
                    <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3916.5892651239193!2d77.20761671533835!3d13.085255290768393!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae17f6a1740001%3A0x8d9c26002a104cd6!2sAnna%20Nagar%20West%20Bus%20Depot!5e0!3m2!1sen!2sin!4v1697138384032!5m2!1sen!2sin"
                        allowfullscreen="" loading="lazy">
                    </iframe>
                </div>
            </section>
    
            <!-- Contact Form Section -->
            <section class="contact-form">
                <h2>Send Us a Message</h2>
                <form action="submit_form.php" method="POST">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name" required>
    
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
    
                    <label for="message">Your Message</label>
                    <textarea id="message" name="message" rows="5" placeholder="Write your message here" required></textarea>
    
                    <button type="submit">Send Message</button>
                </form>
            </section>
        </div>
    
        <footer>
            <p>© 2024 Seoul Flavor | <a href="index.html">Back to Home</a></p>
        </footer>
    </body>
    
    </html>



# OUTPUT:
![Screenshot 2024-12-19 145059](https://github.com/user-attachments/assets/e0b3a660-915a-4d3c-b2ac-c8014b1251d6)
![Screenshot 2024-12-19 145132](https://github.com/user-attachments/assets/6e99ec73-075e-4778-b05b-c17462083c9d)
![Screenshot 2024-12-19 145150](https://github.com/user-attachments/assets/bc168da6-cf9a-49b8-8766-b00e080161d0)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
