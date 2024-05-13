# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{  // mesa esta definindo a class
    position: fixed; // definido a posição da mesa fixa não muda
    width:900px; // define a largura 
    height:600px; // define a altura
    background-color: green; // define a cor de fundo
      }
.robot{  // define a class do robot
   position: relative; // define a posição relativa em defino
   top:5px; // define o topo
   left:15px; // define a posição a quantidade de pixes da esquerda retorna os caracteres mais à esquerda
                 //ou seja o "desenho vai ficar do lado esquerdo da tela 
   width:160px; // define a largura que é de 160 pixes
   height:60px; // define o tamanho de pix da altura
   background-color: black;  }     // define a cor de fundo que é preta  
.jogador{ /// define a class jogador
    position: relative;  // define a posição relativa eu mudo 
    top:390px;  // define o topo
    left:15px; // define os px da esquerda retorna os caracteres mais à esquerda
                  //ou seja o "desenho vai ficar do lado esquerdo da tela 
    width:160px; // define o tamnho px da largura
    height:60px; // define o tamnho da altura em pixes
    background-color: black; }    // define a cor do fundo que é preta 
.baralho{   //define a class baralho 
    position: relative; // define a posição
    top:200px; // define o tamanho do topo
    left:315px; // define a posição dos pixes  //ou seja o "desenho vai ficar do lado esquerdo da tela 
    width:60px; // define o tamnho da largura 
    height:80px; // define o tamnho da altura 
    background-color:yellow;}    // define a cor do fundo que é amarelo 
``` 
<hr>
NOME Juliane Ferreira Santos

COLAR O CODIGO DO JOGO21.HTML
<!DOCTYPE html> 
<html lang="en"> // Idioma principal do site
<head> // cabeça do site 
    <meta charset="UTF-8"> // caracteres especial (ex:~, @, #...)
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> //  Define o título da página como "Jogo21"
    <link rel="stylesheet" href="estilo.css">
</head>
<body> // Inicia a seção do corpo do documento
    <div class="mesa"> // Cria uma divisão com a classe "mesa"
        <div class="robot"></div>  Cria uma divisão com a classe "robot" dentro da divisão "mesa"
        <div class="baralho"></div> //  Cria uma divisão com a classe "baralho" dentro da divisão "mesa"
        <div class="jogador"></div> // Cria uma divisão com a classe "jogador" dentro da divisão "mesa"
    
    </div> // Fecha a divisão "mesa"
</body> // Fecha a seção do corpo do documento
</html> // Fecha o elemento HTML

COLAR O CODIGO DO AQUIVO.CSS
.mesa{  // mesa esta definindo a class
    position: fixed; // definido a posição da mesa fixa não muda
    width:900px; // define a largura 
    height:600px; // define a altura
    background-color: green; // define a cor de fundo
      }
.robot{  // define a class do robot
   position: relative; // define a posição relativa em defino
   top:5px; // define o topo
   left:15px; // define a posição a quantidade de pixes da esquerda retorna os caracteres mais à esquerda
                 //ou seja o "desenho vai ficar do lado esquerdo da tela 
   width:160px; // define a largura que é de 160 pixes
   height:60px; // define o tamanho de pix da altura
   background-color: black;  }     // define a cor de fundo que é preta  
.jogador{ /// define a class jogador
    position: relative;  // define a posição relativa eu mudo 
    top:390px;  // define o topo
    left:15px; // define os px da esquerda retorna os caracteres mais à esquerda
                  //ou seja o "desenho vai ficar do lado esquerdo da tela 
    width:160px; // define o tamnho px da largura
    height:60px; // define o tamnho da altura em pixes
    background-color: black; }    // define a cor do fundo que é preta 
.baralho{   //define a class baralho 
    position: relative; // define a posição
    top:200px; // define o tamanho do topo
    left:315px; // define a posição dos pixes  //ou seja o "desenho vai ficar do lado esquerdo da tela 
    width:60px; // define o tamnho da largura 
    height:80px; // define o tamnho da altura 
    background-color:yellow;}    // define a cor do fundo que é amarelo
