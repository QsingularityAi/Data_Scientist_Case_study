# EduSphere Knowledge Graph Project

## Overview
This project demonstrates a knowledge graph implementation for content personalization using Neo4j, focusing on creating intelligent relationships between users, content, and tags.

## Project Tasks
1. **Knowledge Graph Schema Design**
   - Create a schema connecting users, content, and tags
   - Support content personalization through semantic relationships
   - Visualize graph connections and interactions

2. **Knowledge Graph Construction**
   - Utilize Neo4j for graph database management
   - Implement graph visualization and recommendation algorithms

## Prerequisites
- Python 3.10+
- Neo4j Desktop
- Required Python Libraries:
  ```
  pip install neo4j-driver
  pip install yfiles-jupyter-graphs-for-neo4j
  pip install pandas
  pip install numpy
  pip install scikit-learn
  ```

## Neo4j Setup
- Install Neo4j Desktop
- Create a new database
- Install two essential plugins:
  1. APOC
  2. Graph Data Science

## Key Features
- User-Content Interaction Tracking
- Content Tagging and Similarity Analysis
- Semantic Tag Relationships
- Personalized Content Recommendations

## Project Structure
- `EduGraph.ipynb`: Main Jupyter notebook with implementation
- `graph_schema.png`: Visual representation of graph schema


## Recommendation Approach
The project uses cosine similarity and graph-based techniques to generate personalized content recommendations based on:
- User interaction history
- Content tags
- Semantic tag relationships

## Visualization
Includes graph visualization capabilities using yFiles Jupyter Graphs for Neo4j

## License
See the `LICENSE` file for project licensing details.

