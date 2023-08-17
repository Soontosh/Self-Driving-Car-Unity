# Self-Driving-Car-Unity(Code Only)
A car that can drive from point A to point B, made in Unity! Utilizes the ML-Agents PPO reinforcement-learning library.

## Current Features
- Procedural Road Generation
- Procedural Building Generation
- Procedural Nature Generation
- A* Algorithm
- A* Algorithm Car Integration
- A* Visualization
- A* Demonstration Recorder
- ML-Agent Observations
- ML-Agent Actions

## Upcoming Features
- ML-Agent Rewards

## Upcoming Tasks
- Hyperparameter Tuning

*Procedural Generation*

The procedural generation makes use of a modified [Lindenmeyer System](https://www1.biologie.uni-hamburg.de/b-online/e28_3/lsys.html).

*A Grid Visualization*

Utilizes tree-searching for efficiency. A* Grid is sized dynamically.

*Demonstrator in Action*

Uses the A* Algorithm in tandem with a semi-realistic car controller I made to automatically drive car from point A to point B.  
Saves demonstration to file, which can then be used to train model.
