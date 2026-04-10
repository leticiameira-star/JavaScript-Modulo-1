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
    <style>
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #141414;
    color: #ffffff;
    margin: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 40px 20px;
}
 h3 {
    color: #e50914;
    text-transform: uppercase;
    letter-spacing: 1px;
}

input {
    padding: 12px;
    margin: 10px 5px;
    border-radius: 4px;
    border: 1px solid #333;
    background-color: #333;
    color: white;
    font-size: 1rem;
    transition: border-color 0.3s;
}

button {
    padding: 12px 20px;
    background-color: #e50914;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-weight: bold;
    transition: background-color 0.3s, transform 0.2s;
}
#listarFilmes {
    background-color: #222;
    padding: 20px;
    border-radius: 8px;
    width: 100%;
    max-width: 600px;
    min-height: 100px;
    margin-top: 20px;
    line-height: 1.6;
    box-shadow: 0 4px 15px rgba(0,0,0,0.5);
    white-space: pre-wrap; 
}
.filme-item {
    border-bottom: 1px solid #444;
    padding: 10px 0;
}</style>
</body>
</html>
