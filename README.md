# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Fatima Yuen**

Time spent: **3** hours spent in total

Link to project: https://light-sound-mem-game.glitch.me



## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/Of2t2lbOt8.gif]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/cssref/css_colors.asp 
https://www.tutorialspoint.com/How-to-make-text-italic-in-HTML#:~:text=To%20make%20text%20italic%20in%20HTML%2C%20use%20the,which%20renders%20as%20emphasized%20text.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[I struggled with writing the code for the guess function's game logic. The diagram with the nested conditionals helped. I am not familiar with 
html, css, or javascript so I was not sure about the syntax of my code. To tackle this problem, I first wrote psuedo code on paper which was basically 
same as what the diagram with the nested conditionals showed but incorporated the variables we declared. I tried looking at code for the previous functions to help figure out the syntax. 
In the end, I looked at the hidden solution and took that code because mine was not completely correct. One of my conditionals was if the progress was less than the last turn then keep
playing but I see now that it is shorter and cleaner to just say if the the progress is the last turn then call winGame().]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I'm wondering if everyone who makes websites uses glitch/github. I think it's cool that you can see the changes being made as you code. Do most web developers memorize all this syntax and cool design code?
I feel like there are so many possible colors, shapes, and fonts to choose from so I am wondering if a good amount of time is spent on looking up what fancy designs to use.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would take some time to figure out how to generate a random pattern array for the buttons to play. I would see if I could change the button shapes to stars.
I would also learn to play a song with the sound frequencies and try to have the user play the song back. ]



## License

    Copyright [Fatima Yuen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
