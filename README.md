<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yohannes Maye - Developer Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
            color: #e0e0e0;
            padding: 40px;
            max-width: 1000px;
            margin: 0 auto;
            line-height: 1.6;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #00d4ff;
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.5);
            margin-bottom: 15px;
        }
        h1 {
            font-size: 2.8em;
            color: #00d4ff;
            text-shadow: 0 0 15px rgba(0, 212, 255, 0.5);
        }
        h2 {
            font-size: 1.8em;
            color: #ff6f61;
            border-bottom: 2px solid #ff6f61;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        h3 {
            font-size: 1.4em;
            color: #ffd700;
        }
        .section {
            background: rgba(255, 255, 255, 0.05);
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }
        .section:hover {
            transform: translateY(-5px);
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .tech-stack img {
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .tech-stack img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        ul {
            list-style: none;
            padding-left: 20px;
        }
        ul li {
            margin-bottom: 10px;
            position: relative;
        }
        ul li:before {
            content: "🚀";
            position: absolute;
            left: -20px;
            color: #ff6f61;
        }
        a {
            color: #ff4081;
            text-decoration: none;
            font-weight: 600;
        }
        a:hover {
            color: #ff80ab;
            text-decoration: underline;
        }
        .quote {
            text-align: center;
            font-style: italic;
            color: #b0b0b0;
            margin-top: 30px;
            font-size: 1.1em;
        }
        .connect-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/150" alt="Yohannes Maye" class="profile-img">
        <h1>👋 Hello, I'm Yohannes Maye</h1>
        <h3>Fullstack Web & App Developer | CS Student at Bahir Dar University</h3>
        <p>🚀 Passionate about building scalable web and mobile applications with modern technologies.</p>
    </header>

    <div class="section">
        <h2>💻 Tech Stack</h2>
        <div>
            <strong>Frontend:</strong>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js">
                <img src="https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
                <img src="https://img.shields.io/badge/React_Native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native">
                <img src="https://img.shields.io/badge/Remix-%23000.svg?style=for-the-badge&logo=remix&logoColor=white" alt="Remix">
                <img src="https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS">
                <img src="https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
            </div>
        </div>
        <div>
            <strong>Backend:</strong>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express.js">
                <img src="https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" alt="Django">
                <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
            </div>
        </div>
        <div>
            <strong>Database & Cloud:</strong>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
                <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
                <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
                <img src="https://img.shields.io/badge/Firebase-%23FFCA28.svg?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase">
            </div>
        </div>
        <div>
            <strong>Design & Tools:</strong>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
                <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git">
                <img src="https://img.shields.io/badge/VS_Code-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
            </div>
        </div>
    </div>

    <div class="section">
        <h2>🌟 Featured Projects</h2>
        <ul>
            <li><strong>E-Commerce Platform</strong> - Built with Next.js, TailwindCSS, and PostgreSQL. <a href="#">[GitHub]</a></li>
            <li><strong>Task Manager App</strong> - A React Native app with Firebase for real-time syncing. <a href="#">[GitHub]</a></li>
            <li><strong>Portfolio Site</strong> - Designed with Remix and TailwindCSS. <a href="#">[Live Demo]</a></li>
        </ul>
    </div>

    <div class="section">
        <h2>📊 GitHub Stats</h2>
        <p align="center">
            <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dracula" alt="GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=dracula" alt="Top Languages">
        </p>
    </div>

    <div class="section">
        <h2>📫 Connect With Me</h2>
        <div class="connect-links">
            <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
            <a href="https://twitter.com/yourhandle">Twitter/X</a>
            <a href="https://yourportfolio.com">Portfolio</a>
            <a href="mailto:your.email@example.com">Email</a>
        </div>
    </div>

    <p class="quote">"Code is like poetry; it’s all about finding the right rhythm."</p>
</body>
</html>
