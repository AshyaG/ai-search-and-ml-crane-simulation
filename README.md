# ai-search-and-ml-crane-simulation
This project models and solves a constrained container-stacking problem using symbolic AI planning and classical search algorithms, followed by a machine learning classifier for container prioritisation.

## Overview
- Implemented a state-space model of a crane operating across multiple bays
- Defined logical predicates, transition rules, and action costs
- Solved the planning problem using an optimised Breadth-First Search (BFS)
- Trained and evaluated a K-Nearest Neighbours (KNN) classifier on container data

- ## Key Features
- Symbolic representation of states and actions
- Custom BFS with visited-state checking to reduce redundant expansions
- Cost-aware action modelling (e.g. heavy container penalties)
- Machine learning pipeline with train/test split and accuracy evaluation

- ## Technologies Used
- Python
- Breadth-First Search (AI Planning)
- State-space search
- K-Nearest Neighbours (scikit-learn)
- Pandas, NumPy
- Jupyter Notebook

- ## What I Learned
- How to formally model real-world problems as search spaces
- Trade-offs between optimality, completeness, and performance in search algorithms
- How classical AI methods differ from machine learning approaches
- How to evaluate ML models using accuracy and random state variation
- Ethical and environmental considerations of AI deployment

## How to Run
Open `Crane_problems.ipynb` in Jupyter Notebook and run cells sequentially.
