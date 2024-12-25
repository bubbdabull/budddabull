<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bubb Da Bull - Solana Meme Coin</title>
    <style>
        /* Ensure the page takes up full height */
        html, body {
            height: 100%;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        /* Set the background image */
        body {
            background-image: url();
            background-size: cover; /* Ensures the image covers the entire background */
            background-position: center; /* Centers the image */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        /* Center content */
        .content {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff; /* Adjust text color for contrast */
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7); /* Adds text shadow for better readability */
            padding: 20px;
        }
        /* Style social media links */
        .social-links {
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #fff;
            font-size: 24px;
        }
        .social-links a:hover {
            opacity: 0.7; /* Adds a hover effect */
        }
        /* Style the call-to-action button */
        .cta-button {
            margin-top: 30px;
            padding: 15px 30px;
            background-color: #ff4500; /* Bright color to attract attention */
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        .cta-button:hover {
            background-color: #e03e00; /* Slightly darker shade on hover */
        }
        /* Footer styling */
        footer {
            text-align: center;
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background */
            color: #fff;
            font-size: 14px;
        }
    </style>
    <!-- Include Font Awesome for social media icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="content">
        <h1>Welcome to Bubb Da Bull</h1>
        <p>The Next Big Solana Meme Coin</p>
        <p>Bubb Da Bull is a community-driven meme coin on the Solana blockchain, aiming to bring fun and value to the crypto space. Join our growing community and be part of the bullish movement!</p>
        <a href="https://exchange-link.com" class="cta-button" target="_blank">Buy Bubb Da Bull Now</a>
        <div class="social-links">
            <a href="https://www.facebook.com/YourPage" target="_blank" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
            <a href="https://twitter.com/YourProfile" target="_blank" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
            <a href="https://pump.fun/YourProfile" target="_blank" aria-label="Pump.fun"><i class="fas fa-bullhorn"></i></a>
        </div>
    </div>
    <footer>
        &copy; <span id="current-year"></span> Bubb Da Bull. All rights reserved.
    </footer>
    <script>
        // Set the current year in the footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
