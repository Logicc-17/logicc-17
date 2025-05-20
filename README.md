<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <style>
    body {
      background-color: #0d1117;
      color: #c9d1d9;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    h1, h3 {
      text-align: center;
      animation: fadeInDown 1s ease-in-out;
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .trophy img {
      transition: transform 0.3s ease-in-out;
      border-radius: 12px;
    }

    .trophy img:hover {
      transform: scale(1.05);
    }

    .section-title {
      border-bottom: 2px solid #58a6ff;
      padding-bottom: 5px;
      margin-top: 40px;
      font-size: 1.5em;
      text-align: left;
      color: #79c0ff;
    }

    .project-card, .tech-stack-icons a {
      display: inline-block;
      margin: 10px;
      transition: all 0.3s ease-in-out;
    }

    .project-card:hover, .tech-stack-icons a:hover {
      transform: scale(1.1);
      filter: drop-shadow(0 0 5px #79c0ff);
    }

    .gif-container img {
      transition: all 0.3s ease-in-out;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }

    .gif-container img:hover {
      transform: rotate(1deg) scale(1.05);
    }

    .stats img {
      max-width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .stats img:hover {
      transform: scale(1.02);
    }

    .footer {
      text-align: center;
      margin-top: 60px;
      font-size: 0.9em;
      color: #8b949e;
    }

    @media (max-width: 600px) {
      .gif-container {
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .gif-container img {
        width: 90%;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

<h1>👋 Hello World, I'm Themba</h1>
<h3>🚀 Fullstack Developer | AI Enthusiast | Malawi</h3>

<div class="trophy" align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy ">
    <img src="https://github-profile-trophy.vercel.app/?username=logicc-17&theme=onedark&row=2&column=4 " alt="logicc-17" />
  </a>
</div>

<div class="section-title">🔥 Current Project</div>
<p align="center" class="project-card">
  <strong>Building an AI Image Generator</strong> - Exploring the intersection of creativity and machine learning
</p>

<div class="section-title">🎮 Fun Side</div>
<div class="gif-container" align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNXFmYjViNWFyNWZudWJveGNrdmc0ODNsaW1rNTI2azZ3NnZ0dmxxNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/zhRA0okWxTGiu78uSk/giphy.gif " width="280" height="200" />
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHY0ejhmMHl1MXFzaDR5cWtiOHl4Z2p0Yzdma2gya3dyaGJ6eHNwYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/DqiMTFxiXx0VaVZQbF/giphy.gif " width="280" height="200" />
</div>

<div class="section-title">🛠️ Tech Stack</div>
<div class="tech-stack-icons" align="center">
  <!-- Frontend -->
  <a href="https://reactjs.org/ " target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg " alt="react" width="50" height="50"/>
  </a>
  <a href="https://flutter.dev " target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg " alt="flutter" width="50" height="50"/>
  </a>

  <!-- Backend -->
  <a href="https://nodejs.org " target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg " alt="nodejs" width="50" height="50"/>
  </a>
  <a href="https://www.djangoproject.com/ " target="_blank" rel="noreferrer">
    <img src="https://cdn.worldvectorlogo.com/logos/django.svg " alt="django" width="50" height="50"/>
  </a>

  <!-- Databases -->
  <a href="https://www.mongodb.com/ " target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg " alt="mongodb" width="50" height="50"/>
  </a>
  <a href="https://www.mysql.com/ " target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg " alt="mysql" width="50" height="50"/>
  </a>

  <!-- AI/ML -->
  <a href="https://www.tensorflow.org " target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg " alt="tensorflow" width="50" height="50"/>
  </a>
  <a href="https://pytorch.org/ " target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg " alt="pytorch" width="50" height="50"/>
  </a>
</div>

<div class="section-title">📊 GitHub Stats</div>
<div class="stats" align="center">
  <img width="45%" src="https://github-readme-stats.vercel.app/api?username=logicc-17&show_icons=true&theme=radical&hide_border=true "/>
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=logicc-17&theme=radical " alt="GitHub Streak"/>
</div>

<div class="stats" align="center">
  <img width="90%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=logicc-17&layout=compact&theme=radical&hide_border=true&langs_count=8 "/>
</div>

<div class="footer" align="center">
  ❤️ Built with passion in Malawi | Made for GitHub Profile 🚀
</div>

</body>
</html>
