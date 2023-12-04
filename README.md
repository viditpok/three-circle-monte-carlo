# Three-Circle Monte Carlo Overlap Estimation

This Python script is a Monte Carlo simulation tool designed to estimate the overlap area of three circles. It allows users to input the coordinates and radii of three circles and uses a random sampling method to estimate the area where these circles overlap.

## Installation

1. Ensure you have Python installed on your system.
2. No external libraries are required for the basic functionality of this script.

## Usage

1. Run the script in a Python environment.
2. Enter the center coordinates (x,y) and radius for each of the three circles when prompted. Coordinates can be input in the format `x,y` or `(x,y)`.
3. Specify the number of points to use in the simulation for accuracy.
4. The script will display a plot showing the circles and the estimated overlap area, along with printing the estimated area.

## Features

- Allows user-defined input for the locations and sizes of three circles.
- Uses a Monte Carlo method to estimate the area of overlap between the circles.
- Dynamically calculates the bounding box for the circles to optimize the simulation.
- Plots the circles and the points sampled in the Monte Carlo simulation, visually distinguishing between points inside the overlap and outside.
- Provides an estimate of the overlap area based on the simulation.

## Example

An example input might look like this:

Enter center coordinates for circle A (x,y): 100,100
Enter radius for circle A: 31
Enter center coordinates for circle B (x,y): -1,55
Enter radius for circle B: 95
Enter center coordinates for circle C (x,y): 125,50
Enter radius for circle C: 60
Enter the number of points for accuracy: 100000

After inputting the above, the script will perform the simulation and display the results.

## Note

- The accuracy of the overlap area estimation increases with the number of points used in the simulation. However, a higher number of points may increase the computation time.
- The visualization is basic and meant for a quick overview. For more detailed or customized plots, the matplotlib code in the script can be modified.
