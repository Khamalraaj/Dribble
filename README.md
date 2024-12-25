# Project Responsive Web Design using Bootstrap
## Date:25.12.2024.

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
pharmacy.html
```
<html>
<head>
    <title>ABC Pharmacy Company</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin : 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-image: url('Screenshot 2024-12-17 191121.png');
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
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .menu-item {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
            flex: 1 1 calc(25% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        header {
            background-image: url('download (1).jpeg');
            background-size: cover;
            color: rgba(250, 250, 248, 0.959);
            text-align: center;
            padding: 50px 20px;
        }
        .container {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>“"A pharmacist's job is to ensure that patients receive the right medication, at the right dose, at the right time."”</h1>
        <p>Your another place for Good Care</p>
    </header>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand text-light" href="#">Pharmacy Company</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-light" href="about.html">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-light" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-12">
                <h1>Welcome to ABC Pharmacy Company</h1>
                <p>Your trusted partner in health and wellness. Explore our range of medicines and health services.</p>
            </div>
        </div>
    </div>
    <div align="center">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="btn bg-success text-light" href="register.html">Register Now</a>
            </li>
        </ul>
    </div>

    <section id="menu" class="container">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="download (2).jpeg" alt="Dish 1">
                <p>Medicine</p>
            </div>
            <!-- Repeat for 12 items -->
            <div class="menu-item">
                <img src="download.jpeg" alt="Dish 12">
                <p>Lab Tests</p>
            </div>
            <div class="menu-item">
                <img src="images (1).jpeg" alt="Dish 12">
                <p>Health Care</p>
            </div>
            <div class="menu-item">
                <img src="images.jpeg" alt="Dish 12">
                <p>Health Blogs</p>
            </div>
            
            <div class="menu-item">
                <img src="20offer-banner.jpg" alt="Dish 12">
                <p>Offers</p>
            </div>
            <div class="menu-item">
                <img src="images (2).jpeg" alt="Dish 12">
                <p>Value Store</p>
            </div>            
        </div>
    </section>

    <footer class="bg-light text-center py-3 mt-4">
        <div class="container">
            <p>&copy; 2024 Pharmacy | Designed and Developed by  Khamalraaj S</p>
        </div>
    </footer>

</body>
</html>
```
about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background: linear-gradient(to right, #c81919, #ff7f50); /* Gradient from red to coral */
            color: #fff;
        }
        header {
            width: 100%;
            height: 25vh; /* Full viewport height */
            background: url('e7cc20_91b1a078907d471482c352f860b18dfa~mv2.png') no-repeat center center;
            background-size: cover;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .row {
            width: 100%;
            padding: 20px;
        }
        .bg-light {
            background-color: #f8f9fa;
            color: #000;
        }
        .text-center {
            text-align: center;
        }
        .py-3 {
            padding-top: 1rem;
            padding-bottom: 1rem;
        }
        .mt-4 {
            margin-top: 1.5rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Pharmacy</h1>
    </header>
    <div class="row mt-4" id="about">
        <div class="col-md-12">
            <h2>About Us</h2>
            <p>We are dedicated to providing top-quality pharmaceutical products and exceptional customer service.
                Pharmacy is the science and practice of discovering, producing, preparing, dispensing, reviewing and monitoring medications, aiming to ensure the safe, effective, and affordable use of medicines. It is a miscellaneous science as it links health sciences with pharmaceutical sciences and natural sciences. The professional practice is becoming more clinically oriented as most of the drugs are now manufactured by pharmaceutical industries. Based on the setting, pharmacy practice is either classified as community or institutional pharmacy. Providing direct patient care in the community of institutional pharmacies is considered clinical pharmacy.
                The scope of pharmacy practice includes more traditional roles such as compounding and dispensing of medications. It also includes more modern services related to health care including clinical services, reviewing medications for safety and efficacy, and providing drug information with patient counselling. Pharmacists, therefore, are experts on drug therapy and are the primary health professionals who optimize the use of medication for the benefit of the patients.
                An establishment in which pharmacy (in the first sense) is practiced is called a pharmacy (this term is more common in the United States) or chemists (which is more common in Great Britain, though pharmacy is also used).[citation needed] In the United States and Canada, drugstores commonly sell medicines, as well as miscellaneous items such as confectionery, cosmetics, office supplies, toys, hair care products and magazines, and occasionally refreshments and groceries.
                In its investigation of herbal and chemical ingredients, the work of the apothecary may be regarded as a precursor of the modern sciences of chemistry and pharmacology, prior to the formulation of the scientific method.
            </p>
        </div>
    </div>
    <footer class="bg-light text-center py-3 mt-4">
        <div class="container">
            <p>&copy; 2024 Pharmacy | Designed and Developed by Khamalraaj S</p>
        </div>
    </footer>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: url('download (3).jpeg') no-repeat center center fixed;
            background-size: cover;
            color: #c72626;
            font-size: 18px; /* Increase the font size */
        }
        .container {
            width: 80%;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.8); /* Semi-transparent background */
            padding: 20px;
            border-radius: 10px;
        }
        .row {
            width: 100%;
            padding: 20px;
        }
        .bg-light {
            background-color: #f8f9fa;
            color: #000;
        }
        .text-center {
            text-align: center;
        }
        .py-3 {
            padding-top: 1rem;
            padding-bottom: 1rem;
        }
        .mt-4 {
            margin-top: 1.5rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="row mt-4" id="contact">
            <div class="col-md-12">
                <h2 align="center">Contact Us</h2>
                <p align="center">Email: contact@pharmacycompany.com | Phone: +123 456 7890</p>
            </div>
        </div>
    </div>
    <footer class="bg-light text-center py-3 mt-4">
        <div class="container">
            <p>Designed and Developed by Khamalraaj S</p>
        </div>
    </footer>
</body>
</html>
```
register.html
```
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <script>
            function sfn()
            {
                document.getElementById("result").innerText="Registration Successful";
            }
        </script>
        <div align="center">
            <b>Enter your email </b>
            <input type="email" id="e1"><br>
            <b>Enter your Name </b>
            <input type="text" id="un"><br>
            <b>Enter your co.number</b>
            <input type="number" id="n"><br>
            <div align="center">
                <button class="btn btn-success" onclick="sfn()">Submit</button>
            </div><br>
            <b><p align="center" id="result"></p></b>
        </div>

        <footer class="bg-light text-center py-3 mt-4">
            <div class="container">
                <p>Designed and Developed by Khamalraaj S</p>
            </div>
        </footer>
    </body>

</html>
```




## OUTPUT:
![alt text](<Screenshot 2024-12-25 182147.png>)
![alt text](<Screenshot 2024-12-25 182202.png>)
![alt text](<Screenshot 2024-12-25 182213.png>)
![alt text](<Screenshot 2024-12-25 182313.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
