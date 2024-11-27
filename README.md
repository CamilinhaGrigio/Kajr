<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Virtual</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 90%;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .book {
            background-color: #fff;
            margin-bottom: 20px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
        }
        .book h2 {
            margin: 0;
            color: #333;
        }
        .book p {
            margin: 10px 0;
            color: #666;
        }

        /* Estilos para telas maiores que 768px */
        @media (min-width: 768px) {
            .container {
                width: 80%;
            }
            .book {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
            }
            .book div {
                flex-basis: 45%;
            }
        }

        /* Estilos para telas maiores que 1024px */
        @media (min-width: 1024px) {
            .container {
                width: 70%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Biblioteca Virtual</h1>
        <div class="book">
            <div>
                <h2>Título do Livro 1</h2>
                <p><strong>Autor:</strong> Autor do Livro 1</p>
            </div>
            <div>
                <p><strong>Descrição:</strong> Esta é uma breve descrição do Livro 1. Ele aborda temas importantes sobre...</p>
            </div>
        </div>
        <div class="book">
            <div>
                <h2>Título do Livro 2</h2>
                <p><strong>Autor:</strong> Autor do Livro 2</p>
            </div>
            <div>
                <p><strong>Descrição:</strong> Esta é uma breve descrição do Livro 2. Ele explora conceitos de...</p>
            </div>
        </div>
        <!-- Adicione mais livros aqui -->
    </div>
</body>
</html>
