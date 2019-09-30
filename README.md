# hw3
PC homework 3

1.What code draws the blades of grass?

function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));


2.What code makes the "lawnmower" come by? How often does it come by?

if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }

  fill(40, 100, 60);
  rect(0, height-10, width, 10);
}
It comes by randomly and so the working time of the lawnmover is uncertain.


3.What's the point of the h variable?

This variable makes the grass grow taller and longer with time.


4.What does the -10 do in the second and fourth arguments of the line function, height-10-random(h) ? Why is it there?

It makes the grass grow starting above the brown rectangle. It's the space of the ground.
