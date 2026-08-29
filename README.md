# hello-kittys-.-bakery-
This code creates a Hello Kitty-themed bakery website using HTML, CSS, and JavaScript. HTML adds the bakery items, drinks, images, prices, navigation, and contact section. CSS creates the pink border, dark-blue text, cards, buttons, and hover effects. JavaScript makes the buttons interactive, including ordering, greetings, and returning to the top.
<!DOCTYPE html>

<html>
<head>
    <title>Hello Kitty's Bakery</title>
    <link rel="stylesheet" href="style.css">
</head>

<body id="top">

```
<!-- Navigation Bar -->
<nav>
    🎀 <a href="#desserts">Desserts</a>
    <a href="#snacks">Snacks</a>
    <a href="#drinks">Drinks</a>
    <a href="#contact">Contact</a> 🎀
</nav>

<!-- Hello Kitty Stickers -->
<div class="stickers">
    🎀 🐱 🎀
</div>

<h1 style="text-align: center;">Hello Kitty's Bakery</h1>

<p class="welcome">
    🎀 Welcome to our cute little bakery! 🎀
</p>

<div class="stickers">
    💕 🧁 🍰 🍩 💕
</div>

<h2 id="desserts">Desserts</h2>

<ul>
    <li>
        Chocolate Cake
        <span class="price">$6.00</span>
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=100" alt="Chocolate Cake">
    </li>

    <li>
        Cupcakes
        <span class="price">$3.00</span>
        <img src="https://images.unsplash.com/photo-1587668178277-295251f900ce?w=100" alt="Cupcakes">
    </li>

    <li>
        Donuts
        <span class="price">$2.50</span>
        <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=100" alt="Donuts">
    </li>

    <li>
        Cookies
        <span class="price">$2.00</span>
        <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?w=100" alt="Cookies">
    </li>
</ul>


<h2 id="snacks">Snacks</h2>

<ul>
    <li>
        French Fries
        <span class="price">$3.50</span>
        <img src="https://images.unsplash.com/photo-1573080496219-bb080dd4f877?w=100" alt="French Fries">
    </li>

    <li>
        Chicken Nuggets
        <span class="price">$5.00</span>
        <img src="https://images.unsplash.com/photo-1562967914-608f82629710?w=100" alt="Chicken Nuggets">
    </li>

    <li>
        Pizza
        <span class="price">$7.00</span>
        <img src="https://images.unsplash.com/photo-1574071318508-1cdbab80d002?w=100" alt="Pizza">
    </li>

    <li>
        Sandwiches
        <span class="price">$5.50</span>
        <img src="https://images.unsplash.com/photo-1528735602780-2552fd46c7af?w=100" alt="Sandwiches">
    </li>
</ul>


<!-- Drinks -->
<h2 id="drinks">Drinks 🎀</h2>

<ul>
    <li>
        Strawberry Milk
        <span class="price">$4.00</span>
        <img src="https://images.unsplash.com/photo-1553787499-6f8e3a0c9b1e?w=100" alt="Strawberry Milk">
    </li>

    <li>
        Hot Chocolate
        <span class="price">$4.50</span>
        <img src="https://images.unsplash.com/photo-1542990253-0d0f5be5f0ed?w=100" alt="Hot Chocolate">
    </li>

    <li>
        Pink Lemonade
        <span class="price">$3.00</span>
        <img src="https://images.unsplash.com/photo-1621263764928-df1444c5e859?w=100" alt="Pink Lemonade">
    </li>

    <li>
        Iced Tea
        <span class="price">$3.50</span>
        <img src="https://images.unsplash.com/photo-1556679343-c7306c1976bc?w=100" alt="Iced Tea">
    </li>
</ul>


<!-- Dessert and Snack Cards -->
<h2>Bakery Favorites 💕</h2>

<div class="cards">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=300" alt="Chocolate Cake">
        <h3>Chocolate Cake 🍰</h3>
        <p>$6.00</p>
        <button onclick="orderItem('Chocolate Cake')">Order 🎀</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1587668178277-295251f900ce?w=300" alt="Cupcakes">
        <h3>Cupcakes 🧁</h3>
        <p>$3.00</p>
        <button onclick="orderItem('Cupcakes')">Order 🎀</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=300" alt="Donuts">
        <h3>Donuts 🍩</h3>
        <p>$2.50</p>
        <button onclick="orderItem('Donuts')">Order 🎀</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?w=300" alt="Cookies">
        <h3>Cookies 🍪</h3>
        <p>$2.00</p>
        <button onclick="orderItem('Cookies')">Order 🎀</button>
    </div>

</div>


<!-- More Hello Kitty Decorations -->
<div class="stickers">
    🎀 🐱 💕 🧁 💕 🐱 🎀
</div>


<!-- Contact Section -->
<div class="contact" id="contact">

    <h2>Contact Us 📞</h2>

    <p>📞 Phone: 123-456-7890</p>
    <p>📧 Email: hello@hellokittybakery.com</p>
    <p>📍 Location: Sweet Street Bakery</p>

    <button onclick="sayHello()">
        Say Hello Kitty! 💕
    </button>

</div>


<!-- Back to Top Button -->
<div class="top-button">

    <button onclick="goToTop()">
        🎀 Back to Top 🎀
    </button>

</div>


<footer>
    🎀 Made with love at Hello Kitty's Bakery 🎀
</footer>


<script src="script.js"></script>
```

</body>
</html>

