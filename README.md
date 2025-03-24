# Flappy Bird AI

## Overview
This project is an AI-powered Flappy Bird game where an AI model is trained using NEAT (NeuroEvolution of Augmenting Topologies) to play the game automatically.

## Features
- Uses NEAT for training an AI to play Flappy Bird.
- Flappy Bird game implemented using Pygame.
- AI learns and evolves over multiple generations.

## Requirements
- Python 3.8+
- Pygame
- NEAT-Python

## Installation
1. Install dependencies:
```sh
pip install pygame neat-python
```
2. Clone the repository:
```sh
git clone https://github.com/yourusername/flappy-bird-ai.git
cd flappy-bird-ai
```

## Running the Game
Run the following command to start training the AI:
```sh
python flappy_bird_ai.py
```

## How It Works
- The AI starts with a random population of birds.
- Birds learn over generations by evolving through NEAT.
- The best-performing birds survive and improve their strategy.
