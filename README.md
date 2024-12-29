<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Front Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navigation bar styling */
        .navbar {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        .navbar a:hover {
            text-decoration: underline;
        }

        /* Hero section styling */
        .hero {
            background-color: #f4f4f4;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 3em;
            margin: 0;
        }

        .hero p {
            font-size: 1.5em;
            margin: 20px 0;
        }

        .hero button {
            padding: 10px 20px;
            font-size: 1em;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }

        .hero button:hover {
            background-color: #555;
        }

        /* Footer styling */
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Navigation bar -->
    <div class="navbar">
        <div class="logo">My Website</div>
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </div>
    </div>

    <!-- Hero section -->
    <div class="hero">
        <h1>Welcome to My Website</h1>
        <p>Your one-stop solution for all your needs</p>
        <button onclick="learnMore()">Learn More</button>
    </div>

    <!-- Footer -->
    <div class="footer">
        &copy; 2024 My Website. All rights reserved.
    </div>

    <script>
        // JavaScript function for the button
        function learnMore() {
            alert('Thank you for your interest! More content coming soon.');
        }
    </script>
</body>
</html>
