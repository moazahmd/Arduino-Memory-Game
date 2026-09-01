# Arduino Memory Game

An Arduino-based memory game where the player must memorize and reproduce
a sequence of LED patterns using push buttons.

## Overview

The game generates a sequence of LED signals. The player watches the
sequence and then attempts to reproduce it by pressing the corresponding
buttons in the correct order.

As the player progresses, the sequence becomes longer and the game
becomes more challenging.

## Components Used

- Arduino Uno
- LEDs
- Push buttons
- Resistors
- Breadboard
- Jumper wires

## How It Works

1. The Arduino generates a random sequence.
2. LEDs display the sequence to the player.
3. The player reproduces the sequence using the corresponding buttons.
4. The Arduino checks the player's input.
5. If the sequence is correct, the player advances to the next level.
6. If the sequence is incorrect, the game ends.

## Features

- Randomly generated sequences
- Increasing difficulty
- User input validation
- LED-based visual feedback
- Button-based interaction

## Technologies

- Arduino
- C/C++
- Arduino IDE

## Project Purpose

This project was developed to practice embedded programming,
digital input/output, and interaction between hardware components
and software.
