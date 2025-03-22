# Activity
HTML  AND CSS CODE OF PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
    <style>
    
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

       
        header {
            background-color: #4CAF50;
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }

        .info-box {
            background: white;
            padding: 15px;
            margin: 10px;
            width: 300px;
            border-radius: 8px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }

        .right-box {
            align-self: flex-start;
        }

        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        footer a {
            color: #4CAF50;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Website Task</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="info-box">
            <h2>About CSS</h2>
            <p>Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>
        </section>

        <section class="info-box">
            <h2>Responsive Design</h2>
            <p>Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>
        </section>

        <section class="info-box right-box">
            <h2>Box Model</h2>
            <p>The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>
        </section>
    </main>

    <footer>
        <p>Created by [Student Name] | Follow us on 
            <a href="#">Instagram</a> | 
            <a href="#">Twitter</a> | 
            <a href="#">LinkedIn</a>
        </p>
    </footer>
</body>
</html>

