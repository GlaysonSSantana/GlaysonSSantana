<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glayson Santana | Cibersegurança</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        .profile-img {
            border-radius: 50%;
            border: 3px solid #0077b5;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .badges-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 30px 0;
        }
        .badge {
            transition: transform 0.3s;
            width: 120px;
        }
        .badge:hover {
            transform: scale(1.1);
        }
        .skills-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        .skills-table th, .skills-table td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        .skills-table th {
            background-color: #f2f2f2;
        }
        .project-list {
            padding-left: 20px;
        }
        .social-badges {
            margin-top: 30px;
            text-align: center;
        }
        .social-badge {
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="imagens/img2.jpeg" alt="Glayson Santana" class="profile-img">
        <h1>Glayson Santana</h1>
        <h3>Aspirante a Especialista em Cibersegurança</h3>
        
        <div>
            <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" alt="Kali Linux">
            <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco">
            <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
        </div>
    </div>

    <h2>🚀 Minha Jornada</h2>
    <ul>
        <li><strong>Transição profissional:</strong> De suporte técnico para cibersegurança</li>
        <li><strong>Certificações:</strong> CCNA, CyberOps Associate e Hackers do Bem</li>
        <li><strong>Foco atual:</strong> Pentest básico e análise SOC</li>
    </ul>

    <h2>🛠️ Stack Técnica</h2>
    <table class="skills-table">
        <tr>
            <th>Área</th>
            <th>Tecnologias</th>
        </tr>
        <tr>
            <td><strong>Redes</strong></td>
            <td>Cisco Packet Tracer, Wireshark, TCP/IP</td>
        </tr>
        <tr>
            <td><strong>Segurança</strong></td>
            <td>Kali Linux, OWASP ZAP, Nmap, Metasploit</td>
        </tr>
        <tr>
            <td><strong>Cloud</strong></td>
            <td>AWS Fundamentals, Azure Basics</td>
        </tr>
    </table>

    <h2>🏆 Certificações</h2>
    <div class="badges-container">
        <!-- CCNA -->
        <a href="https://www.credly.com/badges/ac7adeef-441b-4168-8c8d-93338ec54493" target="_blank">
            <img src="https://images.credly.com/size/150x150/images/683783d8-eaac-4c37-a14b-431d2b7e399f/CCNA.png" 
                 alt="CCNA: Introduction to Networks" 
                 class="badge">
        </a>
        
        <!-- CyberOps Associate -->
        <a href="https://www.credly.com/badges/d00a45b4-d95b-4d4d-8552-e478e0b21ee1" target="_blank">
            <img src="https://images.credly.com/size/150x150/images/70d71df5-f3dc-4380-9b9d-f22513a70417/CyberOps-Associate.png" 
                 alt="CyberOps Associate" 
                 class="badge">
        </a>
        
        <!-- NDG Linux Essentials -->
        <a href="https://www.credly.com/badges/792578cb-ad5d-4729-beaa-044b7526bf3f" target="_blank">
            <img src="https://images.credly.com/size/150x150/images/2a6251f2-737f-4b6b-b2ec-43a9184794f8/NDG-Linux-Essentials.png" 
                 alt="NDG Linux Essentials" 
                 class="badge">
        </a>
        
        <!-- Cybersecurity Essentials -->
        <a href="https://www.credly.com/badges/148ffdf1-90ee-4ff4-85ae-8aec057c5977" target="_blank">
            <img src="https://images.credly.com/size/150x150/images/2a84d3d2-e874-4e9f-8f6b-137f6a9bfd1a/Cybersecurity-Essentials.png" 
                 alt="Cybersecurity Essentials" 
                 class="badge">
        </a>
        
        <!-- Network Security -->
        <a href="https://www.credly.com/badges/710a641c-e7c0-4128-ae84-a7d1950b737d" target="_blank">
            <img src="https://images.credly.com/size/150x150/images/4c0e2b9b-4e50-4a4a-9d4d-e5f4f87d8433/Network-Security.png" 
                 alt="Network Security" 
                 class="badge">
        </a>
    </div>

    <h2>📌 Projetos Recentes</h2>
    <ol class="project-list">
        <li>
            <strong>Análise de Tráfego com Wireshark</strong> - Detecção de pacotes maliciosos em captura PCAP
        </li>
        <li>
            <strong>Script de Automação em Bash</strong> - Varredura básica de portas e serviços
        </li>
        <li>
            <strong>Relatório OWASP Top 10</strong> - Identificação de vulnerabilidades em aplicações web
        </li>
    </ol>

    <div class="social-badges">
        <h2>🌐 Conecte-se Comigo</h2>
        <a href="https://www.linkedin.com/in/glayson-santana/" target="_blank" class="social-badge">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
        </a>
        <a href="https://www.credly.com/users/glayson-santana" target="_blank" class="social-badge">
            <img src="https://img.shields.io/badge/Credly-FF6B35?style=for-the-badge&logo=credly&logoColor=white" alt="Credly">
        </a>
        <a href="https://github.com/GlaysonSSantana" target="_blank" class="social-badge">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
        </a>
    </div>
</body>
</html>
