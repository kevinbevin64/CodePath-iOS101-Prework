# Prework - *Random Background Color Switcher*

Submitted by: **Kevin Chen**

**Random Background Color Switcher** is an app that randomly sets the background color of the app when a button is clicked! So click away! 

Time spent: **1** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] Users are see a screen with three labels and a button
- [X] Tapping the button changes the screen color to a random color
 
## Video Walkthrough

<a href="https://www.loom.com/share/8170bbc9a82c42cbaad03c91214bb6df">
   <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/8170bbc9a82c42cbaad03c91214bb6df-88984d84c674cae7-full-play.gif">
</a>

## App Brainstorming (Step 4)

- Apple's Mac Mail client
    - Has lots of features that allow granular control over email such as setting the reply-to recipient and preventing the loading of remote content.
    - Has a simple, easy to use interface that gets out of the way and allows me to do what I need: write emails.
    - Many, many text-formatting options when composing emails, which Gmail doesn't have.
- Flighty
    - Has a beautiful user interface that looks very native! 
    - Allows me to see my flight history, and archives interesting information such as the plane model.
    - The flight adder is smart and fast. 
- ChatGPT 
    - I appreciate that when accessing photos, it uses Apple's private photo accessing API (instead of obtaining full, unrestricted access to users' photos)
    - It's got a fast, fluid interface. 
    - It is simple and unobstrusive. I open the app wanting an answer to a question, and that's what I always get (with no ads!)
- Apple's Weather app
    - It looks amazing, and I like how the background scenes match the true weather super accurately.
    - Gives lots of not only current, but historical information. 
    - Extremely easy to use.

An app I'd like to build would track important information about gym workouts, such as the number of reps and sets, the type of exercise, and workout duration. It would keep track of workouts over time and suggest adjustments to training routines to optimize performance gains. It would also have a great interface that is extremely usable, even to someone who's never used the app before. Fast data-entry is a must, and an Apple Watch version of the app would make it even more convenient for people to use it. 

## Notes

Building the app was relatively smooth. I found dragging and dropping the UI elements onto the screen to be very intuitive. I did have to pause and think a little when I'd written the logic for changing the background color, because the way I initially did it, clicking the button wouldn't change the background color. I then realized that the `view.backgroundColor = randomColor` instruction wasn't a comment, but actual code to write. Adding that solved the problem. 

## License

    Copyright [2025] [Kevin Chen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
