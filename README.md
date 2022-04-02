# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Michael Lian

Time spent: 8 hours spent in total

Link to project: https://glitch.com/edit/#!/exultant-wool-tray?path=script.js%3A18%3A15

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
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/dMg0Miq.gif)
![](https://i.imgur.com/Hc2OxLg.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used Stack Overflow and w3schools.com as an outside resources to complete this submission.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge that I encountered while creating this light and sound memory game was working with JavaScript and trying to implement some of the optional features such as the functionality where the user gets 3 wrong guesses and the random pattern picking. Since I am fairly inexperienced at JavaScript programming, I first gave my best attempt at trying to implement these features on my own to try to learn. However, while implementing the random pattern picking feature, I could not get it to work. I knew that I needed to use the Math.random library but I was exactly sure how to get the game to pick a random pattern since when I tested it the game would simply pick the preset pattern I used when initializing the pattern array.

To overcome this issue, I searched up the JavaScript Math.random documentation on w3schools.com and looked at example implementations that people have submitted on Stack Overflow. Using the documentation and similar examples that other people had, I was able to properly implement the feature so that every time the game is played, a random pattern is played.

Overcoming this issue while working on this project in a language that is still relatively new to me allowed me to improve my problem solving and programming skills.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this submission, I still have a few burning questions about web development. Many of the web sites that I use on a daily basis have millions of users that register, sign in, and submit data on a daily basis. How are websites able to store all of this data and process all these user's requests while still running quickly? Another question I have about web development relates to the diverse range of devices using the internet these days. People need to access websites from devices ranging from large screen televisions to small mobile phones. How are websites able to accommodate these range of devices and still make the styling look good and be usable?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this function, I would try to add a database, create a backend API, and implement some form of user sign in so that users can sign in to accounts to view their past games that they have played and see their progress on the light and sound game. I would also like to add a game settings board so that users can challenge themselves more. This game settings board would allow users to change the difficulty of the game by allowing them to adjust how many guesses they get, how fast the hints are played, and how long the pattern is.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.youtube.com/watch?v=3FffgN-miuk)


## License

    Copyright Michael Lian

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
