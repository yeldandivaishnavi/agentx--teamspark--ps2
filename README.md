# AgentX – Gamified Learning Environment (PS2)

## Problem Statement
Problem Statement 2: Gamified Learning Environment for AgentX

## Overview
This project implements AgentX in a gamified grid-based environment.
The agent learns to reach a goal position using Reinforcement Learning.
Over time, AgentX improves its performance by achieving higher rewards
and completing the task in fewer steps.

## Environment Description
- Grid-based maze environment
- Start position and goal position
- Actions: Up, Down, Left, Right

## Reward Structure
- +10 : Reaching the goal
- -1  : Each step
- -5  : Hitting wall or obstacle

## Algorithm Used
Q-Learning is used to train AgentX.
The agent updates a Q-table based on rewards received from the environment.

## How to Run
```bash
pip install -r requirements.txt
python demo.py

