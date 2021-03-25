# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Varsha Balaji

Time spent: 8 hours spent in total

Link to project: https://glitch.com/edit/#!/colossal-flash-cilantro?path=README.md%3A8%3A0

## Required Functionality

The following **required** functionality is complete:

* [YES] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [YES] "Start" button toggles between "Start" and "Stop" when clicked. 
* [YES] Game buttons each light up and play a sound when clicked. 
* [YES] Computer plays back sequence of clues including sound and visual cue for each button
* [YES] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [YES] User wins the game after guessing a complete pattern
* [YES] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [YES] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [YES] Buttons use a pitch (frequency) other than the ones in the tutorial
* [YES] More than 4 functional game buttons
* [YES] Playback speeds up on each turn
* [YES] Computer picks a different pattern each time the game is played
* [YES] Player only loses after 3 mistakes (instead of on the first mistake)
* [NO] Game button appearance change goes beyond color (e.g. add an image)
* [NO] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [NO] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- Included Instructions at the beginning for a user-friendly experience.
- Centered Heading Text
- Included a mistakes counter for the user to keep track of the number of mistakes they made.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/93TscK8.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://medium.com/@wisecobbler/4-ways-to-populate-an-array-in-javascript-836952aea79f

https://www.includehelp.com/code-snippets/different-ways-to-display-output-in-javascript.aspx

https://learn.shayhowe.com/html-css/adding-media/

https://www.freecodecamp.org/news/how-to-use-javascript-math-random-as-a-random-number-generator/

https://www.w3schools.com/tags/tag_center.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

At first, I had some trouble understanding how Javascript and HTML worked together. My knowledge of both languages was quite individualized which is why it took some self-learning and reading to visualize their compatibility. 
Specifically, I was working on showing the number of mistakes on the screen for the user to keep track when I realized that the mistakes variable was in the Javascript class while I only knew how to print in an HTML file. 
I read a couple articles online that helped explain the compatibility between HTML and Javascript while also teaching me how to print from a Javascript file. After spending some time learning on my own I was able to successfully implement the feature! 
Another issue, quite common, which I faced was debugging when implementing some of the optional features, such as giving the player 3 strikes. Initially, I wasn’t sure where to update the mistake counter in the guess function. 
What helped me overcome this was going line by line and telling myself what each line of code was doing. Whenever I debug, going over the code in a similar manner helps me figure out the algorithm, and it proved to help in this situation as well. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After working on this project, I am intrigued by other features that incorporate Javascript and HTML together. Personally, I have worked on web development solely with HTML/CSS but incorporating Javascript makes the project incredibly versatile. 
I would like to know if there are other languages that can work closely with Javascript or HTML as well to further enhance the project. In addition, I have been exploring API’s and its uses, which is why I would love to know how API’s can be used in web development as well if it is possible. 
I am also interested in what the biggest challenges of working on the front end are. I can imagine that there are a lot of aspects to take into consideration, such as usability, content, appearance, layout, etc., and I’m curious about the obstacles that a web developer faces when building a large-scale project. 
Something I also thought about while building this project was the difference between developing on a desktop compared to a mobile setting. Some questions I had based on this were how do you accommodate for both when developing.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would spend my time making the project more user-friendly. The feature I would be most interested in implementing is making the game multiplayer in order for people to play at the same time against each other. 
What I have in mind is splitting the screen and copying the same board/settings for each user, and each user would then have certain keys on the keyboard that correspond to a certain colored block. 
Another way to implement this in case the different keys are complicated to follow, would be having players take turns and keeping a score for each player at the top of the gameboard.
I would also give the user the ability to add/remove the number of buttons they want as well as letting them choose the speed of the pattern recited. Therefore, they can choose their own level of difficulty for themselves and it makes the game more personal for each player. 
Something that would make the game more easier to navigate would be asking the user if they would like to replay after their turn ending. Therefore, they wouldn’t have to repeatedly click the start button after each round. 
When thinking about my audience, I want to also make the game as child friendly as possible. Letting the users pick the colors of each button could serve as a more attracting feature to a younger audience. 
Lastly, I would definitely want to complete the other optional features I wasn't able to implement.




## License

    Copyright Varsha Balaji

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.