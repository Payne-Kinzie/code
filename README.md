# code

void setup(){
  size(500, 500);
  background(200, 230, 255);
  noStroke();
  }
void draw() {
  if(height/2 > mouseY) {
  fill(255, 35, 0);
  rect(mouseX, mouseY-49, 50, 50); 
  } else {
  fill(255, 200);
  ellipse(mouseX, mouseY, 30, 30);
  }
}
