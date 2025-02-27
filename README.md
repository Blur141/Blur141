<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammed Niyas NF - Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a;
            color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        h1, h2, h3 {
            text-align: center;
            color: #00FF00;
            font-weight: bold;
            margin-top: 20px;
        }

        /* Typing Animation */
        .typing-animation {
            font-family: "Fira Code", monospace;
            font-size: 26px;
            color: #00FF00;
            display: inline-block;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid #00FF00;
            width: 0;
            animation: typing 4s steps(40) 1s forwards, blink 0.75s step-end infinite;
        }

        @keyframes typing {
            to {
                width: 100%;
            }
        }

        @keyframes blink {
            50% {
                border-color: transparent;
            }
        }

        section {
            padding: 40px 20px;
            text-align: center;
            margin-bottom: 40px;
        }

        .badge-container img {
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .badge-container img:hover {
            transform: scale(1.1);
        }

        .connect-links a {
            margin: 10px;
            text-decoration: none;
        }

        .connect-links img {
            transition: transform 0.3s ease;
        }

        .connect-links img:hover {
            transform: scale(1.1);
        }

        .stats-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .stats-container img {
            margin: 10px;
        }
    </style>
</head>
<body>

<!-- Typing Animation -->
<div align="center">
    <h1 class="typing-animation">Linux Admin | DevOps Enthusiast | Automation Specialist | AWS Certified</h1>
    <h3 class="typing-animation">Zabbix & Grafana Expert</h3>
</div>

<!-- About Me -->
<section>
    <h2>👨💻 About Me</h2>
    <p>
        I'm a **Linux Systems Administrator** at Gerab Sys with **7+ months** of hands-on experience in infrastructure management and monitoring. Transitioning into DevOps, I specialize in:
    </p>
    <ul>
        <li>🐧 **Linux Administration** (Oracle Linux, Ubuntu Server)</li>
        <li>📊 **Monitoring Solutions** (Zabbix, Grafana, ILOM)</li>
        <li>🤖 **Automation** (Bash, Ansible, OLVM)</li>
        <li>☁️ **Cloud & DevOps** (AWS, CI/CD pipelines)</li>
    </ul>
    <p>**Currently sharpening:** Advanced Bash scripting, Kubernetes, and Terraform</p>
</section>

<!-- Technical Stack -->
<section>
    <h2>🛠️ Technical Stack</h2>
    <h3>Core Expertise</h3>
    <div class="badge-container">
        <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/Ansible-%231A1918?style=for-the-badge&logo=ansible&logoColor=white" />
        <img src="https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=white" />
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
    </div>
    <h3>Working Knowledge</h3>
    <div class="badge-container">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
        <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white" />
        <img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
    </div>
</section>

<!-- GitHub Stats -->
<section>
    <h2>📈 GitHub Stats</h2>
    <div class="stats-container">
        <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Blur141&show_icons=true&theme=dark&hide_border=true" />
    </div>
</section>

<!-- Connect Section -->
<section>
    <h2>🤝 Let's Connect</h2>
    <div class="connect-links">
        <a href="https://www.linkedin.com/in/mohammedniyasnf/">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
        <a href="https://medium.com/@mohammedniyas654">
            <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
        </a>
        <a href="mailto:mohammedniyas654@gmail.com">
            <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
        </a>
    </div>
</section>

</body>
</html>
