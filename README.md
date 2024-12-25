# Ex.07 Restaurant Website
## Date:25.12.2024

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHAT WITH BITE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="banner">
        <h1>Welcome to Chat With Bite</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="intro">
        <h2>Have a bite ,Savor the Delight</h2>
        <p>Flavors you'll Crave,Moments you'll Savor</p>
    </section>

    <footer>
        <p>© Kabira A (24900476)</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header.banner {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header.banner h1 {
            margin: 0;
        }

        header.banner nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        header.banner nav ul li {
            display: inline;
        }

        header.banner nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header.banner nav ul li a:hover {
            color: #ff6347;
        }

        .menu {
            padding: 20px;
            text-align: center;
        }

        .menu h2 {
            font-size: 2em;
            color: #222;
            margin-bottom: 20px;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 0;
        }

        .item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 15px;
        }

        .item img {
            max-width: 100%;
            height: auto;
            border-bottom: 2px solid #f4f4f4;
        }

        .item h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .item p {
            font-size: 1.2em;
            color: #555;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h2>Our Delicious Menu</h2>
        <div class="menu-items">
            <div class="item">
                <img src="AMBUR MUTTON BIRYANI.jpg" alt="Ambur biriyani">
                <h3>Ambur Biriyani</h3>
                <p>Rs.300</p>
            </div>

            <div class="item">
                <img src="Chicken Chettinad Recipe.jpg" alt="chettinad chicken">
                <h3>Chettinad Chicken</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="Chilli Chicken.jpg" alt="Chilli Chicken">
                <h3>Chilli chicken</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="kerala fish fry.jpg" alt="fish fry">
                <h3>Fish Fry </h3>
                <p>Rs. 400</p>
            </div>

            <div class="item">
                <img src="paneer kabab.jpg" alt="kabab">
                <h3>Kabab</h3>
                <p>Rs. 400</p>
            </div>

            <div class="item">
                <img src="Shahi Paneer.jpg" alt="shahi paneer">
                <h3>Shahi panner</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="paneer dosa.jpg" alt="paneer dosa">
                <h3>Paneer Dosa</h3>
                <p>Rs. 200</p>
            </div>

            <div class="item">
                <img src="chicken kolamu.jpg" alt="chicken kolambu">
                <h3>Chicken Kolambu</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="spicy chicken.jpg" alt="spicy chicken">
                <h3>Spicy Chicken</h3>
                <p>Rs. 390</p>
            </div>

            <div class="item">
                <img src="pasta.jpg" alt="pasta">
                <h3>Rasamalai</h3>
                <p>Rs. 400</p>
            </div>

            


           
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Kabira A</p>
    </footer>
</body>
</html>


administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .team {
            padding: 40px 20px;
            text-align: center;
        }

        .team h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .team-members {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .member {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 200px;
            padding: 20px;
            text-align: center;
        }

        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .member h3, .member h4, .member h5, .member h6 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #333;
        }

        .member p {
            margin: 0;
            font-size: 0.9em;
            color: #666;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner"> 
        <h1>Our Team</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="team">        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="kabira clg photo.png" alt="Kabira">
                <h3>Kabira A</h3>
                <p>Owner</p>
            </div>
            <div class="member">
                <img src="11.jpg" alt="rahul">
                <h3>Rahul</h3>
                <p>Management Team</p>
            </div>
            <div class="member">
                <img src="12.jpg" alt="shahin">
                <h3>Shahin</h3>
                <p>Barista</p>
            </div>
            <div class="member">
                <img src="13.jpg" alt="kausalya">
                <h3>kausalya</h3>
                <p>accountant</p>
            </div>
            <div class="member">
                <img src="14.jpg" alt="sami">
                <h3>sami</h3>
                <p>chef</p>
            </div>
            <div class="member">
                <img src="15.jpg" alt="radhika">
                <h3>Radhika</h3>
                <p>manager</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Kabira A</p>
    </footer>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #2d1eca;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .contact {
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .contact p {
            font-size: 1.2em;
            margin: 10px 0;
            color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="adminstration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact us">
        <h2>Get in Touch</h2>
        <p><strong>Address:</strong>Iyyappa nagar nanganallur ,chennai-600061</p>
        <p><strong>Phone:</strong> 5756974124</p>
        <p><strong>Email:</strong> chatwithbite@gmail.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Kabira A</p>
    </footer>
</body>
</html>


style.css


/* General Reset */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-image: url('table.jpg'); /* Replace with your image file path */
    background-size: cover; /* Ensures the image covers the entire screen */
    background-position: center; /* Centers the image */
    background-attachment: fixed; /* Makes the background fixed on scroll */
    background-repeat: no-repeat; /* Prevents repeating of the image */
}

/* Header Styling */
header.banner {
    background-color: #222;
    color: white;
    padding: 20px 10px;
    text-align: center;
}

header.banner h1 {
    margin: 0;
    font-size: 2.5em;
    letter-spacing: 2px;
}

header.banner nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

header.banner nav ul li {
    display: inline;
}

header.banner nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
    transition: color 0.3s;
}

header.banner nav ul li a:hover {
    color: #ff6347;
}

/* Intro Section */
section.intro {
    padding: 40px 20px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin: 20px;
    border-radius: 10px;
}

section.intro h2 {
    font-size: 2em;
    color: #222;
    margin-bottom: 10px;
}

section.intro p {
    font-size: 1.1em;
    color: #555;
    margin: 0;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 10px 0;
    background-color: #222;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

/* Responsive Design */
@media (max-width: 768px) {
    header.banner nav ul {
        flex-direction: column;
        gap: 10px;
    }

    section.intro {
        margin: 10px;}
}


```

## OUTPUT:

![alt text](<Screenshot 2024-12-25 213416.png>)
![alt text](<Screenshot 2024-12-25 213543.png>)
![alt text](<Screenshot 2024-12-25 213604.png>)
![alt text](<Screenshot 2024-12-25 213439.png>)
![alt text](<Screenshot 2024-12-25 213507.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
