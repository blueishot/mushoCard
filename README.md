<h1 align="center"> 
  MushoCard 
</h1>

<h2 align="center"> 
     <img src='https://i.imgur.com/edU3At2.png' width='25px'>
     Language:
</h2>

<p align='center'>
  <img src='https://img.shields.io/badge/lang-en-blue'>
  <img src='https://img.shields.io/badge/lang-pt--br-brightgreen'>
</p>

<h2 align="center">
  <img src='https://i.imgur.com/eR3h2po.png' width='25px'>
  Informação sobre o projeto: 
</h2>

<p align='justify'>
  Esse projeto tem como base fazer cards que alteram seu conteúdo a partir de manipulações de DOM pelo Javascript, utilizando o trigger onclick e innerhtml para alteração dos componentes dentro dos cards, utilizando como base a pokédex do evento <b>mapadev week</b>.
</p>

<h2 align='center'>
  <img src='https://i.imgur.com/4wdvRVQ.png' width='25px'>
  Baixe o projeto
</h2>

```
# Clone o repositório
$ git clone https://github.com/blueishot/mushoCard.git

# Entre no diretório
$ cd mushoCard
```

<h2 align="center">
  <img src='https://i.imgur.com/X7mSAhJ.png' width='25px'>
  Visão Geral:
</h2>

<p align='justify'>
  O projeto basicamente consiste em duas coisas: um card e um “menu de opções”, ao clicar em uma dessas opções o card mudará tanto o seu título, imagem e conteúdo de informações, o projeto em si não é responsivo pela questão de utilizar a imagem dentro de duas div diferente para dar esse ar de dois tipos de background color, basicamente, esse é o projeto em visão geral:
</p>

<p align='center'>
    <img src='https://i.imgur.com/nSf0e5d.png'>
</p>

<p align='justify'>
    O card em si não tem muita coisa para se dizer, porém, foi utilizado padding para fazer o width e height dele e utilizando uma imagem com % maior que 100% para ocupar duas divs diferente, o foco do projeto está no menu que faz toda a magia, utilizando filter grayscale, transforma as imagens em uma cor cinzenta que ao ter o efeito de hover as cores voltam para o original:
</p>

<p align='center'>
    <img src='https://i.gyazo.com/ec08364fa9f9b66ad73c02b19551a5ce.gif'>
</p>

<p align='justify'>
    A interação do menu com o card é basicamente utilizando o trigger <b>onclick</b>, ao clicar em qualquer uma das opções ele irá modificar todos os innerhtml do card de acordo com o personagem escolhido:
</p>

<p align='center'>
    <img src='https://i.gyazo.com/843676db2fbb1c3b68653728fad96e19.gif' width='450px'>
</p>

<p align='justify'>
    No css não tem como utilizar :focus em imagem, portanto se é utilizado tabindex = 0 dentro da tag da img para que o focus consiga funcionar, assim, quando o menu for pressionado ele continuará com grayscale = 0%, infelizmente o active não é possível utilizar, então ao clicar em qualquer lugar da tela esse focus vai sumir:
</p>

<p align='center'>
    <img src='https://i.gyazo.com/2a29183df16094debd1ea183cdc99266.gif' width='450px'>
</p>

<p align='justify'>
    Finalizando, esse projeto não tem nada de inovador em JS, porém, foi mais com intuito de melhorar a parte de css, utilizando outros tipos de filters e limites de utilização de imagem
</p>

<h2 align='center'>
  <img src='https://i.imgur.com/DBKxyXS.png' width='25px'>
    Ferramentas:
</h2>

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Javascript</li>
    <li>RGABColorPicker</li>
