# projetDB_Indexing

This repository contains the implementation and experimental analysis of high-dimensional tree-based indexing methods, specifically focusing on KD-trees, R-trees, and M-trees.

## Project Structure

```
projetDB_Indexing/
├── KDtrees/              # KD-tree implementation and experiments
├── MtreesImplementation/ # M-tree implementation and experiments
├── Rtrees/              # R-tree implementation and experiments
└── Project_D_Report_OUMAIMA.pdf  # Detailed project report
```

## Overview

This project implements and evaluates three different tree-based indexing techniques for high-dimensional data:
- KD-trees
- R-trees
- M-trees

Each implementation includes:
- Core data structure implementation
- Search algorithms (including k-NN search)
- Performance optimizations
- Experimental visualizations and benchmarks

## Dataset

The implementations were tested using the GIST-960 dataset, which includes:
- 1 million 960-dimensional vectors (training set)
- 1,000 query vectors
- Ground truth data for 100 nearest neighbors

## Implementation Details

Each folder contains:
- Source code for the respective tree implementation
- Jupyter notebooks with experiments and visualizations
- Performance analysis and benchmarking results

## Documentation

For detailed information about the implementations, experimental results, and analysis, please refer to the comprehensive report: `Project_D_Report_OUMAIMA.pdf`

## Technologies Used

- Python
- NumPy
- Jupyter Notebook
- Matplotlib (for visualizations)
