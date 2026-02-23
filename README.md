# Ex.06 Restaurant Website
## Date:23/2/2026
## Name:yashvanth k
## Reg no:212224245003

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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Flame & Fork - Home</title>
<link rel="stylesheet" href="css/style.css">

</head>
<body>
  <header>
    <div class="logo">🔥 Flame & Fork</div>
    <nav>
      <a href="home.html">Home</a>
      <a href="product.html">Menu</a>
      <a href="people.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <h1>30% Off This Weekend</h1>
    <p>Enjoy delicious meals with fresh ingredients and exciting flavors at discounted prices.</p>
  </section>

  <section class="cards">
    <div class="card">
      <h2>Our New Menu</h2>
      <p>Discover chef specials with seasonal produce.</p>
    </div>
    <div class="card">
      <h2>Book a Table</h2>
      <p>Reserve online or by phone for family and friends.</p>
    </div>
    <div class="card">
      <h2>Opening Hours</h2>
      <p>Mon–Sun: 11 AM – 11 PM</p>
    </div>
  </section>

  <footer>
    © 2025 Flame & Fork | Designed by ABHISHEK  
  </footer>
</body>
</html>

administration.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Flame & Fork - Administration</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/people.css">
</head>
<body>
<header>
  <div class="logo">🔥 Flame & Fork</div>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Menu</a>
    <a href="people.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
</header>

<main>
  <h1>Our Team</h1>
  <div class="team">
  <div class="member"><img src="/static/images/p1.jpg"><p>Arjun - Head Chef</p></div>
  <div class="member"><img src="/static/images/p2.jpg"><p>Sneha - Manager</p></div>
  <div class="member"><img src="/static/images/p3.jpg"><p>Kiran - Sous Chef</p></div>
  <div class="member"><img src="/static/images/p4.jpg"><p>Aisha - Pastry Chef</p></div>
  <div class="member"><img src="/static/images/p5.jpg"><p>Ravi - Wait Staff</p></div>
</div>

</main>

<footer>
  © 2025 Flame & Fork | Designed by ABHISHEK
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Flame & Fork - Contact Us</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/contact.css">
</head>
<body>
<header>
  <div class="logo">🔥 Flame & Fork</div>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Menu</a>
    <a href="people.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
</header>

<main>
  <section class="contact-banner">
    <h1>Get in Touch</h1>
    <p>We’d love to hear from you! Send us a message or visit us in person.</p>
  </section>

  <section class="contact-form-section">
    <form class="contact-form" action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="you@example.com" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" placeholder="Write your message here..." required></textarea>

      <button type="submit">Send Message</button>
    </form>

    <div class="contact-info">
      <h2>Visit Us</h2>
      <p>123 Flavor Street, Food City, FC 45678</p>
      <p>Email: info@flameandfork.com</p>
      <p>Phone: +1 (234) 567-8901</p>
    </div>
  </section>
</main>

<footer>
  © 2025 Flame & Fork | Designed by ABHISHEK
</footer>
</body>
</html>

styles.css

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fffaf0;
}

header {
  background: #b22222;
  color: white;
  display: flex;
  justify-content: space-between;
  padding: 15px 30px;
}

header .logo {
  font-weight: bold;
  font-size: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 15px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.banner {
  background: url('/static/images/mybanner.jpg') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 100px 20px;
  min-height: 200px; /* ensures visible height */
}


.banner h1 {
  font-size: 36px;
}

.cards {
  display: flex;
  justify-content: space-around;
  padding: 30px;
}

.card {
  background: #fff;
  padding: 20px;
  border-radius: 10px;
  width: 30%;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

footer {
  text-align: center;
  background: #111;
  color: #ddd;
  padding: 15px;
}

contact.css

main {
  padding: 20px;
}

p {
  font-size: 18px;
  margin: 10px 0;
}

administration.css

.team {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.member {
  text-align: center;
  width: 150px;
}

.member img {
  border-radius: 50%;
  width: 100px;
  height: 100px;
}

```

## OUTPUT:
<img width="828" height="914" alt="Screenshot 2026-02-23 114826" src="https://github.com/user-attachments/assets/12bf31eb-4337-4afe-b6a9-8c96c481e95e" />
<img width="825" height="236" alt="Screenshot 2026-02-23 114851" src="https://github.com/user-attachments/assets/321e6dee-fb4e-4d0e-ae57-c4c3792a8d12" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
