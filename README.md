```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Árvore de Links</title>
    <style>
        ul {
            list-style-type: none; /* Remove as bolinhas da lista */
            padding-left: 20px; /* Indentar as sublistas */
        }
    </style>
</head>
<body>
    <h1>Árvore de Links</h1>
    <ul>
        <li>
            <a href="https://www.exemplo1.com" target="_blank">Exemplo 1</a>
            <ul>
                <li><a href="https://www.exemplo1a.com" target="_blank">Exemplo 1A</a></li>
                <li><a href="https://www.exemplo1b.com" target="_blank">Exemplo 1B</a></li>
            </ul>
        </li>
        <li>
            <a href="https://www.exemplo2.com" target="_blank">Exemplo 2</a>
            <ul>
                <li><a href="https://www.exemplo2a.com" target="_blank">Exemplo 2A</a></li>
            </ul>
        </li>
        <li>
            <a href="https://www.exemplo3.com" target="_blank">Exemplo 3</a>
        </li>
        <!-- Adicione mais links conforme necessário -->
    </ul>
</body>
</html>
```
