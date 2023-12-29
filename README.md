# Traffic Monitoring and Speed Estimation

## Overview
This project involves the use of computer vision techniques to monitor traffic, count the number of vehicles, and estimate their speeds. The system is implemented using Python and OpenCV, with the goal of providing a simple yet effective solution for traffic analysis.

## Key Features
- **Vehicle Detection:** The system detects vehicles in a video stream using background subtraction and contour analysis techniques.
- **Counting Mechanism:** The number of vehicles passing through a specified area is counted in real-time.
- **Speed Estimation:** The system calculates the speed of each vehicle by analyzing its movement over time.
- **Visualization:** The processed video stream is displayed in real-time, showing detected vehicles, counting information, and speed estimates.

## Parameters
- **Minimum Width and Height:** Minimum dimensions for a valid vehicle contour.
- **Line Definitions:** Two lines are defined for counting and speed estimation.
- **Delay:** A delay parameter controls the speed of processing and visualization.

## Usage
1. Run the provided Python script with the specified video file path.
2. View the real-time processed video with vehicle detection, counting, and speed estimation.

## Dependencies
- Python
- OpenCV
- NumPy


## Notes
- Adjust the parameters as needed for different video sources and environments.
- The system is designed for educational purposes and can be extended for more complex scenarios.

#### Feel free to explore, modify, and contribute to this project!
