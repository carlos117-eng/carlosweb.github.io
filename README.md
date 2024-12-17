<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shirts</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        .search-container {
            text-align: center; /* Center the search bar */
            margin-top: 25px; /* Space above the search bar to avoid overlap with title */
        }

        .search-bar {
            padding: 10px; /* Padding inside the input */
            width: 80%; /* Width of the search bar */
            max-width: 400px; /* Maximum width */
            font-size: 1rem; /* Font size */
            border: 2px solid black; /* Border */
            border-radius: 5px; /* Rounded corners */
            background-color: white; /* Background color */
            color: black; /* Text color */
        }
    </style>
</head>
<body>
    <div class="title-container">
        <h1 id="title">Shirts</h1>
        <a href="checkout.html" class="cart-icon">🛒</a>
    </div>
    
    <div class="search-container">
        <input type="text" id="searchBar" placeholder="Search shirts..." class="search-bar">
    </div>
    
    <div class="wrapper">
        <div class="content">
            <h2 class="popular-shirts">Popular Shirts</h2>
            <div class="shirt-slider">
                <button class="slider-button left" onclick="slide(-1)" id="leftButton" disabled>&#10094;</button>
                <div class="shirt-container" id="shirtContainer">
                    <div class="shirt-row" id="shirtRow"></div>
                </div>
                <button class="slider-button right" onclick="slide(1)" id="rightButton">&#10095;</button>
            </div>
    
            <hr class="separator">
    
            <div class="additional-content">
                <p>More content Soon</p>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="footer-content">
            <p>&copy; 2024 Shirts. All rights reserved.</p>
            <div class="social-media">
                <a href="#" target="_blank">Facebook</a>
                <a href="#" target="_blank">Twitter</a>
                <a href="#" target="_blank">Instagram</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
