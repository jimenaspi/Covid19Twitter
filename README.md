# Covid19Twitter
Creating a network of co-occurences of Hashtags using a twitter dataset related to COVID-19 containing Tweets from 10 North-American cities.

This project aims to explore a Twitter data-set related to COVID-19 tweets made in ten different cities in North America over 255 days at the beginning of the pandemic. 

Notebooks folder contains:

-A_Data.ipynb
Read and pre-process the Twitter dataset.

-B_Networks.ipynb
Generate the networks and explore different weight threshold. Algorithms to detect comunities are implemented (label propagation, louvain, and Girvan-Newman)

-C_Cuadrants.ipynb
Code to perform Pairwise analysis of the links in the saved network. Measures such as pearson correlation, levenshtain distance and the weight (co-occurrences) are calculated and plotted.

-D_InteractivePlots.ipynb
Code to save a html interactive version of the network, to explore the labels and the communities found.

-E_ZIpf_Law.ipynb
Code to plot the log-log plot of number of mentions mentions againts mentions rank, and observe the fitting of the Zipf's Law.
