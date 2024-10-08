<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jorge - React Web Developer</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f9;
      color: #333;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 20px;
      text-align: center;
      background: #fff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }

    h1 {
      font-size: 3em;
      color: #007acc;
      margin-bottom: 10px;
    }

    .tagline {
      font-style: italic;
      color: #666;
      font-size: 1.2em;
      margin-bottom: 30px;
    }

    .content {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }

    .box {
      width: 45%;
      margin-bottom: 20px;
      padding: 20px;
      background-color: #f0f8ff;
      border-left: 5px solid #007acc;
      border-radius: 5px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .box h2 {
      margin-top: 0;
      color: #007acc;
    }

    .box p {
      font-size: 1em;
      color: #444;
    }

    .skills {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .skills div {
      background: #007acc;
      color: white;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 50px;
      font-size: 1.1em;
      transition: background 0.3s;
    }

    .skills div:hover {
      background: #005f99;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Jorge - React Web Developer</h1>
    <p class="tagline">"Building sleek, interactive web applications"</p>

    <div class="content">
      <div class="box">
        <h2>Tech Stack</h2>
        <p>🔧 I work with: <strong>.js, .html, .css, .py, .ai</strong></p>
      </div>

      <div class="box">
        <h2>What I Do</h2>
        <p>💻 I specialize in React for frontend development, creating seamless user experiences and scalable web apps.</p>
      </div>

      <div class="box">
        <h2>Open Source Enthusiast</h2>
        <p>🌱 Currently learning all about **Open Source** and contributing to community-driven projects.</p>
      </div>

      <div class="box">
        <h2>Contact Me</h2>
        <p>💬 Ping me about design, React, Python, development, or design thinking.</p>
      </div>
    </div>

    <div class="skills">
      <div>React</div>
      <div>JavaScript</div>
      <div>HTML</div>
      <div>CSS</div>
      <div>Python</div>
      <div>Design Thinking</div>
    </div>
  </div>

</body>
</html>




