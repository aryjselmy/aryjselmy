<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arij Selmi - Profile</title>
<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    text-align: center;
    background-color: #f9f9f9;
    color: #333;
    padding: 20px;
  }
  img {
    margin-top: 20px;
    border-radius: 10px;
  }
  #animated-text {
    color: #e63946;
    font-weight: bold;
  }
</style>
</head>
<body>

<h1>Hi there, I'm Arij Selmi! 👋</h1>
<p>💻 1st Year Engineering Student | 🚀 Entrepreneurial Spirit | 🌱 Tech Innovator</p>

<p><strong>I am a</strong> <span id="animated-text"></span></p>

<hr>

<h2>About Me</h2>
<ul style="list-style:none; padding:0;">
  <li>🌟 Passionate about technology and innovation</li>
  <li>📚 Learning and growing in computer science and engineering</li>
  <li>🛠️ Always ready to solve challenging problems</li>
  <li>💡 Interested in AI, software development, and tech projects</li>
</ul>

<h2>Skills</h2>
<ul style="list-style:none; padding:0;">
  <li>Programming: C, C++, Python, JavaScript</li>
  <li>Web Development: HTML, CSS, React</li>
  <li>Database: MySQL, SQLite</li>
  <li>Tools: Git, GitHub, VS Code, Arduino</li>
</ul>

<h2>Contact Me</h2>
<ul style="list-style:none; padding:0;">
  <li>✉️ School Email: selmi.arij@esprit.com</li>
  <li>✉️ Personal Email: arijselmi580@gmail.com</li>
  <li>🔗 LinkedIn: <a href="https://linkedin.com" target="_blank">linkedin.com/in/yourprofile</a></li>
  <li>🐦 Twitter: <a href="https://twitter.com" target="_blank">twitter.com/yourprofile</a></li>
</ul>

<!-- L'image en bas -->
<p>
  <img src="ChatGPT Image 19 févr. 2026, 23_23_53.png" width="400" alt="Mon Image"/>
</p>

<script>
const words = ["Problem Solver", "Tech Enthusiast", "Innovative Thinker", "Learner"];
let i = 0;

function rotateText() {
    const el = document.getElementById("animated-text");
    el.innerHTML = words[i];
    i = (i + 1) % words.length;
    setTimeout(rotateText, 2000);
}

rotateText();
</script>

</body>
</html>
