<!-- Kaua Stanize 3ºC 18/09/2024 -->
<html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>StaNet</title>
    <style>
        @font-face {
            font-family: 'Minecraft';
            src: url('Minecraft.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
            
        }
    </style>
</head>

<body>
    <header>STANET</header>

    <section class="enunciado">
        <div class="enunciado">
            <h1>EM BUSCA DA CASA AUTOMATICA</h1>
            <p>#viniccius13</p>
        </div>

        <div>
            <iframe width="400" height="200" src="https://www.youtube.com/embed/aWzKb071D9o?list=PLD40851E0E52E9080" title="Em busca da casa automática #1? - Minecraft Aventura" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2> Melhores Feitos</h2>
    
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=">
            <img src="https://img.youtube.com/vi/1ORcsVBVDNo/maxresdefault.jpg">
            </a>
            <a href="https://www.youtube.com/watch?v=plSXaslUsjU">
                <img src="https://img.youtube.com/vi/plSXaslUsjU/maxresdefault.jpg">
                </a>
                <a href="https://www.youtube.com/watch?v=4iYv-mJZh1U">
                    <img src="https://img.youtube.com/vi/4iYv-mJZh1U/maxresdefault.jpg">
                    </a>
                    <a href="https://www.youtube.com/watch?v=eZGVjNPshNU">
                        <img src="https://img.youtube.com/vi/eZGVjNPshNU/maxresdefault.jpg">
                        </a>
        </div>
    </section>

</body>

</html>

/* Kaua Stanize 3ºC 18/09/2024 */
body {
    font-family: 'Minecraft', sans-serif;
    color: #ecf0f1;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    background-image: url('img/fundodosite.jpg');
    background-size: 100%; /* Mantém o background original */
}

header {
    background-color: #34495e;
    width: 100%;
    text-align: center;
    padding: 20px;
    font-size: 2.5em;
    font-weight: bold;
    letter-spacing: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.enunciado {
    margin: 0px;
    text-align: center;
    position: relative;
    width: 100%;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    z-index: -1;
}

.enunciado-content {
    position: relative;
    padding: 20px;
    z-index: 1;
}

.enunciado h1 {
    font-size: 2em;
    margin-bottom: 20px;
}

iframe {
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.categoria {
    margin: 40px 0;
    text-align: center;
    width: 80%;
}

.categoria h2 {
    font-size: 2em;
    margin-bottom: 20px;
    border-bottom: 2px solid #ecf0f1;
    display: inline-block;
    padding-bottom: 10px;
}

.categoria-videos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.categoria-videos a {
    transition: transform 0.3s ease;
}

.categoria-videos a:hover {
    transform: scale(1.1);
}

.categoria-videos img {
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    opacity: 0.5;
}
.categoria-videos img:hover {
    opacity: 1.0;
}

@media (max-width: 768px) {
    .categoria-videos img {
        width: 100%;
    }
}
