# Algorithmic-Prices-Bertrand
Replication Details for my Masters Thesis "Collusion in Oligopolistic Competition, A Machine Learning Approach"


Author: Jan-Felix Heymann
Repository: Algorithmic-Prices-Bertrand
Overview

This repository contains the implementation of a simulation framework for studying algorithmic price setting in a Bertrand competition environment. Bertrand competition models markets with homogeneous goods where firms compete by setting prices, and customers purchase from the lowest-priced firm.

The project explores how reinforcement learning (RL) algorithms simulate price evolution under different market structures, demand functions, and cost setups. It also considers how firms may tacitly collude to achieve supra-competitive pricing, the stability of collusion under asymmetric conditions, and the effects of varying the number of competitors.
Key Features

    Dynamic pricing simulation using reinforcement learning.
    Integration of different demand functions:
        Linear
        Quadratic
        Root-based
    Simulations for varying market conditions:
        Equal vs. asymmetric marginal costs
        Different numbers of competing firms (e.g., 2, 3, 4, and 5 firms).
    Comparison of price convergence rates and cartel stability.
    Analysis of Cournot competition (quantity-based competition).
    Support for long-term simulations with millions of iterations.

Repository Structure

    /notebooks/
    Contains Jupyter notebooks for running simulations, visualizing results, and analyzing various scenarios (e.g., different marginal costs or demand functions).

    /data/
    Stores any synthetic datasets generated or used during simulations.

    /src/
    Source code for simulation functions and reinforcement learning algorithms.

    /figures/
    Graphs and visualizations produced during the simulation runs.

    requirements.txt
    List of Python dependencies required to run the simulations.

Getting Started
Prerequisites

    Python 3.9 or higher
    Jupyter Notebook (optional for running .ipynb files)


Running the Simulations

    Clone the repository:

    git clone https://github.com/JanHeymann/Algorithmic-Prices-Bertrand.git
    cd Algorithmic-Prices-Bertrand

    Explore the provided Jupyter notebooks in the notebooks/ folder to run simulations interactively.

    Alternatively, use the scripts in the src/ directory for batch simulations.

Examples

    Simulating Bertrand Competition with Asymmetric Marginal Costs
    Run the relevant notebook or script to explore price evolution under unequal costs. The output includes visualizations of moving averages for firm prices.

    Impact of the Number of Firms
    Analyze how the speed of price convergence and cartel stability change with the number of competitors.

    Demand Function Variations
    Compare the effects of linear, quadratic, and root-based demand functions on price strategies.

Results and Analysis

This repository provides extensive visualizations and statistical analyses for key scenarios:

    Moving averages of prices under different demand functions.
    Impact of increasing firm numbers on the stability of tacit collusion.
    Comparison of Bertrand and Cournot competition in algorithmic pricing contexts.

Graphs and tables are saved in the /figures/ directory and can be reproduced or modified by running the provided scripts or notebooks.
