# Ex.06 Restaurant Website
## Date:23-12-2025

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
contact.html


 
<html>
<head>
  
  <title> MIDNIGHT MASALA - Contact Us</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Contact Us</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="a">
    <div class="b">
      <h2>Address:</h2>
      <p>MIDNIGHT MASALA<br>
         NH hightway road 600112</p>
    </div>
    <div class="b">
      <h2>Phone:</h2>
      <p>044 0044 </p>
    </div>
    <div class="b">
      <h2>Email:</h2>
      <p>mid@gmail.com</p>
    </div>
  </section>

  <footer><p>CREATED BY 
                    ROHITH(2501770)</p></footer>
</body>
</html>

index.html


<html>

<head>
  >
  <title>MIDNIGHT MASALA - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    
    <h1> MIDNIGHT MASALA</h1>
    <h5>“Where cravings come alive after dark”</h5>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="len">
    
   
  </section>

  <section class="a">

  <div class="b">
    <h2>Menu</h2>
    <img src="menu.jpeg" alt="Menu">
    <p class="menu-quote">"New dishes hotter than your ex"  </p>
    <a href="menu.html">See our menu</a>
  </div>

  <div class="b">
    <h2>Book a Table</h2>
    <img src="book table.jpeg" alt="Book a Table">
    <p>Reserve your spot .</p>
    <a href="contact.html">Book now</a>
  </div>

  <div class="b">
    <h2>SHOP TIMING</h2>
    <img src="shop timing.jpeg" alt="Shop Timing">
    <p>
      MON – SUN <br>
      9:00 PM – 6:00 AM
    </p>
  </div>

</section>


admin.html



<html>
<head>
  
  <title>Administration</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1> Administration Team</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="a">
    <div class="b"><img src="r.jpeg" ><h2> ROHITH</h2><p>CEO</p></div>
    <div class="b"><img src="Screenshot 2025-12-18 110446.png"><h2>ABE OYE HAKLE</h2><p>Head Chef</p></div>
    <div class="b"><img src="s.jpeg"><h2>SURAJ PATEL RAJ</h2><p>Assistant Chef</p></div>
    <div class="b"><img src=" ag.jpg "><h2>ANDREW GARFIELD</h2><p>HR</p></div>
    <div class="b"><img src=" be.jpg "><h2>BILLIE EILISH</h2><p>Finance</p></div>
    <div class="b"><img src=" p.jpeg "><h2>POPCORN </h2><p>Marketing</p></div>
  </section>

  <footer><p>Created by Rohith</p></footer>
</body>
</html>


menu.html



<html>
<head>
  <meta charset="UTF-8">
  <title>Menu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1 style="color: chartreuse;">Menu</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section class="a">
    <div class="b"><h2>BIRIYANI</h2><img src="biriyani.JPG"></div>
    <div class="b"><h2>BUTTER CHICKEN</h2><img src="butter chiken.jpg"></div>
    <div class="b"><h2>SALMON RICEBOWL</h2><img src="salmon rice bowl.jpg"></div>
    <div class="b"><h2>STRATA</h2><img src="strata.webp"></div>
    <div class="b"><h2>SPAGHETTI</h2><img src="spaghetti-vegetaspaghetti.jpg"></div>
    <div class="b"><h2>RAMEN</h2><img src="-Spinach-Ramen-1.jpg"></div>
    <div class="b"><h2>GRILLED TURKEY</h2><img src="-grilled-turkey-.avif"></div>
    <div class="b"><h2>KABOBS</h2><img src="kabobs.jpg"></div>
    <div class="b"><h2>MALAI KOFTA</h2><img src="malai kofta.jpg"></div>
    <div class="b"><h2>MILK SHAKES</h2><img src="milkshakes.jpg"></div>
    <div class="b"><h2>LAVA CAKES</h2><img src="choco lava.jpg"></div>
    
  </section>

  <footer><p>Rohith G (25018770)</p></footer>
</body>
</html>
style.css

body {
  margin: 0;
 font-style: calc();
  background:
    linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url("bg.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
  
}

header {
  text-align: center;
  padding: 10px; 
  color: chartreuse;
  font-size: larger;
}


header img {
  width: 100px;
}
p {
  background-color: blueviolet;
  color: #decfcf;
  text-align: center;
  text-size-adjust: inherit;
}

nav {
  background-color: blueviolet;
  display: flex;
  justify-content: center;
  margin-top: 5px;
  margin-bottom: 10px;
}

nav a {
  color: rgb(0, 0, 0);
  text-decoration: none;
  padding: 14px 25px;
  font-weight: bold;
}

nav a:hover {
  background-color: #e67e22;
}

.len {
  background: url(" Screenshot 2025-10-03 194325.png ") no-repeat center center/cover;
  padding: 80px 20px;
  color: rgb(235, 247, 7);
  text-align: center;
  font-size: 1.2em;
  position: relative;
}

.len h1 {
  color: #e67e22;
  font-size: 2.5em;
  margin-bottom: 10px;
}


.a {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  padding: 15px;

  position: relative;
 
}



.b {
  background-color: goldenrod;
  border-radius: 10px;

  width: 110px;           /* ⭐ CHANGE THIS NUMBER */
  
  padding: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  text-align: center;
}


.a img {
  height: 80%;
  width: 100%;
  border-radius: 10px;
}

footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
div.b a {
  background-color: orange;
  border-radius: 30px;
}

.b img {
  width: 100%;
  height: 140px;        
  object-fit: cover;
  border-radius: 10px;
}




```

## OUTPUT:
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
