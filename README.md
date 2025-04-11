# Alliances
This project uses graph balancing theory in order to predict changing military alliances between countries during a global conflict. Although the overall trend of military alliances is not necessarily toward balance, we can use cyclical patterns to estimate whether the network is trending toward or away from balance.

### Data
Spreadsheets: This folder contains Numbers files in the form of adjacency matrices which were used to produce CSV files. 1 represents a military alliance, -1 represents a military conflict, and 0 means the countries are neutral.

Starting: This folder contains CSV files with the alliance ajacency matrices near the "start" date for WW1 and WW2 at a year when the network begins to trend toward balance.

### Code

alliances.ipynb: The parameters in this file can be changed to run an algorithm on various CSV files which visualizes how the network might be balanced over time.

### Docs
