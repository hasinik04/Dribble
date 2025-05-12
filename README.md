# Project Responsive Web Design using Bootstrap
## Date:

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
    <title>Gaming World</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Gaming World</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#games">Games</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-dark text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Welcome to Gaming World</h1>
            <p class="lead">Your ultimate destination for gaming news, reviews, and updates!</p>
            <a href="#features" class="btn btn-primary mt-3">Explore Now</a>
        </div>
    </header>

    <!-- Features Section -->
    <section id="features" class="py-5">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="c:\Users\admin\Downloads\game image.jpeg" class="card-img-top" alt="Latest News">
                        <div class="card-body">
                            <h5 class="card-title">Latest News</h5>
                            <p class="card-text">Stay updated with the latest gaming trends and news from around the globe.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="c:\Users\admin\Downloads\game image2.jpeg" class="card-img-top" alt="Top Reviews">
                        <div class="card-body">
                            <h5 class="card-title">Top Reviews</h5>
                            <p class="card-text">Read reviews of the most popular games from our experts.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="c:\Users\admin\Downloads\game images3.jpeg" class="card-img-top" alt="Community">
                        <div class="card-body">
                            <h5 class="card-title">Community</h5>
                            <p class="card-text">Join our gaming community and connect with other gamers worldwide.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Games Section -->
    <section id="games" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Featured Games</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\fortnite.jpeg" class="card-img-top" alt="Game 1">
                        <div class="card-body">
                            <h5 class="card-title">FORTNITE</h5>
                            <p class="card-text">An exciting adventure game that will keep you on the edge of your seat.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\lego world.jpeg" class="card-img-top" alt="Game 2">
                        <div class="card-body">
                            <h5 class="card-title">LEGO WORLD</h5>
                            <p class="card-text">Dive into this RPG with stunning visuals and a gripping storyline.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\minicraft" class="card-img-top" alt="Game 3">
                        <div class="card-body">
                            <h5 class="card-title">MINECRFAT</h5>
                            <p class="card-text">Experience fast-paced action in this thrilling multiplayer game.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Write your message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2024 Gaming World. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
 
## OUTPUT:
![Screenshot 2025-05-12 192933](https://github.com/user-attachments/assets/76989089-e5eb-42fa-8198-99b4b53c5359)

![Screenshot 2025-05-12 193006](https://github.com/user-attachments/assets/249d0fbf-5f57-4d39-9c32-93acbb3a78f7)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
