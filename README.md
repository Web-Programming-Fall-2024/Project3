# Group 6 Project 3: Fifteen Puzzle

## Group Member:

- Sophie Nguyen

## Materials:

- [Website](https://codd.cs.gsu.edu/~nnguyen177/MyWebPro/Project3/objective-c/index.html)
- [Proposal](https://drive.google.com/file/d/1MJOc_1o9nvO8rTBhJcKigGro_y3cSWbS/view?usp=sharing)
- [PowerPoint](https://docs.google.com/presentation/d/1gCV34ijYuw9ZymO9bP8dZkjKEJym_8wf/edit?usp=sharing&ouid=115868471783120857845&rtpof=true&sd=true)
- [Video]()

## Project Summary:

This project focuses on developing an interactive sliding puzzle game known as the "Fifteen Puzzle." The game consists of a 4x4 grid of numbered tiles with one missing tile, where players aim to arrange the tiles in numerical order. It features user-friendly mechanics, visual feedback for movable tiles, and additional functionalities such as shuffle, multiple backgrounds, and an end-of-game notification to enhance player engagement.

## Setup:

Please download the folder [assets](https://drive.google.com/drive/folders/1FJyAd-mUFIfSSWO7mGRQDURh6dJEvZAT?usp=drive_link) and put it in the root folder. Then, run this file ``.

## Key Features:

- **Homepage:** Introduces the Fifteen Puzzle game, offering an interactive welcome animation. It briefly overviews the game rules and invites players to start playing.
- **Game Page:** Hosts the puzzle grid and game controls. This page includes:
  
  ○ **Puzzle Grid:** A 4x4 interactive grid displaying the tiles and blank space.
  
  ○ **Shuffle Button:** Randomizes the puzzle into a solvable state for a new game.
  
  ○ **Settings Panel:** Allows users to choose different background themes or adjust grid sizes.
  
- **End-of-Game Page:** Notifies the user when they successfully solve the puzzle, showing elapsed time, the number of moves, and the best scores.

## Functionalities:

- **Interactive Puzzle:**
  
  ○ Users can click on a tile adjacent to the blank space to move it into the empty position.
  
  ○ Hovering over a movable tile changes its style (border turns red, text underlined, text color changes to green).
  
- **Shuffle Feature:** Randomizes the tiles into a solvable configuration using efficient algorithms.
- **End-of-Game Notification:** Displays a celebratory message or animation when the puzzle is solved.
- **Settings Panel:** Multiple grid sizes (e.g., 3x3, 6x6, etc.) and random or user-selectable background themes.
- **Timer and Move Counter:** Tracks the time elapsed and moves made during the game, updating the best records for improved replayability.
- **Background Music:** Optional background music to add excitement and engagement.
