# React Tetris! :joystick:

![reacttetris](https://user-images.githubusercontent.com/55235406/85699498-7d9cbc80-b6d3-11ea-970f-ade81053cd13.gif)

A small game project based around the classic retro arcade game Tetris! Code is written entirely in React using hooks and styled-components. 

Play a few rounds of React-Tetris at [reacttetris.netlify.app](reacttetris.netlify.app)!

Features: 

- Arrow key controls
- Scoreboard
- Advanced Levels

This project was very different to anything else I've made in React :sweat_smile:. Creating a game (Rather than a website!), naturally presents a lot of unique issues never encountered in previous projects. 

**Collision Detection**
After creating the function which allows the Tetromino (Tetris shape) to fall. If you then rotated a Tetromino along the edge of the grid, the shape of the Tetromino would morph. This was not anticipated at all... The issue was solved by creating an *if else* that checks if any of the cells in the Tetromino collide with the edges of the grid :+1:

This project was created and adapted from FreeCodeCamps React tutorial: https://www.freecodecamp.org/news/react-hooks-tetris-game/

Despite being out of my comfort zone, React Tetris taught me a lot about advanced Javascript, file management, appropriate naming conventions and of course React hooks. 

