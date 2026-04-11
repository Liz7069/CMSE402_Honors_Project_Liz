# CMSE402_Honors_Project_Liz


# Network Visualization with NetworkX: A Practical Tutorial

## Overview

This project is a publicly accessible data visualization tutorial that demonstrates how to analyze and visualize network data using Python and NetworkX.

Unlike many existing NetworkX resources, this tutorial focuses not only on how to construct graphs, but also on how to design visualizations that clearly communicate structure and relationships in the data.

The tutorial combines:
- network analysis techniques
- visualization design principles
- interpretation of results

---

## Motivation

Many existing NetworkX tutorials focus primarily on function usage and graph construction. However, they often do not explain how visualization choices affect interpretation.

This tutorial was created to fill that gap by:
- comparing different layout algorithms
- mapping analytical metrics (degree, centrality, clustering) to visual encodings
- explaining how design decisions influence what patterns are visible

The goal is to help users not only create network visualizations, but also understand how to design them effectively.

---

## What This Tutorial Covers

- Loading and processing network datasets
- Constructing graphs using NetworkX
- Applying layout algorithms (spring, circular, Kamada-Kawai)
- Computing network metrics:
  - degree
  - clustering coefficient
  - closeness centrality
  - betweenness centrality
- Visual encoding techniques:
  - node size
  - node color
  - edge width
- Multi-panel comparison of network metrics
- Shortest path visualization

---

## Dataset

This tutorial uses publicly available network datasets:

- **Hartford drug-use network** (used in course activities)
- **Les Misérables character network** (co-occurrence graph)

These datasets are included in the repository for reproducibility.

---

## Tools and Libraries

- Python
- NetworkX
- Matplotlib
- NumPy

---

## Connection to Data Visualization Principles

This tutorial incorporates ideas from data visualization theory and course readings:

- **Cairo**: emphasis on clear, meaningful, and explanatory visualizations  
- **Tufte**: reduction of unnecessary visual clutter  
- **Perception principles**: careful use of color and size to guide attention  

Examples include:
- using sequential colormaps for continuous values
- using node size to represent importance
- maintaining consistent node positions across panels for comparison

---

## Repository Structure
