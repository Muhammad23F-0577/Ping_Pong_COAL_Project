# Pong Ping Game (Assembly - NASM)

## Project Overview
This project is a 2-player Pong game developed in x86 Assembly Language using NASM. It runs in a DOS environment using DOSBox and demonstrates low-level programming concepts such as memory handling, interrupts, and basic graphics.

---

## Features
- Two-player gameplay
- Player 1: W (Up), S (Down)
- Player 2: Arrow Keys (Up/Down)
- Real-time ball movement
- Collision detection (walls and paddles)
- Score tracking system
- Pause/Resume using 'P'
- Restart using 'R'
- Winning condition (first to 5 points)

---

## Core Concepts Used
- BIOS Interrupts (INT 10H, INT 16H)
- Keyboard input handling
- Game loop logic
- Collision detection
- Low-level graphics rendering

---

## Tools and Environment
- Assembler: NASM
- Emulator: DOSBox
- Platform: x86 (8086 compatible)

---

## How to Run
1. Save file as `pong.asm`
2. Open DOSBox
3. Mount your folder and navigate to it
4. Compile:
