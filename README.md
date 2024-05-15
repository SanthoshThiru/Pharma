# Project Responsive Web Design using Bootstrap
## Date: 15/05/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
1.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pure Pharmaceuticals</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #2c3e50;
            color: white;
        }

        .navbar-brand {
            font-weight: bold;
        }

        .navbar-nav .nav-link {
            color: white !important;
        }

        .jumbotron {
            background-color: rgba(0, 0, 0, 0.5);
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Pure Pharmaceuticals</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="1.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="2.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="3.html">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="4.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Page Content -->
    <div class="container mt-5">
        <div class="jumbotron">
            <div class="container">
                <h1 class="display-4"><u>Welcome to Pure Pharmaceuticals</u></h1>
                <p class="lead">Welcome to Pure Pharmaceuticals, your trusted destination for health and wellness solutions! Our commitment to your well-being is unwavering. Explore our offerings and experience the difference.</p>
                <p class="lead">Here's what makes us unique:</p>
                <ul class="list-unstyled">
                    <li class="lead"><strong>Expert Care:</strong> Our seasoned pharmacists provide tailored guidance and support, ensuring your journey to better health is personalized and effective.</li>
                    <li class="lead"><strong>Quality Products:</strong> Discover our curated selection of premium medications and supplements, sourced from reputable suppliers to guarantee your well-being.</li>
                    <li class="lead"><strong>Convenience:</strong> With our user-friendly platform and accessible locations, obtaining your health essentials is hassle-free, allowing you to prioritize your well-being.</li>
                    <li class="lead"><strong>Health Resources:</strong> Empower yourself with our extensive collection of articles, guides, and wellness tips, designed to equip you with the knowledge to lead a healthier lifestyle.</li>
                    <li class="lead"><strong>Community Engagement:</strong> We are deeply rooted in community health. Through collaborative efforts and educational initiatives, we strive to foster a healthier tomorrow for all.</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-4 mt-5">
        <div class="container">
            <p class="mb-0">&copy; All rights reserved. 2024 SANTHOSHT(212223220100)</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

```
2.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Pure Pharmaceuticals Company</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Pure Pharmaceuticals Company</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="1.html">Home</a>
                    </li>
                    <li class="nav-item dropdown active">
                        <a class="nav-link dropdown-toggle" href="2.html" id="navbarDropdownAbout" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            About
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                            <a class="dropdown-item" href="#vision">Vision</a>
                            <a class="dropdown-item" href="#mission">Mission</a>
                            <a class="dropdown-item" href="#values">Values</a>
                            
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="3.html">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Page Content -->
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-12">
                <h1 class="text-center">About Pure Pharmaceuticals Company</h1>
                <div id="vision">
                    <h2>Vision</h2>
                    <p>Pure Pharmaceuticals' vision is to make healthcare accessible, affordable, and convenient for every
                        individual, leveraging technology to streamline the healthcare delivery process and improve health
                        outcomes.</p>
                </div>
                <div id="mission">
                    <h2>Mission</h2>
                    <p>Pure Pharmaceuticals mission aims to bridge the gap between patients and healthcare providers by
                        providing a platform where users can easily access medicines, healthcare products, and services
                        from the comfort of their homes.</p>
                </div>
                <div id="values">
                    <h2>Values</h2>
                    <ul>
                        <li>Customer-Centricity: Pure Pharmaceuticals places the needs and preferences of its customers
                            at the forefront of its operations.</li>
                        <li>Integrity: The company upholds the highest standards of integrity and ethics in all its
                            dealings.</li>
                        <li>Innovation: Pure Pharmaceuticals embraces innovation and technology to continuously improve
                            its services.</li>
                        <li>Empowerment: Pure Pharmaceuticals believes in empowering individuals to take control of their
                            health.</li>
                        <li>Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-4 mt-5">
        <div class="container">
            <p>&copy; All rights reserved. 2024 SANTHOSHT(212223220100)</p>
        </div>
    </footer>
    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

```
3.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pure Pharmaceuticals</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="1.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="2.html">About</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="3.html">Products <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="4.html">Contact</a>
          </li>
        </ul>
        
      </div>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1 class="text-center">Our Best Selling Products!</h1>
        <div class="card-deck">
          <div class="card">
            <img src="product1.jpg" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Paracetemol</h5>
              <p class="card-text">30 tablets of Paracetemol that acts as a painkiller and fever reducer.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="product2.jpg" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Amoxicillin</h5>
              <p class="card-text">30 tablets of Amoxicillin to treat bacterial infection</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="product3.jpeg" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Aspirin</h5>
              <p class="card-text">50 tablets of aspirin to be used as painkiller.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; All rights reserved. 2024 SANTHOSHT(212223220100)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
4.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Pure Pharmaceuticals</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pure Pharmaceuticals</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="1.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="2.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="3.html">Products</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="4.html">Contact <span class="sr-only">(current)</span></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, contact us!</p>
        <form>
          <div class="form-group">
            <label for="name"><strong>Your Name</strong></label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email"><strong>Your Email</strong></label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message"><strong>Message</strong></label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>Pure Pharmaceuticals</h2>
        <address>
          <strong><u>Address:</u></strong><br>
          Door No.30/1,King's Palace , Tambaram,<br> Chennai, Tamil Nadu 600018 <br><br>
          <strong><u>Email:</u></strong><br>
          purepharmaceuticals@gmail.com<br>
          <br>
          <strong><u>Phone:</u></strong><br>
          +9876543210
        </address>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy;  All rights reserved. 2024 SANTHOSHT(212223220100)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

```



## OUTPUT:
![alt text](<Screenshot 2024-05-15 085224.png>)
![alt text](<Screenshot 2024-05-15 085737.png>)
![alt text](<Screenshot 2024-05-15 085612.png>)
![alt text](<Screenshot 2024-05-15 085625.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
