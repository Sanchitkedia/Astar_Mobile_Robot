# Project : A* algorithm for a mobile robot

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
7. sys
8. math

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
  - Clearance: 3
  - Radius: 7
  - START NODE: (19,19,0)
  - GOAL NODE: (70,200,0)
  - Step size: 10

- Test case 2
  - Clearance: 6
  - Radius: 4
  - START NODE: (19,19,2)
  - GOAL NODE: (70,200,0)
  - Step size: 5

- Test case 3
  - Clearance: 5
  - Radius: 5
  - START NODE: (50,125,0)
  - GOAL NODE: (430,230,0)
  - Step size: 5

- Test case 4 [Goal node not reachable] [Takes a long time to run]
  - Clearance: 5
  - Radius: 5
  - START NODE: (550,125,0)
  - GOAL NODE: (430,230,0)
  - Step size: 5

### Video of vizualization of Test Case 1 in pygame

https://user-images.githubusercontent.com/61658557/226221975-0393bb61-ddd9-4a8d-b8d8-c88066c0fb8e.mp4

### Video of vizualization of Test Case 2 in pygame

https://user-images.githubusercontent.com/61658557/226221978-e169c7ad-4b6a-4e8d-8acd-815d39b2658f.mp4

### Video of vizualization of Test Case 3 in pygame

https://user-images.githubusercontent.com/61658557/226221986-35014175-20e2-4697-974e-a0c0b745bb71.mp4

### Terminal output of Test Case 4

![A*Planner_Test_Case4](https://user-images.githubusercontent.com/61658557/226222089-e646a761-c67d-4f90-8387-71694f4c8e2f.png)
