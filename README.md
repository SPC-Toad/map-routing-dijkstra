# Euclidean Graph Project

This project involves creating a Euclidean Graph in Java. The `EuclideanGraph` class is designed to manage the creation and manipulation of a graph based on Euclidean distances between points.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Helpful Resource](#helpful-resource)

## Introduction

The `EuclideanGraph` class allows for the creation of graphs where nodes are points in Euclidean space, and edges represent the distances between these points. This can be useful for various applications, including geographic information systems, network design, and more.

## Features

- Create a graph with nodes positioned in Euclidean space.
- Calculate distances between nodes.
- Add and remove nodes and edges.
- Find the shortest path between nodes using Euclidean distance.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/euclidean-graph.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd euclidean-graph
    ```

3. **Compile the Java files:**
    ```sh
    javac EuclideanGraph.java
    ```

## Usage

1. **Run the `EuclideanGraph` class:**
    ```sh
    java EuclideanGraph
    ```

2. **Sample code to create and manipulate a Euclidean Graph:**

    ```java
    // Create an instance of EuclideanGraph
    EuclideanGraph graph = new EuclideanGraph();

    // Add nodes with coordinates (x, y)
    graph.addNode(1, 2);
    graph.addNode(3, 4);

    // Add an edge between the nodes
    graph.addEdge(0, 1);

    // Calculate the distance between two nodes
    double distance = graph.calculateDistance(0, 1);
    System.out.println("Distance: " + distance);

    // Find the shortest path between two nodes
    List<Integer> path = graph.findShortestPath(0, 1);
    System.out.println("Shortest path: " + path);
    ```

## Helpful Resource

For a visual explanation and detailed guide on Euclidean graphs, you can refer to this [YouTube video](https://www.youtube.com/watch?v=GazC3A4OQTE&t=316s).
