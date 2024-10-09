Pacman Animation README
Overview
This project is a simple web-based animation featuring a Pacman character that moves back and forth across the screen. The animation is created using HTML, CSS, and JavaScript, allowing users to initiate the movement by clicking a button.

Features
Pacman Animation: A Pacman character that moves horizontally across the screen.
Image Frames: Utilizes multiple images to create the appearance of Pacman opening and closing as it moves.
Interactive Control: Start the animation with a button click.
Prerequisites
A modern web browser (Chrome, Firefox, etc.) to run the HTML file.
Ensure the Pacman images (PacMan1.png, PacMan2.png, PacMan3.png, PacMan4.png) are available in the same directory as the HTML file.
How to Use
Clone the Repository: Download or clone this repository to your local machine.
Add Images: Place the required Pacman images in the same folder as the HTML file.
Open the HTML File: Open index.html (or whatever you've named it) in a web browser.
Start the Animation: Click the "start" button to initiate the Pacman movement.
Code Structure
HTML: Contains a button to start the animation and a script section for JavaScript functionality.
JavaScript:
Pacman Image Array: An array holding the filenames of the Pacman images.
Create Function: create() generates a new Pacman image and positions it at the top of the page.
Move Function: move() updates the position of Pacman, alternating between moving forward and backward while changing its image based on movement direction.
Customization
Pacman Images: You can replace the Pacman images with your own designs. Ensure the filenames match those in the code.
Animation Speed: Adjust the setTimeout(move, 200) line to change the speed of the animation.
Movement Range: Change the position limits (currently set to 0 and 600) to modify the movement area.
License
This project is open-source and available for personal or educational use. Feel free to modify and expand upon it!

Acknowledgments
This project is a fun exploration of basic animations in web development.
