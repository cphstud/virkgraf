# Bite-Sized Neo4j for Data Scientists
### Written by: Dr. Clair J. Sullivan, Data Science Advocate, Neo4j
#### email: clair.sullivan@neo4j.com
#### Twitter: @CJLovesData1
#### Last updated: December 3, 2021

All notebooks can be found in `notebooks/`.
Some videos are strictly based on Cypher querys, which can be found in `cypher/`.

### Note:
The notebooks in this repository are not meant to be stand-alone and thus are not commented.  They go with the videos.  So you are encouraged to watch the videos and then consult the notebooks should you will to look at the actual code in depth.

## Videos

### :sparkles: :sparkles: Find this video series as its [own webpage](https://neo4j.com/video/bite-sized-neo4j-for-data-scientists/) on the Neo4j webpage!!! :sparkles: :sparkles:

### [Complete YouTube playlist of full series](https://dev.neo4j.com/bite_sized_playlist)

[Part 1: Connect from Jupyter to a Neo4j Sandbox](https://dev.neo4j.com/bites_part1)

[Part 2: Using the py2neo Python Driver](https://dev.neo4j.com/bites_part2)

[Part 3: Using the Neo4j Python Driver](https://dev.neo4j.com/bites_part3)

[Part 4: Basic Cypher Queries (and with Google Colab)](https://dev.neo4j.com/bites_part4)
  - This video uses a Google Colab notebook, which can be found [here](https://dev.neo4j.com/bites_part4_notebook)

[Part 5: Populating the Database from Pandas](https://dev.neo4j.com/bites_part5)
  - This video refers to a YouTube video on how to create efficient Cypher queries, which is linked in the references below.

[Part 6: Populating the Database with LOAD CSV](https://dev.neo4j.com/bites_part6)
  - This video references [this GitHub repo](https://github.com/mathbeveridge/gameofthrones) that has the data used in this part.

[Part 7: Populating the Database with the neo4j-admin tool](https://dev.neo4j.com/bites_part7)
  - This video works from the command line using Docker.  The shell commands are provided in GitHub gists, which can be found [here](https://gist.github.com/cj2001/9321ff16672921e1c197b67336f97f19).
  - The data for this part can be found in `data/` (the files are `got-s1-nodes.csv` and `got-s1-edges.csv`).

[Part 8: Populating the Database from a JSON file](https://dev.neo4j.com/bites_part8)
  - This video references a JSON file I created for my NODES 2021 tutorial, "Creating a Knowledge Graph with Neo4j: A Simple Machine Learning Approach."
    - [Repository for the workshop](https://dev.neo4j.com/nodes2021_kg_workshop): Contains the JSON file
      - I have also put this file in the `data/` directory of this repository, but the Cypher query I used in the video (`cypher_queries/part8.cql`) uses the workshop repo.
    - [Video of the workshop](https://dev.neo4j.com/kg_workshop)

[Part 9: Cypher Queries 2](https://dev.neo4j.com/bites_part9)

[Part 10: Creating In-Memory Graphs with Cypher Projections](https://dev.neo4j.com/bites_part10)

[Part 11: Import RDF Data from Wikidata](https://dev.neo4j.com/bites_part11)
  - To query Wikidata, it is helpful to know how to use SPARQL.  The query builder that I showed (which has several great example queries) can be found [here](https://query.wikidata.org/).  Wikidata also provides a good [SPARQL tutorial](https://www.wikidata.org/wiki/Wikidata:SPARQL_tutorial).
  - This video shows the use of Neosemantics for importing the RDF data.  See below in the References for docs on how to use it.
  - This video also shows _very_ quickly demonstrates Neo4j Bloom for visualization and queries.  For an in-depth look at how to use Bloom, see [this video](https://dev.neo4j.com/3p6q7IP).

[Part 12: Creating In-Memory Graphs with Native Projections](https://dev.neo4j.com/bites_part12)
  - This is the sister video for Part 10, which explored the other method for creating in-memory graphs.

[Part 13: Calculating Centrality](https://dev.neo4j.com/bites_part13)

[Part 14: Community Detection with the Louvain Method](https://dev.neo4j.com/bites_part14)

[Part 15: Community Detection via Weakly Connected Components](https://dev.neo4j.com/bites_part15)

[Part 16: Using Strongly Connected Components to Detect Communities](https://dev.neo4j.com/bites_part16)

[Part 17: Creating FastRP Graph Embeddings](https://dev.neo4j.com/bites_part17)
  - For more information on how FastRP works, see the following blog posts:
    - [Behind the scenes on the Fast Random Projection algorithm for generating graph embeddings](https://dev.neo4j.com/fastrp_background)
    - [Making FastRP Graph Embeddings Work for You](https://dev.neo4j.com/frp_tuning)


## References

- [O'Reilly Graph Algorithm Examples in Apache Spark & Neo4j Book](https://dev.neo4j.com/graph_algorithms_book)
- [The Neo4j Cheat Sheet and Quick Reference](https://dev.neo4j.com/neo4j_cheatsheet)
- [Neo4j Cypher Reference Card](https://neo4j.com/docs/cypher-refcard/current/)
- [Advanced Cypher Query Tuning (video)](https://youtu.be/xPSKqm4hFRc)
- [Awesome Procedures on Cypher (APOC) User Guide](https://neo4j.com/labs/apoc/4.1/)
- [Graph Data Science Library API Docs](https://dev.neo4j.com/graph_data_science)
- [Neosemantics Docs](https://neo4j.com/labs/neosemantics/)
- [Bloom Docs](https://neo4j.com/docs/bloom-user-guide/current/)
