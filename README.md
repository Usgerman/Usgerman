/* Allgemeine Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 90%;
    margin: 0 auto;
}

/* Header */
header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
}

nav ul {
    list-style: none;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Section */
section {
    padding: 30px 0;
    background-color: #fff;
    margin-bottom: 20px;
}

h2 {
    color: #444;
    font-size: 2em;
    margin-bottom: 20px;
}

ul {
    list-style: disc;
    margin-left: 20px;
}

h3 {
    font-size: 1.5em;
    margin-top: 20px;
}

/* Form */
form {
    margin-top: 20px;
}

form label {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    margin-top: 15px;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
