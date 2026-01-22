# Calculadora Simples

Projeto desenvolvido com o objetivo de praticar lógica de programação e manipulação do DOM utilizando JavaScript.

##Tecnologias utilizadas
- HTML5
- CSS3
- JavaScript

##Funcionalidades
- Operações básicas (soma, subtração, multiplicação e divisão)
- Interface simples e intuitiva
- Interação com o usuário via botões

##Aprendizados
- Manipulação do DOM
- Eventos em JavaScript
- Organização de código

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Simples</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="calculator">
        <h1>Calculadora Simples</h1>
        <input type="number" id="num1" placeholder="Número 1">
        <input type="number" id="num2" placeholder="Número 2">
        <br>
        <button id="addButton">Somar (+)</button>
        <button id="subtractButton">Subtrair (-)</button>
        <button id="multiplyButton">Multiplicar (*)</button>
        <button id="divideButton">Dividir (/)</button>
        <br>
        <p>Resultado: <span id="result"></span></p>
    </div>
    
    <script src="script.js"></script>
</body>
</html>
