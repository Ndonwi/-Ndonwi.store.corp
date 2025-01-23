/* Reset default margin and padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f0f8ff; /* Light blue background */
    color: #333;
}

header {
    background-color: #003366; /* Dark blue header */
    color: white;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
    font-size: 2rem;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
}

.banner {
    background: #1e90ff; /* Bright blue for banner */
    color: white;
    padding: 60px 0;
    text-align: center;
}

.products {
    padding: 40px 20px;
    text-align: center;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.product {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 200px;
    text-align: center;
    border: 2px solid #003366; /* Dark blue border */
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    border: 2px solid #003366; /* Dark blue border around images */
}

.product h3 {
    margin-top: 10px;
    color: #003366;
}

.buy-btn {
    background-color: #1e90ff; /* Bright blue */
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 10px;
}

.buy-btn:hover {
    background-color: #003366; /* Dark blue on hover */
}

footer {
    background-color: #003366; /* Dark blue footer */
    color: white;
    text-align: center;
    padding: 20px 0;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form button {
    background-color: #1e90ff; /* Bright blue */
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #003366; /* Dark blue on hover */
}
