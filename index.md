<html>
  <head>
    <title>Maggie's GitHub.io</title>
    <script src="https://cdn.jsdelivr.net/npm/p5@1.11.1/lib/p5.min.js"></script>
  </head>
  
  <body>
    <h1>Maggie Nguyen</h1>
    <p>Welcome to Maggie Nguyen's page.</p>
    <script>
//Maggie Nguyen - Rainbow Squares 
let userInput = ""; //stores input 

function setup() {
  createCanvas(1000, 1000); //1000x1000 square canvas
  background(225); //white background
  userInput = prompt("Hello, welcome to Maggie's Website. Please enter your name for website personalization:");
}

function draw() {
  background(225); //sets background to white 

  const r = color(255, 0, 0); //red using RGB 
  const o = color(255, 165, 0); //orange 
  const y = color(255, 255, 0); //yellow
  const g = color(0, 255, 0); //green 
  const b = color(0, 0, 255); //blue 
  const p = color(128, 0, 128); //purple 

  
  fill(255);
  rect(0, 0, 1000, 1000); //side to side, up down, width, length 
  fill(r); 
  rect(25, 25, 950, 950);
  fill(o);
  rect(50, 50, 900, 900);
  fill(y);
  rect(75, 75, 850, 850);
  fill(g);
  rect(100, 100, 800, 800);
  fill(b);
  rect(125, 125, 750, 750);
  fill(p);
  rect(150, 150, 700, 700);
  fill(r); 
  rect(175, 175, 650, 650);
  fill(o);
  rect(200, 200, 600, 600);
  fill(y);
  rect(225, 225, 550, 550);
  fill(g);
  rect(250, 250, 500, 500);
  fill(b);
  rect(275, 275, 450, 450);
  fill(p);
  rect(300, 300, 400, 400);
  fill(r); 
  rect(325, 325, 350, 350);
  fill(o);
  rect(350, 350, 300, 300);
  fill(y);
  rect(375, 375, 250, 250);
  fill(g);
  rect(400, 400, 200, 200);
  fill(b);
  rect(425, 425, 150, 150);
  fill(p);
  rect(450, 450, 100, 100);
  fill(r); 
  rect(475, 475, 50, 50);
  fill(o);
  rect(488, 488, 25, 25);

  if (frameCount % 2 === 0) {
    fill(random(255), random(255), random(255)); //random colors
  } else {
    fill(255); //white text
  }
  
  textSize(115); //font size
  textAlign(CENTER, CENTER); //aligns text
  
    if (userInput) {
    text(userInput.toUpperCase(), width / 2, height / 2); //makes letters uppercase 
  } else {
    text("HELLO USER", width / 2, height / 2);
  }
} //end of Rainbow Squares


    </script>
  </body>
</html>
