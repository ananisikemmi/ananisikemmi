/* styles.css */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
    position: fixed;
    width: 100%;
    bottom: 0;
}

h1, h2 {
    color: #333;
}

.intro, .shoes-list, .payment-form {
    margin: 20px 0;
}

.intro img, .shoes-list img {
    max-width: 100%;
    height: auto;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin-bottom: 20px;
}

.payment-form form {
    max-width: 600px;
    margin: 0 auto;
}

.payment-form label {
    display: block;
    margin: 5px 0;
}

.payment-form input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
}

button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}



