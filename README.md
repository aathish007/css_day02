##index.html
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="assets/images/lemon.jpeg" alt="Little Lemon Logo">
            <h1>LITTLE LEMON</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="promo">
            <h2>30% Off This Weekend</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
        </section>
        <section class="info">
            <div class="info-box">
                <img src="assets/images/pastah.jpeg" alt="New Menu">
                <h3>Our New Menu</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="#">See our new menu</a>
            </div>
            <div class="info-box">
                <img src="assets/images/pastah2.jpeg" alt="Book a Table">
                <h3>Book a table</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="#">Book your table now</a>
            </div>
            <div class="info-box">
                <img src="assets/images/pastah3.jpeg" alt="Opening Hours">
                <h3>Opening Hours</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies.</p>
                <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
            </div>
        </section>
    </main>
    <footer>
        <img src="assets/images/lemon.jpeg" alt="Little Lemon Logo">
        <p>Copyright Little Lemon</p>
    </footer>
</body>
</html>
```
##styles.css:
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #fff;
    padding: 20px;
    border-bottom: 1px solid #ccc;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #000;
    font-weight: bold;
}

.promo {
    background: url('assets/images/pastah5.jpeg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.promo h2 {
    font-size: 3em;
    margin: 0 0 20px;
}

.promo p {
    font-size: 1.2em;
    margin: 0 auto;
    max-width: 600px;
}

.info {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.info-box {
    background-color: #fff;
    padding: 20px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    width: 30%;
    text-align: center;
}

.info-box img {
    max-width: 100%;
    border-radius: 10px;
}

.info-box h3 {
    font-size: 1.5em;
    margin: 20px 0 10px;
}

.info-box p {
    font-size: 1em;
    color: #333;
}

.info-box a {
    text-decoration: none;
    color: #007BFF;
    font-weight: bold;
    display: inline-block;
    margin-top: 10px;
}

footer {
    background-color: #fff;
    text-align: center;
    padding: 20px;
    border-top: 1px solid #ccc;
    margin-top: 20px;
}

footer img {
    height: 30px;
    margin-bottom: 10px;
}

footer p {
    margin: 0;
    font-size: 0.9em;
    color: #555;
}

```

##output:
![image](https://github.com/user-attachments/assets/009d27e6-81ee-4bac-be26-c4c960c27943)
