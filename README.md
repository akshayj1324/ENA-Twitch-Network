# Exploratory Network Analysis of Twitch Sreamer Network in R using igraph package
This project is a part of the Network and Predictive Analytics course during my Master's at Penn State University

#### -- Project Status: [Completed]

## Project Objective
The purpose of this project is evaluate and explore the network, learn about its size, structure, and subgroup measurements, topographical, interconnected measures. It also identifies the central actors and key players in the network and offers a way to market a product either directed towards the streaming community or the gaming community that follows a particular stream while maximizing your reach.

### Methods Used
* Inferential Statistics
* Data Visualization

### Technologies
* R 
* R Studio
* iGraph

## Project Description
* **Goal:** The goal of this project is to perform exploratory network analysis on twitch streamers to identify central actors and key players in the network and offers a way to market a product.
* **Data Source:**
  * These datasets contain Twitch user-user networks of gamers who stream in a certain language. Nodes are the users themselves and the links are mutual friendships between them.
  * You can download the data from [here](https://snap.stanford.edu/data/twitch-social-networks.html)
  * For exploration we are only focusing on twitch streamers from Portuguese Brazilian speaking community.
* **Data Preparation:** Further for the visualization and marketing purposes we are focusing on Top 100 Streamers from Portuguese Brazilian speaking community.
* **Focus of Analysis:**
  * Topographical Measures.
  * Interconnectedness Measures.
  * Sub-Group Measures.
  * Centrality Measures.
  * Brokerage in the Network.

## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- data visualization
- writeup/reporting

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Partially pre-processed Data is being kept [here](/Data/) within this repo.
3. Data processing/transformation scripts are being kept [here](/preprocessing.ipynb)

## Featured Notebooks/Analysis/Deliverables
* [Base R script](/ena_twitch.Rmd) This is the R markdown that contains code for performing exploratory analysis
* [HTML export](/ena_twitch.html) This is the html export of the RMarkdown as we have some 3D visualizations that are easy to explore here.
* [Preprocessing Script](/preprocessing.ipynb) This is the preprocessing script. You only neeed to use this if you are using all the 6 streaming communities.
* [Documentation](/ENA-TwitchSocialNetworks.pdf) This the the documentation of the project mainly consisting of business questions and eda for explaining out answers.

## Contact
Feel free to contact me with any questions via [LinkedIn](https://www.linkedin.com/in/akshay2718/)