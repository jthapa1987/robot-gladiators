# Robot Gladiators

Robot Gladiators is a browser-based JavaScript combat game where players battle enemy robots, manage resources, and upgrade their stats to survive multiple rounds. The game runs entirely in the browser using prompts, alerts, and console logs.

## Features

- Turn-based combat system with randomized attack order
- Random damage calculation for both player and enemies
- Player object with methods for resetting stats, refilling health, and upgrading attack
- Enemy robots stored as objects with randomized attack values
- Shop system with upgrade and refill options
- Fight-or-skip decision system with input validation
- High score tracking using localStorage
- Fully replayable game loop with start and end screens

## How to Play

1. Enter your robot's name when prompted.
2. Fight enemy robots one by one.
3. Choose to **FIGHT** or **SKIP** each battle.
4. Earn money by defeating enemies.
5. Visit the shop between rounds to:
   - Refill health
   - Upgrade attack
6. Try to beat the high score stored in your browser.
7. Play again after the game ends.

## Technologies Used

- JavaScript (ES5)
- HTML
- Browser APIs (alert, prompt, confirm)
- localStorage

## Future Improvements

- Add UI instead of alerts/prompts
- Add sound effects and animations
- Add more enemy types
- Add inventory or special abilities
- Add difficulty levels

## Live Demo
Play the game here: https://jthapa1987.github.io/robot-gladiators/

## Author
Created by Jeevan Thapa.
