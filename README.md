# Iafood<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iafood</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f8f8f8;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #e0e0e0;
            padding: 10px;
        }
        nav h2 {
            margin: 0;
        }
        nav ol {
            padding-left: 20px;
        }
        main {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #f8f8f8;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .btn-primary {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }
        .btn-primary:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header role="banner">
        <h1>iafood</h1>
    </header>

    <!-- Índice do Site -->
    <nav>
        <h2>Índice</h2>
        <ol>
            <li><a href="#cabecalho">Cabeçalho</a></li>
            <li><a href="#secao-principal">Seção Principal</a>
                <ol>
                    <li><a href="#slogan">Slogan</a></li>
                    <li><a href="#descricao">Descrição</a></li>
                    <li><a href="#botao-acao">Botão de Ação</a></li>
                    <li><a href="#vantagens">Lista de Vantagens</a></li>
                    <li><a href="#imagem">Imagem</a></li>
                </ol>
            </li>
            <li><a href="#rodape">Rodapé</a></li>
            <li><a href="#visualizar">Como Visualizar o Site Localmente</a></li>
            <li><a href="#publicacao">Publicação Online</a></li>
            <li><a href="#sobre">Sobre a iafood</a></li>
        </ol>
    </nav>

    <main role="main">
        <section class="container" aria-labelledby="heading-slogan" id="secao-principal">
            <h2 id="heading-slogan">Sua comida pronta em segundos,<br/>com a inteligência do futuro</h2>
            <p id="descricao">
                Imagine uma máquina revolucionária que transforma sua fome em refeições fresquinhas e deliciosas na velocidade da luz. 
                A iafood é a solução instantânea para quem quer praticidade sem abrir mão do sabor e da qualidade.
            </p>
            <button class="btn-primary" aria-label="Peça a sua iafood agora mesmo" id="botao-acao">Peça a sua iafood agora</button>
            <ul class="feature-list" aria-label="Principais vantagens da iafood" id="vantagens">
                <li>Prepara pratos variados e nutritivos em poucos segundos</li>
                <li>Interface inteligente fácil de usar, só escolher e esperar</li>
                <li>Compacta e perfeita para casa, escritório ou onde desejar</li>
                <li>Economiza tempo e reduz o desperdício com preparo sob demanda</li>
                <li>Conectividade com app para monitorar e personalizar suas refeições</li>
                <li>Design moderno e elegante para integrar seu ambiente</li>
            </ul>
            <div class="image-container" id="imagem">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/30419caa-5ce8-40ca-a818-5f1cb67d3b8e.png" alt="Imagem estilizada de uma máquina moderna chamada iafood que prepara comida instantânea, com luzes e painel digital futurista em ambiente moderno" />
            </div>
        </section>
    </main>
    <footer role="contentinfo" id="rodape">
        © 2024 iafood – Comida instantânea na velocidade da inteligência
    </footer>
</body>
</html>
