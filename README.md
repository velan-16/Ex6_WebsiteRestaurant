# Ex.06 Restaurant Website
## Date:19-12-2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Velan's kitchen</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:Arial,Helvetica,sans-serif}
    body{background:#f7f7f7;color:#333}
    header{background:#111;color:#fff;padding:20px 40px;display:flex;justify-content:space-between;align-items:center}
    header h1{font-size:28px}
    nav a{color:#fff;margin:0 15px;text-decoration:none;font-weight:bold}
    nav a:hover{color:#ff9800}

    .hero{height:80vh;background:url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') center/cover no-repeat;display:flex;align-items:center;justify-content:center;text-align:center;color:#fff}
    .hero h2{font-size:48px;background:rgba(0,0,0,0.6);padding:20px;border-radius:10px}

    section{padding:60px 40px}
    .title{text-align:center;margin-bottom:40px}
    .title h2{font-size:36px;color:#111}

    .about{display:grid;grid-template-columns:1fr 1fr;gap:30px;align-items:center}
    .about img{width:100%;border-radius:15px}

    .menu{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}
    .menu-card{background:#fff;border-radius:15px;overflow:hidden;box-shadow:0 5px 15px rgba(0,0,0,0.1)}
    .menu-card img{width:100%;height:200px;object-fit:cover}
    .menu-card div{padding:15px}

    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
    .gallery img{width:100%;border-radius:15px}

    .contact{background:#111;color:#fff;text-align:center}
    .contact p{margin:10px 0}

    footer{background:#000;color:#aaa;text-align:center;padding:15px}

    @media(max-width:768px){
      .about{grid-template-columns:1fr}
      .hero h2{font-size:32px}
    }
  </style>
</head>
<body>

<header>
  <h1>Velan's kitchen</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero" id="home">
  <h2>Delicious Food, Cozy Place</h2>
</div>

<section id="about">
  <div class="title"><h2>About Us</h2></div>
  <div class="about">
    <p>
      Welcome to Velan's kitchen! We serve freshly prepared dishes using
      high-quality ingredients. Our chefs blend traditional flavors with modern
      cooking styles to give you a memorable dining experience.
    </p>
    <img src="https://images.unsplash.com/photo-1528605248644-14dd04022da1" alt="Restaurant Interior" />
  </div>
</section>

<section id="menu">
  <div class="title"><h2>Our Menu</h2></div>
  <div class="menu">
    <div class="menu-card">
      <img src="https://images.unsplash.com/photo-1604908177225-6c6fca31b3c5" />
      <div><h3>Grilled Chicken</h3><p>₹280</p></div>
    </div>
    <div class="menu-card">
      <img src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe" />
      <div><h3>Veg Salad</h3><p>₹180</p></div>
    </div>
    <div class="menu-card">
      <img src="https://images.unsplash.com/photo-1598515214146-dab39da1243d" />
      <div><h3>Cheese Pizza</h3><p>₹320</p></div>
    </div>
    <div class="menu-card">
      <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b" />
      <div><h3>Dessert</h3><p>₹150</p></div>
    </div>
  </div>
</section>

<section id="gallery">
  <div class="title"><h2>Gallery</h2></div>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5" />
    <img src="https://images.unsplash.com/photo-1525351484163-7529414344d8" />
    <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" />
    <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4" />
  </div>
</section>

<section id="contact" class="contact">
  <div class="title"><h2>Contact Us</h2></div>
  <p>📍 Chennai, India</p>
  <p>📞 +91 8220670380</p>
  <p>✉ Velan's kitchen@email.com</p>
  <p>Sugavelan S</p>
  <p>25005466</p>
</section>

<footer>
  <p>© 2025 JuJu Restaurant. All Rights Reserved.</p>
</footer>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 113459.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
