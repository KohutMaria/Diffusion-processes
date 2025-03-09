# Diffusion Processes on Complex Networks

This repository contains programming assignments from the *Diffusion Processes on Complex Networks* course, part of my Master's studies at Wrocław University of Science and Technology. The assignments are implemented in Jupyter Notebooks and explore various models and algorithms related to complex networks, random walks, and diffusion processes.

## Contents

The repository includes five Jupyter notebooks, each covering a different topic:

### 1. **DPOCN_2: Graph Data Structures and Algorithms**
- Implementation of a class for **undirected weighted graphs**.
- Methods to:
  - Add and retrieve vertices and edges.
  - Get neighbors of a vertex.
  - Check if a vertex belongs to the graph.
  - Compute **shortest paths** from a given vertex.
  - Save the **DOT representation** of the graph to a text file.

### 2. **DPOCN_3: Random Graph Generation and Social Network Analysis**
- Implementation of methods to generate:
  - **Random graphs**.
  - **Watts-Strogatz small-world networks**.
  - **Barabási–Albert scale-free networks**.
- Visualization and statistical analysis:
  - Calculate **average degrees**.
  - Fit the **degree distribution** for different types of graphs.
- **Social network analysis**:
  - Web scraping to obtain a **Facebook friendship network**.
  - Visualization and structural analysis of the obtained network.

### 3. **DPOCN_4: Random Walks on Lattices and Graphs**
- Implementation of different **random walk models**:
  - **Simple random walk** on a square lattice (visualized as a GIF).
  - **Pearson’s random walk** in the plane with statistical analysis of time steps.
  - **Random walk on a given graph** (Watts-Strogatz, Barabási-Albert, and random graphs).
- Estimation and analysis of **average hitting times for different graph structures**.

### 4. **DPOCN_5: SIR Epidemic Model on Networks**
- Implementation of methods for **SIR (Susceptible-Infected-Recovered) model simulations**:
  - Simulate SIR dynamics using a **set of differential equations** and analyze phase portraits for different parameter values.
  - Simulate SIR dynamics on various network types (**2D lattice, random, Watts-Strogatz, and Barabási–Albert graphs**).
  - Explore the effect of **an updating scheme in the network version** on the final epidemic outcome.

### 5. **DPOCN_6: q-Voter Model and Opinion Dynamics**
- Implementation of the **q-voter model** for opinion dynamics.
- Simulation of the model on different graph structures.
- Analysis of **magnetization** in the system and its dependence on parameters.
