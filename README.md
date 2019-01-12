# JAVA

// Programa para ver la letra presionada

void setup(){
  size(500,500);
  textSize(250);
  textAlign(CENTER);
  frameRate(30);
}

void draw(){
  background(0);
  if(keyPressed) text(key,250,325); else background(0);
}
