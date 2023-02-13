<h1 align="center">
  <img alt="Canvas - Javascript" src="https://raw.githubusercontent.com/nayarawatanuki/javascript__graphics/main/assets/img/readme/Cover%20-%20canvas-javascript.png#vitrinedev"/>
</h1>

### Índice

* [:pencil: Descrição do Projeto](#pencil-descrição-do-projeto)
* [:white_circle: Status do Projeto](#white_circle-status-do-projeto)
* [:hammer: Funcionalidades e Demonstração da Aplicação](#hammer-funcionalidades-e-demonstração-da-aplicação)
* [:open_file_folder: Acesso ao Projeto](#open_file_folder-acesso-ao-projeto)
* [:rocket: Abrir e rodar o projeto](#rocket-abrir-e-rodar-o-projeto)
* [:keyboard: Tecnologias utilizadas](#keyboard-tecnologias-utilizadas)
* [:woman_technologist: Desenvolvedor(a) do Projeto](#woman_technologist-desenvolvedora-do-projeto)

</br>

## :pencil: Descrição do Projeto
O projeto **[Canvas - javascript](https://nayarawatanuki.github.io/javascript__graphics/)**, é uma demonstração inicial do que pode ser realizado com o elemento `<canvas>` do HTML, manipulado por `javascript`. 
Esse projeto contém o objetivo de aprender a manipular elementos `HTML` com `javascript`. 
</br>Desenvolvido para o curso de **JAVASCRIPT E HTML: PRATIQUE LÓGICA COM DESENHOS, ANIMAÇÕES E UM JOGO** da plataforma [Alura](https://www.alura.com.br/).

</br>

## :white_circle: Status do Projeto
> Projeto concluído :white_check_mark:

</br>

## :hammer: Funcionalidades e Demonstração da Aplicação
Criado o arquivo `index.html` e declarações básicas do `HTML5`, foi inserida a tag `<canvas>` e aberta a tag `<script>`, onde as declarações de javascript foram inseridas.
Com o objetivo de desenhar algo na tela, foi criadas variáveis `screen` (para a tag `<canvas>`) e `brush` (para o conteúdo inserido por javascript, na tag `<canvas>`). 

</br>

**Foi aprendido e utilizado:** 

> `var screen = document.querySelector('canvas');`</br>
  `var brush = screen.getContext('2d');`
 
`brush.fillStyle = 'lightgrey';`, esse atributo foi aplicado para definir a cor do "pincel" utilizado.

- **Retangulo** `brush.fillRect();`
  - `brush.fillRect(0, 0, 600, 400);`, o números inseridos significam o tamanho desejado do retangulo, inserido por posições de eixo, ou seja:
    1. posição inicial X do “pincel”, 
    2. posição inicial Y do “pincel”, 
    3. posição final X do “pincel”, 
    4. posição final Y do “pincel”.
  - `brush.strokeRect();` (borda)

- **Triangulo:**
  - `brush.beginPath();`, serve para dizermos qual será a direção seguida pelo pincel.
  - `brush.moveTo(300, 200);`, posicionando o pincel exatamente no ponto 300, da coordenada X (que mede 600), e 200 na Y (que mede 400).
  - `brush.lineTo(200, 400);`, esta posição será o ponto de encontro entre o verde e o cinza, e a linha inferior do `<canvas>`, portanto, 200 no eixo X, e 400 no eixo Y.
  - `brush.lineTo(400, 400);`, criará uma linha horizontal, do ponto criado até o ponto em que o cinza encontra o vermelho, de coordenadas 400 (X), e 400 (Y).
  - `pincel.fill();`, para preencher e finalizar.

- **Circulo** `brush.arc();`
  - Posicionamento da esfera, definido como 300 (X) e 200 (Y);
  - Tamanho, ou seja, o raio - definido como 50;
  - Ângulo inicial, e o ângulo final, em radianos (multiplicado por PI - 3,14);
  
  ou seja:
    `brush.arc(300, 200, 50, 0, 2 * 3.14);`
    
- **Modulo 2:**
  Objetivo deste módulo foi simplificar todo o processo de construção das imagens em apenas uma função, basicamente organização de código.
  
- **Modulo 3:**
  Objetivo deste módulo foi trabalhar apenas com circunferencias e seus comportamentos.
  
- **Modulo 4:**
  Objetivo deste módulo foi inserir e trabalhar animações.
  
- **Modulo 5:**
  Objetivo deste módulo foi contruir jogos/atividades simples.

</br>

## :open_file_folder: Acesso ao projeto
Você pode acessar o [código fonte do projeto](https://github.com/nayarawatanuki/javascript__graphics) ou [baixá-lo](https://github.com/nayarawatanuki/javascript__graphics/archive/refs/heads/main.zip).

Caso obte por baixá-lo: 
Após baixar o projeto, você pode abrir com o VS Code. Para isso, abra o explorer (primeiro icone no menu) clique em:
- Abir pasta ou Open folder
- Procure o local onde o projeto está localizado e o selecione (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de procurá-lo)
- Por fim, clique em Selecionar pasta ou Select Folder

</br>

## :rocket: Abrir e rodar o projeto
Caso tenha interesse em visualizar o que foi realizado: [Canvas - javascript](https://nayarawatanuki.github.io/javascript__graphics/) 

Ou, caso prefira baixá-lo clicando [aqui](https://github.com/nayarawatanuki/javascript__graphics/archive/refs/heads/main.zip).

> Após baixar o projeto, abra a pasta do projeto (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de abrir), então clique no:
> - Aqruivo **``index.html``**
> - O projeto abrirá em seu navegador padrão (aconselho configurar para o Chrome, se possível)

</br>

## :keyboard: Tecnologias utilizadas
![HTML + CSS](https://raw.githubusercontent.com/nayarawatanuki/javascript__graphics/main/assets/img/readme/html-css-js.PNG)</br>

</br>

## :woman_technologist: Desenvolvedor(a) do Projeto
:star: [Nayara Watanuki](https://github.com/nayarawatanuki)
