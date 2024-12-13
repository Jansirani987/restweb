# Ex.07 Restaurant Website
## Date:13.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
            padding: 10px;
            text-align: center;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #575757;
        }

        .banner {
            background: url('pexels-naimbic-2290753.jpg') no-repeat center center/cover;
            color: black;
            padding: 60px;
            text-align: center;
        }

        .banner h2 {
            font-size: 2em;
            margin: 0;
        }

        .content {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }

        .card {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            padding: 20px;
            width: 30%;
            text-align: center;
        }

        .card img {
            width: 100%;
            border-radius: 10px 10px 0 0;
        }

        .card h3 {
            margin: 10px 0;
        }

        .card p {
            color: #666;
        }

        .card a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #222;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        .card a:hover {
            background-color: #575757;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: #fff;
            margin-top: 20px;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
</head>
<body>
    <header>
        <img src="smj.jpg" class="picture">

        <h1> SMJ Restaurant</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="banner">
        <h2>Special Weekend Discounts!</h2>
        <p>Enjoy up to 30% off on our exclusive dishes this weekend. Come and experience the taste of excellence.</p>
    </div>

    <div class="content">
        <div class="card">
            <img src="istockphoto-1147524737-1024x1024 (1).jpg">
            <h3>Our New Menu</h3>
            <p>Discover our latest dishes crafted with fresh ingredients and bursting with flavors. Try something new today!</p>
            <a href="menu.html">View Menu</a>
        </div>
        <div class="card">
            <img src="istockphoto-1645453133-1024x1024.jpg">
            <h3>Book a Table</h3>
            <p>Reserve your table now and enjoy a wonderful dining experience at SMJ Restaurant with your loved ones.</p>
            <a href="table.html">Reserve Now</a>
        </div>
        <div class="card">
            <img src="istockphoto-2160382162-1024x1024.jpg">
            <h3>Opening Hours</h3>
            <p>We are open to serve you:<br>Mon - Fri: 10 AM - 9 PM<br>Sat - Sun: 11 AM - 10 PM</p>
        </div>
    </div>

    <footer>
        <p>Designed and Developed by JANSI RANI</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - SMJ Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #575757;
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .menu-item {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            text-align: center;
        }

        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 10px 0;
            font-size: 1.5em;
        }

        .menu-item p {
            color: #666;
            padding: 0 10px;
            font-size: 0.9em;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: #fff;
            margin-top: 20px;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
</head>
<body>
    <header>  
        <img src="smj.jpg" class="picture">
        <h1>SMJ Restaurant - Menu</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="menu">
        <div class="menu-item">
            <img src="grilled chicken.jpeg" alt="Grilled Chicken">
            <h3>Grilled Chicken</h3>
            <p>Juicy and perfectly grilled chicken served with a side of fresh vegetables.</p>
        </div>
        <div class="menu-item">
            <img src="caesar.jpeg" alt="Caesar Salad">
            <h3>Caesar Salad</h3>
            <p>Crisp romaine lettuce, croutons, and parmesan cheese tossed in Caesar dressing.</p>
        </div>
        <div class="menu-item">
            <img src="pasta.jpeg" alt="Pasta Primavera">
            <h3>Pasta Primavera</h3>
            <p>Fresh pasta tossed with seasonal vegetables in a light garlic sauce.</p>
        </div>
        <div class="menu-item">
            <img src="potato.jpeg" alt="Steak and Potatoes">
            <h3>Steak and Potatoes</h3>
            <p>Succulent steak cooked to perfection with a side of roasted potatoes.</p>
        </div>
        <div class="menu-item">
            <img src="sea food.jpeg" alt="Seafood Platter">
            <h3>Seafood Platter</h3>
            <p>A delicious assortment of fresh seafood including shrimp, fish, and calamari.</p>
        </div>
        <div class="menu-item">
            <img src="cake.jpeg" alt="Chocolate Cake">
            <h3>Chocolate Cake</h3>
            <p>Rich and moist chocolate cake topped with creamy chocolate frosting.</p>
        </div>
        <div class="menu-item">
            <img src="pizza.jpeg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>Classic pizza with fresh mozzarella, basil, and a drizzle of olive oil.</p>
        </div>
        <div class="menu-item">
            <img src="biriyani.webp" alt="Chicken Biryani">
            <h3>Chicken Biryani</h3>
            <p>Flavored basmati rice cooked with tender chicken and aromatic spices.</p>
        </div>
        <div class="menu-item">
            <img src="soup.webp" alt="Tomato Soup">
            <h3>Tomato Soup</h3>
            <p>Warm and creamy tomato soup served with crispy croutons.</p>
        </div>
        <div class="menu-item">
            <img src="vegetable_stir_fry.jpg" alt="Vegetable Stir Fry">
            <h3>Vegetable Stir Fry</h3>
            <p>Fresh vegetables stir-fried with a savory soy-based sauce.</p>
        </div>
        <div class="menu-item">
            <img src="tandoori.webp" alt="Tandoori Paneer">
            <h3>Tandoori Paneer</h3>
            <p>Marinated paneer grilled to perfection with spices and herbs.</p>
        </div>
        <div class="menu-item">
            <img src="cake.webp" alt="Cheesecake">
            <h3>Cheesecake</h3>
            <p>Silky smooth cheesecake with a buttery graham cracker crust.</p>
        </div>
    </div>

    <footer>
        <p>Designed and Developed by Your Name</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #343a40;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #495057;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .team-section {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .team-member {
            text-align: center;
            background: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .team-member img {
            width: 100%;
            height: 80%;
            max-width: 150px;
            border-radius: 20%;
            margin-bottom: 10px;
        }
        .team-member h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .team-member p {
            font-size: 0.9em;
            padding-bottom: 15px;
            color: #555;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
</head>
<body>
    <header>
        <img src="smj.jpg" class="picture">
        <h1>Restaurant Administration</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <main>
        <div class="container">
            <h2>Meet the Team</h2>
            <div class="team-section">
                <div class="team-member">
                    <img src="owner.jpg" alt="owner.jpg">
                    <h3>John Doe</h3>
                    <p>Owner</p>
                </div>
                <div class="team-member">
                    <img src="founder.jpg" alt="founder.jpg">
                    <h3>Mani</h3>
                    <p>founder</p>
                </div>
                <div class="team-member">
                    <img src="marketing director.jpg" alt="marketing director.jpg">
                    <h3>Kavi</h3>
                    <p>Marketing director</p>
                </div>
                <div class="team-member">
                    <img src="manger.jpg" alt="manger.jpg">
                    <h3>Michael Brown</h3>
                    <p>Manager</p>
                </div>
                <div class="team-member">
                    <img src="finance accounter.jpg" alt="finance accounter.jpg">
                    <h3>Jansi</h3>
                    <p>finance accounter</p>
                </div>
                <div class="team-member">
                    <img src="chef.jpg" alt="chef.jpg">
                    <h3>Chris Wilson</h3>
                    <p>chef</p>
                </div>
            </div>
        </div>
    </main>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - [Restaurant Name]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: white;
            background-color: black;
            padding: 0px;
        }
        nav {
            background-color: #333;
            overflow: hidden;
            padding: 10px;
            text-align: center;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #575757;
        }
        .contact-info, .contact-form {
            margin: 20px 0;
        }
        .contact-info p {
            margin: 5px 0;
            font-size: 16px;
            color: #555;
        }
        .contact-info a {
            color: #007BFF;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin-bottom: 5px;
            font-weight: bold;
        }
        form input, form textarea {
            margin-bottom: 15px;
            padding: 10px;
            font-size: 14px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px;
            font-size: 16px;
            color: #fff;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="container">
        <h1>Contact Us</h1>
        <div class="contact-info">
            <p><strong>Address:</strong> 123 Food Street, Gourmet City, FL 45678</p>
            <p><strong>Phone:</strong> <a href="tel:+123456789">+1 (234) 567-890</a></p>
            <p><strong>Email:</strong> <a href="mailto:info@restaurant.com">info@restaurant.com</a></p>
        </div>
        <div class="contact-form">
            <h2>Send Us a Message</h2>
            <form action="/submit-contact" method="POST">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </div>
    </div>
</body>
</html>

table.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Table Booking</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        .booking-details {
            border: 1px solid #ddd;
            padding: 20px;
            max-width: 400px;
            margin: 0 auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color:black;
        }
        p {
            margin: 10px 0;
        }
        .highlight {
            font-weight: bold;
            color: #555;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        .h11{
color:white;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
</head>
<body>
    <header>
        <img src="smj.jpg" class="picture">
        <h1 class="h11">SMJ Restaurant</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <h1>Restaurant Table Booking Information</h1>

    <div class="booking-details">
        <p><span class="highlight">Table Capacity:</span> Up to 4 guests</p>
        <p><span class="highlight">Booking Timings:</span> 12:00 PM to 10:00 PM</p>
        <p><span class="highlight">Advance Booking:</span> Recommended at least 24 hours prior</p>
        <p><span class="highlight">Contact:</span> +1 (123) 456-7890</p>
        <p><span class="highlight">Location:</span> 123 Gourmet Street, Foodville</p>
    </div>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)
![alt text](<Screenshot (67).png>)
![alt text](<Screenshot (68).png>)
![alt text](<Screenshot (69).png>)
![alt text](<Screenshot (70).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
