<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matrizes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #6666cc;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            background-color: #8888dd;
            padding: 20px;
        }
        .header, .footer {
            background-color: #333399;
            padding: 10px;
        }
        .content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .box {
            background-color: #6666cc;
            padding: 15px;
            margin: 10px;
            flex: 1;
            min-width: 250px;
        }
        .sidebar {
            background-color: #4444aa;
            padding: 15px;
            width: 20%;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="header"> 
        <h1>Matrizes</h1>
    </div>
    <div class="container">
        <div class="content">
            <div class="box">
                <h2>O que é matriz?</h2>
                <p>A matriz é uma representação de dados...</p>
            </div>
            <div class="box">
                <img src="matriz_exemplo.png" alt="Exemplo de Matriz">
            </div>
        </div>
        <div class="content">
            <div class="box">
                <h2>Matrizes Especiais</h2>
                <p>Existem casos especiais de matrizes, como matriz identidade...</p>
            </div>
        </div>
    </div>
    <div class="sidebar">
        <h3>Matrizes Explicação</h3>
        <p>Vídeo sobre MATRIZES:</p>
    </div>
    <div class="footer">
        <p>Logo</p>
    </div>
</body>
</html>
