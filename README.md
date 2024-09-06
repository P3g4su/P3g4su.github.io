<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo de Pedro Augusto Nunes Machado</title>
    <style>
        body {
            background-color: #000;
            color: #00FF00;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            box-sizing: border-box;
        }

        .container {
            width: 80%;
            max-width: 1000px;
            height: 90%;
            border: 1px solid #00FF00;
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.5);
            background-color: #000;
            padding: 20px;
            position: relative;
            overflow-y: auto;
            border-radius: 10px;
            z-index: 1;
            scrollbar-color: #00FF00 #000; /* Firefox */
            scrollbar-width: thin; /* Firefox */
        }

        .container::-webkit-scrollbar {
            width: 12px; /* largura da barra de rolagem */
        }

        .container::-webkit-scrollbar-track {
            background: #000; /* cor do fundo da faixa da barra de rolagem */
        }

        .container::-webkit-scrollbar-thumb {
            background-color: #00FF00; /* cor da barra de rolagem */
            border-radius: 10px; /* cantos arredondados da barra de rolagem */
            border: 3px solid #000; /* borda ao redor da barra de rolagem */
        }

        h1, h2, h3 {
            color: #00FF00;
            border-bottom: 1px solid #00FF00;
            padding-bottom: 5px;
        }

        h1 {
            font-size: 2em;
            text-align: center;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.5em;
            margin-top: 20px;
        }

        h3 {
            font-size: 1.2em;
            margin-top: 10px;
        }

        pre {
            background: #111;
            border: 1px solid #00FF00;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
            white-space: pre-wrap;
            margin: 10px 0;
        }

        .photo {
            text-align: center;
            margin: 20px 0;
        }

        .photo img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 2px solid #00FF00;
        }

        .interactive {
            margin-top: 20px;
            text-align: center;
        }

        .interactive a {
            display: inline-block;
            color: #00FF00;
            text-decoration: none;
            font-size: 18px;
            margin: 10px 15px;
            text-align: center;
            padding: 10px 20px;
            border: 2px solid #00FF00;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        .interactive a:hover {
            background-color: #00FF00;
            color: #000;
        }

        .secret-button {
            position: fixed;
            top: 0;
            left: 0;
            width: 30px;
            height: 30px;
            background-color: #000;
            border: 2px solid #00FF00;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #00FF00;
            cursor: pointer;
            font-size: 18px;
            text-align: center;
            line-height: 30px;
            transition: background-color 0.3s, opacity 0.3s;
            z-index: 2;
            opacity: 0;
        }

        .secret-button:hover {
            background-color: #00FF00;
            color: #000;
            opacity: 1;
        }

        .matrix {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .matrix div {
            position: absolute;
            top: -100%;
            animation: drop 5s linear infinite;
            color: #00FF00;
            font-size: 20px;
            text-shadow: 0 0 5px #00FF00;
        }

        @keyframes drop {
            to {
                top: 100%;
            }
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -2;
        }

        .stars div {
            position: absolute;
            background: #FFF;
            border-radius: 50%;
            opacity: 0.8;
            animation: twinkle 1.5s infinite alternate;
        }

        @keyframes twinkle {
            from {
                opacity: 0.5;
            }
            to {
                opacity: 1;
            }
        }

        .footer {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            text-align: center;
            font-size: 14px;
            color: #00FF00;
            padding: 10px;
            background-color: #000;
        }
    </style>
</head>
<body>
    <div class="matrix"></div>
    <div class="stars"></div>

    <div class="container">
        <div class="photo">
            <img src="eu.jpeg" alt="Pedro Augusto Nunes Machado">
        </div>

        <h1>Pedro Augusto Nunes Machado</h1>
        <pre><code>
$ profissão="Estudante de Defesa Cibernética | Python | Hardware hacking | Técnico em Automação Industrial"
$ idade="18 anos"
$ descrição="Apaixonado por tecnologia desde cedo, com uma vontade constante de aprender e me aperfeiçoar. Em busca da minha primeira oportunidade profissional, onde possa aplicar minhas habilidades e colaborar em equipe para alcançar grandes resultados. Sou determinado, dedicado e sempre pronto para novos desafios."
$ local="Suzano, São Paulo, Brasil"
$ contato="11 98781-9675 | panmachado301@gmail.com"
        </code></pre>

        <h2>Resumo</h2>
        <pre><code>
$ resumo="Estudante de Defesa Cibernética, com formação técnica em Automação Industrial. Começando a jornada com Linux e segurança de redes. Busco oportunidades para crescer profissionalmente, aplicar conhecimentos e contribuir para projetos desafiadores."
        </code></pre>

        <h2>Principais Competências</h2>
        <pre><code>
$ competencias=(
    "Administração de Sistemas Linux: Conhecimento básico em instalação e configuração de servidores Linux."
    "Segurança de Redes: Introdução a conceitos de segurança e monitoramento de tráfego de rede."
    "Automação de Processos: Desenvolvimento de scripts em Python para automação de tarefas."
    "Hardware Hacking: Experiência com Arduino, ESP32, e RFID."
    "Gestão de Projetos: Aplicação de metodologias Six Sigma para resolução de problemas."
)
        </code></pre>

        <h2>Formação Acadêmica</h2>
        <pre><code>
$ educacao=(
    "FIAP: Curso Superior de Tecnologia (CST) em Defesa Cibernética - Fevereiro de 2024 - Dezembro de 2025"
    "Instituto Federal de Educação, Ciência e Tecnologia de São Paulo - IFSP: Técnico em Automação Industrial - Fevereiro de 2022 - Dezembro de 2023"
)
        </code></pre>
        
        <h2>Certificações</h2>
        <pre><code>
$ RH124: Red Hat Certified System Administrator - Fevereiro de 2024 - Abril de 2024
$ RH134: Red Hat Certified System Administrator - Abril de 2024 - Junho de 2024
$ Six Sigma white belt - 2023 
        </code></pre>    
        
        <h2>Experiência Profissional</h2>
        <pre><code>
$ experiencia="Projeto Acadêmico em Segurança da Informação: Desenvolvimento de um sistema de monitoramento de redes para detectar atividades suspeitas e análise de vulnerabilidades."
$ "Projeto DDoS: Desenvolvimento de uma ferramenta de ataque DDoS na camada de aplicação como parte de um desafio acadêmico para testar a robustez de sistemas."
$ "Projeto da Porta: Projeto de segurança para controlar o acesso físico a ambientes utilizando tecnologia de RFID e autenticação multifatorial."
        </code></pre>

        <div class="interactive">
            <a href="https://www.linkedin.com/in/pedro-augusto-nunes-machado-2b98b7239" target="_blank">LinkedIn</a>
            <a href="mailto:panmachado301@gmail.com">Email</a>
            <a href="https://github.com/P3g4su/mytools" target="_blank">GitHub</a>
            <a href="https://www.youtube.com/playlist?list=PLSeuPlaylist" target="_blank">YouTube</a>
        </div>

        <div class="footer">
            &copy; 2024 Pedro Augusto Nunes Machado - Todos os direitos reservados
        </div>
    </div>

    <div class="secret-button" onclick="alert('Botão secreto ativado!')">S</div>

    <script>
        function createMatrix() {
            const matrix = document.querySelector('.matrix');
            const columns = Math.floor(window.innerWidth / 20);

            for (let i = 0; i < columns; i++) {
                const column = document.createElement('div');
                column.textContent = Array.from({ length: 20 }, () => String.fromCharCode(Math.floor(Math.random() * 94) + 33)).join('');
                column.style.left = `${i * 20}px`;
                column.style.animationDelay = `${Math.random() * 5}s`;
                matrix.appendChild(column);
            }
        }

        createMatrix();
        

        // Gerar efeito de estrelas
        const stars = document.querySelector('.stars');
        for (let i = 0; i < 200; i++) {
            const star = document.createElement('div');
            star.style.width = `${Math.random() * 2 + 1}px`;
            star.style.height = star.style.width;
            star.style.top = `${Math.random() * 100}vh`;
            star.style.left = `${Math.random() * 100}vw`;
            stars.appendChild(star);
        }
    </script>
</body>
</html>
