# Matrix-hardware.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tool Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Tool Collection</h1>
    </header>
    <main>
        <div class="image-container">
            <h2>Hammer</h2>
            <img src="https://via.placeholder.com/200x200/FF0000/FFFFFF?text=Hammer+Image" alt="A hammer tool">
        </div>

        <div class="image-container">
            <h2>Screwdriver</h2>
            <img src="https://via.placeholder.com/200x200/00FF00/000000?text=Screwdriver+Image" alt="A screwdriver tool">
        </div>

        <div class="image-container">
            <h2>Light</h2>
            <img src="https://via.placeholder.com/200x200/0000FF/FFFFFF?text=Light+Image" alt="A light source">
        </div>
    </main>
    <footer>
        <p>&copy; 2025 Tool Gallery</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: cornsilk; /* A nice, soft yellowish background */
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh; /* Ensures the body takes at least the full viewport height */
}

header {
    margin-bottom: 30px;
    text-align: center;
}

h1 {
    color: #333;
}

main {
    display: flex;
    flex-wrap: wrap; /* Allows containers to wrap to the next line on smaller screens */
    justify-content: center;
    gap: 30px; /* Space between the image containers */
}

.image-container {
    background-color: #fff; /* White background for each image container */
    border: 1px solid #ddd; /* Light grey border */
    border-radius: 8px; /* Slightly rounded corners */
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
    width: 250px; /* Fixed width for each container */
}

.image-container h2 {
    color: #555;
    margin-top: 0;
    margin-bottom: 15px;
}

.image-container img {
    max-width: 100%; /* Ensures images fit within their containers */
    height: auto; /* Maintains aspect ratio */
    border-radius: 4px; /* Slightly rounded corners for images */
}

footer {
    margin-top: 50px;
    color: #777;
    font-size: 0.9em;
}


