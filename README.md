# Ex.07 Restaurant Website
## Date:

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Royal Feast Restaurant</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #1a1a1a;
      color: #fff;
    }
    header {
      background-image: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092');
      background-size: cover;
      background-position: center;
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: gold;
      text-shadow: 2px 2px 5px #000;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 4rem;
      margin: 0;
    }
    header p {
      font-size: 1.5rem;
      margin-top: 0.5rem;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      text-align: center;
      color: gold;
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      margin-bottom: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background-color: #2a2a2a;
      padding: 1.5rem;
      border-radius: 10px;
      border: 1px solid gold;
    }
    .card h3 {
      color: gold;
      font-family: 'Playfair Display', serif;
      font-size: 1.75rem;
      margin-bottom: 0.5rem;
    }
    .card p {
      color: #ccc;
      font-size: 1rem;
    }
    .card img {
      width: 100%;
      height: 240px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    

    footer {
      background-color: #000;
      text-align: center;
      padding: 1rem;
      color: #aaa;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Royal Feast</h1>
    <p>Experience the Taste of Majesty</p>
  </header>

  <section>
    <h2>Our Signature Dishes</h2>
    <div class="grid">
      <div class="card">
        <img src="Cheese balls.jpg" alt="CHEESE BALLS">
        <h3>CHEESE BALLS</h3>
      </div>
      <div class="card">
        <img src="pasta.jpg" alt="WHITE PASTA">
        <h3>WHITE PASTA</h3>
      </div>
      <div class="card">
        <img src="Noodles.jpg" alt="NOODLES">
        <h3>NOODLES</h3>
      </div>
      <div class="card">
        <img src="Pizza.jpg" alt="PIZZA">
        <h3>PIZZA</h3>
      </div>
      <div class="card">
        <img src="Veg Machurian.jpg" alt="VEG MANCHURIAN">
        <h3>VEG MANCHURIAN</h3>
      </div>
      <div class="card">
        <img src="fries.jpg" alt="FRENCH FRIES">
        <h3>FRENCH FRIES</h3>
      </div>
      <div class="card">
        <img src="Friedrice.jpg" alt="VEG FRIED RICE">
        <h3>VEG FRIED RICE</h3>
      </div>
      <div class="card">
        <img src="soup.jpg" alt="TOMATO SOUP">
        <h3>TOMATO SOUP</h3>
      </div>
    </div>
  </section>

  <section>
    <h2>Our Services</h2>
    <div class="grid">
      <div class="card">
        <h3>Fine Dining</h3>
        <p>Luxurious dining hall designed to offer a royal ambience and experience.</p>
      </div>
      <div class="card">
        <h3>Catering Services</h3>
        <p>Elegant food presentation and royal menus for weddings and events.</p>
      </div>
      <div class="card">
        <h3>Home Delivery</h3>
        <p>Get royal meals delivered to your doorstep, fresh and fast.</p>
      </div>
    </div>
  </section>
  
  <section>
    <h2>Book Now</h2>
    <form>
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name" required><br><br>

      <label for="email">Email Address:</label><br>
      <input type="email" id="email" name="email" required><br><br>

      <label for="phone">Phone Number:</label><br>
      <input type="tel" id="phone" name="phone" required><br><br>

      <label for="guests">Number of Guests:</label><br>
      <input type="number" id="guests" name="guests" required min="1"><br><br>

      <button type="submit">Book Now</button>
    </form>
  </section>


  <footer>
    <p>&copy; 2025 Royal Feast Restaurant | All Rights Reserved</p>
  </footer>

</body>
</html>

```

## OUTPUT:
<img width="1887" height="966" alt="image" src="https://github.com/user-attachments/assets/17dadc73-275f-4b1e-86e6-07336d16386d" />
<img width="1803" height="922" alt="image" src="https://github.com/user-attachments/assets/bb642b9a-dbcb-4d96-ad5f-f52ae570be9a" />
<img width="1802" height="969" alt="image" src="https://github.com/user-attachments/assets/0a4daf8c-a4aa-4602-88f7-93b7d8af2d34" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
