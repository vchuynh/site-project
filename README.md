# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Van Huynh**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/hulking-crystal-television

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/bd82d275-1de2-4bce-8a02-3471b0ab46b2%2Fgiffy.gif?v=1616611705499)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[None]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[In trying to implement the guess function, I was a little confused with the game logic specifically the guess function.  I'm used to C++ and the type of variables being passed in are stated in the function parameter.  I kept thinking it was the button itself being passed in and was confused. I mentally stepped through the program to know how all the functions come together and realized it was the number representing the button.  After that, it was came very easily because of the game logic flowchart.  I wasn't sure if the turn was over and saw that it had something to do with the guessCounter reaching a certain value.  I then looked over playClueSequence() and knew it had to be equal to progress for the turn to be over.  If progress was ever equal to the length of the pattern array, then the game would be over. The design document was very straightforward and clear in its explanation.  I would constantly look over the design document at how the game is supposed to be implemented and act.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[How complex can front-end web development become?  This project was fairly simple and brief.  I can imagine it becoming more difficult to code more complex games.  However, websites, that don't display games like this project, I can imagine being fairly straightforward at least on the user side of things.  The simplicity of coding HTML, CSS, and JavaScript in this project makes me wonder about back-end development. Is back-end web development usually the most difficult?  What are databases used for and what goes on behind the front-end?  Looking at websites, many seem fairly simple on the front-end that I wouldn't think would require anything more than the ideas this project entailed.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[Adding a random secret pattern would be the first change I would make.  I would add several different difficulties such as easy, medium, and hard.   Easy would have 4 buttons, medium would have 6 buttons, and hard would have 8.  They would also respectively have the clues play faster.  Also, a counter for a person's high score for each pattern that they complete as well as a counter for the current number of patterns they have completed.  Instead of the different sounds for each button, each button could have a sound if they were played correctly according to the pattern.  If the player doesn't choose the correct button, not only would it end the game, but a clear incorrect sound would be played.  ]



## License

    Copyright [Van Huynh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.