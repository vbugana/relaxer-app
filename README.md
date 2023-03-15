# Relaxer App

A relaxing breathing app with a visual director to tell you when to breathe in, hold and breathe out

## Project Specifications

- Create circle and gradient circle with CSS
- Create and animate pointer (Small circle)
- Create grow and shrink animations
- Add JavaScript to create the breath animation effect

## Description

This is a JavaScript code snippet that creates a breathing animation.

The animation involves changing the size of a container element and displaying different text messages to guide the user through a breathing exercise. The animation runs on a loop, which repeats every totalTime milliseconds.

The const keyword is used to define constants that will be used throughout the script. The container and text variables are set to the HTML elements with the corresponding IDs.

The `totalTime` constant defines the total length of the breathing cycle, in milliseconds. The breatheTime constant is set to 2/5 of the `totalTime`, which corresponds to the time it takes to inhale and exhale. The `holdTime` constant is set to 1/5 of the `totalTime`, which corresponds to the time when the user holds their breath.

The `breathAnimation()` function defines the sequence of actions that will be taken during each cycle of the animation. It first changes the text inside the text element to "Breathe In!" and adds the grow class to the container element, which increases its size. After `breatheTime` milliseconds, it changes the text to "Hold" for `holdTime` milliseconds. Finally, it changes the text to "Breathe Out!" and adds the shrink class to the container element, which reduces its size.

The `setInterval()` function is used to repeat the `breathAnimation()` function every `totalTime` milliseconds, creating a loop that runs the animation continuously.

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
