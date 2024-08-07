# Gravity Simulator

## Introduction

A simple simulation of gravitational interactions in a 2D space, developed in Python and visualized using Tkinter. The Gravity Simulator approximates the gravitational interactions between multiple bodies using Euler's Method.

## Features

- Simulates gravitational interactions between multiple bodes.
- Visualizes the movement and trails of the bodies.
- Configurable properties for bodies and simulation parameters.
- Allows custom bodies and automatically generated bodies.

## Usage

To run the Gravity Simulator, ensure you have Python installed on your system.

1. Clone the repository.

   ```bash
   git clone git@github.com:styxofsyntax/Gravity-Simulator.git
   ```

2. Open the respective directory in terminal and run the following command.

   ```bash
   python main.py
   ```

## Configuration

### Properties

- width: Width of the simulation window.
- height: Height of the simulation window.
- x_padding: Horizontal padding to keep bodies from spawning too close to the edges.
- y_padding: Vertical padding to keep bodies from spawning too close to the edges.
- bg_color: Background color of the simulation window.
- max_time: Maximum time frames for the simulation.
- start_time: Initial time frame.
- generate_bodies: Boolean to generate random bodies.
- append_bodies: Boolean to append generated bodies to custom bodies.
- bodies: List of custom bodies.
- body: Configuration for generating random bodies.

### Body Properties

- num_bodies: Number of random bodies to generate.
- mass_max: Maximum mass of random bodies.
- velocity_max: Maximum initial velocity for random bodies.
- trail_length: Length of the trail to show for each body.
- random_color: Boolean to assign random colors to bodies.
- trail_color: Color of the trails for random bodies.
- color: Default color for random bodies.

## Screenshots

![Screenshot 1](img/sim1.png)

![Screenshot 2](img/sim5.png)

![Screenshot 3](img/sim7.png)
