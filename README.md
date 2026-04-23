<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KHEMP | Full-Stack Developer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Fira+Code:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --primary: #7c3aed;
            --secondary: #a78bfa;
            --text-main: #e6edf3;
            --text-dim: #8b949e;
            --border-color: #30363d;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            padding-bottom: 50px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        .header-img {
            width: 100%;
            display: block;
            margin-bottom: 20px;
            border-radius: 0 0 12px 12px;
        }

        .center {
            text-align: center;
        }

        .section {
            margin: 40px 0;
        }

        hr {
            border: 0;
            height: 1px;
            background: var(--border-color);
            margin: 40px 0;
        }

        h3 {
            font-size: 1.5rem;
            color: var(--secondary);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .profile-card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 24px;
            font-family: 'Fira Code', monospace;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            position: relative;
            overflow: hidden;
        }

        .profile-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 4px;
            height: 100%;
            background: var(--primary);
        }

        .profile-line {
            margin-bottom: 8px;
            display: flex;
        }

        .profile-label {
            color: var(--secondary);
            width: 80px;
            flex-shrink: 0;
        }

        .profile-value {
            color: var(--text-main);
        }

        .about-content {
            margin-top: 20px;
        }

        .about-list {
            list-style: none;
        }

        .about-list li {
            margin-bottom: 12px;
            display: flex;
            align-items: flex-start;
            gap: 10px;
        }

        .about-list li::before {
            content: '•';
            color: var(--primary);
            font-weight: bold;
        }

        .tech-stack-group {
            margin-bottom: 24px;
        }

        .tech-stack-title {
            font-weight: 600;
            margin-bottom: 12px;
            color: var(--text-dim);
            text-transform: uppercase;
            font-size: 0.8rem;
            letter-spacing: 0.1em;
        }

        .badge-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            justify-content: center;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 16px;
            margin-bottom: 16px;
        }

        @media (max-width: 768px) {
            .stats-grid {
                grid-template-columns: 1fr;
            }
        }

        .float-right {
            float: right;
            margin-left: 20px;
            margin-bottom: 20px;
            border-radius: 12px;
        }

        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }

        .trophy-container {
            margin-top: 20px;
        }

        .trophy-container img {
            max-width: 100%;
        }

        b {
            color: var(--secondary);
            font-weight: 600;
        }
    </style>
</head>
<body>

    <img class="header-img" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:7c3aed,100:a78bfa&height=200&section=header&text=Hey!%20I'm%20KHEMP%20🐝&fontSize=45&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Full-Stack%20Developer%20from%20🇹🇭%20Thailand&descAlignY=58&descSize=18&descColor=e2d9f3" alt="Header" />

    <div class="container">
        <div class="center section">
            <a href="https://github.com/StellarBearX">
                <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2500&pause=800&color=A78BFA&center=true&vCenter=true&multiline=true&width=650&height=80&lines=🌱+Learning+SpringBoot+%7C+FastAPI+%7C+Kotlin;💻+ReactJS+%2F+NextJS+%2F+TypeScript+Enthusiast;🐝+Buzz+Buzz...+Always+Building+Something!" alt="Typing SVG" />
            </a>
            <br />
            <img src="https://komarev.com/ghpvc/?username=StellarBearX&label=👀+Profile+Views&color=7c3aed&style=for-the-badge" alt="Views" />
            <img src="https://img.shields.io/github/followers/StellarBearX?label=Followers&style=for-the-badge&color=a78bfa&labelColor=1a1a2e" alt="Followers" />
        </div>

        <hr />

        <div class="section clearfix">
            <img class="float-right" src="https://i.pinimg.com/originals/00/81/7e/00817ec76a94ec4467d3116ea76c3f33.gif" width="180" alt="Bee animation" />
            
            <h3>About Me</h3>
            
            <div class="profile-card">
                <div class="profile-line"><span class="profile-label">Name</span><span class="profile-value">: KHEMP</span></div>
                <div class="profile-line"><span class="profile-label">From</span><span class="profile-value">: Thailand 🇹🇭</span></div>
                <div class="profile-line"><span class="profile-label">Role</span><span class="profile-value">: Full-Stack Developer</span></div>
                <div class="profile-line"><span class="profile-label">Status</span><span class="profile-value">: Currently Buzzing 🐝</span></div>
            </div>

            <div class="about-content">
                <ul class="about-list">
                    <li>Currently learning <b>SpringBoot, FastAPI, ReactJS, Kotlin</b></li>
                    <li>Ask me about <b>ReactJS, NextJS, TypeScript</b></li>
                    <li>Reach me: <b>kunanan.ws@gmail.com</b></li>
                    <li>Fun fact: I code like a bee — <b>always busy, always building</b> 🍯</li>
                </ul>
            </div>
        </div>

        <hr />

        <div class="section center">
            <h3>Tech Stack</h3>

            <div class="tech-stack-group">
                <div class="tech-stack-title">Frontend</div>
                <div class="badge-grid">
                    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
                    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
                    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
                    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
                    <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue.js" />
                    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
                </div>
            </div>

            <div class="tech-stack-group">
                <div class="tech-stack-title">Backend</div>
                <div class="badge-grid">
                    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
                    <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring" />
                    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
                    <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
                    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
                    <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
                    <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
                </div>
            </div>

            <div class="tech-stack-group">
                <div class="tech-stack-title">Database & Cloud</div>
                <div class="badge-grid">
                    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
                    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
                </div>
            </div>

            <div class="tech-stack-group">
                <div class="tech-stack-title">Tools & Design</div>
                <div class="badge-grid">
                    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
                    <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
                    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
                    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
                </div>
            </div>
        </div>

        <hr />

        <div class="section center">
            <h3>GitHub Stats</h3>
            <div class="stats-grid">
                <img src="https://github-readme-stats.vercel.app/api?username=StellarBearX&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=ffffff&count_private=true" alt="Stats" />
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=StellarBearX&theme=tokyonight&hide_border=true&background=0D1117&stroke=A78BFA&ring=A78BFA&fire=FF6B6B&currStreakLabel=ffffff" alt="Streak" />
            </div>
            <img style="width: 80%; max-width: 400px;" src="https://github-readme-stats.vercel.app/api/top-langs/?username=StellarBearX&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=ffffff&layout=compact&langs_count=8" alt="Top Langs" />
        </div>

        <hr />

        <div class="section center">
            <h3>🏆 Trophies</h3>
            <div class="trophy-container">
                <img src="https://github-profile-trophy.vercel.app/?username=StellarBearX&theme=tokyonight&no-frame=true&no-bg=true" alt="Trophies" />
            </div>
        </div>
    </div>

</body>
</html>
