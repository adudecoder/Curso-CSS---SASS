# Curso de CSS com Sass/Scss

## O que é Sass/Scss ?
O **Sass/Scss** é uma linguagem de extensão do CSS, a sigla significa “Syntactically Awesome Style Sheets” traduzindo ao pé da letra, folhas de estilo com uma sintaxe incrível. A sua ideia é adicionar recursos especiais como variáveis, mixins, funções e operações e outras opções variadas

## O que é **CSS** ?
**CSS** é uma sigla para *Cascading Style Sheets*(Folhas de Estilo em Cascatas), usado para estilizar a linguagem de marcação como o **HTML**, com o **CSS** é possível separar o conteúdo da estilização da sua página e podendo ajustar tamanho, formato, cor e posições de elementos e ainda sendo possível fazer animações dentro da página.

## Seletores
Parte da página **HTML** que vc quer ou toda a página **HTML**
* Exemplo
```
p {
  color: red;
}
```
A letra **P** é o **seletor**, color é **Propriedade** e red é o **Valor da propriedade**.

## Propriedades
Uma **propriedade CSS** é uma característica (como a cor) cujo valor define o aspecto de como o navegador deve exibir o elemento.

## Métodos para utilizar o CSS
1. Primeiro método é utilizando uma tag do **HTML** chamada de tag **Style**
* Utilizando uma tag **Style** dentro do **HTML**, seguindo o exemplo abaixo!
```
 <html>
<head>
<style>
  h1 {color:red;}
  p {color:blue;}
</style>
</head>
<body>

<h1>A heading</h1>
<p>A paragraph.</p>

</body>
</html> 
```
Porém temos uma desvantagem que a cada arquivo **HTML** teremos que abrir uma tag **Style** dentro desse arquivo o que deixa o código maior e mais pesado para a execução
2. Segundo método é utilizando o **CSS-Inline**
* Esse método consiste em vc utilizar uma **PROPRIEDADE STYLE** dentro de uma tag **HTML**, como nós podemos ver no exemplo abaixo.
```
<!DOCTYPE html>
<html>
<body style="background-color:black;">

<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>

</body>
</html>
```
Assim como o método da **tag Style**, a cada arquivo **HTML** criado vc deve colocar um **CSS-Inline** em eleentos o qual vc deseja manipular sua estilização
3. Terceiro método é utilizando o **CSS Externo**
* Esse método consiste em vc criar um arquivo externo **.CSS** e fazer um link dele com o arquivo **HTML** usando uma tag chamada de **LINK**.
```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
</body>
</html>
```
esse é o método mais utilizado e dinamico podendo ser aplicado estilizações a uma unica página ou varias páginas.
