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
<html>
    <title>DRIBBLE</title>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <div class="container">
                <a class="navbar-brand fs-1 fw-bold" href="#">DRIBBLE</a>
                <div class="d-flex">
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">Home</a>
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">About</a>
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">Contact</a>
                </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Popular</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Newest</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Random</a>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="container my-5">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">
                <div class="col">
                    <div class="card">
                        <img src="1.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 1</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="2.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 2</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="3.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 3</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="4.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 4</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="5.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 5</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="6.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 6</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="7.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 7</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="8.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Card 8</h6>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section id="contact" class="contact-section py-5 bg-light">
            <div class="container">
                <h2 class="text-center mb-4">Contact Us</h2>
                <form>
                    <div class="mb-3">
                        <label for="name" class="form-label">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="mb-3">
                        <label for="email" class="form-label">Your Email</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter your email">
                    </div>
                    <div class="mb-3">
                        <label for="message" class="form-label">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send</button>
                </form>
            </div>
        </section>
        <footer class="bg-dark text-white text-center py-3">
            <p>&copy; Designed and Developed by SIBHIRAAJ R </p>
        </footer>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    </body>
</html>
```

## OUTPUT:

![Screenshot 2025-05-21 105116](https://github.com/user-attachments/assets/6591dcdb-85ec-468e-878a-e90da9a09398)

![Screenshot 2025-05-21 105129](https://github.com/user-attachments/assets/5123a4b5-2a9e-4a69-a5b6-520150cd0d05)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
