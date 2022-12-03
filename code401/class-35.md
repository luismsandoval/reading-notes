# Graphs

## Terminology

1. Vertex - node that can have zero or more adjacent vertices

2. Edge - a connection between two nodes

3. Neighbor - a nodes adjacent nodes (connected via edge)

4. Degree - number of edges connected to a vertex

## Directed / Undirected

### undirected

- A graph where each edge is bi-directional. Meaning both nodes are directly connected.

- {value: a } => {value: b} && {value: a} <== {value: b}

### directed

- A graph where each edge is directed

- {value: a } => {value: b} && {value: a} => {value: c} && {value: b} => {value: a}

## Complete v Connected v Disconnected

### Complete

- All nodes are connected to all other nodes

### Connected

- All nodes have at least one edge

### Disconnected

- Some nodes may not have edges

## Adjacency list

```typescript
interface Node<NV, EV> {
  value: NV;
  edges: Map<Node<NV, EV>, EV>;
}

Set<Node<NV, EV>>();
```

![adjacency list](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjList.PNG)
