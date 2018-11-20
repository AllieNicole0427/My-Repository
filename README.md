void setup() {
  size(240, 240);
  background(255);

void draw() {
  //head & body
  rectMode(CENTER);
  stroke(125);
  fill(240, 240, 240);
  ellipse(100, 128, 63, 70);
  ellipse(100, 70, 60, 60);
  
  //outer eye
  fill(0, 0, 150);
  ellipse(90, 70, 8, 16);
  ellipse(110, 70, 8, 16);
  
  //iris
  fill(0);
  ellipse(90, 70, 4, 8);
  ellipse(110, 70, 4, 8);
  
  //face
  noFill();
  ellipse(100, 80, 8, 8);  //nose
  line(90, 90, 110, 90);   //mouth
  
  //ears
  fill(240, 240, 240);
  ellipse(75, 45, 22, 22);
  ellipse(125, 45, 22, 22);
  
  //paws
  ellipse(75, 120, 22, 22);  //left top
  ellipse(125, 120, 22, 22);  //right top
  ellipse(73, 160, 22, 22);  //left bottom
  ellipse(127, 160, 22, 22);  //right bottom
  }
