<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tree Service Academy</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa; /* Light background */
            color: #333;
        }
        header {
            background: linear-gradient(to right, #004d40, #00796b); /* Professional gradient */
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.8rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        nav {
            background-color: #00251a;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            font-size: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            padding: 20px;
            background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
            color: white;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin-top: 15px;
        }
        .hero .cta-button {
            background-color: #00796b;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .hero .cta-button:hover {
            background-color: #004d40;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 30px;
            color: #004d40;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .feature-box {
            background-color: white;
            width: 30%;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .feature-box i {
            font-size: 2rem;
            color: #00796b;
            margin-bottom: 10px;
        }
        .feature-box h3 {
            font-size: 1.3rem;
            color: #004d40;
            margin-bottom: 10px;
        }
        .testimonials, .faculty {
            background-color: #e8f5e9;
            padding: 30px 20px;
            border-radius: 8px;
        }
        .testimonial, .faculty-member {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .testimonial img, .faculty-member img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin-right: 15px;
        }
        .testimonial p, .faculty-member p {
            font-size: 1rem;
            color: #333;
        }
        .pricing {
            text-align: center;
            margin-top: 30px;
        }
        .pricing .price {
            font-size: 2rem;
            color: #00796b;
            font-weight: bold;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
        footer a {
            color: #80cbc4;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .features {
                flex-direction: column;
                align-items: center;
            }
            .feature-box {
                width: 90%;
            }
            .hero {
                flex-direction: column;
                text-align: center;
            }
            .hero img {
                width: 100%;
                margin-top: 20px;
            }
        }
    </style>
</head>
<body>

<!-- Navigation -->
<nav>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Header -->
<header>
    <h1>Tree Service Academy</h1>
    <p>Your path to a successful tree service business starts here.</p>
</header>

<!-- Hero Section -->
<section class="hero">
    <div>
        <h2>Learn, Grow,
