# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Brandon Somoze**

Time spent: **3.5** hours spent in total

Link to project: https://glitch.com/edit/#!/faithful-swanky-hyacinth?path=index.html%3A97%3A81

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![Original walkthrough+Playback Speeds up on each turn](http://g.recordit.co/EX2njd9Fyk.gif)

![Different patterns + 3 mistakes allowed](http://g.recordit.co/H0JBOWCQif.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I used the MDN web docs in order to refresh on using Math.random]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge I encountered was when trying to implement the randomized submissions. I had forgotten how to use Math.random and also wasn't really sure how I was going to randomize the submissions everytime. What I decided to do, was to start with Math.random, look up how it works, and this gave me a good start to adding the feature. Then I considered what I needed to do in order to randomize the patterns, find random numbers between 1 and 6 (the number of buttons) and then put those numbers into the pattern array. Now I needed to decide how many numbers I actually wanted there to be in the patterns, and I decided that 8 was a good number. Using these two ideas, I decided to use a for loop that iterated 8 times, and in the for loop I would calculate the random number and put it into the array at that index. For iteration 1, the first element would go into Pattern[0] and so on. In the development of this feature, it was crucial for me to look at what we are trying to accomplish and then find what I needed to do do acccomplish that goal, and slowly put each piece together. That is how I overcome challenges I find in programming.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Even though the marker gets pushed back quickly as technology develops, I’m interested in knowing the limitations we have in web development. What are some features that just can’t be implemented? Which ones are going to be available in the near future? What is it that drives forward these innovations, and gets the boundaries pushed back even further? How can I become a part of these innovations? 
I'm also wondering what can actually be down with web development. Whenever I think of web development, I instantly think of websites. What does web development actually mean generally, and what topics does it encompass? What are other applications of web development that are building websites?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a couple more hours, I would implement the last two optional features, by changing the buttons to each represent a different animal when clicked on, and also output the sound that the animal makes. Apart from this, I would clean up the code, removing all the excess lines we don’t need (provided by glitch at the start), and restructure the code into clearer sections to improve readability. Also, I would give the game a continue option upon winning, if the user decides to keep playing, either the size of the pattern increases, the speed of the clues increases, or both increase in the same round. With this increase in difficulty, I would try to implement a point system and an online leaderboard. As the user plays more difficult levels, they get more points on completion, and there would be a leaderboard of all the players usernames and their points. This would mean implementing a database to store all of this data.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/uHJ_8i8LhMM)


## License

    Copyright [Brandon Somoza]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
