# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Peleg Shilo**

Time spent: **2.5** hours spent in total

Link to project: https://glitch.com/edit/#!/northern-glorious-enigmosaurus

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
!["User Story"](http://g.recordit.co/yojPwzdfp2.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I didn't know any Javascript. Thankfully, a lot of programming knowledge is transferrable, so when I had to create the game logic by myself I used the examples I already went through together with educated guesses as to how the syntax should work. I was lucky to get the logic right on the first try. I was totally expecting it to fail, as most code does before debugging, especially if you don't know the language. I also like the flat if else structure that I wrote better than the "correct" answer because I think it is easier to read and modify.

I generally find learning programming to be best when done as you go, like in this case, as long as you have a good enough idea of how to implement what you want to implement. Therefore I think the ideal programming course contains both a more conceptual and basic understanding of different technologies and the places they take, while having a project (or multiple) that allows you to gain familiarity with the programming and deep dive into certain topics.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I feel like there is a significant leap between working with simple web development to creating a fully fledged website. I would like to learn more about web frameworks that help bridge this gap.

In addition, I would like to know how javascript libraries work, since the instructions said that we used at least one but I didn't see any import statement. How does the browser know how to handle libraries? Especially when javascript happens on the client-side, so there's additional requirements to make sure client computers aren't harmed. Do websites have an equivalent of a Python venv for each?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would like to add custom sound files, because I am interested how they can run exactly as long as the user clicks when audio files have a predetermined length. I would also like to add some changeable difficulty option, either changing the sequence length of the time it is shown.

I would also love to add keyboard controls, like arrow keys instead of pressing buttons. I always wondered how you can do those.

I would also like to ask some people what they think about the website and what improvements they would like to see, and implement the most requested features and modifications.



## License

    Copyright Peleg Shilo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.