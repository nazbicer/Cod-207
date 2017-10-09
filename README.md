# Cod-207
Homework 1
void setup() {
  size(800,250);
  background(#F2F5FA);
}

void draw() {
  
  
  //drawing rectangle
   stroke(#09E3D2);
 rect(190,155,20,20);

stroke(#09E35E);
rect(190,75,20,20);

stroke(#08C652);
rect(220,90,20,20);

stroke(#08C6B8);
rect(220,140,20,20);

  stroke(#08BC87);
  rect(255,115,20,20);

 
  //draw lines
  
  //darker purple
  strokeWeight(4);
 stroke(#B05CDE);
 line(120,190,120,60);
 
 stroke(#DCB3F2);
 line(130,170,130,80);
 
 //darkest purple 
  strokeWeight(4);
  stroke(#8E1FCB);
  line(110,170,110,80);
  
  //brigtest blue
  smooth(2) ;
  strokeWeight(4);
  stroke(#BDD4FA);
  line(80,170,80,80);
  
  //darker blue
  stroke(#78A3ED);
  line(90,190,90,60);
  
  //darkest blue
  stroke(#1C5DC9);
  line(100,170,100,80);
  
  //drawing triangles
  strokeWeight(3);
  stroke(#19F7D0);
  triangle(170,170,190,155,170,140);
  
  stroke(#19F799);
  triangle(190,155,170,140,190,125);
  
  stroke(#19F770);
  triangle(170,140,190,125,170,110);
  
  stroke(#19F759);
  triangle(190,125,170,110,190,95);
  
  stroke(#19F74B);
  triangle(170,110,190,95,170,80);

//drawing ellipse
stroke(#FAE100);
  ellipse(360,130,70,90);
  
  //drawing quad
  stroke(#FFEF58);
  quad(380,140,400,150,410,120,390,110);
  
  stroke(#FCF187);
  quad(440,90,460,80,470,55,445,60);
  
  stroke(#FCF187);
  quad(440,150,460,160,470,185,445,180);
  
  stroke(#F7AFAF);
  quad(470,110,490,100,500,75,475,80);
  
  quad(470,130,490,140,500,165,475,160);
  
  stroke(#FA9A9A);
  quad(500,135,520,125,530,100,505,105);
  
  stroke(#FA8383);
quad(545,110,565,100,575,75,550,80);

stroke(#FA8383);
quad(545,130,565,140,575,165,550,160);

stroke(#FA6A6A);
quad(580,135,600,125,610,100,585,105);


//drawing lines
stroke(#F54A4A);
line(650,160,650,90);

stroke(#F73737);
line(670,180,670,70);
 
 stroke(#F52828);
 line(690,200,690,50);
  
  stroke(#F50C0C);
  line(710,220,710,30);
  
  

  
  
}
