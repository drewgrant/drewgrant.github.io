<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drew Grant - Professional Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
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
            border-bottom: #bbb 1px solid;
        }
        header h1 {
            text-align: center;
            text-transform: uppercase;
            margin: 0;
        }
        header img {
            position: absolute;
            top: 100px;
            right: 100px;
            height: 100px; /* Adjust the height as needed */
            /*border-radius: 50%; /* Optional: makes the image round */
        }
        nav ul {
            padding: 0;
            list-style: none;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        .main-content {
            display: flex;
            justify-content: space-between;
            padding: 20px 0;
        }
        .content-section {
            width: 48%;
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .content-section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .publication-list {
            list-style: none;
            padding: 0;
        }
        .publication-list li {
            margin-bottom: 10px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Drew Grant</h1>
            <img src="/docs/assets/img/headshot2.jpg">
            <nav>
                <ul>
                    <li><a href="#skills">Technical Skills</a></li>
                    <li><a href="#publications">Publications</a></li>
                    <li><a href="#research">Research Interests</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <div class="main-content">
            <div id="skills" class="content-section">
                <h2>Technical Skills</h2>
                <ul>
                    <li>Programming Languages: Python, C++</li>
                    <li>Web Technologies: HTML, CSS, JavaScript</li>
                    <li>Database Management: SQL, MongoDB</li>
                    <li>Tools: Git, Docker, Jenkins</li>
                    <li>Operating Systems: Linux, Windows</li>
                </ul>
            </div>
            <div id="publications" class="content-section">
                <h2>Publications</h2>
                <ul class="publication-list">
                    <li><strong>Author 1, Author 2</strong>. "Title of the Paper". <em>Journal Name</em>, Year.</li>
                    <li><strong>Author 1, Author 2</strong>. "Title of the Paper". <em>Conference Name</em>, Year.</li>
                    <li><strong>Author 1, Author 2</strong>. "Title of the Paper". <em>Journal Name</em>, Year.</li>
                </ul>
            </div>
        </div>
        <div id="research" class="content-section">
            <h2>Research Interests</h2>
            <p>
                I am particularly interested in the following research areas:
            </p>
            <ul>
                <li>Artificial Intelligence and Machine Learning</li>
                <li>Data Analytics and Big Data</li>
                <li>Software Development and Engineering</li>
                <li>Cybersecurity</li>
                <li>Human-Computer Interaction</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Drew Grant. All Rights Reserved.</p>
    </footer>
</body>
</html>
