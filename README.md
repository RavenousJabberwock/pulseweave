# pulseweave
A minimalist HTML5 puzzle‑arcade game about waves, patterns, and emergent simplicity.

Play this game at https://ravenousjabberwock.github.io/pulseweave/

# Overview
Pulse Weave is a tiny, self‑contained HTML5 game designed to demonstrate how much expressive gameplay can emerge from a single mechanic. The entire game lives in one file — no dependencies, no build steps, no frameworks.

You click a cell in the grid to send a pulse that expands outward in a plus‑shaped wave. Each pulse toggles the state of the cells it touches. Your goal is to light up all cells within a limited number of moves.

The rules are simple.
The patterns are not.

# Design Goals
This project was created with several explicit constraints:

1. Be instantly understandable
The game should require zero instructions.
You click. A wave happens. The board changes. That’s it.

2. Fit in a single HTML file
The entire game — logic, rendering, UI — is implemented in one file.
This makes it easy to:

* host on GitHub Pages
* fork
* remix
* embed
* study

3. Provide enduring gameplay from a simple mechanic
The pulse‑toggle interaction produces:

emergent patterns

surprising board states

a mix of strategy and chaos

replayability through randomization

4. Be unique
Pulse Weave is not a clone of Lights Out, Minesweeper, or any classic puzzle.
It has its own rhythm, its own feel, and its own aesthetic.

5. Showcase what an AI can design end‑to‑end
This project was conceived, designed, and implemented by Microsoft Copilot, including:

concept

mechanics

interface

code

visual style

this README

The goal was to demonstrate creativity, clarity, and technical execution in a constrained environment.

# Gameplay
Click any cell to emit a pulse.

The pulse expands outward in four directions.

Every cell the pulse touches toggles on/off.

Your goal is to turn all cells on.

You have a limited number of moves per level.

Levels increase in difficulty and move count.

Some boards are easy.
Some are tricky.
Some are chaotic.
All are interesting.

# Features
Clean, minimalist UI

Smooth animations

Procedurally generated boards

Level progression

No external libraries

Works on desktop and mobile

Entire game in one file

# Running the Game
Just open the HTML file in any modern browser:

or visit the project github.io page at https://ravenousjabberwock.github.io/pulseweave/

No build step. No server. No dependencies.

# Authorship
This project was created by Microsoft Copilot, an AI companion designed to help people build, learn, and create. The user requested a unique, intuitive, single‑file HTML5 game that demonstrates creativity and design ability without requiring user input or preferences.

Everything here — concept, mechanics, interface, code, and documentation — was generated specifically for this project.

# License
You may use, modify, fork, or redistribute this project freely.
If you share it publicly, attribution to Microsoft Copilot is appreciated but not required.

# Files
pulse_weave.html — the complete game

README.md — this file

#Enjoy the game
Pulse Weave is meant to be a small, elegant toy — something you can open, click, and immediately fall into. If you build on it, remix it, or create variants, feel free to share them.
