# README for Kruskal and Heap Sort Repository

## Overview

This repository contains Python implementations of two important algorithms:

1. **Kruskal's Algorithm**: Used to find the Minimum Spanning Tree (MST) of a graph. It is a greedy algorithm that ensures the resulting MST has the minimum total edge weight while connecting all vertices.
2. **Heap Sort Algorithm**: A popular sorting technique based on the heap data structure, which ensures efficient sorting with a time complexity of \(O(n \log n)\).

## Features

- **Kruskal's Algorithm**:
  - Reads input graph as an edge list with weights.
  - Sorts edges by weight and uses a union-find data structure to ensure no cycles are formed.
  - Outputs the edges in the MST and their total weight.

- **Heap Sort Algorithm**:
  - Utilizes a binary heap for sorting.
  - Handles ascending and descending order sorting.
  - Demonstrates in-place sorting without requiring additional memory.

## Requirements

- Python 3.8 or later
- No external libraries are required.

## How to Use

### Kruskal's Algorithm
1. Prepare a file containing the graph data as an edge list or modify the `edges` list directly in the script.
2. Run the script:
   ```bash
   python kruskal.py
   ```
3. The output will display the edges in the MST and their total weight.

### Heap Sort Algorithm
1. Update the `array` variable in the script with the list you want to sort.
2. Run the script:
   ```bash
   python heap_sort.py
   ```
3. The output will display the sorted array.

## Files in the Repository

- `kruskal.py`: Implementation of Kruskal's algorithm.
- `heap_sort.py`: Implementation of the heap sort algorithm.
- `README.md`: This file, providing details about the project.

## Example Input and Output

### Kruskal's Algorithm
**Input**:  
Graph with 4 vertices and edges:
```
(1, 2, 10), (1, 3, 15), (2, 4, 4), (3, 4, 6)
```

**Output**:
```
Edges in MST: [(2, 4, 4), (3, 4, 6), (1, 2, 10)]
Total weight: 20
```

### Heap Sort Algorithm
**Input**:  
Unsorted array:
```
[5, 3, 8, 4, 2]
```

**Output**:
```
Sorted array: [2, 3, 4, 5, 8]
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to enhance the implementation or add new features.

## License

This repository is licensed under the MIT License. See `LICENSE` file for more details.

---

Enjoy exploring these foundational algorithms! 😊
