Download Link: https://assignmentchef.com/product/solved-python-3-program-to-model-driving-a-robot-around-in-an-environment
<br>
5/5 - (6 votes)

l. Overview



This assignment will give you practice using classes in Python to solve a

problem.

ll. Instructions

Write a Python 3 program to model driving a robot around in an environment. The robot has the following attributes:

» x-coordinate

» y-coordinate

» fuel amount

It can do the following things:

» move left, right, up, and down:

» display its current status

» fire its laser

The robot should begin at location (10, 10), and should start with a fuel amount of 100.

When told to move, the robot’s fuel should decrease by 5, and it should move one unit in the desired direction (left/right means -1/+1 to the x- coordinate, down/up means -1/+1 to the y-coordinate). Displaying the status should print the location and fuel to the console in the format: “(x coordinate, y-coordinate) – Fuel: fuel-amount “, such as (9, 4) – Fuel: 75.

Firing the laser should output “Pew! Pew!” to the console and reduce the fuel-amount by 15.

If the robot does not have enough fuel for any of the above actions, it should display the text, “Insufficient fuel to perform action” In that case it should not move, fire the laser, or reduce the fuel.

USER INTERFACE

The user is presented with a prompt: “Enter command: ” and can enter

any of the following commands:

left

right

up

» down

fire

status

quit

Any other commands should be ignored, and the user re-prompted.  When the user enters the quit command, the program should display the text, “Goodbye” and then exit.

DESIGN

Your program should demonstrate good object-oriented design principles. You should use functions for appropriate main interaction, and a class with appropriate variables and methods (member functions)

to model the robot.