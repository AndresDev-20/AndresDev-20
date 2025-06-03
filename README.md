<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AndresDev Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.8;
      margin: 0;
      padding: 0;
    }

    header {
      text-align: center;
      background-color: #fff;
      padding: 40px 20px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    header img {
      max-width: 100%;
      height: auto;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    h1, h2 {
      color: #2E7D32;
      text-align: center;
    }

    p {
      font-size: 18px;
      text-align: center;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li::before {
      content: "✅ ";
      color: #4CAF50;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    th, td {
      padding: 12px;
      border: 1px solid #ddd;
    }

    thead {
      background-color: #e8f5e9;
    }

    tbody tr:nth-child(even) {
      background-color: #f1f8e9;
    }

    .stats {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
      margin-top: 30px;
    }

    blockquote {
      font-style: italic;
      border-left: 4px solid #4CAF50;
      padding-left: 20px;
      margin-top: 30px;
      color: #666;
    }

    @media (min-width: 600px) {
      .stats {
        flex-direction: row;
        justify-content: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="./Images/Header.png" alt="Header Image">
  </header>

  <main class="container">
    <h1>👋 Know a little about me 👨‍💻</h1>
    <p>
      I am a passionate Full-Stack Developer dedicated to creating modern and functional web applications. 
      Learning new technologies and solving challenging problems through code is my superpower. 🚀
    </p>

    <h2>🛠️ My Main Skills</h2>
    <ul>
      <li><strong>Languages:</strong> JavaScript, TypeScript, Python, Java</li>
      <li><strong>Frontend:</strong> React.js, Redux, Tailwind CSS</li>
      <li><strong>Backend:</strong> Node.js, Express.js, Spring Boot</li>
      <li><strong>Databases:</strong> MySQL, PostgreSQL, MongoDB, SQLite</li>
      <li><strong>Tools:</strong> Git/GitHub, Figma, Postman</li>
    </ul>

    <h2>📌 Featured Projects</h2>
    <table>
      <thead>
        <tr>
          <th>Project</th>
          <th>Description</th>
          <th>Technologies</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Computers Store (Vanilla)</strong></td>
          <td>A simulated online store using HTML, CSS, and JS Vanilla.</td>
          <td>HTML, CSS, JS</td>
        </tr>
        <tr>
          <td><strong>Pokedex Frontend</strong></td>
          <td>Pokedex app with React and Pokémon API.</td>
          <td>React.js, CSS</td>
        </tr>
        <tr>
          <td><strong>TheraClinic</strong></td>
          <td>Clinic management system, complete frontend and backend.</td>
          <td>Node.js, React, MongoDB</td>
        </tr>
        <tr>
          <td><strong>Rick and Morty App</strong></td>
          <td>Character visualization app from Rick and Morty using React.</td>
          <td>React.js, Public API</td>
        </tr>
      </tbody>
    </table>

    <h2>👨‍💻 About Me</h2>
    <ul>
      <li>🌍 I am from Ibagué, Tolima, Colombia.</li>
      <li>🕒 My time zone is GMT-5.</li>
      <li>🎓 Currently specializing in full-stack web development.</li>
      <li>🧠 Passionate about learning new technologies like Next.js.</li>
      <li>✨ Always looking for new challenges and opportunities to grow!</li>
    </ul>

    <h2>📊 GitHub Stats</h2>
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api?username=AndresDev-20&show_icons=true&theme=radical" 
           alt="GitHub Stats"/>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AndresDev-20&layout=compact&theme=radical" 
           alt="Top Languages"/>
    </div>

    <h2>🌟 Inspiring Quote</h2>
    <blockquote>
      "Code is like art: there is always something new to discover and learn. Never stop creating." 🌟
    </blockquote>
  </main>
</body>
</html>
