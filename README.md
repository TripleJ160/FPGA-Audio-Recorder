# Audio Message Recorder Prototype
This repository contains the source code and documentation for a prototype of an audio message recorder/player implemented on an FPGA board as part of the CDA 4203/4203L Spring 2024 course final project.

# Project Overview
The goal of this project was to design and prototype an audio recorder/player system using an FPGA board, with a focus on implementing key features such as recording, playback, deletion of messages, and volume control. The system utilizes a picoBlaze soft microcontroller as the main controller and includes components such as an audio CODEC, storage memory, LCD display, user controls, microphone, speaker, and serial terminal interface.

# Features Implemented
On start-up, the system displays a welcome message and a menu of options including:

- Play a message
- Record a message
- Delete a message
- Delete all messages
- Volume control

During playback, the user can pause/resume the message.
The recorder can record/store messages in 5 different slots.

# Getting Started
Clone the repository to your local machine.
Review the project documentation and source code to understand the implementation details and functionality.
Connect the FPGA board according to the provided specifications.
Flash the bitstream onto the FPGA board using the provided files.

# Instructions
- Connect board to PC to access a serial interface through PUTTY (Set COM ID correctly)
- Uses buttons on the FPGA board for navigation. Requires Switch 6 for audio codec to be switched on before recording/testing.
- Use the buttons to navigate the menu on the serial interface for all operations.

# Demo
A video demonstration of the project can be found here: https://youtu.be/Eu4xqRAyRH4

# Team Members
Johan John Joji
Lazar Lazarevich
Brendan Berlin

License
This project is licensed under the MIT License.
