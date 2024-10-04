Azul Claro (#A8DADC)
Azul Escuro (#1D3557)
Branco (#FFFFFF)
Preto (#000000)

/Apresentação da agencia
Bem-vindo à [Nome da Agência]!
Na [Nome da Agência], transformamos seus sonhos de viagem em realidade! Com uma equipe dedicada de especialistas em turismo, oferecemos pacotes personalizados para destinos incríveis ao redor do mundo.

Seja uma escapada de fim de semana, uma viagem em família ou uma aventura solo, estamos aqui para cuidar de todos os detalhes, desde passagens aéreas até hospedagens e passeios exclusivos. Nosso compromisso é proporcionar uma experiência única e inesquecível, com suporte completo antes, durante e após sua viagem.

Explore novos horizontes com a [Nome da Agência] e descubra o prazer de viajar sem preocupações. Entre em contato conosco e comece a planejar sua próxima aventura hoje mesmo!

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

<style>
        body {
            background-color: #FFFFFF; 
        }
        .header {
            background-color: #A8DADC; 
            color: #FFFFFF; 
        }
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5rem;
        }
    </style>

<nav class="navbar navbar-expand-lg header">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">AirDream</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Início</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sobre Nós</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Destinos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contato</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz4fnFO9gybUImc+X6Q1H58W8Xn3FX3X5F7Y5o1CwJ1cZXlfcXm6Rj95I" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-1EL/Bo+ukHqSR5DhPYZGFbI8RYgZ+cLt7l73KbB6mZbSgFw9o5UxWx59Fqj3yHZn" crossorigin="anonymous"></script>









    <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Destinos populares</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
<link rel="stylesheet" href="destino.css">

</head>
<body>

    

    <h1 class="Destinos" style="text-align: center;">Destinos Mais Populares</h1>
    <p class="Destinos2" style="text-align: center;">Esta é a página responsável por apresentar os destinos turísticos mais populares ao redor do mundo.</p>

    <div class="galeria">
    <figure class="imagem">
        <a href="../agencia/cadastro.html"><img src="eiffel/eiffel1.jpg" alt="Imagem da Torre Eiffel"></a>
        <figcaption>Torre Eiffel, Paris, França</figcaption>
    </figure>
    <figure class="imagem">
        <a href="../agencia/cadastro.html"><img src="espanha/espanha1.jpg" alt="Imagem da Espanha"></a>
        <figcaption>Praça de Espanha, Madrid, Espanha</figcaption>
    </figure>
    <figure class="imagem">
        <a href="../agencia/cadastro.html"><img src="EUA/EUA1.jpg" alt="Imagem dos EUA"></a>
        <figcaption>Estátua da Liberdade, Nova York, EUA</figcaption>
    </figure>
    <figure class="imagem">
        <a href="../agencia/cadastro.html"><img src="china/china1.jpg" alt="Imagem da China"></a>
        <figcaption>Grande Muralha da China</figcaption>
    </figure>
    <figure class="imagem">
        <a href="../agencia/cadastro.html"><img src="italia/italia1.jpg" alt="Imagem da Itália"></a>
        <figcaption>Taj Mahal, Agra, Índia</figcaption>
    </figure>
    </div>
    
</body>
</html>





((((((((((((((((((((((CSSS)
.destinos {
    margin-bottom: 10px; /* Espaçamento abaixo do título */
    text-align: center;
}

.destinos2 {
    margin-bottom: 20px; /* Espaçamento abaixo do parágrafo */
    text-align: center;
}

.galeria {
    display: flex; /* Usa flexbox para alinhar as imagens */
    flex-wrap: wrap; /* Permite que as imagens quebrem para a próxima linha */
    justify-content: center; /* Centraliza as imagens */
    gap: 20px; /* Espaçamento maior entre as imagens */
}

.imagem {
    width: 300px; /* Largura da imagem */
    border-radius: 15px; /* Bordas arredondadas */
    overflow: hidden; /* Para garantir que as bordas arredondadas funcionem */
    border: 2px solid #ccc; /* Borda de 2px cinza */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Sombra para um efeito de profundidade */
    transition: transform 0.2s; /* Transição suave para o efeito de movimento */
}

.imagem:hover {
    transform: scale(1.05); /* Aumenta a imagem em 5% ao passar o mouse */
}

.imagem img {
    width: 100%; /* Imagem ocupa toda a largura do contêiner */
    height: 300px; /* Altura fixa para a imagem */
    object-fit: cover; /* Cobre o contêiner sem distorcer a imagem */
}

figcaption {
    text-align: center; /* Centraliza o texto da descrição */
    margin-top: 10px; /* Espaçamento acima da descrição */
    font-size: 14px; /* Tamanho da fonte da descrição */
    color: #333; /* Cor do texto da descrição */
}
