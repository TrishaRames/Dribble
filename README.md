# Project Responsive Web Design using Bootstrap
## Date: 23-12-2024 

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Showcase</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .hero-section {
            background: linear-gradient(135deg, #6f538d, #40cba4);
            color: rgb(16, 16, 17);
            text-align: center;
            padding: 100px 20px;
        }
        .hero-section h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        .hero-section p {
            font-size: 1.2rem;
        }
        .card:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            transform: translateY(-5px);
            transition: all 0.3s ease-in-out;
        }
        footer
         {
            background-color: #db30eb;
            color: rgb(106, 204, 165);
            padding: 20px;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="container">
            <h1>Creative Designs for the Modern World</h1>
            <p>Browse, Inspire, and Collaborate with Top Designers Globally.</p>
            <a href="#" class="btn btn-light btn-lg mt-3">Get Started</a>
        </div>
    </section>

    <!-- Featured Designs -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Featured Projects</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="design1.png" class="card-img-top" alt="Design Example">
                        <div class="card-body">
                            <h5 class="card-title">Elegant App UI</h5>
                            <p class="card-text">A sleek and modern interface design for mobile applications.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="design2.png" class="card-img-top" alt="Design Example">
                        <div class="card-body">
                            <h5 class="card-title">Artistic Branding</h5>
                            <p class="card-text">Unique branding concepts to elevate your business identity.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="design3.png" class="card-img-top" alt="Design Example">
                        <div class="card-body">
                            <h5 class="card-title">Web Concept</h5>
                            <p class="card-text">Innovative ideas for responsive and interactive websites.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center">
        <p>&copy; 2025 Design by R.Trisha | All Rights Reserved</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (62).png>)
![alt text](<Screenshot (63).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
