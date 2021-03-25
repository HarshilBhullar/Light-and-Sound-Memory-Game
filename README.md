# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Harshil Bhullar

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/second-torch-dragonfruit?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [✔️] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [✔️] "Start" button toggles between "Start" and "Stop" when clicked. 
* [✔️] Game buttons each light up and play a sound when clicked. 
* [✔️] Computer plays back sequence of clues including sound and visual cue for each button
* [✔️] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [✔️] User wins the game after guessing a complete pattern
* [✔️] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [✔️] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [✔️] Buttons use a pitch (frequency) other than the ones in the tutorial
* [✔️] More than 4 functional game buttons
* [✔️] Playback speeds up on each turn
* [✔️] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/WWzEhBdW97.gif)

Here's an example of picking a random pattern each time the game is played:
![](http://g.recordit.co/uiqQW6nacP.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used this resource to figure out how to randomly generate a number between a specific range: https://stackoverflow.com/questions/4959975/generate-random-number-between-two-numbers-in-javascript



2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    A challenge I encountered specifically was trying to figure out how to use math.random() to return a value that was not just confined to the range 0-1. I have very limited knowledge of Javascript, so trying to understand its syntax while also implementing logic through libraries was a little confusing. However, after reading the documentation of math.random(), as well as reading an article explaining how to scale the return value of math.random(), I was able to successfully return a random integer that was within the range of 1-6 (since I created 6 buttons instead of the original 4).
    Another challenge I encountered was trying to understand the difference between the declarations ‘let’, ‘var’, and ‘const’. Throughout the project, I noticed that all 3 were used for purposes that seemed very similar. This was throwing me off since, while it made sense when to use ‘const’, I did not get why one would use ‘let’ over ‘var’. It seemed that ‘let’ was more versatile; you can update variables that were declared with ‘let’, and you can declare the same variable in different scopes without any errors. ‘let’ seemed to give you more flexibility when declaring variables with the same name in different scopes. However, I learned that ‘var’ allows you to declare variables with the same name within the same scope, while ‘let’ does not. This cleared up my confusion between the two methods of declaring variables, and it allowed me to more quickly finish the project.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
	Throughout completing my submission, I had multiple questions about web development.
	My first question was, since I am using an online platform that allows me to view my project live, how would I be able to actively view my website while doing local development? I know React has functionality for this when I use npm (or other scripts I believe), but is it possible with plain html, js, and css?
	I was also wondering, to what extent can we customize a website with just playing around with css? Are there external tools that web designers use for further customization and cooler animations or features? Or is everything done in css?
	Another thought that crossed my mind was how websites are able to be viewed on mobile devices. I know that many websites have a mobile version of their site when accessing it on a mobile device, but how exactly does the website know to display the mobile version, and how much work would it take to implement the mobile version?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
	If I had more time to work on this project, I would definitely first complete the remaining optional features that were recommended in the instructions. Another feature that could be added would be to create various difficulty levels. For example, the easy mode would just contain 4 buttons, and the time for each sound would be long. The medium, hard, and subsequent modes would have more buttons and less time per sound. In addition, another feature to add would be an endless mode, where there is not set pattern length, and the game will only end when the user loses. This would be a nice segway to another feature: a leaderboard system. Upon ending a game in endless mode, the user could input their name and add it to the leaderboards for anyone to view.



## License

    Copyright Harshil Bhullar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
