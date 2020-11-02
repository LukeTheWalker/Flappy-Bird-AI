# Neuroevoluted FlappyBird-playing agent
Watch the real time evolution of an Artificial Intelligence trying to survive the classic Flappy Bird game

## Usage 
In order to run this experiment no other external framework is required apart from the one in the repository itself.

Either download the repository as ```.zip``` and then launch the ```index.html``` file inside the decompressed folder 

Or, ```git-clone``` this repository at ```https://github.com/LukeTheWalker/Flappy-Bird-AI.git``` 

## Example
Here below is a short video of a sample training

![][video]



## Training Options
Many variables may be changed in order to infuence the enviroment in which the AI will train.

All of them may be easily accesed through in the ```settings.js``` file, below the most importantant:

-```birdSize``` influencing the size of bird, bigger birds will take more time to adapt since they will easily hit the pipes

-```pipeSpacing``` which yields the same influence of ```birdSize```

-```pipeSize``` influencing the width of pipes 

-```spaceBetweenPipes``` changes the space between two different pipes

-```popNum``` setting the number of individual created per generation

-```worldSpeed``` changes the speed at which the worlds advances, easily editable through the slider in the bottom left corner 


## Thanks
This project was entirely possibily thanks to the amazing [ml5.js](https://github.com/ml5js/ml5-library) library

The inspiration for this project came from the video serie about [flappy bird and neuroevolution](https://www.youtube.com/watch?v=c6y21FkaUqw) by The Coding Train

[video]: https://github.com/LukeTheWalker/Flappy-Bird-AI/blob/master/flappy.gif
