<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohit Singh - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      text-align: center;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    h1, h2, h4 {
      margin: 0;
    }

    h1 {
      font-size: 3em;
      margin-top: 20px;
      animation: fadeIn 2s ease-in-out;
    }

    h2 {
      font-size: 2em;
      color: #555;
      margin: 10px 0;
      animation: slideIn 1.5s ease-in-out;
    }

    h4 {
      font-size: 1.2em;
      line-height: 1.6;
      animation: fadeUp 2s ease-in-out;
    }

    a {
      text-decoration: none;
      color: #007BFF;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #0056b3;
    }

    .badges {
      margin: 30px 0;
      display: inline-block;
      animation: zoomIn 2s ease-in-out;
    }

    img {
      margin: 10px;
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.1);
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideIn {
      from { transform: translateY(-30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes zoomIn {
      from { transform: scale(0.9); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
  </style>
</head>
<body>

<h1>👋 Hi Visitor</h1>

<h2>I'm Rohit Singh!</h2>

<h4>
  - 👀 Passionate about exploring the world of technology through code.<br>
  - 🌱 Currently diving deep into C++ and sharpening my skills.<br>
  - 💞️ Open to collaborating on exciting projects and contributing to open-source communities.<br>
  - 📫 Reach me on Twitter: <a href="https://twitter.com/CodebyRoS" target="_blank">@CodebyRoS</a><br>
  - 😄 Pronouns: he/him<br>
  - ⚡ Fun fact: I have a blend of sophistication and a great sense of humor.<br>
</h4>

<div class="badges">
  <h3>Currently learning:</h3>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++ Badge">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C Badge">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
</div>

<div class="badges">
  <h3>Front-end technologies:</h3>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge">
</div>

<div class="badges">
  <h3>Tools:</h3>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git Badge">
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="VS Code Badge">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux Badge">
</div>

</body>
</html>
