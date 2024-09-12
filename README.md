# JANTA-HIGH-SCHOOL-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Greenfield Academy | Excellence in Education</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
        }
        a {
            text-decoration: none;
            color: #333;
        }
        header {
            background-color: #00539C;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
        }
        header p {
            font-size: 1.2rem;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #003366;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav a:hover {
            background-color: #ff9900;
            color: white;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        h2 {
            color: #00539C;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.1rem;
        }
        .cta-btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #ff9900;
            color: white;
            font-size: 1rem;
            border-radius: 5px;
            margin-top: 20px;
        }
        .cta-btn:hover {
            background-color: #00539C;
            color: white;
        }
        footer {
            background-color: #003366;
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        footer p {
            margin: 10px 0;
        }

        /* Academic Programs Section */
        .programs {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .program-item {
            background-color: white;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 20px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .program-item h3 {
            margin-top: 0;
        }

        /* Media Queries for responsiveness */
        @media (max-width: 768px) {
            .programs {
                flex-direction: column;
                align-items: center;
            }
            .program-item {
                width: 90%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Greenfield Academy</h1>
    <p>Excellence in Education for a Brighter Future</p>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#academics">Academics</a>
    <a href="#admissions">Admissions</a>
    <a href="#news">News & Events</a>
    <a href="#contact">Contact Us</a>
</nav>

<div class="container">
    <!-- About Us Section -->
    <section id="about" class="section">
        <h2>About Greenfield Academy</h2>
        <p>Greenfield Academy is a premier educational institution offering a well-rounded curriculum that nurtures both academic and personal development. Our mission is to inspire a passion for lifelong learning and to empower students to become leaders in their communities.</p>
        <p>With state-of-the-art facilities and a commitment to excellence, we provide students with an environment where they can thrive both academically and socially.</p>
    </section>

    <!-- Academic Programs Section -->
    <section id="academics" class="section">
        <h2>Academic Programs</h2>
        <div class="programs">
            <div class="program-item">
                <h3>STEM Education</h3>
                <p>Our STEM program emphasizes hands-on learning in science, technology, engineering, and math to prepare students for the challenges of tomorrow.</p>
            </div>
            <div class="program-item">
                <h3>Humanities & Arts</h3>
                <p>We offer a rich curriculum in humanities, arts, and social sciences to cultivate creativity and critical thinking in our students.</p>
            </div>
            <div class="program-item">
                <h3>Sports & Athletics</h3>
                <p>Greenfield Academy's athletics program fosters teamwork, leadership, and resilience through competitive and recreational sports.</p>
            </div>
        </div>
    </section>

    <!-- Admissions Section -->
    <section id="admissions" class="section">
        <h2>Admissions</h2>
        <p>We are now accepting applications for the upcoming academic year. Our admissions process is designed to ensure we find the right students who will thrive in our dynamic learning environment.</p>
        <p>Learn more about our application process, deadlines, and scholarship opportunities.</p>
        <a href="#contact" class="cta-btn">Apply Now</a>
    </section>

    <!-- News & Events Section -->
    <section id="news" class="section">
        <h2>News & Events</h2>
        <p>Stay updated with the latest news and events happening at Greenfield Academy. From academic achievements to sports victories, we celebrate the success of our students and faculty.</p>
    </section>
</div>

<!-- Footer Section -->
<footer>
    <p>&copy; 2024 Greenfield Academy | All Rights Reserved</p>
    <p>123 Main Street, Hometown, Country | Tel: (123) 456-7890 | Email: info@greenfieldacademy.edu</p>
</footer>

</body>
</html>
