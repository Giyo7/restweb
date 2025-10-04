# Ex.07 Restaurant Website
## Date:02.10.2025

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
STYLE.CSS:

/* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #ea0a63;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

HOME.HTML:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Restaurant</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="advertisement_banner.png" alt="Delicious Food Banner">
  </section>

  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Your Lince giyo</p>
  </footer>
</body>
</html>

ADMINISTRATION.HTML:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="ChatGPT Image Oct 1, 2025, 10_11_10 AM.png" alt="Admin 1">
      <h3>John Smith</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="generate the image a e.png" alt="Admin 2">
      <h3>Emily Rose</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="ChatGPT Image Oct 1, 2025, 10_15_30 AM.png" alt="Admin 3">
      <h3>David Lee</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="ChatGPT Image Oct 1, 2025, 10_13_38 AM.png" alt="Admin 4">
      <h3>Sophie Turner</h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="generate the image a.png" alt="Admin 5">
      <h3>Mike Jordan</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="customer.png" alt="Admin 6">
      <h3>Lisa Kim</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Your Lince giyo</p>
  </footer>
</body>
</html>

MENU.HTML:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="menu-item">
      <img src="pizza.jpg" alt="Pizza">
      <h3>Cheese Pizza</h3>
      <p>Classic cheese pizza with tomato sauce.</p>
    </div>
    <div class="menu-item">
      <img src="veg burger.jpg" alt="Burger">
      <h3>Beef Burger</h3>
      <p>Grilled beef patty with fresh veggies.</p>
    </div>
    <div class="menu-item">
      <img src="salad.jpg" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>Crisp lettuce with creamy Caesar dressing.</p>
    </div>
    <div class="menu-item">
      <img src="sushi roll.jpg" alt="Sushi">
      <h3>Sushi Rolls</h3>
      <p>Fresh and delicious sushi assortment.</p>
    </div>
    <div class="menu-item">
      <img src="hotdog.jpg" alt="Steak">
      <h3>hot dog</h3>
      <p>hot and Spicy.</p>
    </div>
    <div class="menu-item">
      <img src="tacos.jpg" alt="Tacos">
      <h3>Mexican Tacos</h3>
      <p>Spicy beef tacos with salsa.</p>
    </div>
    <div class="menu-item">
      <img src="soup.jpg" alt="Soup">
      <h3>Tomato Soup</h3>
      <p>Warm and creamy tomato soup.</p>
    </div>
    <div class="menu-item">
      <img src="sandwich.jpg" alt="Sandwich">
      <h3>Club Sandwich</h3>
      <p>Layered sandwich with chicken and bacon.</p>
    </div>
    <div class="menu-item">
      <img src="pancakes.jpg" alt="Pancakes">
      <h3>Pancakes</h3>
      <p>Fluffy pancakes with syrup.</p>
    </div>
    <div class="menu-item">
      <img src="ice creams.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="french fries.jpg" alt="Fries">
      <h3>French Fries</h3>
      <p>Crispy golden fries.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Your Lince giyo</p>
  </footer>
</body>
</html>

CONTACT.HTML:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 123 Food Street, Goutham City, FL 45678</p>
    <p>📞 <strong>Phone:</strong> (123) 246-7890</p>
    <p>✉ <strong>Email:</strong> contact@ourrestaurant.com</p>
  </section>

  <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by Your Lince giyo</p>
  </footer>

</body>
</html>
```
## OUTPUT:
![alt text](<res/resapp/static/Screenshot 2025-10-02 074742.png>)
![alt text](<res/resapp/static/Screenshot 2025-10-02 074810.png>)
![alt text](<res/resapp/static/Screenshot 2025-10-02 074841.png>)
![alt text](<res/resapp/static/Screenshot 2025-10-02 074922.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
