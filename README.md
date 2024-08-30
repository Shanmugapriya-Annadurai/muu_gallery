//html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery -Muu Furniture Store</title>
    <link rel="stylesheet" href="/CSS/gallery.css">
</head>
<body>

<header>
    <div class="container">
        <h1><a href="Home.html">Muu Furniture Store</a></h1>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="gallery">
    <div class="container">
        <h2>Our Gallery</h2>
        <p>Explore our wide range of furniture collections and find the perfect pieces for your home.</p>
        <div class="gallery-grid">
            <div class="gallery-item">
                <img src="/Source/minh-pham-OtXADkUh3-I-unsplash.jpg" alt="Gallery Image 1">
                <p>Modern Living Room Set</p>
            </div>
            <div class="gallery-item">
                <img src="/Source/view-table-arrangement-by-wedding-planner.jpg" alt="Gallery Image 2">
                <p>Classic Wooden Dining Table</p>
            </div>
            <div class="gallery-item">
                <img src="/Source/interior-decoration-inspired-by-mexican-folklore (1).jpg" alt="Gallery Image 3">
                <p>Comfortable Bedroom Suite</p>
            </div>
            <div class="gallery-item">
                <img src="/Source/Office by kathy ireland® Echo L Shaped Desk in Gray Sand - Bush Furniture ECH026GS.jpeg.jpg" alt="Gallery Image 4">
                <p>Elegant Office Furniture</p>
            </div>
            
        </div>
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2024 Muu Furniture Store. All rights reserved.</p>
      
    </div>
</footer>

</body>
</html>




//css code


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Header */
header h1 a {

    color: #fff;
    text-decoration: none;
}
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Gallery Section */
.gallery {
    padding: 50px 0;
    text-align: center;
}

.gallery .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.gallery h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

.gallery p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 20px;
    color: #666;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.gallery-item {
    border: 1px solid #ddd;
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    background: #fff;
    text-align: left;
}

.gallery-item img {
    width: 100%;
    height: auto;
}

.gallery-item p {
    margin: 10px;
    font-size: 1em;
    color: #333;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

footer nav ul {
    list-style-type: none;
}

footer nav ul li {
    display: inline-block;
    margin-right: 20px;
}

footer nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
body{
    background-image: url('/Source/WhatsApp\ Image\ 2024-07-26\ at\ 20.54.49_3dddd8fe.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
