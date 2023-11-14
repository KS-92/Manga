# Manga

Data of 162 manga titles are available in "Manga_network_data.zip".

When you use the data, please cite the following paper:<br>
[Sugishita, K. and Masuda, N., Social network analysis of manga: similarities to real-world social networks and trends over decades, Applied Network Science, 8, 79, 2023.](https://link.springer.com/article/10.1007/s41109-023-00604-0?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=oa_20231113&utm_content=10.1007/s41109-023-00604-0)

Folder "Static" includes edgelist files of static and weighted character networks for the 162 manga titles. You can easily read the files running [read_weighted_edgelist](https://networkx.org/documentation/stable/reference/readwrite/generated/networkx.readwrite.edgelist.read_weighted_edgelist.html) on Python package networkx.<br>
Folder "Temporal" includes csv files of temporal edge lists for the 162 manga titles. "i" and "j" denote IDs of characters. "t" denotes the page.

Note that the characters are anonymized. We cannot answer which character corresponds to which ID. 
