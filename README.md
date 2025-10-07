# Ex.07 Restaurant Website
## Date:07/10/2025

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - MADARA RESTAURANTS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1> MADARA RESTAURANTS</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="banner">
    <img src="hotel.png"Delicious Food ">
  </section>



  <section class="content">
    <h2>Welcome!</h2>
    <p>where comfort meets charm, Stay with us,feel at home wherever you roam</p>
  </section>

  

  <footer>
    <p>&copy; 2025. Designed by VISHWA S</p>
  </footer>
</body>
</html>

administration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - FRIENDS DABHA</title>
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
      <img src="saudhu.png" alt="Admin 1">
      <h3>MOHAMED SAUDHU</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="murga.png" alt="Admin 2">
      <h3>MURGA PERUMAL</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="hari.png" alt="Admin 3">
      <h3>MHARI PRASANTH</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="arun.png" alt="Admin 4">
      <h3>ARUN</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="balaji.png" alt="Admin 5">
      <h3>BALAJI </h3>
      <p>Assistant chef</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by VISHWA S</p>
  </footer>
</body>
</html>

menu.html
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - MADARA RESTAURANTS</title>
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
    <!-- Repeat for 06 items -->
    <div class="menu-item">
      <img src="parotta.png" alt="kothu parotta">
      <h3>parotta</h3>
      <p>parotta with the taste of madurai</p>
    </div>
    <div class="menu-item">
      <img src="dosa.png" alt="nice dosa">
      <h3>dosa </h3>
      <p>dosa with sambar.</p>
    </div>
    <div class="menu-item">
      <img src="vadapav.png" alt="vadapav">
      <h3>Creamy vadapav</h3>
      <p>Sooo Cheese.. with salat.</p>
    </div>
    <div class="menu-item">
      <img src="chicken rice.png" alt="chicken">
      <h3>chicken with tomato sause</h3>
      <p>chicken which melts in your mouth</p>
    </div>
    <div class="menu-item">
      <img src="variety rice.png" alt="rice">
      <h3>yummy variety rice</h3>
      <p>Sweetness with the taste of variety of rice.</p>
    </div>
    <div class="menu-item">
      <img src="briyani.png" alt="kuska">
      <h3>feel the taste with creamy</h3>
      <p>enjoy with briyani</p>
    </div>
    
  </section>

  <footer>
    <p>&copy; 2025. Designed by VISHWA S</p>
  </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - MADARA RESTAURANTS</title>
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
    <p>📍 <strong>Address:</strong> no /121  tambaram, Chennai , Tamil Nadu</p>
    <p>📞 <strong>Phone:</strong> (123) 143-536-4568</p>
    <p>✉ <strong>Email:</strong> madararestaurants@gmail.com</p>
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
    <p>&copy; 2025. Designed by  VISHWA S</p>
  </footer>

</body>
</html>

```

## OUTPUT:
![alt text](<vishwa/restapp/static/Screenshot (27).png>)
![alt text](<vishwa/restapp/static/Screenshot (28).png>)
![alt text](<vishwa/restapp/static/Screenshot (29).png>)
![alt text](<vishwa/restapp/static/Screenshot (30).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
