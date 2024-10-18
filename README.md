Self-Driving Car Simulation in JavaScript (No Libraries)
This project implements a self-driving car simulation using JavaScript and a simple neural network, without relying on any external libraries or frameworks. The car learns to navigate a road autonomously by processing inputs from sensors and controlling its movement based on a neural network model.

Key Features:

Neural Network: A basic neural network built from scratch in JavaScript, allowing the car to make driving decisions based on sensor inputs.
Sensors: The car is equipped with virtual sensors that detect road boundaries and obstacles, feeding data into the neural network.
Controls: Customizable car controls and physics, simulating acceleration, steering, and braking behavior.
Road and Environment: Dynamically generated roads and lanes to test the car’s driving capabilities.
Visualizer: Real-time visual representation of the neural network and the car’s sensor inputs.
Responsive UI: A simple user interface built with HTML and CSS to interact with the simulation.
No External Libraries: All features, from the neural network to the car physics, are implemented from scratch using vanilla JavaScript, HTML, and CSS.

File Overview:

car.js: Defines the car object, its controls, and movement.
controls.js: Handles user inputs and car control logic.
network.js: Implements the neural network that processes sensor data and outputs steering decisions.
sensor.js: Simulates the car’s sensor system for detecting the environment.
road.js: Generates the road and lane structure for the simulation.
visualizer.js: Visualizes the neural network and the car's decision-making process.
main.js: Entry point of the application, initializing the simulation and connecting the various modules.
index.html: The main HTML file that hosts the UI and simulation canvas.
style.css: Styles for the simulation UI.
utils.js: Contains utility functions used across the project.

How It Works:

The car uses its sensors to detect distances from road boundaries and obstacles.
These sensor readings are processed by the neural network, which determines the car's steering and acceleration.
As the simulation runs, the car learns to navigate the road by making better driving decisions over time.
