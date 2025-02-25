<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Working Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Interactive Website</h1>
        <p>This website demonstrates a working example using HTML, CSS, and JavaScript.</p>
    </header>

    <main>
        <section>
            <h2>About This Website</h2>
            <p>This simple website has interactive features like background color change when clicking a button.</p>
        </section>

        <section>
            <h2>Interactive Feature</h2>
            <button id="changeColorBtn">Change Background Color</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Interactive Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html> 
/* General Body Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
}

/* Header Styles */
header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Main Content Styles */
main {
    padding: 20px;
}

/* Section Styling */
section {
    background-color: white;
    margin: 10px 0;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Button Styles */
button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #45a049;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}
// This JavaScript will handle the background color change
document.getElementById('changeColorBtn').addEventListener('click', function() {
    // List of colors
    const colors = ['#f4f4f9', '#dff0d8', '#f2dede', '#d9edf7', '#d9f7d9'];
    
    // Pick a random color from the array
    const randomColor = colors[Math.floor(Math.random() * colors.length)];

    // Apply the random color as the background color
    document.body.style.backgroundColor = randomColor;
});
