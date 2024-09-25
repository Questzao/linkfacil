# linkfacil
# Site de Download de Arquivos

Este projeto é um site simples que permite aos usuários fazer download de arquivos.

## Estrutura do Projeto



## index.html

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Download</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Site de Download</h1>
        <p>Escolha um arquivo para download:</p>
    </header>
    <main>
        <ul id="file-list">
            <li><a href="[Nova pasta.zip](https://github.com/user-attachments/files/17133472/Nova.pasta.zip)" download>Download Exemplo PDF</a></li>
            <li><a href="files/exemplo.zip" download>Download Exemplo ZIP</a></li>
            <li><a href="files/exemplo.txt" download>Download Exemplo TXT</a></li>
        </ul>
    </main>
    <script src="scripts.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f4;
}

header {
    background: #35424a;
    color: white;
    padding: 20px 0;
    text-align: center;
}

main {
    margin-top: 20px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    margin: 10px 0;
}

a {
    text-decoration: none;
    color: #35424a;
    padding: 10px;
    background: #e2e2e2;
    border-radius: 5px;
}

a:hover {
    background: #d4d4d4;
}

// Este arquivo pode ser usado para adicionar funcionalidades futuras
console.log('Site de Download Carregado');


### Instruções

1. **Salve o conteúdo acima em um arquivo chamado `README.md`.**
2. **Crie a estrutura de pastas conforme indicado.**
3. **Adicione os arquivos que deseja disponibilizar na pasta `files`.**
4. **Abra o `index.html` em um navegador para testar.**

Se precisar de mais alguma coisa ou de ajustes, é só avisar!

