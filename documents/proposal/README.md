# Proposal

This `README` will contain the proposal for the project including the Research Question, the Hypothesis, the Methodology, the Data, and the Timeline.

## Title: Cross City Urban Public Transit Networks Analysis

### Summary

The goal of this project is to use network machine learning techniques to analyze the public transport networks of 25 cities across the world provided in the dataset [A Collection of Public Transport Network Data Sets for 25 Cities.](https://zenodo.org/record/1186215)

### Objectives

- How do the topological properties of public transport networks differ across different cities? What are the key factors that drive these differences?
- Which public transport stops are the most important in each city based on their centrality measures? How can this information be used to optimize public transport routes?
- How do the public transport networks of different cities compare in terms of connectivity and performance?
- How do public transport networks compare across different cities (similarities and differences)?
- Predict the travel time and travel cost between different locations within a city.

### Tasks

#### Data Preprocessing

- Cleaning the dataset and creating graphs for each city.

#### Exploration

- Analyzing the topological properties of the public transport networks
- Identifying important stops based on their centrality measures.
- Identifying communities within the network using clustering algorithms.
- Examining the correlation between station names and the node properties across cities.
- Evaluating if the lengths of shortest paths correspond to minimum geographical distance and minimum travel time?

#### Exploitation

- Predicting (across cities)
  - the type of edges (transport routes)
  - travel time between different locations within a city
  - probability of reaching a destination within a certain time frame.

### Timeline

- 17/04 - 21/04: Data preprocessing (1 week)
- 24/04 - 05/05: Exploration (Network analysis) (2 weeks)
- 08/05 - 26/05: Exploitation (ML models and predictions) (3 weeks)
- 29/05 - 09/06: Final report writing (2 weeks)
- 12/06 - 16/06: Final presentation (1 week)
