# Clarke-Wright Savings (CWS) Heuristic for Vehicle Routing Problem

This repository implements the Clarke-Wright Savings (CWS) Heuristic algorithm for solving the Vehicle Routing Problem (VRP). The CWS heuristic is an efficient method for finding near-optimal solutions for VRP by merging routes that minimize transportation costs, such as distance or time.

## Features

- Implementation of Clarke-Wright Savings Heuristic for VRP.

- Input customization for different vehicle capacities and customer demands.

- Visualization of routing solutions.

- Performance analysis with real-world datasets.

## Installation

**Clone the repository:**

```bash
git clone https://github.com/yourusername/cws-heuristic-vrp.git
cd cws-heuristic-vrp
```

**Install dependencies:**
Ensure you have Python 3.x installed. Then, install the required packages:

```bash
pip install -r requirements.txt
```

**Unzip the Data Folder in the same directory**

## Usage
To run the Clarke-Wright Savings Heuristic algorithm on a sample dataset, use the provided Jupyter notebook __cws_heuristic_vrp.ipynb__:

**Open the notebook:**

```bash
jupyter notebook cws_heuristic_vrp.ipynb
```

## Configure the input:

Modify the vehicle Capacity, Instance Name, and __fileName__ to point to the provided instance file (.txt), and demand in the notebook cells.
Run the notebook cells to execute the CWS heuristic and visualize the solution.

## Output:

The output will include the optimized vehicle routes and the total cost of the solution.

## Example
```bash
# Example usage in the Jupyter notebook
from cws_heuristic import ClarkeWrightSavings

# Initialize problem parameters
instanceName = 'A-n80-k10'
vehicle_capacity = 100
fileName = os.path.join(r'<Instance_File_Path>', instanceName + '_input_nodes.txt')
# Run Clarke-Wright Savings Heuristic
```

## Analysis

The code provides the cost savings for the solution and the path chosen for vehicle routing problem

## Future Work

- __Enhancements__: Explore hybrid heuristics that combine CWS with other metaheuristics like Genetic Algorithms or Simulated Annealing for better performance.

- __Benchmarking__: Compare the CWS heuristic results with exact algorithms and other heuristics on larger datasets.

- __Scalability__: Optimize the implementation for larger, more complex VRPs involving multiple depots and heterogeneous fleets.**

- __Parallelization__: Investigate the possibility of parallelizing the CWS heuristic to speed up computation.**

## License
This project is licensed under the MIT License - see the LICENSE file for details.

