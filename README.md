# Manga

Data of 162 manga titles are available in "Manga_network_data.zip".

When you use the data, please cite the following paper:<br>
[Sugishita, K. and Masuda, N., Social network analysis of Japanese manga: similarities to real-world social networks and trends over decades, arXiv:2303.07208, 2023.](https://arxiv.org/abs/2303.07208)

Folder "Static" includes edgelist files of static and weighted character networks for the 162 manga titles. You can easily read the files running [read_weighted_edgelist](https://networkx.org/documentation/stable/reference/readwrite/generated/networkx.readwrite.edgelist.read_weighted_edgelist.html) on Python package networkx.<br>
Folder "Temporal" includes csv files of temporal edge lists for the 162 manga titles. "i" and "j" denote IDs of characters. "t" denotes the page.

Note that the characters are anonymized. We cannot answer which character corresponds to which ID. 
