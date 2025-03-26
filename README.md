# Data_for_manuscript

This dataset contains GROMACS molecular dynamics simulation files for seven different protein structures, each represented in three distinct functional forms: free pMHC, free TCR, and TCRpMHC. For each structure and form, two independent simulation replicates (parallel runs) were conducted to ensure statistical reliability.

The repository includes:

Full GROMACS input and output files for all simulations (e.g., .gro, .mdp, .xtc, .tpr, etc.).
A structured Excel file (.xlsx) containing post-simulation analysis results, including calculated properties such as RMSF, SASA, gRINN outputs, and other structural metrics.
These results were generated using the createDataset.ipynb script for each structure. Only a sample notebook is provided; the analyses were performed externally and are not included in the notebooks.
Jupyter notebooks for custom analyses and visualizations of simulation results, such as RMSF, energy heatmaps, clustering, and network-based evaluations.
This dataset supports reproducibility and further analysis of structural dynamics across different protein states and replicates. It may be useful for benchmarking, comparative studies, or method development in computational structural biology.
