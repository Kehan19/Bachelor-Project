# K Shortest Paths - Bachelor Project

## Overview
This project focuses on implementing and analyzing algorithms for solving the **K Shortest Paths Problem** in a graph. The goal is to compute not just the single shortest path but the top K shortest paths between two nodes in a weighted graph. This problem has applications in fields such as network routing, transportation, and logistics.

## Objectives
- Develop efficient algorithms for finding the K shortest paths.
- Compare the performance and accuracy of different algorithms.
- Evaluate the algorithms on various datasets, including real-world and synthetic graphs.

## Key Features
- **Algorithm Implementation**: Includes classical algorithms such as Yen's Algorithm and modern optimizations.
- **Graph Visualization**: Allows visualization of paths using tools like Matplotlib or Graphviz.
- **Performance Metrics**: Analyze time complexity, space complexity, and execution time.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - NetworkX: For graph creation and manipulation
  - Matplotlib: For visualizing graph paths
  - NumPy: For numerical computations

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/k-shortest-paths
   ```
2. Navigate to the project directory:
   ```bash
   cd k-shortest-paths
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the input graph as an adjacency list or use predefined datasets.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Specify the source and destination nodes, and the value of K.
4. View the output paths and performance metrics.

## Project Structure
- **`main.py`**: Entry point of the application.
- **`algorithms/`**: Contains implementations of various K shortest paths algorithms.
- **`data/`**: Sample graph datasets.
- **`tests/`**: Unit tests for algorithms.
- **`visualizations/`**: Scripts for generating visual representations of the paths.

## Datasets
- Real-world road network data
- Synthetic random graphs (e.g., Erdos-Renyi, Barabasi-Albert models)

## Future Work
- Extend the implementation to handle dynamic graphs.
- Add support for multi-criteria shortest paths.
- Explore parallelization techniques for performance improvement.

## Contributors
- Kenneth Birk Hansen - \[\href{mailto:kbirkhansen@gmail.com}{kbirkhansen@gmail.com}\]

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## References
- Yen, J.Y. (1971). Finding the K Shortest Loopless Paths in a Network. Management Science.
- Thorup, M. (2004). Compact oracles for reachability and approximate distances in planar digraphs. Journal of the ACM.

---

Feel free to reach out for collaboration or questions!
