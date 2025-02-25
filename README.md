/* General Body Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* Header Styles */
header {
    background-color: #333;
    color: white;
    padding: 15px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo h1 {
    margin: 0;
}

header nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Home Section */
#home {
    background-color: #5aaf6a;
    color: white;
    padding: 50px 20px;
    text-align: center;
}

/* Car Listings Section */
#cars {
    padding: 50px 20px;
    text-align: center;
}

.car-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.car {
    background-color: white;
    padding: 20px;
    margin: 10px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 30%;
}

.car img {
    width: 100%;
    border-radius: 8px;
}

.car h3 {
    font-size: 1.5em;
    margin-top: 10px;
}

.car p {
    font-size: 1.2em;
    color: #333;
}

.details-btn {
    background-color: #4CAF50;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.details-btn:hover {
    background-color: #45a049;
}

/* Contact Section */
#contact {
    background-color: #f9f9f9;
    padding: 50px 20px;
    text-align: center;
}

#contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

#contact form input, #contact form textarea {
    width: 300px;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

#contact form button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

#contact form button:hover {
    background-color: #45a049;
}

/* Footer Section */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
