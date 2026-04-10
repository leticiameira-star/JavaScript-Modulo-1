# JavaScript-Modulo-1


HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Filmes</title>
    <script src="cadastro.js" defer></script>
</head>
<body>
    <h3>Cadastro de Filme🎥</h2>
    <input type="text" id="titulo" placeholder="digite um Titulo">
    <input type="number" id="ano" placeholder="digite o Ano">
    <input type="text" id="classificacao" placeholder="classificação">
    <button id="btnCadastrar">Cadastrar Filme🎥🎬</button>

    <h3>Filtrar por classificação</h3>
    <input type="text" id="filtrarClass" placeholder="Digite a classificação">
    <button id="btnFiltarClass">Filtrar</button>

    <h3>Filtar por ano 📆</h3>
    <input type="number" id="filtrarAno" placeholder="Digite o ano">
    <button id="btnFiltarAno">Filtar</button>

    <h3>Lista de Filmes 🎞️🎥🎬</h3>
    <p id="listarFilmes"></p>
    
</body>
</html>
