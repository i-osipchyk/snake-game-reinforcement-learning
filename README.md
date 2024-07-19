# Snake Game Reinforcement Learning

This repository contains code for running an AI agent that learns to play the Snake game by itself using reinforcement learning.

## Project Description

The AI agent is built using reinforcement learning techniques and is trained to play the classic Snake game. The goal is to maximize the score by learning the optimal strategy through interactions with the game environment.

## Requirements

- Python 3.7
- NumPy 1.21

> **Note:** There is an issue running this code on MacOS machines with the latest version of Python, so Python 3.7 is required. NumPy version is set to 1.21 to ensure compatibility with Python 3.7.

## Instructions to Run

### 1. Create and Activate Virtual Environment

#### MacOS/Linux
```bash
python3.7 -m venv venv && source venv/bin/activate
```
#### Windows
```bash
python3.7 -m venv venv && venv\Scripts\activate
```

> **Note:** Make sure to select correct version of Python

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Run the code
```bash
python agent.py
```