# Dijkstra Pathfinding Visualization with Obstacles

This project implements Dijkstra's algorithm to find the shortest path between two points on a 2D map with defined obstacles. It includes a real-time visualization of the search process and the resulting path, along with video output to track the algorithm's steps.

## Features
- **User Input for Start and End Points**: Enter coordinates for the starting and destination points.
- **Obstacle Avoidance**: The algorithm considers several types of obstacles, including rectangles and a hexagonal region, with configurable clearance.
- **Visualization**: Visual representation of the map, obstacles, search steps, and the final path using OpenCV.
- **Video Recording**: Saves the visualization as a video (`dijkstra_ChandhanSaai_Katuri.mp4`) for later review.

## Requirements
- Python 3.9
- Libraries:
  - `numpy`
  - `opencv-python`
  - `heapq` (standard Python library)

Install the required libraries using pip:
```bash
pip install numpy opencv-python
```

## How to Run
- Clone this repository:
```bash
git clone (https://github.com/ChandhanSaai/Dijkstra/tree/main)
```
- Run the script:
```bash
python dijkstra_ChandhanSaai_Katuri.py
```
- Follow the on-screen prompts to enter the start and end points in the format x, y (e.g., 50, 50).
- The program will compute the shortest path, visualize the process, and save the video output as dijkstra_ChandhanSaai_Katuri.mp4.

## Code Structure
- Obstacle Check Functions: Ensure points are free from obstacles and within map boundaries.
- Dijkstra's Algorithm: Calculates the shortest path using a priority queue.
- Visualization: Uses OpenCV to render the map, obstacles, search steps, and path.
## Example
- Input:
```bash
Start Point: 50, 50
End Point: 1150, 50
``` 
- Output:
Visualization showing the shortest path and search process.
Video saved as dijkstra_ChandhanSaai_Katuri.mp4.
## Demo

![Pathfinding Demo](dijkstra_chandhan.gif)

