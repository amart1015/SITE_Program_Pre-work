# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Anthony Manuel Martin**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/fallacious-spiny-pineapple

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
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Gif demonstrating all of the images on the buttons:
![](https://media.giphy.com/media/mL8QjQWnJ4Zu3NXM3B/giphy.gif)

Gif demonstrating gameplay with wrong box chosen:
![](https://media.giphy.com/media/w5WZcAORBTV6Z25fqI/giphy.gif)

Gif demonstrating gameplay with timer running out:
![](https://media.giphy.com/media/PPVx8q88psEX4eJxdJ/giphy.gif)

Gif demonstrating gameplay with different patterns for each round:
![](https://media.giphy.com/media/79izrkW2Xk6djAmLrH/giphy.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

   
    - [https://icons8.com/icon/set/logos/stickers](https://icons8.com/icon/set/logos/stickers)
    - [https://www.w3schools.com/css//css_font_websafe.asp](https://www.w3schools.com/css//css_font_websafe.asp)
    - [https://www.w3schools.com/cssref/css_colors.asp](https://www.w3schools.com/cssref/css_colors.asp)
    - [https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random](https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random)
    - [https://www.w3schools.com/css/](https://www.w3schools.com/css/)
    - [https://www.w3schools.com/html/](https://www.w3schools.com/html/)
    - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
    - [https://www.w3schools.com/jsref/met_win_setinterval.asp](https://www.w3schools.com/jsref/met_win_setinterval.asp)
    - [https://www.w3schools.com/js/js_timing.asp](https://www.w3schools.com/js/js_timing.asp)
    

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    The biggest challenge throughout the progression of this project was my need for experience with using HTML, CSS, and JavaScript. While I have taken several programming classes, they consisted mainly of C++ and Java. I decided to dedicate a week to get comfortable with the languages used in this project. I found that following the general instructions for the game was doable; however, the optional features did test me. 
   I found implementing more than four game buttons to be highly doable. While implementing the feature to speed up the clue playback after each turn, I ran into issues with the timing of the playback. I found that the value I was assigning the variable clueHoldTime to lower by was too large, causing the website not to show the clues. My solution to this was decrementing the hold time by a lower value. When it came to implementing a randomized secret pattern, I was able to implement it using outside sources to learn about JavaScript’s random number generator function.
  Furthermore, I found the implementation of the three strikes for the player much simpler to execute. When it came to implementing images on the buttons, I had a persistent issue with uploading onto the assets folder of the glitch website. I was assisted through the CodePath pre-work support chat on slack. This resulted in the successful implementation of images on the buttons. 
   One of the biggest challenges I had was implementing the timer function. The main issue was getting the timer to start after the pattern was shown. While reviewing the initial instructions for the pre-work, I discovered that the variable delay in playClueSequence would be the perfect solution for my problem. I made functions to start and stop the timer and incorporated the start timer function in the playClueSequence function. I utilized the setTimeout function so that the timer would not start immediately when the playClueSequence function started, and the game timer worked flawlessly.
  Overall, I found that creating this project was attainable with the resources provided to me through the Pre-work instructional guide and several outside sources. It did take dedication and drive, but I learned many aspects of web development. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

   1.	One of the main questions that I have about web development, specifically with my implementation of the game, is if my code would be considered efficient compared to industry standards? 
   2.	Do most web developers use HTML along with CSS and JavaScript?
   3.	What other programming languages are widely used in web development?
   4.	Is the process of making a website compatible with mobile devices, such as smart phones, one that requires a lot of optimization?
   5.	Is Glitch widely used in the web development industry?
   6.	What are the best methods to ensure that the website that you have created is mostly free of mistakes and bugs?
   7.	What are some of the most popular programming techniques when it comes to web development?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

   If I had more time to work on this project, I would have liked to personalize it. While there are several unique aspects to my website, such as the font of the header and the color of the background, it primarily consists of the features and style of the website that the instructions were based on. Specifically, I would have liked to add a start screen with a start and help button. The start button would have started the game, similar to the one already implemented, and the help button would have contained information on how to play the game. My main priority was to implement all the required and additional features. Additionally, I would have liked to implement more efficient code so that the website could operate more effectively. I firmly believe that I will learn the necessary skills to implement more efficient code with this internship. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/lr_73epcB8c)


## License

    Copyright Anthony Manuel Martin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.