# Compte Rendu Net 4103/7431 Réseau complexe
## Col Jean-Baptiste

## Question 2: Social Network Analysis with the Facebook100 Dataset

### (a) For these three networks plot the degree distribution for each of the three networks that you downloaded. What are you able to conclude from these degree distributions?

On remarque que pour les trois réseaux que plus le degré augmente, plus la densité diminue, ce qui veut dire qu'il y a beaucoup de noeuds avec un degré faible et peu de noeuds avec un degré élevé.

### (b) Compute the global clustering coefficient and mean local clustering coefficient for each of the 3 networks. In addition compute the edge density of each network. Should either of these networks be construed as sparse? Based on the density information and the clustering information what can you said about the graph topology?

Tous les ont une densité de liens très faible (c'est à dire une très petite par rapport à 1) ce qui signifie que les réseaux sont très clairsemés.

- caltech_edge_density =  0.05640442132639792
- mit_edge_density =  0.012118119495041378
- johnsHopkins_edge_density =  0.013910200162372396

On remarque aussi que le coefficient de clustering est très faible, ce qui signifie que les réseaux sont très peu connectés. 
 
- caltech_global_clustering_coefficient =  0.2912826901150874
- mit_global_clustering_coefficient =  0.18028845093502427
- johnsHopkins_global_clustering_coefficient =  0.19316123901594015
 
On peut donc conclure que les réseaux ont une topologie très dispersés et peu connectés.


### (c) For each network, also draw a scatter plot of the degree versus local clustering coefficient. Based on these calculations as well as your  revious ones, are you able to draw any conclusions about any similarities or differences between the tree networks? What other observations can you make?

Les réseaux ont tous une allure similaire, c'est à dire que plus le degré augmente, plus le coefficient de cluestering converge vers une valeur proche de 0,2 pour caltech et mit et 0,1 pour johnsHopkins. C'est à dire que les noeuds de grand degré ont une probabilité moyenne de 0,2 (0,1 pour johnsHopkins) d'avoir des voisins qui sont eux-mêmes connectés entre eux.

Plus les degrés ont une valeur basse, plus les coefficients de clustering peuvent prendre des valeurs éparses entre 0 et 1. C'est à dire que les noeuds de faible degré ont une probabilité forte d'avoir soit beaucoup de voisins qui sont eux-mêmes connectés entre eux soit presque aucun.

Humainement celà se comprends très bien, il y a souvent des petits groupes d'amis qui se connaissent très bien les uns les autres et donc qui sont eux-mêmes connectés entre eux. Il y a aussi parmi ces personnes des gens qui suivent d'autres gens très connus, ce qui fait augmenter le degré des gens connus mais qui ne sont pas eux-mêmes connectés entre eux (ce qui explique pourquoi les noeuds de fort degré ont un coefficient de clustering plus faible).

## Question 3: Assortativity Analysis with the Facebook100 Dataset


## Question 4: Link prediction



