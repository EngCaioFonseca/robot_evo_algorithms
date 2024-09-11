# Evolutionary Robotics Simulation

This project implements a genetic algorithm for evolving robot behaviors.

## Main Script: geneticAlgorithm.py

This script runs the main evolutionary simulation.

### Key Components:

- Creates an initial population of robots
- Evaluates fitness of individuals
- Implements generational evolution
- Prints population statistics

### Usage:

1. Initialize a parent population
2. Evaluate initial fitness
3. Run evolution for a set number of generations
4. Create child populations
5. Evaluate and replace parent population
6. Print final results

## Classes

### POPULATION

Manages a group of individual robots.

Methods:
- `Initialize()`: Create initial set of individuals
- `Evaluate(show)`: Assess fitness of individuals
- `Print()`: Display population information
- `Fill_From(parents)`: Generate new population from parents

### INDIVIDUAL

Represents a single robot (implementation not shown in provided code).

### ROBOT

Represents the physical robot model (implementation not shown in provided code).

## Dependencies

- `pyrosim`: Likely used for robot simulation
- `matplotlib.pyplot`: For potential data visualization
- `random`: For introducing variability
- `numpy`: For numerical operations
- `copy`: For object copying
- `pickle`: For object serialization (not used in shown code)

## Usage Example
