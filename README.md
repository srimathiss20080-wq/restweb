# Ex.07 Restaurant Website
## Date:15/10/2025

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
rest.html

<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>THE GRILL</title>
        <link rel="stylesheet" href="style1.css">
    </head>
   
        <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="administration.html">Administration</a>

        </div>
    <body style="color: rgb(169, 8, 169);">
        <center>
        <img src="logo.png" style="height: 150px;">
        </center>
        <center>
            <h1 style="color:rgb(169, 0, 169); font-size: 50px;">THE GRILL</h1>
    <table> 
        <center>
        <tr>
            <td><img src="biriyani.png" style="width: 300px; height: 250px;"></td>
            <td><img src="tikka.png" style="width:300px; height: 250px;"></td>
            <td><img src="lolli.png" style="width:300px; height: 250px;"></td>
            <td><img src="noodles.png" style="width:300px; height: 250px;"></td>
            <td><img src="parotta.png" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:rgb(227, 14, 14);"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:rgb(219, 11, 11);"><center>CHICKEN TIKKA</center></h3></td>
            <td><h3 style="color:rgb(250, 10, 10);"><center>CHICKEN LOLLIPOP</center></h3></td>
            <td><h3 style="color:rgb(210, 8, 8);"><center>NOODLES</center></h3></td>
            <td><h3 style="color:rgb(241, 9, 9);"><center>BUN PAROTTA</center></h3></td>
        </tr>
    </table>
    <h2>OUR specialities:
        <h2><center>ARE:</center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>Welcome to our grill restaurant, where every meal is a celebration of fresh, high-quality ingredients and expertly grilled flavors. From sizzling steaks and juicy burgers to flavorful vegetarian dishes, our menu offers something for everyone. We take pride in providing a customizable dining experience, allowing you to create your perfect meal. Whether you're enjoying a casual lunch, a family gathering, or a special celebration, our cozy and inviting atmosphere makes every occasion memorable. With weekly specials, friendly service, and a commitment to quality, we promise an unforgettable dining experience. Come visit us and taste the difference today!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>THE BEST PLACE TO EXPERIENCE THE REAL TASTE!</center></h4></td>
        </tr>
         <footer align="center" id="copywrite">
                Designed and developed by Srimathi S(25017525) &copy 2025
            </footer>
    </body>        
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - THE GRILL</title>
  <link rel="stylesheet" href="style2.css">
</head>
<body>
  <header class="header">
    <h1>Tasty Bites</h1>
    <nav>
      <ul>
        <li><a href="rest.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Our Menu</h2>
    <ul>
        <li>
            <img src="biriyani.png" alt="Biriyani" width="90" height="90">
            Biriyani - $52
        </li>
        <li>
            <img src="burger.png" alt="KING SIZE BURGER" width="90" height="90">
            Burger - $25
        </li>
        <li>
            <img src="choco.png" alt="choco" width="90" height="90">
            Choco lava cake - $30
        </li>
        <li>
            <img src="pizza.png" alt="pizza" width="90" height="90">
           Family Pizza - $73
        </li>
        <li>
            <img src="salad.png" alt="Caesar Salad" width="90" height="90">
            Caesar Salad - $8
        </li>
        <li>
            <img src="mutton.png" alt="Mutton Gravy" width="90" height="90">
            Mutton Gravy - $10
        </li>
        <li>
            <img src="noodles.png" alt="Noodles" width="90" height="90">
            
            Raman Noodles- $7
        </li>
        <li>
            <img src="french.png" alt="French Fries" width="90" height="90">
            French Fries - $4
        </li>
        <li>
            <img src="salmon.png" alt="salmon" width="90" height="90">
            Salmon Fish - $9
        </li>
        <li>
            <img src="tikka.png" alt="tikka" width="90" height="90">
            Chicken Tikka - $15
        </li>
        <li>
            <img src="parotta.png" alt="parotta" width="90" height="90">
            Bun Parotta - $8
        </li>
        <li>
            <img src="lolli.png" alt="loli" width="90" height="90">
            Chicken Lillipop - $20
        </li>
        
    </ul>
</section>
      <footer align="center" id="copywrite">
                Designed and developed by Srimathi S(25017525) &copy 2025
            </footer>
      </body>
      </html>
contact.html
<html>
    <head>
        <title> CONTACT </title>
         <link rel="stylesheet" href="style3.css">
    </head>
    
    <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="administration.html">Administration</a>

        </div>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(24, 22, 24)">contact<h1>
            <h4  style="color:rgb(26, 19, 24)">+91 9080702009 <br> |The Grill restuarent@gmail.com</h4>
            <P  style="color:rgb(12, 11, 12)">Address: no.39 Near SEC ,Thandalam,Kanchipuram <br>
                <br> contact us to place the order<br>
            <hr> THE PLACE WHERE YOU FIND THE REAL TASTE
            </P>
            <footer align="center" id="copywrite">
                Designed and developed by Srimathi S(25017525) &copy 2025
            </footer>
         </section> 
    </center>
    </body>
</html> 

administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE GRIILL - Administration</title>
 <link rel="stylesheet" href="style4.css">
</head>
<body>    

<header>
        <h1>THE GRILL</h1>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="administration.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="mypic.jpg" alt="CEO">
                <div class="admin-details">
                    <h3>Srimathi S</h3>
                    <p>CEO of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="atharva.png" alt="Manager">
                <div class="admin-details">
                    <h3>Atharva</h3>
                    <p>Manager of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="samantha.png" alt="Master Chef">
                <div class="admin-details">
                    <h3>Samantha</h3>
                    <p>Master Chef of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="kashmira.png" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>kashmira</h3>
                    <p>Assistant Managing Director of THE GRILL</p>
                </div>
            </div>
        </div>
    </div>

   
 <footer align="center" id="copywrite">
                Designed and developed by Srimathi S(25017525) &copy 2025
            </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-10-15 153712.png>)
![alt text](<Screenshot 2025-10-15 153724.png>)
![alt text](<Screenshot 2025-10-15 153738.png>)
![alt text](<Screenshot 2025-10-15 153749.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
