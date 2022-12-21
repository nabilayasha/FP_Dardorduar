## Balloon Popper

This is a simple game I made using HTML5 Canvas, JavaScript and THREE.js. The goal is to pop the balloons before they fly out of sight. The game is not complete yet, but I will be adding more features to it in the future.

## How to play
Click start to start the game. Click on the balloons as they float up to pop them. The game ends when you miss 5 balloons.

## Features
- [x] Add background image
    -using a skybox in THREE.js for reflections on the balloons
    -using HTML/CSS and image for clouds
- [x] Add balloons of different colors
    -using color array with 10 set colors
    -standard THREE.js material color is reassigned to a random color from the array each time a new balloon is created
- [x] Add a score counter
- [x] Add a life counter
- [x] Add a start button
- [x] Object collision detection
    -using THREE.js raycaster
- [x] Object pooling for balloons
    -using THREE.js object3D

## To do
- [x] Add a balloon pop sound
- [ ] Add a balloon pop particle effect
- [ ] Add a background music
- [ ] Add a high score counter
- [ ] Add a game over screen
- [ ] Add a start screen
- [ ] increase difficulty as time goes on
- [ ] Add a pause button


## Credits
sound fx by
https://picturetosound.com/en/download/574
Sound effects by https://picturetosound.com
Youtube: https://www.youtube.com/c/picturetosound

images generated with Stable Diffusion 
https://github.com/AUTOMATIC1111/stable-diffusion-webui