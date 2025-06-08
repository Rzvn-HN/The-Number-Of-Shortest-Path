# 🛣️ The-Number-Of-Shortest-Path


This Java program finds the number of distinct shortest paths between city `0` and city `n - 1` in a connected, undirected, weighted graph.

It uses **Dijkstra's algorithm** to compute shortest distances and **dynamic programming** to count the number of such paths efficiently.

## Features
- Handles up to 200 nodes with large weights (up to 1e9)
- Uses a priority queue for optimal performance
- Output is computed modulo `1_000_000_007`

## Usage
Input is read from standard input. Each line represents:
- `n m` — number of nodes and edges
- Followed by `m` lines of `x y t` representing an edge between `x` and `y` with time cost `t`.

The program prints the number of shortest paths from node `0` to node `n - 1`.

hw3-analy-algo
