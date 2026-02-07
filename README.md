# Formula 1 Game & Watch Tufty 2350 Version
![DownloadCountTotal](https://img.shields.io/github/downloads/joyrider3774/formula1_tufty2350/total?label=total%20downloads&style=plastic) ![DownloadCountLatest](https://img.shields.io/github/downloads/joyrider3774/formula1_tufty2350/latest/total?style=plastic) ![LatestVersion](https://img.shields.io/github/v/tag/joyrider3774/formula1_tufty2350?label=Latest%20version&style=plastic) ![License](https://img.shields.io/github/license/joyrider3774/formula1_tufty2350?style=plastic)

Formula 1 Game & Watch is a small, fictive formula 1 game & watch style lcd game with high score keeping. The Game was initially created over a decade ago for a small retrogame competition, after which it got ported to the gp2x. This version is based on the gp2x version but with added high scoring.

## Playing the Game
The aim of the game, is to avoid hitting other traffic coming down the screen, you do this by moving your car on the bottom left or right. 

## Controls tufty2350
- A: Move Player left
- C: Move Player right
- A or C: Start a new game at the boot or gameover screen

## notes 
this repo uses a fork of pimoroni-pico where a change has been mode to not build the examples but also a change to the old st7789 driver to make it work with the overlocking done on tufty .
rp2350. You could still use the original repo if you disable / comment the overclocking in pimoroni_tufty2350.h in the boards directory