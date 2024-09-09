<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Felipe's GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        #header {
            background-color: #282c34;
            color: #61dafb;
            padding: 20px;
            border-radius: 10px;
            margin: 20px;
        }
        img {
            border-radius: 10px;
        }
        h1, h3 {
            margin: 0;
        }
        #animation-container {
            margin: 20px;
            padding: 20px;
        }
        .pulse {
            display: inline-block;
            width: 100px;
            height: 100px;
            background-color: #61dafb;
            border-radius: 50%;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% {
                transform: scale(1);
                opacity: 1;
            }
            50% {
                transform: scale(1.2);
                opacity: 0.5;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div id="header">
        <img src="https://media.giphy.com/media/btwPhnNxMZgBIA5gHj/giphy.gif" width="200" alt="Felipe's GIF"/>
        <h1>Hello, I'm Felipe :)</h1>
        <h3>I'm from Colombia, and I enjoy programming while listening to music :b<br>Systems Engineering student at UDEC</h3>
    </div>

    <div id="animation-container">
        <div class="pulse"></div>
        <p>Welcome to my GitHub profile!</p>
    </div>

    <script>
        // Simple animation with JavaScript
        const pulse = document.querySelector('.pulse');
        let growing = true;

        function animatePulse() {
            if (growing) {
                pulse.style.transform = 'scale(1.5)';
                growing = false;
            } else {
                pulse.style.transform = 'scale(1)';
                growing = true;
            }
        }

        setInterval(animatePulse, 1000);
    </script>
</body>
</html>

<!--
**FeliEraso03/FeliEraso03** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
