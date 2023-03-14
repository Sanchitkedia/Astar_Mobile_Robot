# Project : A* algorithm for a point robot

The project is to implement the A* algorithm for path planning of a mobile robot.
The project is a part of the course ENPM661 - Planning for Autonomous Robots at the University of Maryland, College Park.
The vizualization of the project is done using pygame.
The project is implemented in Python 3.8.10

## Contributor

- Sanchit Kedia  UID:119159620
- Tanmay Haldankar UID:119175460

## Installation

The project uses the following libraries:

1. numpy v1.23.5
2. pygame v2.2.0
3. vidmaker v2.3.0
4. heapq
5. time
6. argparse

## Usage

### The project with vizualization in pygame can be run using the following command

```sh
cd <path to the project>
python3 a_star_sanchit_tanmay.py -h # Use this command to get help for the command line arguments
python3 a_star_sanchit_tanmay.py # Use this command to run the project with vizualization in pygame wihout saving the video

# Saving video slows down the vizualization of the project please be patient while the video is being saved the program will quit automatically after the video is saved
python3 a_star_sanchit_tanmay.py --save_video # Use this command to run the project with vizualization in pygame and save the video
```

## Output

- Test case 1
  - START NODE: (19,19)
  - GOAL NODE: (440,125)

- Test case 2
  - START NODE: (19,231)
  - GOAL NODE: (125,125)

- Test case 3 [Goal node not reachable]
  - START NODE: (50,125)
  - GOAL NODE: (572,220)

### Video of vizualization of Task 1 in pygame
