# Dynamic Hierarchical Cooperative Swarm Algorithm (DHCS)

## Overview

The **Dynamic Hierarchical Cooperative Swarm Algorithm (DHCS)** is a novel optimization technique inspired by swarm intelligence. The algorithm involves agents that adapt their roles dynamically to balance exploration and exploitation in high-dimensional optimization landscapes. The agents cooperate by forming clusters, sharing solutions, and periodically synchronizing to avoid stagnation.

This approach is particularly effective for solving complex optimization problems such as the **Ackley function**.

- Refer [DOMCUMENT](DOCUMENT.md) to know more.

## Features

- **Dynamic Agent Roles**: Agents take on different roles such as explorers, refiners, and leaders based on their performance.
- **Memory Sharing**: Agents maintain and share high-quality solutions to improve convergence.
- **Dynamic Clustering**: Agents form clusters based on proximity and fitness, with cluster leaders guiding others.
- **Synchronization**: Periodic synchronization of agents’ positions and velocities to prevent divergence.

## Algorithm Details

1. **Agent Behavior**: Agents explore, exploit, and lead other agents to find optimal solutions.
2. **Memory and Role Adaptation**: Agents store their best-found solutions and adapt their roles based on fitness improvement.
3. **Cluster Formation**: Agents are grouped based on proximity and fitness, with the best agent becoming a leader.
4. **Synchronization**: Agents are synchronized if no significant improvement occurs for a set number of iterations.

## Requirements

To run this algorithm, the following Python packages are required:

- `numpy` (for numerical operations)
- `matplotlib` (for plotting the convergence history)
- `random` (for generating random values)
- `time` (for measuring execution time)

You can install the necessary dependencies using `pip`:

```bash
pip install numpy matplotlib
```

## Usage

1. Clone the repository to your local machine:

```bash
request code over email at email address bajpaikrishna715@gmail.com
```

2. Navigate to the project directory:

```bash
cd DHCS
```

3. Run the algorithm:

```bash
python dhcs_algorithm.py
```

The script will execute the **DHCS** algorithm using the Ackley function as the optimization benchmark. You will see the convergence history printed in the terminal, and a plot of the global best fitness over iterations will be displayed.

## License Terms

The DHCS Algorithm (referred to as "this algorithm") is subject to a **custom license**. 

**No one is allowed to use, distribute, or modify this algorithm without prior written consent from the author.** The algorithm is provided for academic and research purposes only unless otherwise stated by the author.

You may not copy, modify, distribute, or otherwise use the algorithm for any commercial or non-commercial purpose without explicit permission from the author.

For permission inquiries, please contact bajpaikrishna715@gmail.com.

## Usage

Until permission is granted, this software should not be used, distributed, or modified.


### Terms of Use:
- The use of this algorithm is restricted to specific permissions granted by the owner.
- Any usage outside of these permissions is prohibited.

For permission to use or modify this algorithm, please contact bajpaikrishna715@gmail.com.

## Acknowledgements

This work is based on ideas from swarm intelligence and optimization techniques. Special thanks to the community for contributing to the development of optimization algorithms and mathematical models.

## Contact

For any inquiries or further information, please contact the author at bajpaikrishna715@gmail.com.

