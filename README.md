# Matrix-hardware.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Hardware Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Your Hardware Store!</h1>
    </header>
    <main>
        <img src="tools.jpg" alt="A collection of various hardware tools" class="main-image">

        <p>Your one-stop shop for all your hardware needs.</p>
        <p>We offer a wide range of tools, building materials, and home improvement supplies.</p>
    </main>
    <footer>
        <p>&copy; 2025 Your Hardware Store. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    background-color: #FFFACD; /* Lemon Chiffon - a nice light yellow */
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    text-align: center;
}

header {
    background-color: #FFD700; /* Gold */
    color: white;
    padding: 10px 0;
    margin-bottom: 20px;
}

h1 {
    color: #333; /* Dark gray for contrast */
}

main {
    background-color: white;
    padding: 20px;
    margin: 0 auto;
    max-width: 800px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

footer {
    margin-top: 20px;
    padding: 10px;
    background-color: #FFD700; /* Gold */
    color: white;
    font-size: 0.9em;
}

.main-image {
    max-width: 100%; /* Ensures the image doesn't overflow its container */
    height: auto;    /* Maintains the image's aspect ratio */
    display: block;  /* Removes extra space below the image */
    margin: 20px auto; /* Adds space above/below and centers it */
    border-radius: 8px; /* Slightly rounded corners */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}

