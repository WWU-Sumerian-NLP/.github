# WWU Sumerian NLP

## Purpose 
We build tools to aid in the processing and analysis of ancient Sumerian tablets. This is through an NLP library written in Go and a no-code dashboard that serves our tools to non-technical researchers. We are actively developing our tools and are open to request for new integrations.

In addition, our tools can be leveraged to create applications that aid in the research of assyriologists. For example, we've created an application to build knowledge graphs and visualize them in neo4j to aid in prosophological studies

## About Us 
Dr. Yudong Liu (https://cs.wwu.edu/liuy2) </br>
Dr. Changyu Liu (https://zjnu.academia.edu/ChangyuLiu) </br>
Hansel Guzman-Soto (https://www.linkedin.com/in/hansel-guzman-soto/)


## Repositories

- [Sumerian_NLP_go](https://github.com/WWU-Sumerian-NLP/Sumerian_NLP_go) - These our NLP libraries, some modules include entity and relation extraction.

- [Sumerian_KG_python](https://github.com/WWU-Sumerian-NLP/Sumerian_KG_python) - This is our API that takes data generated from our NLP libraries to create a knowledge graph and store it in Neo4j. 

- [Server_go](https://github.com/WWU-Sumerian-NLP/Server_go) - This is our server that handles interactions between our dashboard, NLP libaries and other APIs. 

- [Nocode_dashboard_react](https://github.com/WWU-Sumerian-NLP/Nocode_dashboard_react) - This is our no-code dashboard.

- [Neo4jgraph_visualization_react](https://github.com/WWU-Sumerian-NLP/Neo4jgraph_visualization_react) - This is an early prototype of a graph visualization for sumerian knowledge graphs.

## General Architecture 

![architecture_main](https://github.com/WWU-Sumerian-NLP/images/blob/master/complete_arch.png) 

This picture above shows how our no-code dashboard and NLP libraries is leveraged to a create knowledge graphs. 

