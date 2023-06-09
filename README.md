# Cross City Urban Transit Networks Analysis

Authors: Nitish and Ravinithesh.

Network Machine Learning course, Spring Semester 2023

<br/>

## Abstract

This project presents a network analysis of public transport systems in 25 cities. Various topological properties and connectivity measures were analysed along with centrality measures to identify critical transport stops. Furthermore, the analysis explored the potential for predicting directed edges and identifying the types of transport modes based on node features. The findings provide valuable insights into the connectivity of public transport systems.

[Complete Report](./documents/report/urban_transit_networks_analysis.pdf)

<br/>

## Structure

- `notebooks/`: Contains the notebooks used in the creation of metadata, plots, and results analysis.
  - `EDA/`:
    - `exploration.ipynb`: Exploratory Analysis of the data.
  - `Exploitation/`:
    - `edge-prediction/`: Notebooks for edge prediction tasks
    - `label-prediction/`: Notebooks for label prediction tasks
  - `IO/`:
    - `city-transport-graph.ipynb`: Create and save city transport graphs.
- `data/`: Contains the (some) data required to execute the scripts and notebooks. Large files and folders are stored separately.
  - `transport_data/`: Contains the public transport network data sets for 25 cities. ```Not uploaded on Github```
    - `checkpoints/`: Contains the intermediate data stored during the analysis.
    - `images/`: Contains the images to use in the notebooks.
    - `network_graphs/`: Contains the city-wise directed and undirected graphs generated with the notebook in IO.
- `documents`: Contains the documents related to the project.
  - `proposal/`: Contains the proposal document.
  - `report/`: Contains the tex and files used in generating the report document.
  - `presentation/`: Contains files used in generating the presentation document.

<br/>

## Installation and Usage

### Installation

```bash
pip install -r requirements.txt
```

## License

Cross City Urban Transit Networks Analysis - Nitish Ravishankar and Ravinithesh Annapureddy

Copyright (c) 2023

This program is licensed under the terms of the MIT License.
