## 👨‍💻 Kayke Queiroz dos Santos

Hi! I'm **Kayke Queiroz dos Santos** 👨‍💻  

I'm 22 years old and based in Brasília, Brazil.  
I'm currently studying **Software Engineering (5th semester)** at **IDP (Instituto de Desenvolvimento e Pesquisa)** and I'm an **IEEE member**.

I'm focused on **Front-end development** and **AI & automation solutions**, especially workflow automation using tools like **n8n**.  
I enjoy building clean, semantic, SEO-friendly projects and automating processes to solve real problems.

---

## 📬 Contact Me

<p align="left">
  <a href="tel:+5561999999999"><img src="assets/phone-button2.svg" /></a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/seu-link"><img src="assets/linkedin-button.svg" /></a>&nbsp;&nbsp;
  <a href="https://www.instagram.com/seu-instagram"><img src="assets/instagram-button.svg" /></a>&nbsp;&nbsp;
  <a href="mailto:seuemail@gmail.com"><img src="assets/email-button.svg" /></a>
</p>


---

## 🚀 Projects

<p align="left">
  <a href="https://seu-usuario.github.io/portfolio">
    <img src="assets/portfolio-button2.svg" />
  </a>
</p>

---


## 🧠 Languages

<p align="left">
  <img src="tech/html.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/css.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/js.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/react.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/cplusplus.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/java.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/python.svg" height="40" />
</p>

---

## 🛠️ Tools

<p align="left">
  <img src="tech/git.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
    <img src="tech/github2.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/docker.svg" height="50" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/vscode.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/figma.svg" height="40" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/n8n.svg" height="50" width="50" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="tech/wordpress.svg" height="40" />
</p>


</p>

## 👾 My Contribution Graph 👾

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pac-Man Game Boy</title>
    <style>
        .gameboy-container {
            display: inline-block;
            background: #b8b8b8;
            border: 5px solid #2f2f2f;
            border-radius: 24px;
            padding: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
            position: relative;
            max-width: 100%;
        }

        /* Topo com luzes */
        .gameboy-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            padding: 0 15px;
        }

        .power-light {
            width: 14px;
            height: 14px;
            background: #e74c3c;
            border-radius: 50%;
            box-shadow: 0 0 8px #e74c3c;
        }

        .gameboy-title {
            font-family: 'Courier New', monospace;
            font-weight: bold;
            font-size: 20px;
            color: #2c3e50;
            text-shadow: 1px 1px 0 rgba(255,255,255,0.5);
            letter-spacing: 1px;
        }

        .sound-dots {
            display: flex;
            gap: 4px;
        }

        .sound-dot {
            width: 6px;
            height: 6px;
            background: #333;
            border-radius: 50%;
        }

        /* Moldura da tela */
        .screen-frame {
            background: #8b9c6a;
            border-radius: 16px;
            padding: 18px;
            margin-bottom: 20px;
            box-shadow: inset 0 0 20px rgba(0,0,0,0.4);
        }

        .screen-inner {
            background: #1a1a1a;
            border: 4px solid #333;
            border-radius: 10px;
            padding: 12px;
            box-shadow: inset 0 0 15px rgba(0,0,0,0.7);
        }

        /* A tela onde o gráfico vai - NÃO DIMINUI O GRÁFICO */
        .gameboy-screen {
            background: #0f380f;
            border-radius: 6px;
            border: 2px solid #000;
            overflow: hidden;
            /* Não definir width/height fixos para não redimensionar o gráfico */
            display: block;
        }

        /* Controles */
        .controls-row {
            display: flex;
            justify-content: center;
            gap: 60px;
            margin-bottom: 15px;
        }

        /* D-Pad */
        .dpad {
            position: relative;
            width: 90px;
            height: 90px;
        }

        .dpad-center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 35px;
            height: 35px;
            background: #444;
            border-radius: 50%;
            box-shadow: inset 0 3px 8px rgba(0,0,0,0.7);
        }

        .dpad-up, .dpad-down, .dpad-left, .dpad-right {
            position: absolute;
            background: #333;
            box-shadow: inset 0 3px 8px rgba(0,0,0,0.7);
        }

        .dpad-up {
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 32px;
            height: 40px;
            border-radius: 8px 8px 0 0;
        }

        .dpad-down {
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 32px;
            height: 40px;
            border-radius: 0 0 8px 8px;
        }

        .dpad-left {
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 40px;
            height: 32px;
            border-radius: 8px 0 0 8px;
        }

        .dpad-right {
            right: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 40px;
            height: 32px;
            border-radius: 0 8px 8px 0;
        }

        /* Botões A/B */
        .buttons {
            display: flex;
            align-items: center;
            gap: 25px;
        }

        .btn-a, .btn-b {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            box-shadow: 0 5px 0 rgba(0,0,0,0.3), inset 0 2px 0 rgba(255,255,255,0.3);
        }

        .btn-a {
            background: radial-gradient(circle at 30% 30%, #e74c3c, #c0392b);
        }

        .btn-b {
            background: radial-gradient(circle at 30% 30%, #3498db, #2980b9);
        }

        /* Botões Start/Select */
        .start-select {
            display: flex;
            justify-content: center;
            gap: 40px;
        }

        .btn-start, .btn-select {
            width: 65px;
            height: 20px;
            background: #444;
            border-radius: 10px;
            box-shadow: 0 4px 0 #222, inset 0 2px 0 rgba(255,255,255,0.1);
        }

        /* Logo Nintendo */
        .nintendo-logo {
            color: rgba(0,0,0,0.4);
            font-family: monospace;
            font-size: 14px;
            letter-spacing: 3px;
            text-align: center;
            margin-top: 10px;
        }

        /* Para o gráfico - mantém tamanho original */
        .graph-img {
            display: block;
            max-width: 100%;
            height: auto;
            width: auto;
        }
    </style>
</head>
<body>
    <div align="center" style="padding: 20px;">
        <div class="gameboy-container">
            <!-- Topo do Game Boy -->
            <div class="gameboy-top">
                <div class="power-light"></div>
                <div class="gameboy-title">PAC-MAN</div>
                <div class="sound-dots">
                    <div class="sound-dot"></div>
                    <div class="sound-dot"></div>
                    <div class="sound-dot"></div>
                </div>
            </div>

            <!-- Tela com gráfico -->
            <div class="screen-frame">
                <div class="screen-inner">
                    <div class="gameboy-screen">
                        <!-- SEU GRÁFICO - TAMANHO ORIGINAL -->
                        <picture>
                            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kayke-Queiroz/Kayke-Queiroz/output/pacman-contribution-graph-dark.svg">
                            <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kayke-Queiroz/Kayke-Queiroz/output/pacman-contribution-graph.svg">
                            <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Kayke-Queiroz/Kayke-Queiroz/output/pacman-contribution-graph.svg" class="graph-img">
                        </picture>
                    </div>
                </div>
            </div>

            <!-- Controles -->
            <div class="controls-row">
                <div class="dpad">
                    <div class="dpad-center"></div>
                    <div class="dpad-up"></div>
                    <div class="dpad-down"></div>
                    <div class="dpad-left"></div>
                    <div class="dpad-right"></div>
                </div>
                
                <div class="buttons">
                    <div class="btn-b"></div>
                    <div class="btn-a"></div>
                </div>
            </div>

            <!-- Start/Select -->
            <div class="start-select">
                <div class="btn-select"></div>
                <div class="btn-start"></div>
            </div>

            <!-- Logo Nintendo -->
            <div class="nintendo-logo">NINTENDO</div>
        </div>
    </div>
</body>
</html>




