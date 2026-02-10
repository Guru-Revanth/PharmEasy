# Ex08 Pharmacy Website using Bootstrap
## Date:

## AIM:
To design a responsive and visually appealing Pharmacy web page using Bootstrap, featuring a navigation bar, categorized product panels with images and descriptions, and a footer, ensuring easy navigation, user accessibility, and professional layout suitable for an online medical or wellness platform.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Link Bootstrap CSS and JavaScript along with jQuery.

### Step 5:
Create a navigation bar at the top of the page.

### Step 6:
Add the brand name “PharmEasy” in the navigation bar.

### Step 7:
Insert menu options for Home, Services (with dropdown), and Contact Us.

### Step 8:
Add options for Sign Up and Login on the right side of the navigation bar.

### Step 9:
Include a search box with a submit button inside the navigation bar.

### Step 10:
Create the main content area centered on the page.

### Step 11:
Divide the page content into two rows.

### Step 12:
In the first row, place three panels for Pain Relief, Vitamins & Supplements, and Baby Care.

### Step 13:
In the second row, place three panels for Skin Care, Fitness Essentials, and Home Health Care.

### Step 14:
Add images inside each panel representing the respective category.

### Step 15:
Provide short descriptions under each image as panel footers.

### Step 16:
Add a footer at the bottom displaying copyright information.

### Step 17:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PharmEasy</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <!-- jQuery & Bootstrap JS -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmEasy</a>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navBar">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navBar">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active"><a class="nav-link" href="#">Home</a></li>

            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown">Services</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">Medicines</a>
                    <a class="dropdown-item" href="#">Health Check</a>
                    <a class="dropdown-item" href="#">Delivery</a>
                </div>
            </li>

            <li class="nav-item"><a class="nav-link" href="#">Contact Us</a></li>
        </ul>

        <!-- Search Box -->
        <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search Medicine">
            <button class="btn btn-light my-2 my-sm-0" type="submit">Search</button>
        </form>

        <!-- Sign Up & Login -->
        <ul class="navbar-nav ml-3">
            <li class="nav-item"><a class="nav-link" href="#">Sign Up</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Login</a></li>
        </ul>
    </div>
</nav>


<!-- Main Content -->
<div class="container mt-4">

    <!-- First Row -->
    <div class="row text-center">

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Pain Relief</h5>
                    <p>Medicines for headache, fever and pain.</p>
                </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Vitamins & Supplements</h5>
                    <p>Boost immunity with supplements.</p>
                </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Baby Care</h5>
                    <p>Baby products for hygiene and health.</p>
                </div>
            </div>
        </div>

    </div>

    <!-- Second Row -->
    <div class="row text-center mt-4">

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Skin Care</h5>
                    <p>Skin creams and personal care products.</p>
                </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Fitness Essentials</h5>
                    <p>Protein and fitness supplements.</p>
                </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" class="card-img-top">
                <div class="card-body">
                    <h5>Home Health Care</h5>
                    <p>Medical devices for home use.</p>
                </div>
            </div>
        </div>

    </div>

</div>


<!-- Footer -->
<footer class="bg-dark text-white text-center p-3 mt-4">
    © 2026 PharmEasy. All Rights Reserved.
</footer>

</body>
</html>

```

## OUTPUT:
<img width="1536" height="1024" alt="pharm-output" src="https://github.com/user-attachments/assets/7e6dd88f-4e46-4bb4-8797-5bedd4047b44" />


## RESULT:
A responsive and visually appealing Pharmacy web page using Bootstrap is designed successfully.
