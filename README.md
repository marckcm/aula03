#Desafios 01

1-Faça um algoritmo no PHP, que solicita três valores e soma os mesmos, usando os elementos echo. 


#Desafio 01:

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Soma de Três Valores</title>
</head>
<body>
<h2>Soma de Três Valores</h2>
<form method="post" action="">
<input type="number" name="valor1" placeholder="Digite o primeiro valor" required><br>
<input type="number" name="valor2" placeholder="Digite o segundo valor" required><br>
<input type="number" name="valor3" placeholder="Digite o terceiro valor" required><br>
<input type="submit" value="Calcular">
</form>
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
//Código aqui !!!
}
?>
</body>
</html>


#Desafio 02:

02- Faça um algoritmo no PHP, que solicita três notas de um aluno e mostre na tela a média dele e o nome, usando os elementos echo e ternário.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Verificação de Média</title>
</head>
<body>
<h2>Verificação de Média</h2>
<form method="post" action="">
<label for="nota1">Nota 1:</label>
<input type="number" name="nota1" id="nota1" required><br>
<label for="nota2">Nota 2:</label>
<input type="number" name="nota2" id="nota2" required><br>
<input type="submit" value="Calcular Média">
</form>
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
//Código aui !!!
}
?>
</body>
</html>

O operador ternário em PHP é uma forma abreviada de expressar uma estrutura condicional simples. Ele permite que você avalie uma expressão e retorne um valor com base nessa avaliação em uma única linha de código. A sintaxe do operador ternário é a seguinte:
condição ? valor_se_verdadeiro : valor_se_falso;

#Desafio 03:

**Desafio:** Cálculo da Média de Três Valores e Verificação. O usuário deverá inserir três valores e o sistema calculará a média. Se a média for maior ou igual a 7, o sistema indicará que o resultado está "acima do esperado". Caso contrário, o resultado será "abaixo do esperado".
