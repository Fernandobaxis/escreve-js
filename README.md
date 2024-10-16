V# escreve-jsB<!DOCTYPE html>
<html lang.en">
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.10.0/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.10.0/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="utf-8" />

  </head>
  <body>
    <main>
    </main>
    <script src="sketch.js"></script>
  </body>
</html>
.
// aventura, fantasia, drama

// a viagem de chihiro, Livre, fantasia, aventura
// as aventuras de pi, 10, drama, fantisia, aventura
// depois da chuva, 10, drama
// guardiões da galáxia, 12, fantisia, aventura,
// o menino que descobriu o vento, 14, drama

let campoIdade;

function setup() {
createCanvas(400,400);
  campoIdade = createInput("15")
}


function draw() { 
  background(220);
  let idade = campoIdade.value()
  let recomendacao = geraRecomendacao(idade);
  text(recomendacao, width/2, height/2);
}

function geraRecomendacao(idade){
  if(idade >= 10) {
    return "As aventuras de Pi";
  } else {
  return "A viagem de Chihiro";
}
}  html, body {
  margin: 0;
  padding: a
}
canvas {
  display: block;