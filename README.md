# Lab Project: Blinky-Buzzy Toy

## Description
This project involves creating a toy using the **MSP430 Microcontroller** by utilizing the board's features: buttons, LEDs, a speaker, and an LED screen. The toy must generate sounds, control the LEDs' brightness, and implement a state machine to manage its different states. The state machine transitions are controlled via the four buttons on the expansion board (P2.0-3). 

One of the functions used to transition the state machine was written in assembly language, as required by the project guidelines.

The project was originally outlined by Dr. Eric Freudenthal as part of the curriculum for CS 3320 Intro to Computer Architecture at The University of Texas at El Paso.

## Features
- Generates sounds through the speaker.
- Dynamically changes the LEDs' brightness (both bright and dim).
- Implements a state machine to manage the toy's states.
- Transitions between states using the four buttons on the MSP430 expansion board (P2.0-3).
- One state transition function was implemented in assembly language.

## Files
The project consists of several source files and a Makefile:

- `main.c`: The main source code that handles the state machine logic and interacts with peripherals like LEDs and buttons.
- `led_control.c`: Functions to control the LED brightness and the LED screen.
- `sound.c`: Functions to generate sounds through the speaker.
- `state_machine.c`: Implements the state machine logic and transitions.
- `state_machine.s`: Assembly file with an assembly language implementation for one of the state transitions.
- `project.h`: Header file containing function declarations for the various source files.
- `Makefile`: The makefile with rules to build and clean the project.

## Directory Structure
- `demos/`: This directory contains sample programs that help you understand how to program the MSP430 microcontroller. They are useful for learning about compiling and running code on the microcontroller.
- `project/`: Contains the source code for your toy (the main project directory).

