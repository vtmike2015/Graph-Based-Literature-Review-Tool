# Graph-Based-Literature-Review-Tool

This Network-graph based literature review tool uses the open-source version of [Neo4j](https://neo4j.com/) with Jupyter Notebooks written in Python to import academic literature metadata from a variety of sources including OpenAlex, arXiv, Web of Science and more. Using a simple data model schema, literature metadata can be quickly imported, aggregated and normalized for analysis. 

![Data Model Schema](https://github.com/vtmike2015/Graph-Based-Literature-Review-Tool/blob/main/Images/Data_Schema.png "Data Model Schema")

This tool is described in the paper ["A Network-Graph Based IT Artifact Aiding the Theory Building Process"](https://scholarspace.manoa.hawaii.edu/handle/10125/80136) published by the 2022 Hawaii International Conference on System Sciences (HICSS).

Modeling academic literature data as a network graph helps answer questions involving:
<ul>
<li>Understanding relationships between entities (such as Work and Authors, Authors and Institution)</li>
<li>Self-referencing to the same type of entity (such as Works referencing Works)</li>
<li>Exploring relationships of varying or unknown depth (such as References of References)</li>
<li>Discovering different paths (such as Author connections through Intitution or co-authored Works)</li>
</ul>
