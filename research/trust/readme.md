Notes
=====

social network analysis algorithms
--

1. software: data collection, visualization, network structure, dynamics, includes algorithms for calculating network metrics (centrality, clustering coefficient, community detection)
	1. examples: Gephi, Pajek, NodeXL
2. graph sampling algorithms: improves efficiency of analysis (e.g. 10,000 nodes vs 8,000,000,000 nodes is a massive difference in graph complexity)
3. graph pattern matching: locate subgraphs which match a predefined pattern
	1. algorithms: isomorphism, graph simulation
4. ??? not present (except in the references of course)
5. reduced computational cost of metric recalculation algorithms: "all pairs shortest paths, closeness, and between' s" (It is likely the document is missing information, since the [4]th reference is not used anywhere)
6. social network analysis
	1. structure: density, centrality, clustering
	2. node attributes: e.g. age, gender, etc.
	3. dynamics: information diffusion, community formation
7. random graph generation
	1. number of nodes
	2. average degree
	3. clustering coefficient
8. social influence: studies how information flows between individuals based on information diffusion.
	1. entropy
	2. mutual information
9. algorithms for social network coverage and reach: aims to identify the minimum set of nodes (influential nodes; optimal paths) that will maximize coverage and/or reach of information in a network
10. almost word for word the same as 9
11. ??? not present
12. community detection algorithms: clique percolation method, node-centric overlapping community detection
13. ??? not present
14. nature-inspired link prediction and community detection algorithms

Methods
1. graph density, centrality measures, community detection algorithms, network models, graph embedding techniques
2. evaluation: scalability, accuracy, robustness, interpretability
3. graph density: how "dense" or connected a graph is. ratio of edges to the total number of possible edges
4. centrality measures: quantifies importance or influence of individual nodes
5. community detection algorithms: identifies groups of nodes that are more densely connected to each other than to the rest of the network
6. network models: mathematical or computational representations of networks
7. graph embedding techniques: represents nodes and edges as vectors. Particularly useful for feeding machine learning algorithms
8. scalability: ability of a system, network, or process to efficiently scale up/out
9. accuracy: correctness of a model's predictions compared to actual outcomes in a dataset
10. robustness: Robustness can be evaluated using various techniques, including sensitivity analysis, where the model's performance is tested under different conditions or with perturbed inputs, and adversarial testing, where the model is tested against intentionally crafted inputs designed to fool the model. Improving the robustness of a model often involves techniques such as data augmentation, regularization, ensemble methods, and designing models that are inherently more resistant to noise and adversarial attacks.
11. interpretability: ability to understand and explain decisions or predictions of a machine learning model ("transparent rules", visualizations, feature importance scores)
12. Method: rational multi-objective analysis (MOORA)
"Moora" seems to be a modern method, more practical and use-full compared to classic methods. "MOORA is simply amazing." -directly from the paper
**This is a graph analysis technique use-full for decision making. Decide which nodes should be trusted according to the observer of results.**

>A green multi-criteria selection method for a comprehensive study of possibilities that takes into account high heterogeneity and a variety of useful components. The MOORA technique is presented to effectively resolve complex decision-making challenges. This method usually yields grades that are rigidly contradictory. Considers and strives to select the best solution while taking into account both positive and negative standards.

There is also MOOSRA (fun name Moose-Ra; there's a fun image)

----
Understanding Graph-Based Trust Evaluation in Online Social
Networks: Methodologies and Challenges

> Quantifying trust in OSNs is a notoriously difficult problem because of the complexity of OSNs and of trust itself. Studies in trust span multiple disciplines including economics [Huang 2007], sociology [Möllering 2001], political science [Newton 2001], psychology [Julian 1967; Cook et al. 2005], and computer science [Marsh 1994]

Explorations have been via: network structure, user behaviours, community detection, "and so on"

computing paradigm - social computing?? Are we talking actual computation, or some esoteric thing - an abstract idea.

Different models for trust evaluation exist. It appears proposals and reviews of these models began around 2007.

trust is regarded as: "a measure of confidence that an entity or entities will behave in an expected manner" (not a consensus)
Multiple definitions are present. Another that stuck out: "the subjective probability by which one user expects another user performs a given action" [I would add, at the end: for a given reason]
