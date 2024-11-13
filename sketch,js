let Cor;
let Posição_Horizontal = 200;
let Posição_Vertical = 200;

function setup() {
  createCanvas(400, 400);
  background("white");
  Cor = color(random(0, 255), random(0, 255), random(0, 255));
}

function draw() {
  circle(Posição_Horizontal, Posição_Vertical, 50);
  fill(Cor);
  if (mouseX > Posição_Horizontal) {
    Posição_Horizontal = Posição_Horizontal + 1;
  }
  if (mouseX < Posição_Horizontal) {
    Posição_Horizontal = Posição_Horizontal - 1;
  }
  if (mouseY > Posição_Vertical) {
    Posição_Vertical = Posição_Vertical + 1;
  }
  if (mouseY < Posição_Vertical) {
    Posição_Vertical = Posição_Vertical - 1;
  }
  if(mouseIsPressed){
    Cor = color(random(0, 255),random(0, 255),random(0, 255),random(0,100)) ;
  }
}
