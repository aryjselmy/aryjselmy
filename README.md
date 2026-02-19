<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Arij Selmi - Profile</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            background-color: #f9f9f9;
            color: #333;
        }

        #animated-text {
            color: #e63946;
            font-weight: bold;
        }

        img {
            border-radius: 10px;
            max-width: 250px;
            height: auto;
            margin-bottom: 20px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        a {
            color: #1d3557;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <!-- IMAGE -->
    <img src="ChatGPT Image 19 févr. 2026, 23_23_53.png" alt="My Photo">

    <h1>Hi there, I'm Arij Selmi 👋</h1>
    <p>💻 Engineering Student | 🚀 Entrepreneurial Spirit | 🌱 Tech Innovator</p>

    <p><strong>I am a </strong><span id="animated-text"></span></p>

    <hr>

    <h2>About Me</h2>
    <ul>
        <li>🌟 Passionate about technology and innovation</li>
        <li>📚 Growing in computer science and engineering</li>
        <li>🛠️ Love solving challenging problems</li>
        <li>💡 Interested in AI & Software Development</li>
    </ul>

    <h2>Skills</h2>
    <ul>
        <li>Programming: C, C++, Python, JavaScript</li>
        <li>Web: HTML, CSS, React</li>
        <li>Database: MySQL, SQLite</li>
        <li>Tools: Git, GitHub, VS Code, Arduino</li>
    </ul>

    <h2>Contact</h2>
    <ul>
        <li>✉️ School: selmi.arij@esprit.com</li>
        <li>✉️ Personal: arijselmi580@gmail.com</li>
        <li>🔗 LinkedIn: <a href="https://linkedin.com" target="_blank">linkedin.com</a></li>
        <li>🐦 Twitter: <a href="https://twitter.com" target="_blank">twitter.com</a></li>
    </ul>

    <script>
        const words = ["Problem Solver", "Tech Enthusiast", "Innovative Thinker", "Learner"];
        let i = 0;

        function rotateText() {
            document.getElementById("animated-text").textContent = words[i];
            i = (i + 1) % words.length;
            setTimeout(rotateText, 2000);
        }

        rotateText();
    </script>

</body>
</html>
