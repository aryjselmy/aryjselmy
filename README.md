<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Arij Profile</title>

    <style>
        body {
            font-family: Arial;
            text-align: center;
            background-color: #f9f9f9;
        }
        #animated-text {
            color: red;
            font-weight: bold;
        }
    </style>
</head>

<body>

<h1>Hi I'm Arij 👋</h1>
<p>I am a <span id="animated-text"></span></p>

<script>
window.onload = function() {

    const words = ["Problem Solver", "Tech Enthusiast", "Learner"];
    let i = 0;

    function rotate() {
        document.getElementById("animated-text").innerHTML = words[i];
        i = (i + 1) % words.length;
    }

    rotate();
    setInterval(rotate, 2000);
};
</script>

</body>
</html>
