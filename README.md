<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Phuthanet Khumrat</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        nav {
            background-color: #333;
            padding: 15px;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        .profile {
            margin: 50px auto;
            width: 250px;
            text-align: center;
        }
        .profile img {
            width: 100%;
            border-radius: 50%;
            border: 5px solid #333;
        }
        .profile h1 {
            margin: 15px 0;
            font-size: 24px;
        }
        .profile p {
            font-size: 16px;
            color: #555;
        }
        .portfolio {
            margin: 40px auto;
            max-width: 800px;
        }
        .portfolio h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .project {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .project a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <nav>
        <ul>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="form.html">Form</a></li>
            <li><a href="pagelayout.html">Page Layout</a></li>
            <li><a href="BoxModel.html">Box Model</a></li>
        </ul>
    </nav>

    <section class="profile">
        <img src="image/profile.jpg" alt="Profile Picture">
        <h1>Phuthanet Khumrat</h1>
        <p>Web Developer & Designer </p>
    </section>

    <section class="portfolio">
        <h2>My Projects</h2>
        <div class="projects">
            <div class="project">
                <p>🔹 <a href="menu.html">Menu</a></p>
            </div>
            <div class="project">
                <p>📄 <a href="form.html">Form</a></p>
            </div>
            <div class="project">
                <p>📌 <a href="pagelaout.html">Page Layout</a></p>
            </div>
            <div class="project">
                <p>📦 <a href="BoxModel.html">Box Model</a></p>
            </div>
        </div>
    </section>

</body>
</html>
