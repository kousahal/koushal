# koushal
A Personal Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koushal Yadav - IT Professional</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #000;
            margin: 0;
            padding: 0;
            color: #fff;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: right;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        section#showcase {
            min-height: 400px;
            background: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.forbes.com%2Fsites%2Fforbestechcouncil%2F2020%2F05%2F28%2Fthe-future-of-tech-requires-humans%2F&psig=AOvVaw3fNLEW0LNBOele9c9MgBBZ&ust=1718649021395000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCPjF9tbg4IYDFQAAAAAdAAAAABAEy') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        section#showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        section#showcase p {
            font-size: 20px;
        }
        section#main {
            padding: 20px;
        }
        .box {
            float: left;
            width: 30%;
            padding: 20px;
            margin: 10px 1.5%;
            background-color: #800080;
            border-radius: 8px;
            box-sizing: border-box;
        }
        .box h3 {
            text-align: center;
        }
        .box img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #333;
            text-align: center;
            clear: both;
        }
        footer p {
            margin: 0;
        }
        @media (max-width: 768px) {
            header li {
                float: none;
                display: block;
                text-align: center;
                padding: 10px;
            }
            .box {
                width: 100%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Koushal Yadav</h1>
            </div>
            <nav>
                <ul>
                    <div id="skills" class="box">
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Welcome to My Personal Page</h1>
            <p>Innovative Solutions for a Better Tomorrow</p>
        </div>
    </section>

    <section id="main" class="container">
        <div id="skills" class="box">
            <h3>Skills</h3>
            <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.myperfectresume.com%2Fcareer-center%2Fresumes%2Fhow-to%2Fskills&psig=AOvVaw1RqNMQ7eASJreftUIRYYDk&ust=1718648769332000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCLD1397f4IYDFQAAAAAdAAAAABAE" alt="Skills Image">
            <p>
                - Programming Languages: Java, Python, C++<br>
                - Web Development: HTML, CSS, JavaScript, React<br>
                - Database Management: SQL, MongoDB<br>
                - DevOps: Docker, Kubernetes, Jenkins<br>
                - Cloud Services: AWS, Azure, Google Cloud Platform
            </p>
        </div>
        <div id="projects" class="box">
            <h3>Projects</h3>
            <img src="https://images.unsplash.com/photo-1521737711861-2b6f67a2af8e" alt="Projects Image">
            <p>
                <strong>Project 1: E-commerce Website</strong><br>
                Description: Developed a full-stack e-commerce application using MERN stack.<br>
                <strong>Project 2: Machine Learning Model</strong><br>
                Description: Built a predictive model using Python and scikit-learn to analyze sales data.<br>
                <strong>Project 3: DevOps Pipeline</strong><br>
                Description: Created a CI/CD pipeline using Jenkins and Docker to automate the deployment process.
            </p>
        </div>
        <div id="contact" class="box">
            <h3>Contact</h3>
            <p>Email: koushal.yadav@example.com</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/koushalyadav" target="_blank">linkedin.com/in/koushalyadav</a></p>
        </div>
    </section>

    <footer>
        <p>Koushal Yadav &copy; 2024</p>
    </footer>
</body>
</html>
