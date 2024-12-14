# Ex.07 Restaurant Website
## Date:14-12-24

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-image: url('bground.jpg');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #343a40;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #495057;
        }
        .container {
            padding: 20px;
        }
        .menu-items, .admin, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .menu-item, .admin-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
            flex: 1 1 calc(25% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .menu-item img, .admin-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Delicious Bites</h1>
        <p>Your favorite place for exquisite meals</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>
    
    <section id="home" class="container">
        <h2>Home</h2>
        <p>Enjoy a world of flavors at Delicious Bites, where every bite is a celebration of taste.</p>
    </section>

    <section id="menu" class="container">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="dish1.jpg" alt="Dish 1">
                <p>Spaghetti Carbonara</p>
            </div>
            <!-- Repeat for 12 items -->
            <div class="menu-item">
                <img src="dish2.jpg" alt="Dish 12">
                <p>Margherita Pizza</p>
            </div>
            <div class="menu-item">
                <img src="dish3.webp" alt="Dish 12">
                <p>Grilled Chicken Caesar Salad</p>
            </div>
            <div class="menu-item">
                <img src="dish4.webp" alt="Dish 12">
                <p>Sushi Platter</p>
            </div>
            <div class="menu-item">
                <img src="dish6.jpg" alt="Dish 12">
                <p>Veggie Burger with Sweet Potato Fries</p>
            </div>
            <div class="menu-item">
                <img src="dish7.jpg" alt="Dish 12">
                <p>Butter Chicken with Naan</p>
            </div>
            <div class="menu-item">
                <img src="dish8.jpg" alt="Dish 12">
                <p>Shrimp Alfredo Pasta</p>
            </div>

            <div class="menu-item">
                <img src="dish12.jpg" alt="Dish 12">
                <p>Tiramisu</p>
            </div>
            <div class="menu-item">
                <img src="dish11.jpg" alt="Dish 12">
                <p>Chocolate Lava Cake</p>
            </div>
            <div class="menu-item">
                <img src="dish10.jpg" alt="Dish 12">
                <p>BBQ Pulled Pork Sandwich</p>
            </div>
            <div class="menu-item">
                <img src="dish21.jpg" alt="Dish 12">
                <p>Mediterranean Falafel Wrap</p>
            </div>
            <div class="menu-item">
                <img src="dish77.jpg" alt="Dish 12">
                <p>Biriyani</p>
            </div>
            
        </div>
    </section>

    <section id="administration" class="container">
        <h2>Administration</h2>
        <div class="admin">
            <div class="admin-card">
                <img src="dhamo.webp" alt="Admin 1">
                <p>Dhamo - Manager</p>
            </div>
            <!-- Repeat for 6 people -->
            <div class="admin-card">
                <img src="matham.jpg" alt="Admin 6">
                <p>RangaRaj - Chef</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Address: 123 Food Street,Saveetha Nagar,Thandalam,Chennai</p>
        <p>Phone: +91 9876543218</p>
        <p>Email: contact@deliciousbites.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Delicious Bites | Designed by Yuvaram</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-14 220332-1.png>)
![alt text](<Screenshot 2024-12-14 220344.png>)
![alt text](<Screenshot 2024-12-14 220355.png>)
![alt text](<Screenshot 2024-12-14 220411.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
