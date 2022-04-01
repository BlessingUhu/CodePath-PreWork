# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Blessing Uhunmwangho**

Time spent: **50** hours spent in total

Link to project: (https://glitch.com/edit/#!/responsible-prickle-stem)

## Required Functionality

The following **required** functionality is complete:

- [DONE] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [DONE] "Start" button toggles between "Start" and "Stop" when clicked.
- [DONE] Game buttons each light up and play a sound when clicked.
- [DONE] Computer plays back sequence of clues including sound and visual cue for each button
- [DONE] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [DONE] User wins the game after guessing a complete pattern
- [DONE] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [DONE] Buttons use a pitch (frequency) other than the ones in the tutorial
- [DONE] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- Buttons use a pitch (frequency) other than the ones in the tutorial,
- More than 4 functional game buttons,
- A Am - Pm timer to implemented
- A background music.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/96220166/161219631-b6f8cc50-e9f5-4a99-90b9-0854b67d9856.gif)
![ezgif com-gif-maker](https://user-images.githubusercontent.com/96220166/161219828-11738625-3f41-4041-aa3b-6453e5159ae7.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   [I used these website: https://cssreference.io/ and https://www.w3schools.com/js/js_syntax.asp ]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   [A challenge I encountered in HTML was trying to find why the </body> tag at the end of the code was giving an error. I then realized that I accidentally deleted a <div> tag and so my code could not run. Being new to HTML, I wasn’t exactly sure what was going on, I was even tempted to delete everything I created and start a new one. However, I checked each line to see if each syntax was correct and if each opening tag had the correct closing tag. This is when I found my mistake. Another challenge I faced was with Javascript. First, it was the audio that could not play after writing the code. I had to check several times if I missed something, if a variable was declared in the wrong order, if there was a missing semicolon, and so on. I had to close the computer and come back to it an hour later. When I came back, Glitch refreshed, I ran the code again and to my surprise, it was working. I was happy but also confused because all I had to do was refresh the page. A problem with javascript was creating my own game logic at the end. I struggled with knowing what syntax to use, how to use the syntax so that the game makes sense and does not crash. I looked back at my previous codes and saw that when it was time to control or store a user’s guess, the code started with function(){}. I knew I had to use the if statements inside the curly braces to set the conditions for the guesses. To help me out with putting my thought process into code, I used a website to find which syntax as appropriate. With every code I wrote, I crosschecked with CodePath’s code to see if I was going in the right direction. Lastly, after the end of my project, I accidently clicked on "import from github" on the glitch IDE and my codes deleted completely. Luckily, I saved the project's file on my computer. Since the file was in tgz format, I had to convert it to a zip file. I then opened the file and was unable to retrive my code. I realized I had to download the Atom IDE to open up all the files. The files was able to open and I recovered my work.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   [In Web development, is it compulsory to use HTML, CSS and Javascript together? Knowing that each language plays its own role, does all three need to go together?
   How is security added to a website or game so that an outside developer does not hack the website? How strenuous is it to be a web developer?
   Do websites and games always need to be debugged for maximum performance? Why do some websites crash after some time even when the initial code was right?
   How is a game or website made to fit in any type of device? How are modern games made to have such detailed graphics in them?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   [With a few more hours I would like to add more features to the game. I would use javascript and HTML to make a feature - when the user wins the game or in every correct guess, a box will pop up on the screen and encourage the player with words like “Great job” or “BRAVO!!”. The pop-ups will have sounds to it. In addition, I would add a feature that visibly shows the points the user has or what points they should be targeting. This feature will also visibly show their “best try” and would motivate the user to keep playing to beat that score. Lastly, I would add different levels to the game. Once the user masters a level, they move to the next, and this time, it would be more challenging. The user gets more points with each level advancement. If possible, I can create rewards that the user can obtain for them to beat that level; as long as they win.]

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/bc69cda19eb7440bbe4fa8d267e8641b)

## License

    Copyright [Blessing Uhunmwangho]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
