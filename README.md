# Stochastic-Network-Dynamics-Opinion-Formation-Simulation-Project
🔁 Stochastic Network Dynamics & Opinion Formation – Simulation Project
This repository presents a comprehensive simulation-based analysis of random walks, hitting times, and opinion dynamics on networked systems. The project explores key models such as continuous-time Markov processes, hitting/return times, and the French-DeGroot model for opinion evolution across various graph structures.

🧠 Project Focus
🔄 Continuous-Time Random Walks
Simulated the movement of a single particle over a network with custom-defined transition rate matrices.

Measured and compared simulated vs. theoretical return times to and from specific nodes.

Analyzed hitting times and their relationship with system connectivity and rates.

🧭 Hitting Time Analysis
Estimated average time from a start node to a destination using:

10,000-run simulations

Linear algebraic methods for theoretical hitting time calculations

Quantified simulation error and validated the model using convergence behavior.

🧩 Opinion Dynamics with French-DeGroot Model
Simulated opinion convergence over 60–100 iterations.

Verified consensus formation under different initial conditions and network modifications.

Measured:

Final consensus state and value

Variance of the consensus (theoretical & simulation-based)

Investigated network sensitivity by removing/adding edges and introducing self-loops.

🔬 Open Particle System Simulation
Simulated particle inflow and transitions through a directed open network using two models:

Proportional rate passing (rate depends on number of particles at each node)

Fixed rate passing (constant transition rate)

Identified the maximum stable input rate (1000 particles/unit time) for both systems.

Visualized system behavior and node stability through time-series plots.

🧰 Tools & Libraries
Python 3, NumPy, Matplotlib

Random sampling, linear systems, network modeling

📁 Files
main notebook.ipynb: Complete simulation code with logic, plots, and data generation.

report.pdf: Full project report detailing problem descriptions, methodology, and results.

