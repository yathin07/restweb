# Ex.07 Restaurant Website
## Date:11-10-25

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Palmshore - Home</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Palmshore Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Welcome to Palmshore! Best foods across the globe</h2>
    <p style="text-align:center;">Enjoy our wide variety of foods and experience excellent service.</p>
    <img src="food1.jpg" alt="Restaurant Image" style="width:25%; height:50%; margin-top:40px;">
    <img src="food2.jpg" alt="Restaurant Image" style="width:30%; height:50%; margin-top:40px;">
    <img src="food3.jpg" alt="Restaurant Image" style="width:28%; height:30%; margin-top:40px;">
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Menu - Palmshore</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Palmshore Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <!-- Repeat for 12 food items -->
        
        <div class="menu-item">
            <img src="burger.jpg" alt="Food 2"style="width:20%; height:100px;">
            <h3>Burger</h3>
            <p>130</p>
        </div>
        <div class="menu-item">
            <img src="pasta.webp" alt="Food 3"style="width:20%; height:100px;">
            <h3>Pasta</h3>
            <p>99</p>
        </div>
        <div class="menu-item">
            <img src="biriyani1.jpeg" alt="Food 3"style="width:20%; height:100px;">
            <h3>Biriyani</h3>
            <p>99</p>
        </div>
        <div class="menu-item">
            <img src="icecream.jpg" alt="Food 3"style="width:20%; height:100px;">
            <h3>Icecream</h3>
            <p>110</p>
        </div>
        <div class="menu-item">
            <img src="tiramisu.jpg" alt="Food 3"style="width:20%; height:100px;">
            <h3>Tiramisu</h3>
            <p>90</p>
        </div>
        <!-- Add remaining 9 food items similarly -->
    </div>
</div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Administration - Palmshore</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Palmshore Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Our Team</h2>
    <div class="admin-grid">
        <!-- Repeat for 6 people -->
        <div class="admin-item">
            <img src="person1.jpg" alt="Person 1"style="width:20%; height:100px;">

            <h3>Vijay</h3>
            <p>Manager</p>
        </div>
        <div class="admin-item">
            <img src="person22.jpg" alt="Person 2"style="width:20%; height:100px;">
            <h3>Virat</h3>
            <p>Chef</p>
        </div>
        <div class="admin-item">
            <img src="person3.jpg" alt="Person 3"style="width:20%; height:100px;">
            <h3>Sid</h3>
            <p>Waiter</p>
        </div>
        
        <!-- Add remaining 3 people similarly -->
    </div>
</div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - Palmshore</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Palmshore Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="container">
    <h2>Contact Us</h2>
    <div class="contact-info">
        <p>Address: 123 Delicious Street, Food City</p>
        <p>Phone: +91-9876543210</p>
        <p>Email: info@palmshore.com</p>
        <p>Follow us on:
            <a href="#">Facebook</a>,
            <a href="#">Twitter</a>,
            <a href="#">Instagram</a>
        </p>
        <p>Business Hours: Mon-Sun: 10am - 10pm</p>
        
    </div>
</div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #ff6347; /* Tomato color */
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav {
    text-align: center;
    background-color: #333;
}

nav a {
    color: white;
    padding: 14px 20px;
    text-decoration: none;
    display: inline-block;
}

nav a:hover {
    background-color: #ff6347;
}

.container {
    width: 80%;
    margin: auto;
    padding: 20px 0;
}

h1, h2 {
    text-align: center;
    margin-bottom: 20px;
}

/* Menu page styling */
.menu-grid {
    display:flex;
    flex-wrap: wrap;
    gap: 30px;
}

.menu-item {
    width: 220px;
    text-align: center;

}

.menu-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

/* Administration page styling */
.admin-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.admin-item {
    background-color: white;
    padding: 10px;
    text-align: center;
    border-radius: 10px;
}

.admin-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 50%;
}

/* Contact page styling */
.contact-info {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 20px;
}
footer a {
    color: #ff6347;
    text-decoration: none;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-10-10 190531.png>)
![alt text](<Screenshot 2025-10-10 190554.png>)
![alt text](<Screenshot 2025-10-10 190615.png>)
![alt text](<Screenshot 2025-10-10 190628.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
