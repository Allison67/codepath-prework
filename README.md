# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Xintong Ji**

Time spent: **6** hours spent in total

Link to project: (https://pineapple-gigantic-moth.glitch.me/)

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
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
![](https://i.imgur.com/4L2DTmW.gif)
![](https://i.imgur.com/uGQQ2cK.gif)
![](https://i.imgur.com/z7VHHXu.gif)
![](https://i.imgur.com/OcRmJri.gif)
![](https://i.imgur.com/ujNW1UY.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://stackoverflow.com/questions/5786851/define-a-global-variable-in-a-javascript-function]
[https://www.w3schools.com/js/js_random.asp]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Understanding the javascript part's logic is challenging for me. Basically, it requires us to combine and organize HTML and CSS to fulfill specific functions. Each function, such as start and end, is always associated with features in HTML and CSS. It is easy to get lost here. For example, when defining the playClueSequence() function in the javascript, I had to go through it several times to understand its process. What I could do to help me understand the logic was to draw a diagram that goes step by step, giving me a more direct insight into what the function should fulfill. Besides, the functions of tone, such as the playTone, the startTone, and the stopTone also a little bit confusing at first. These are all features that I haven't seen before, and I need trial and error to really understand what it does. The parameters involved are also very complicated, and I have to try different numbers repeatedly to understand what it means.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[What we have done for now is design a website that allows the player to play the game. But I am wondering how to store the information generated from this website. For example, what should I do if I want to ask players to sign up and log in every time they want to play this game, and how can the information about their account be stored? Also, I am imagining we design a database containing all the users and their associated data, such as the number they played or how many times they succeeded. How can we achieve this? Where can the data be stored and be drawn next time? These are some questions I am considering after this submission.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I may probably spend more time on the sound effect. Because I am a piano player, I would like to compose a song for the sound effect in this game. Each button has different sounds, and the designed sequence can compose a melody instead of random tones. This requires me to spend more time generating the tones, such as choosing different pitches or even developing chords. The speed of each sound is also critical in this case. Each tone may have a different speed to compose a melody. Also, it must be interesting with the random features if a random song is chosen and played in each trial. While playing this game, the players can follow the pattern of buttons and play out the music by themselves if they win the game, giving them a sense of achievement.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/1b858a13337b46bd9d066e5938014e86)


## License

    Copyright [Xintong Ji]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.