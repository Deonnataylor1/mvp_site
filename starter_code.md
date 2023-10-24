# Put this in the HTML section of your codepen MVP
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Simple Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>About Us</h2>
            <p>This is a simple website to demonstrate HTML, CSS, and JavaScript.</p>
        </section>
        <section>
            <h2>Contact Us</h2>
            <p>You can reach us at: example@email.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Simple Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```

# Put this in the CSS section of your codepen MVP
```css
/* Reset some default browser styles */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Style the header */
header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

/* Style the navigation menu */
nav ul {
    background-color: #333;
    list-style-type: none;
    text-align: center;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

/* Style the main content */
main {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

/* Style the footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

```