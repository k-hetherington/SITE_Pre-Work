# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kelsey Hetherington

Time spent: 7 hours

Link to project: https://glitch.com/edit/#!/impossible-harsh-crafter

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
![](https://i.imgur.com/6R7Pg1H.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used the following websites as reference for some parts of my code:

-  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
- https://www.samanthaming.com/tidbits/87-5-ways-to-append-item-to-array/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I encountered many syntax errors/typos in my code since I am not that familiar with javascript, html, nor CSS. 
Luckily, I was able to quickly resolve these issues by testing my code after each step within the pre-work assignment, and not continuing until they were fixed. 
I also had some trouble figuring out how to implement the optional strikes feature, since my game would never end, no matter how many mistakes I made. 
However after trying out different things and rereading my lines of code as well as explaining what each line does I was able to locate my error and fix it. 
The cause of this error ended up being that I never increased the strikes variable after each mistake made. 
Additionally, another challenge I encountered was when I was implementing the secret pattern for the start of each new game. 
Because I’m not familiar with this syntax I mistakenly added it to an array with Python’s “append” feature instead of Javascripts “push”. 
I ended up using the console.log method to find the bug. 
Most of my setbacks were because I made simple syntax errors, which made me feel confident in my ability to understand the logic of each task. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this submission, I have questions about the process of web development within the professional setting. 
What steps are taken in the workplace to ensure bug-free code and what tricks do software engineers use to work through bugs?
I am also interested in team work that is used on big software engineering projects.
How are such complex assignments tackled and what is the freedom that a software programmer has in their code. 
Are they limited to a certain runtime criteria? Or are they trusted to use the most efficient code for each task. 
I am also interested in exploring the worlds of front-end and back-end programming and what it looks like behind the scenes. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project I would create a tile-randomizing function that rearranges the placement of buttons on the board after each guess.
I would also like it so that the amount of tiles rearranged increases as the end of the pattern approaches. 
I think that in addition to the other features it would be a fun challenge to the game. 
I would also create a record board that would display the time of each game completed corresponding to a name of a player, that way you would be able to try to beat your record after every game and monitor your improvement. 
Lastly, I’d like to introduce a level system in which after each game the following level will increase in difficulty, where difficulty is measured by an increase of rearranging the board, amount of buttons added, and decreased guess time. 

## License

    Copyright Kelsey Hetherington

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.