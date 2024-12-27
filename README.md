# Project Responsive Web Design using Bootstrap
## Date:
27-12-24
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
    <title>Creative Showcase</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg" style="background-color: #563d7c;">
        <div class="container">
            <a class="navbar-brand text-white" href="#">CreativeHub</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#team">Team</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="text-center text-white" style="background: linear-gradient(45deg, #ff6b6b, #f06595); padding: 60px 0;">
        <div class="container">
            <h1 class="display-3">Welcome to CreativeHub</h1>
            <p class="lead">Your gateway to stunning designs and innovations</p>
            <a href="#portfolio" class="btn btn-light btn-lg">Explore Now</a>
        </div>
    </header>

    <div id="services" class="container my-5">
        <h2 class="text-center mb-4">Our Services</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">Graphic Design</h5>
                        <p class="card-text">Creative and innovative graphic design solutions for all your needs.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">Web Development</h5>
                        <p class="card-text">Modern, responsive, and user-friendly websites built to impress.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">Branding</h5>
                        <p class="card-text">Helping you create a powerful and memorable brand identity.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="portfolio" class="text-center text-white py-5" style="background-color: #007bff;">
        <div class="container">
            <h2 class="mb-4">Our Portfolio</h2>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card border-0">
                        <img src="C:\Users\admin\simplewebserver\Dribble\Eren Yeager _ Freedom _ Attack on Titan _ Wallpaper 4k.jpg" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="C:\Users\admin\simplewebserver\Dribble\eb5f69bc-13f5-4844-9e1f-f27565c6e207.jpg" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="C:\Users\admin\simplewebserver\Dribble\I grow_  monkey D Luffy .  pirate King...لوفي .ملك القراصنة" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="team" class="container my-5">
        <h2 class="text-center mb-4">Meet the Team</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="C:\Users\admin\simplewebserver\Dribble\john doe.jpg" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Member 1">
                    <div class="card-body">
                        <h5 class="card-title">John Doe</h5>
                        <p class="card-text">Lead Designer</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="C:\Users\admin\simplewebserver\Dribble\james.avif" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Member 2">
                    <div class="card-body">
                        <h5 class="card-title">Jane Smith</h5>
                        <p class="card-text">Web Developer</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="C:\Users\admin\simplewebserver\Dribble\brown.jpg" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Member 3">
                    <div class="card-body">
                        <h5 class="card-title">Michael Brown</h5>
                        <p class="card-text">Marketing Specialist</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; Developed and designed by Vignesh S</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-12-27 230417.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
