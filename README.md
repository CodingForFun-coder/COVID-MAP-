# COVID-MAP-
through January 20, 2020 to July 28, 2020

Blog Post
	In the p5.Js database/documentation there were so many concepts that could have been used and picked them as being so useful. From writing text to giving the words color, any of these concepts that could have been used is very useful.  One of these concepts that is useful is the MouseClicked(). Although this can be seen as a simple variable it the. mouseClicked () function is called once after a mouse button is pressed and released over the element. Some mobile browsers may also trigger this event on a touch screen, if the user performs a quick tap.This can be used to attach element specific event listeners.

Visual Example: 
let cnv, d, g;
function setup() {
  cnv = createCanvas(100, 100);
  cnv.mouseClicked(changeGray); // attach listener for
  // activity on canvas only
  d = 10;
  g = 100;
}

function draw() {
  background(g);
  ellipse(width / 2, height / 2, d, d);
}

// this function fires after the mouse has been
// clicked anywhere
function mouseClicked() {
  d = d + 10;
}

// this function fires after the mouse has been
// clicked on canvas
function changeGray() {
  g = random(0, 255);
}
		4) We used the mouseClicked function to find all of the X and Y coordinates so that we would be able to make the csv and be able to show the impact of the coronavirus on the map. It was very useful because we needed to make it so that it could have been more presentable.
Example: 
function mouseClicked() {
 console.log("X Coordinate: " + mouseX + " Y Coordinate: " + mouseY);
}
