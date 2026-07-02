<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seleção Futura • Elite Brasileira</title>
    <link rel="stylesheet" href="css/styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <span class="flag">🇧🇷</span>
                <span>SELEÇÃO FUTURA</span>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Início</a></li>
                <li><a href="#jogadores">Jogadores</a></li>
                <li><a href="#galeria">Galeria</a></li>
                <li><a href="#historia">Legado</a></li>
            </ul>
            <div class="hamburger">☰</div>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1 class="futuristic-title">SELEÇÃO BRASILEIRA</h1>
            <p class="subtitle">A ELITE FUTURISTA DO PLANETA</p>
            <a href="#jogadores" class="btn">Conhecer os Craques</a>
        </div>
    </section>

    <section id="jogadores" class="section">
        <div class="container">
            <h2 class="section-title">Estrelas da Seleção</h2>
            <div class="players-grid" id="players-grid"></div>
        </div>
    </section>

    <section id="galeria" class="section">
        <div class="container">
            <h2 class="section-title">Momentos Épicos</h2>
            <div class="gallery-grid">
                <img src="https://picsum.photos/id/1015/800/500" alt="Brasil">
                <img src="https://picsum.photos/id/106/800/500" alt="Copa">
                <img src="https://picsum.photos/id/201/800/500" alt="Estádio">
                <img src="https://picsum.photos/id/237/800/500" alt="Torcida">
            </div>
        </div>
    </section>

    <section id="historia" class="section history">
        <div class="container">
            <h2 class="section-title">Legado Verde e Amarelo</h2>
            <p class="history-text">Da magia de Pelé à velocidade de Vinícius Jr, a Seleção Brasileira continua escrevendo a história do futebol mundial com estilo futurista.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Seleção Futura • Feito com paixão pelo Brasil</p>
    </footer>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close">×</span>
            <img id="modal-img" src="" alt="">
            <h3 id="modal-name"></h3>
            <p id="modal-desc"></p>
        </div>
    </div>

    <script src="js/script.js"></script>
</body>
</html>
