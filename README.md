<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Red_circuit_board.jpg/800px-Red_circuit_board.jpg" width="600"/>
</p>

<h1 align="center">Hi there, I'm Arij Selmi! 👋</h1>

<p align="center">
  💻 1st Year Engineering Student | 🚀 Entrepreneurial Spirit | 🌱 Tech Innovator
</p>

<p align="center">
  <strong>I am a</strong>
  <span id="animated-text"></span>
</p>

---

### About Me
- 🌟 Passionate about technology and innovation
- 📚 Learning and growing in computer science and engineering
- 🛠️ Always ready to solve challenging problems
- 💡 Interested in AI, software development, and tech projects

---

### Skills
- Programming: C, C++, Python, JavaScript
- Web Development: HTML, CSS, React
- Database: MySQL, SQLite
- Tools: Git, GitHub, VS Code, Arduino

---

### Contact Me
- ✉️ Email: your.email@example.com
- 🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com)
- 🐦 Twitter: [twitter.com/yourprofile](https://twitter.com)

---

<script>
const words = ["Problem Solver", "Tech Enthusiast", "Innovative Thinker", "Learner"];
let i = 0;
let timer;

function rotateText() {
    const el = document.getElementById("animated-text");
    el.innerHTML = words[i];
    i = (i + 1) % words.length;
    timer = setTimeout(rotateText, 2000);
}

rotateText();
</script>
