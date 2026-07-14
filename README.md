# Hybrid GCN-Guided DSATUR Approach

## Project Overview

This project presents a hybrid approach combining **Graph Convolutional Networks (GCN)** with the **DSATUR (Dynamic Saturation) algorithm** to address the graph coloring problem more effectively. This is a course project for the Basic Graph Theory program at AIUB.

## Problem Statement

The graph coloring problem is a fundamental problem in graph theory where the goal is to assign colors to vertices of a graph such that no two adjacent vertices share the same color. The minimum number of colors needed is called the chromatic number.

Traditional greedy algorithms like DSATUR are efficient but may not produce optimal solutions for complex graphs. This project explores whether augmenting DSATUR with machine learning techniques (GCN) can improve solution quality.

## Key Concepts

### DSATUR Algorithm

- **D**ynamic **Saturation** algorithm
- A greedy graph coloring algorithm that prioritizes vertices with higher saturation degree
- Known for producing good approximate solutions quickly

### Graph Convolutional Networks (GCN)

- A neural network architecture for learning on graph-structured data
- Can capture complex patterns in graph properties
- Used here to guide the coloring process or predict optimal orderings

### Hybrid Approach

- Combines the efficiency of DSATUR with the learning capability of GCN
- Aims to achieve better solution quality than pure greedy approaches

## Project Structure

```
Hybrid-GCN-Guided-DSATUR-Approach/
├── README.md                          # Project documentation
├── Hybrid GCN-Guided DSATUR Approach _BGT_Project.pdf  # Project specification
├── src/                               # Source code (to be added)
├── data/                              # Benchmark graphs (to be added)
├── models/                            # GCN model implementation (to be added)
├── experiments/                       # Experimental results (to be added)
└── docs/                              # Additional documentation (to be added)
```

## Implementation

_(To be completed)_

### Requirements

- Python 3.8+
- PyTorch or TensorFlow
- NetworkX
- PyTorch Geometric (for GCN implementation)

### Usage

_(To be added)_

## Results & Evaluation

The project evaluates the approach on:

- Benchmark graph instances
- Comparison with traditional DSATUR
- Metrics: chromatic number achieved, computational time, solution quality

## References

- Welsh, D. J., & Powell, M. B. (1967). "An upper bound for the chromatic number of a graph and its application to timetabling problems"
- Kipf, T., & Welling, M. (2016). "Semi-supervised classification with graph convolutional networks"

---

**Note:** This README will be updated as the project progresses.
