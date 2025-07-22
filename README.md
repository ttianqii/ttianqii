<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Header</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
        
        .header-container {
            position: relative;
            width: 100%;
            height: 400px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #000;
        }
        
        .background-image {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: 1;
        }
        
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(
                135deg,
                rgba(0, 0, 0, 0.2) 0%,
                rgba(0, 0, 0, 0.1) 50%,
                rgba(0, 0, 0, 0.3) 100%
            );
            z-index: 2;
        }
        
        .text-container {
            position: relative;
            z-index: 3;
            text-align: center;
            padding: 20px;
        }
        
        .pixel-font {
            font-family: 'Press Start 2P', monospace;
            color: #ffffff;
            text-shadow: 
                2px 2px 0px #000000,
                -2px -2px 0px #000000,
                2px -2px 0px #000000,
                -2px 2px 0px #000000,
                0px 2px 0px #000000,
                2px 0px 0px #000000,
                0px -2px 0px #000000,
                -2px 0px 0px #000000;
            line-height: 1.4;
            letter-spacing: 2px;
        }
        
        .main-title {
            font-size: 28px;
            margin-bottom: 20px;
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        .subtitle {
            font-size: 14px;
            color: #ffdd44;
            text-shadow: 
                2px 2px 0px #000000,
                -2px -2px 0px #000000,
                2px -2px 0px #000000,
                -2px 2px 0px #000000,
                0px 2px 0px #000000,
                2px 0px 0px #000000,
                0px -2px 0px #000000,
                -2px 0px 0px #000000;
        }
        
        @keyframes glow {
            from {
                text-shadow: 
                    2px 2px 0px #000000,
                    -2px -2px 0px #000000,
                    2px -2px 0px #000000,
                    -2px 2px 0px #000000,
                    0px 2px 0px #000000,
                    2px 0px 0px #000000,
                    0px -2px 0px #000000,
                    -2px 0px 0px #000000,
                    0 0 5px #ffffff,
                    0 0 10px #ffffff;
            }
            to {
                text-shadow: 
                    2px 2px 0px #000000,
                    -2px -2px 0px #000000,
                    2px -2px 0px #000000,
                    -2px 2px 0px #000000,
                    0px 2px 0px #000000,
                    2px 0px 0px #000000,
                    0px -2px 0px #000000,
                    -2px 0px 0px #000000,
                    0 0 10px #ffffff,
                    0 0 20px #ffffff,
                    0 0 30px #ff4444;
            }
        }
        
        /* Pixelated effect */
        .pixelated {
            image-rendering: -moz-crisp-edges;
            image-rendering: -webkit-crisp-edges;
            image-rendering: pixelated;
            image-rendering: crisp-edges;
        }
        
        /* Responsive design */
        @media (max-width: 768px) {
            .main-title {
                font-size: 20px;
            }
            .subtitle {
                font-size: 10px;
            }
            .header-container {
                height: 300px;
            }
        }
        
        @media (max-width: 480px) {
            .main-title {
                font-size: 16px;
            }
            .subtitle {
                font-size: 8px;
            }
            .header-container {
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <div class="header-container">
        <!-- Using image from your GitHub repository -->
        <img src="./red-bg1.jpg" alt="Background" class="background-image pixelated">
        <div class="overlay"></div>
        <div class="text-container">
            <h1 class="pixel-font main-title">Hello, I'm Kenji</h1>
            <h2 class="pixel-font subtitle">Jaruphat Kiatchaisiriporn</h2>
        </div>
    </div>
</body>
</html>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=FF3333&center=true&vCenter=true&width=700&lines=BANGKOK+UNIVERSITY+%E3%80%90%E3%83%90%E3%83%B3%E3%82%B3%E3%82%AF%E5%A4%A7%E5%AD%A6%E3%80%91;School+of+Information+Technology+and+Innovation;Computer+Science+Major;ภาษาไทย+ENGLISH+中文+FRANÇAIS+日本語" alt="Typing SVG" />
</div>
<br>
<div align="center">
  
### 🎓 About Me

**💼 BANGKOK UNIVERSITY【バンコク大学】💎**  
**💻 School of Information Technology and Innovation**  
**🎯 Computer Science Major**

</div>

---

## 🛠️ Tech Stack

**Programming Languages**
<p> <img src="https://skillicons.dev/icons?i=js,ts,python,go" style="height:35px;" /> </p>

**Frontend Development**
<p> <img src="https://skillicons.dev/icons?i=html,css,react,nextjs,vue,tailwind" style="height:35px;" /> </p>

**Backend Development**
<p> <img src="https://skillicons.dev/icons?i=nodejs,go" style="height:35px;" /> </p>

**Design & Tools**
<p> <img src="https://skillicons.dev/icons?i=figma,git,github,postman,docker,vscode" style="height:35px;" /> </p>

---

## 📊 GitHub Stats

<div align="center">
  <img width="50%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ttianqii&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" alt="Top Languages" />
  <img width="50%" src="https://github-readme-streak-stats.herokuapp.com/?user=ttianqii&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

## 🏆 GitHub Achievements

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ttianqii&theme=tokyonight&no-frame=true&no-bg=false&margin-w=4&row=1&column=6" alt="GitHub Trophies" />
</div>

---

## 📫 Let's Connect!

<div align="center">

**📧 Email:** jaruphat536@gmail.com

<p>
<a href="mailto:jaruphat536@gmail.com" target="_blank">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://github.com/ttianqii" target="_blank">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
</p>

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=ttianqii&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile Views" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Footer" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/ttianqii/ttianqii/output/snake-green-dots-red-snake.svg" alt="Snake animation" />
</div>




<!---
ttianqii/ttianqii is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
