# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Nguyen Tai Tam

Time spent: 8 hours spent in total

Link to project: [https://glitch.com/edit/#!/seed-crimson-hardhat]
Implement the game: [https://seed-crimson-hardhat.glitch.me]

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
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Here's a walkthrough of implemented Light and Sound Memory Game (both winning and losing version):

![](https://i.imgur.com/KQaXChV.gif)

![](https://i.imgur.com/E95Y5Ew.gif)

![](https://i.imgur.com/4O894CG.gif)

![](https://i.imgur.com/p7UVLLk.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

In order to familiarize myself with syntax written in HTML, CSS and JavaScript as well as to understand what the given code is doing, I have already taken the first course in FreeCodeCamp - Responsive Web Design. Furthermore, I have also gone through half of all lessons in the course JavaScript Data Structures and Algorithms on FreeCodeCamp. I think they are all resources I have turned to because I worked on this project on my own. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One major challenge I faced is to translate the pseudocode of game logic into actual code in JavaScript. This required me to fully understand the function already written above so that I can incorporate calling functions into the logic of the game. What I did is to look back at the code syntax I have learnt in the FreeCodeCamp course, understand clearly what each line of code in each function is doing and then draft my code operating the logic of cade. After familiarizing myself with code syntax, I understand the idea of keeping track of the number of rounds the player has already gone through. And winning can only be reached when the player passes all 8 rounds. However, the logic is made more complicated when we have to keep track of passing from one round to another. I understand that after passing one round, the game will take a new pattern to challenge the player's memory. And then, it requires the game to activate a different set of sounds and buttons clicked. I am also aware that when the player tries to answer, each click he implements is kept track to compare with the correct answer. This comparison is done by indexing the list of patterns we already laid out at the beginning. When all correct guesses are reached, the player comes closer to winning the game. To evaluate my approach, I believe this is effective because I tried my best to spend time cracking the code on my own. Breaking the code on my own will reinforce my understanding better than immediately asking other people when I got stuck. It allowed me a chance to work on that first, force myself to really implement it and by that remember it longer. This somehow relates to active learning which is my school's primary pedagogical approach. I believe in the long term, learning coding requires us to fully understand the strategies so that we can know how to apply it in different contexts.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 


After the project, I am so fascinated by how algorithmic thinking can be combined with web design to build such an interactive product like this game. I am even further intrigued by how instructors can come up with the underlying operations to control the game procedures in JavaScript. For me, it sparked my realization about the power of how algorithms and data structures really come in web development. Before that, I used to take a course in HTML and CSS. I can understand how to update styles or visual look of the website, but I still get very confused about how the website can receive users' behavior or activities to accordingly respond to in an appropriate manner. This project really makes me even want to know more about how I can strengthen my knowledge about algorithmic strategies and incorporate them in building interactive webs. I am very curious about how to better apply algorithmic strategies and data structures in web development so that the flow of operation for user experience can be smoother and more logical. I believe that websites can not only represent games but also object modeling or media tools. Therefore, I really want to learn more about hands-on projects so that I can broaden my mind about the applicability of these technical skills in creating good products serving the society.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

With a few more hours, I believe it would be feasible to aim for more additional features of the game. I am really interested in making the game more attractive and challenging because that's what makes the game more widely known. In terms of design, like one of the optional problems, instead of using only colors, the game can have more fun with photos. To specify, I can include 8 photos of my facial expressions and the user needs to memorize my facial expressions, which is actually cool! In this approach, I have one idea which is only to include an argument of img in HTML. Furthermore, as an avid traveler, it would be nice if cards represent different places in the world. And to make the game more intriguing, the card can contain 3-d photos which would be nice for players to admire the beauty of cities. Along with visual effects, the sound associated with each button can be changed to national anthems of countries or famous trendy songs in these countries' languages. This would be fun and efficient for cultural immersion! In terms of the game logic, I completely agree in randomizing the pattern production so that the level of difficulty will be set higher for players. Each round should have completely random answers and all buttons do not need to be clicked so that the strategy of elimination is useless here for players. Another feature I want to present is the system of recording scores players achieve after multiple wins with increasing difficulty. This can further spark an interactive gaming community. This seems pretty ambitious because it sounds like a lot of work. However, it is always fun to experiment ideas if I have more time!



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/679758e58c484fdeb9428c810e8a2764)


## License

    Copyright Nguyen Tai Tam

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.