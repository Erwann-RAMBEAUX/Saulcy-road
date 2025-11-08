# Saulcy Road

![Language](https://img.shields.io/badge/Language-C-blue.svg)
![Library](https://img.shields.io/badge/Library-SDL2-red.svg)
![Build](https://img.shields.io/badge/Build-Make-green.svg)
![Status](https://img.shields.io/badge/Status-Academic%20Project-lightgreen.svg)

**Saulcy Road** is a classic arcade-hopper game, inspired by *Crossy Road*, built entirely in C. This project features multiple rendering modes and an intelligent AI agent capable of playing the game autonomously.

> **Note:** This application was developed as a team-based academic project for an advanced course on C programming, data structures, and artificial intelligence.

## 🎯 Key Features

* **Dual-Mode Interface:** Play in a lightweight, fast **text-based terminal mode** or with a full **graphical UI** powered by the libSDL library.
* **AI-Powered Player:** An intelligent agent, built with game-tree search algorithms, can play the game autonomously and attempt to achieve the highest possible score.
* **Modular Core Logic:** The core game engine (rules, state, logic) is completely decoupled from the UI, allowing for easy testing, maintenance, and portability.

## 🛠️ Technology Stack

* **Language:** C (C11)
* **Graphics & Input:** [libSDL](https://www.libsdl.org/) (Simple DirectMedia Layer)
* **Build System:** `make`
* **AI:** Implements decision-making algorithmsfor the autonomous agent.
* **Testing:** A dedicated test suite using a C-based unit testing framework.

## 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:

* A C compiler (e.g., `gcc` or `clang`)
* `make`
* **libSDL2** (Simple DirectMedia Layer 2)
    * On Debian/Ubuntu: `sudo apt-get install libsdl2-dev`
    * On macOS (with Homebrew): `brew install sdl2`

## 🚀 Building from Source
   ```
   Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Erwann-RAMBEAUX/Saulcy-road.git
    cd Saulcy-road
    ```

2.  Compile the project using the provided `Makefile`. You can build specific targets:
    ```bash
    # Build all targets (core, text, sdl)
    make build
    ```
3. Run the project
    ```bash
    make run
    or
   ./app
    ```
   ```
