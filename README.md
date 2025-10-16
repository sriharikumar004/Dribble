# Project Responsive Web Design using Bootstrap
## Date:16/10/2025

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
edu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title><b>educational website</b></title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>

    <header>
        <nav class="navbar">
            <div class="logo"><b>online learning</b></div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="course.html">course</a></li>
                <li><a href="#">About</a></li>
                <li><a href="course.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to online learning</h1>
        <p>"Innovative Educational Website for Students and Creators/free courses"</p>
        <a href="course.html" class="btn">courses</a>
    </section>

    <section class="products">
        <h2><b>advanced courses</b></h2>
        <div class="course-grid">
            <div class="course-card">
                <img src="Screenshot 2025-10-16 093750.png" alt="course 1" />
                <h3>artificial intelligence</h3>
                
                <button>Add course</button>
            </div>
            <div class="course-card">
                <img src="Screenshot 2025-10-16 094034.png" alt="course 2" />
                <h3>dicover the space</h3>
               
                <button>Add course</button>
            </div>
            <div class="course-card">
                <img src="Screenshot 2025-10-16 094144.png" alt="course 3" />
                <h3>CodeCraft: From Beginner to Pro in Web Development</h3>
                <button>Add course</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; online education, All rights reserved.</p>
    </footer>

</body>

</html>

course.html


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>courses</title>
    <style>
        .product-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            transition: course 0.3s ease;
        }

        .product-card:hover {
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
        }

        .product-image {
            height: 200px;
            object-fit: contain;
            margin-bottom: 10px;
        }

        .rating {
            color: #f5c518;
        }
    </style>
</head>

<body>
    <div class="container py-4">
        <h2 class="mb-4">Featured courses/paid courses</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">


            <div class="col">
                <div class="course-cardtext-center">
                    <img src="Screenshot 2025-10-16 094906.png"  alt="course 1">
                    <h5 class="mt-2">Data Science</h5>
                    <p class="text-success fw-bold">₹2,499</p>
                    <p class="rating">★★★★☆ (4.2)</p>
                    <button class="btn btn-primary">Add the course</button>
                </div>
            </div>

            <div class="col">
                <div class="product-card text-center">
                    <img src="Screenshot 2025-10-16 094957.png"  alt="course 2">
                    <h5 class="mt-2">Software Development</h5>
                    <p class="text-success fw-bold">₹5,999</p>
                    <p class="rating">★★★★★ (4.8)</p>
                    <button class="btn btn-primary">Add the course</button>
                </div>
            </div>

            <div class="col">
                <div class="product-card text-center">
                    <img src="Screenshot 2025-10-16 103820.png" alt="course 3">
                    <h5 class="mt-2">Cyber Security</h5>
                    <p class="text-success fw-bold">₹299</p>
                    <p class="rating">★★★☆☆ (3.9)</p>
                    <button class="btn btn-primary">Add the course</button>
                </div>
            </div>

        
        </div>
    </div>
</body>

</html>
```


## OUTPUT:
![alt text](<img 1.png>)

![alt text](<img 2.png>)

![alt text](<img 3.png>)

![alt text](<img 4.png>)

![alt text](<img 5.png>)

![alt text](<img 6.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
