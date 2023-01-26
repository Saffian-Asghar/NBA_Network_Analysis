# Synergy Evaluation of NBA Players
This project uses network analysis techniques to study the interactions and relationships between NBA players, specifically focusing on the Los Angeles Lakers team and the effect of Lebron James on the team. We made two series of networks, one with and without Lebron James and another one with the win or loss involvement of the players. Each network is all the play events from playbyplayv2, such that edges are Source: Assister, Target: Goal Scorer. Thus, it's a directed network.

The data used in this project was collected from the <a href="https://github.com/swar/nba_api">nba_api</a> package, which provides access to NBA statistics and data. The analysis was done using Python and the NetworkX library.

## Data Collection
The data was collected by using the nba_api package to fetch play-by-play data for the Los Angeles Lakers team. The data was then pre-processed to create the necessary edge lists and node attributes.

## Data Analysis
The data was analyzed using various network analysis techniques, including centrality measures, community detection, and network visualization. The results of the analysis provide insights into the most important players, the relationships between players, and the overall structure of the team with and without Lebron James.

## Requirements
- Python 3.x
- NetworkX
- pandas
- nba_api
- Gephi

## Usage
- Clone the repository

 <code>git clone https://github.com/Saffian-Asghar/NBA_Network_Analysis.git</code>
- Install the required libraries
<code>pip install -r requirements.txt </code>

- Run the Jupyter notebook to reproduce the analysis

- Notebook with number pre-text denotes order of execution of scripts during the project.

## Folder Structure
- `notebooks`: contains Jupyter notebooks for data collection, processing, and analysis
- `results`: contains network data in csv format, modified data, figures, etc.
- `figures`: contains figures for the results of the analysis
## Results
- With Lebron James Playing

![Alt text](Figures/04_Network%20Visualizations%20in%20Gephi/04_withLebron.svg)

- Without Lebron James Playing

![Alt text](Figures/04_Network%20Visualizations%20in%20Gephi/04_withoutLebron.svg)

We also evaluated networks for games that were won by LA Lakers vs the ones they lost. In that case, we have the following results:
- Games Won
![Alt text](Figures/04_Network%20Visualizations%20in%20Gephi/04_LakersWonScoringOpp.svg)

- Games Lost
![Alt text](Figures/04_Network%20Visualizations%20in%20Gephi/04_LakersLostScoringOpp.svg)

The results of the analysis can be found in the Jupyter notebooks and the results folder. The results include the following:

- player centrality measures
- community detection
- network visualization
## Conclusion
This project provides a unique perspective on the relationships between NBA players and the effect of a superstar on the team, and can be used to gain insights into the league as a whole.

## Contribution
Feel free to fork the project, and make changes and pull request.

## Licence
This project is under <a href="https://github.com/Saffian-Asghar/NBA_Network_Analysis/blob/main/LICENSE" target="_new">MIT</a> licence.
