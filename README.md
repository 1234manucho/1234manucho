<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHILLS CODER · README</title>
    <!-- Font for consistency (optional) -->
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* minimal reset for better rendering on github dark/light — but keeps the vibe */
        body { background: #0B1F3A; margin: 0; padding: 20px; display: flex; justify-content: center; font-family: 'JetBrains Mono', monospace; }
        .readme-card {
            max-width: 1100px;
            width: 100%;
            background: #0B1F3A; /* deep navy base */
            color: #e0e0e0;
            border-radius: 32px;
            padding: 24px 32px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.8), 0 0 0 2px #FFD70020;
        }
        /* make all SVG and images play nice */
        img, svg {
            max-width: 100%;
            vertical-align: middle;
        }
        /* stylish divider */
        .divider-custom {
            height: 2px;
            background: linear-gradient(90deg, transparent, #FFD700 20%, #FFD700 80%, transparent);
            margin: 30px 0 20px 0;
            opacity: 0.6;
        }
        /* glow for bot container */
        .bot-spotlight {
            background: #0a1a30;
            border-radius: 60px;
            padding: 10px 20px 5px 20px;
            display: inline-block;
            margin: 10px auto;
            box-shadow: 0 0 30px #ffd70040;
            border: 1px solid #FFD70030;
        }
        /* headings gold */
        h1, h2, h3 {
            color: #FFD700;
            letter-spacing: 1px;
        }
        a {
            text-decoration: none;
        }
        .badge-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            justify-content: center;
        }
        .stats-wrapper {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
    </style>
</head>
<body>
<div class="readme-card">

    <!-- ================= HEADER ================= -->
    <div align="center">
        <!-- using image from capsul render (public url) but keep it -->
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:142850&height=230&section=header&text=CHILLS%20CODER&fontSize=58&fontColor=FFD700&animation=fadeIn" alt="header wave" style="max-width: 100%; border-radius: 20px 20px 0 0;" />
        <br/>
        <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=28&duration=3000&pause=1000&color=FFD700&center=true&vCenter=true&width=900&lines=Full+Stack+Engineer;AI+%2B+Cloud+Builder;Automation+Architect;Data-Driven+Developer" alt="typing svg" />
    </div>

    <!-- divider -->
    <div class="divider-custom"></div>

    <!-- ================= CHILLS-BOT (IMPROVED VISIBILITY) ================= -->
    <div align="center">
        <div class="bot-spotlight">
            <!-- ORIGINAL SVG with preserved animations — directly embedded, large & visible -->
            <svg width="280" height="300" viewBox="0 0 240 260" xmlns="http://www.w3.org/2000/svg">
                <style>
                    @keyframes blink {
                        0%, 92%, 100% { transform: scaleY(1); }
                        94%, 96% { transform: scaleY(0.1); }
                    }
                    @keyframes bob {
                        0%, 100% { transform: translateY(0); }
                        50% { transform: translateY(4px); }
                    }
                    @keyframes wave {
                        0%, 100% { transform: rotate(0deg); }
                        50% { transform: rotate(18deg); }
                    }
                    @keyframes pulse {
                        0%, 100% { opacity: 0.6; }
                        50% { opacity: 1; }
                    }
                    @keyframes glow {
                        0% { filter: drop-shadow(0 0 4px #FFD700); }
                        50% { filter: drop-shadow(0 0 12px #FFD700); }
                        100% { filter: drop-shadow(0 0 4px #FFD700); }
                    }
                    .bot { animation: bob 3s ease-in-out infinite; }
                    .eye { animation: blink 5s infinite; transform-origin: center; }
                    .hand { transform-origin: top center; animation: wave 3s infinite ease-in-out; }
                    .antenna { animation: pulse 2s infinite; }
                    .core { animation: glow 2.5s infinite; }
                </style>
                <!-- Antenna -->
                <line x1="120" y1="20" x2="120" y2="45" stroke="#FFD700" stroke-width="4"/>
                <circle cx="120" cy="15" r="7" class="antenna" fill="#FFD700"/>

                <!-- Robot -->
                <g class="bot">
                    <rect x="40" y="45" rx="24" ry="24" width="160" height="130" fill="#0B1F3A"/>

                    <!-- Eyes -->
                    <circle cx="85" cy="95" r="10" class="eye" fill="#FFD700"/>
                    <circle cx="155" cy="95" r="10" class="eye" fill="#FFD700"/>

                    <!-- Smile -->
                    <path d="M85 125 Q120 145 155 125" stroke="#FFD700" stroke-width="4" fill="none"/>

                    <!-- AI Core -->
                    <circle cx="120" cy="155" r="10" class="core" fill="#FFD700"/>

                    <!-- Hands -->
                    <rect x="18" y="105" width="22" height="70" rx="10" fill="#142850"/>
                    <rect x="200" y="105" width="22" height="70" rx="10" class="hand" fill="#142850"/>
                </g>

                <!-- Feet -->
                <rect x="80" y="185" width="30" height="18" rx="8" fill="#142850"/>
                <rect x="130" y="185" width="30" height="18" rx="8" fill="#142850"/>
            </svg>
            <br/>
            <span style="color:#FFD700; font-size: 1.4rem; font-weight: 600;">⚡ CHILLS-BOT · AI Mascot ⚡</span>
            <br/>
            <span style="color:#ccc;">AI-Powered • Data-Driven • Always Building</span>
        </div>
    </div>

    <!-- divider -->
    <div class="divider-custom"></div>

    <!-- 💫 About Me -->
    <h2>💫 About Me</h2>
    <p>I’m a <strong>Full Stack Engineer</strong> building <strong>scalable, intelligent, and data-driven systems</strong> across web, cloud, and automation ecosystems.</p>
    <p><strong>What I specialize in</strong><br/>
    🚀 Modern Web Engineering <br/>
    ☁️ Cloud-Native Architectures <br/>
    🤖 AI-Assisted Automation <br/>
    📊 Data Science & Analytics</p>
    <p>I turn <strong>ideas → production systems → scalable platforms</strong>.</p>

    <div class="divider-custom"></div>

    <!-- 🌐 Portfolio -->
    <h2>🌐 Portfolio</h2>
    <div align="center">
        <a href="https://portfolio-3ee27.web.app/">
            <img src="https://img.shields.io/badge/View%20Live%20Portfolio-0B1F3A?style=for-the-badge&logo=vercel&logoColor=FFD700" alt="portfolio"/>
        </a>
        <br/><br/>
        <!-- Using microlink screenshot – as before -->
        <img src="https://api.microlink.io/?url=https://portfolio-3ee27.web.app/&screenshot=true&meta=false&embed=screenshot.url" width="900" style="border-radius: 20px; border: 2px solid #FFD70040;" alt="portfolio preview"/>
    </div>

    <div class="divider-custom"></div>

    <!-- 🌍 Connect -->
    <h2>🌍 Connect With Me</h2>
    <div align="center" class="badge-grid">
        <a href="https://instagram.com/baba_kaunty"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="instagram"/></a>
        <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-0B1F3A?style=for-the-badge&logo=linkedin&logoColor=FFD700" alt="linkedin"/></a>
        <a href="https://x.com"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=twitter&logoColor=white" alt="X"/></a>
        <a href="mailto:onecocktail@gmail.com"><img src="https://img.shields.io/badge/Email-0B1F3A?style=for-the-badge&logo=gmail&logoColor=FFD700" alt="email"/></a>
    </div>

    <div class="divider-custom"></div>

    <!-- 🚀 Core Tech Stack -->
    <h2>🚀 Core Tech Stack</h2>
    <div align="center">
        <!-- skillicons lineup (as before) -->
        <img src="https://skillicons.dev/icons?i=python,js,ts,java,kotlin,go,php,c,cpp,csharp,r,scala,swift,rust,dart,html,css,react,next,nodejs,flask,django,laravel,angular,mongodb,mysql,postgres,sqlite,firebase,docker,kubernetes,aws,gcp,azure,git,linux,nginx,tensorflow,pytorch&perline=12" alt="tech stack"/>
    </div>

    <div class="divider-custom"></div>

    <!-- 📊 GitHub Analytics -->
    <h2>📊 GitHub Analytics</h2>
    <div align="center" class="stats-wrapper">
        <img height="180em" src="https://github-readme-stats.vercel.app/api?username=1234manucho&show_icons=true&hide_border=true&bg_color=0B1F3A&title_color=FFD700&icon_color=FFD700&text_color=FFFFFF" alt="stats"/>
        <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=1234manucho&layout=compact&hide_border=true&bg_color=0B1F3A&title_color=FFD700&text_color=FFFFFF" alt="top langs"/>
    </div>

    <!-- 🔥 Contribution Streak -->
    <h2>🔥 Contribution Streak</h2>
    <div align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com?user=1234manucho&fire=FFD700&ring=FFD700&currStreakLabel=FFD700&hide_border=true" alt="streak"/>
    </div>

    <!-- 🧬 GitHub Trophies -->
    <h2>🧬 GitHub Trophies</h2>
    <div align="center">
        <img src="https://github-profile-trophy.vercel.app/?username=1234manucho&theme=onedark&no-frame=true&row=1&column=7" alt="trophies"/>
    </div>

    <!-- 🧠 Recent Activity -->
    <h2>🧠 Recent Activity</h2>
    <div align="center">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=1234manucho&bg_color=0B1F3A&color=FFD700&line=FFD700&point=FFFFFF&hide_border=true" alt="activity graph" width="100%"/>
    </div>

    <!-- Latest Repositories -->
    <h2>🧠 Latest Repositories</h2>
    <div align="center" style="display: flex; flex-wrap: wrap; gap: 16px; justify-content: center;">
        <!-- using github-readme-stats pin cards -->
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=1234manucho&repo=NjiaMoja&hide_border=true&bg_color=0B1F3A&title_color=FFD700" alt="NjiaMoja"/>
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=1234manucho&repo=AgriTrue&hide_border=true&bg_color=0B1F3A&title_color=FFD700" alt="AgriTrue"/>
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=1234manucho&repo=WorkLinkAfrica&hide_border=true&bg_color=0B1F3A&title_color=FFD700" alt="WorkLinkAfrica"/>
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=1234manucho&repo=MachineAnalyzer&hide_border=true&bg_color=0B1F3A&title_color=FFD700" alt="MachineAnalyzer"/>
    </div>

    <!-- 🐍 Contribution Snake (dark version) -->
    <h2>🐍 Contribution Snake</h2>
    <div align="center">
        <img src="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake-dark.svg" alt="snake" style="background: #0a1a2a; border-radius: 20px;"/>
    </div>

    <!-- 👁 Profile Views -->
    <h2>👁 Profile Views</h2>
    <div align="center">
        <img src="https://komarev.com/ghpvc/?username=1234manucho&label=Profile%20Views&color=FFD700&style=for-the-badge" alt="views"/>
    </div>

    <!-- 💰 Support -->
    <h2>💰 Support My Work</h2>
    <div align="center">
        <a href="https://paypal.me/onecocktail544@gmail.com"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="paypal"/></a>
    </div>

    <!-- footer wave -->
    <div align="center">
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:142850,100:0B1F3A&height=120&section=footer" alt="footer wave" style="border-radius: 0 0 20px 20px;"/>
    </div>

    <!-- small note: everything is original, bot now more visible and stylized -->
    <br/>
    <div align="center">
        <span style="color: #FFD700;">⚡ CHILLS CODER · full stack energy ⚡</span>
    </div>
</div>
</body>
</html>