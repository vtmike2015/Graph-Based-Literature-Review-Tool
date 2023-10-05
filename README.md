# Graph-Based-Literature-Review-Tool
Graph-Based-Literature-Review-Tool

This Network-graph based literature review tool uses the open-source version of Neo4j (https://neo4j.com/) with Jupyter Notebooks written in Python to import academic literature metadata from a variety of sources including OpenAlex, arXiv, Web of Science and more. 

This tool is described in the paper "A Network-Graph Based IT Artifact Aiding the Theory Building Process" published by the 2022 Hawaii International Conference on System Sciences (HICSS) available at https://scholarspace.manoa.hawaii.edu/handle/10125/80136

Modeling academic literature data as a network graph helps answer questions involving:

Understanding relationships between entities (such as Work and Authors, Authors and Institution)
Self-referencing to the same type of entity (such as Works referencing Works)
Exploring relationships of varying or unknown depth (such as References of References)
Discovering different paths (such as Author connections through Intitution or co-authored Works)

