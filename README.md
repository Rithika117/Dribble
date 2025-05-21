![image](https://github.com/user-attachments/assets/28408a38-fb26-4b4b-b142-68273b1fa711)# Project Responsive Web Design using Bootstrap
## Date:21/05/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy Company</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome (for icons) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <!-- Navbar with background color -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Pharmacy Company</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section with background image -->
    <div class="jumbotron text-center text-white" style="background-image: url('c:\Users\admin\Downloads\images (1).jpg'); background-size: cover; height: 350px;">
        <div class="container py-5">
            <h1>Welcome to Pharmacy Company</h1>
            <p>Your health and wellness are our priority. We provide the best pharmaceutical products and services to ensure your well-being.</p>
        </div>
    </div>

    <!-- Main Content Section -->
    <div class="container mt-5">
        <h2 class="text-center mb-4">Our Services</h2>
        <div class="row text-center">
            <div class="col-md-4">
                <div class="card shadow-sm rounded">
                    <div class="card-body">
                        <i class="fas fa-pills fa-3x mb-3 text-primary"></i>
                        <h5 class="card-title">Prescription Medications</h5>
                        <p class="card-text">We offer a wide range of prescription medications tailored to your needs.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow-sm rounded">
                    <div class="card-body">
                        <i class="fas fa-briefcase-medical fa-3x mb-3 text-primary"></i>
                        <h5 class="card-title">Over-the-Counter Medications</h5>
                        <p class="card-text">Get access to quality OTC medications for common health issues.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow-sm rounded">
                    <div class="card-body">
                        <i class="fas fa-heartbeat fa-3x mb-3 text-primary"></i>
                        <h5 class="card-title">Health Consultations</h5>
                        <p class="card-text">Book a consultation with our experienced healthcare professionals.</p>
                    </div>
                </div>
            </div>
        </div>

        <h2 class="text-center mt-5 mb-4">Featured Products</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg rounded">
                    <img src="c:\Users\admin\Downloads\images (2).jpg" class="card-img-top" alt="Product 1">
                    <div class="card-body">
                        <h5 class="card-title">Pain Relief</h5>
                        <p class="card-text">Effective pain relief for various conditions. Fast-acting and reliable.</p>
                    </div>
                    <div class="card-footer text-muted text-center">
                        <button class="btn btn-primary">View Product</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg rounded">
                    <img src="c:\Users\admin\Downloads\images (3).jpg" class="card-img-top" alt="Product 2">
                    <div class="card-body">
                        <h5 class="card-title">Cough Syrup</h5>
                        <p class="card-text">Relieves coughing and sore throat symptoms with a soothing effect.</p>
                    </div>
                    <div class="card-footer text-muted text-center">
                        <button class="btn btn-primary">View Product</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg rounded">
                    <img src="c:\Users\admin\Downloads\istockphoto-186607295-612x612.jpg" class="card-img-top" alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Vitamins & Supplements</h5>
                        <p class="card-text">Boost your immunity with our premium vitamins and supplements.</p>
                    </div>
                    <div class="card-footer text-muted text-center">
                        <button class="btn btn-primary">View Product</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer with background color and improved design -->
    <footer class="bg-primary text-white text-center py-4 mt-5">
        <div class="container">
            <!-- Footer content with social links -->
            <div class="row">
                <div class="col-12">
                    <p>Designed and Developed by <strong>RITHIKA K</strong></p>
                    <p>&copy; 2024 Pharmacy Company. All rights reserved.</p>
                </div>
            </div>

            <!-- Social Media Links Section -->
            <div class="row">
                <div class="col-12">
                    <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-white"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

## OUTPUT:

![Screenshot (243)](https://github.com/user-attachments/assets/401d8521-4fd2-4923-90b2-d88ec95a1c91)

![Screenshot (244)](https://github.com/user-attachments/assets/6ce7554a-3c3c-4195-8d5c-4a5effc318c3)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
