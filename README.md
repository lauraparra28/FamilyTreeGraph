# FamilyTreeGraph
This project represents a graph based on the genealogical family tree of my father's family. Use a knowledge graph to visualize the relationships and connections between family members.

# Knowledge Graph Vs. Tree 
A knowledge graph and a tree are both data structures employed for organizing information, yet they exhibit fundamental distinctions in their design and functionality. The primary variance lies in the flexibility of their connections and the hierarchical structure. Unlike a tree, which adheres to a rigid hierarchical format with unidirectional and hierarchical relationships, a knowledge graph provides greater flexibility, enabling the representation of more intricate and multidirectional connections [[1]](https://www.geeksforgeeks.org/difference-between-graph-and-tree/).

| Característica              | Knowledge Graph                                 | Tree Graph                                       |
|-----------------------------|-------------------------------------------------|--------------------------------------------------|
| **Estrutura**               | Utiliza nós e relações para modelar informações. | Organizado hierarquicamente com nós em níveis.    |
| **Flexibilidade**           | Permite relações mais complexas e multidirecionais sem restrições hierárquicas. | Segue uma estrutura hierárquica rígida e relações unidirecionais. |
| **Representação**           | Adequado para representar conhecimento complexo em diversas áreas. Comum em web semântica, bases de dados de grafos, e sistemas de recomendação. | Utilizado para organizar informações de maneira hierárquica, como estruturas de arquivos ou árvores genealógicas. |


# Repository Structure
Explanation of the files and folders present in the repository.

- Arvore_Parra_Castro_Grafo.ipynb: File that contains the graph data in ipynb format, version 1.
- Family_Graph.ipynb: File that contains the graph data in ipynb format, final version. 
- ´grafo_familiar.json´ : File that contains the graph data in JSON format [In progress]
- visualization_grafo.py: Python script to generate graph visualizations. [In progress]
- ´README.md´: This file, providing detailed information about the project.

# Family Tree Data
This section describes the structure of the data in the ´family_graph.json´ file. What information is included for each family member? How are relationships represented?

Example structure of family_graph.json:

{
  "family_members": [
    {
      "name": "Father",
      "children": ["Child1", "Child2"],
      "father": null,
      "mother": null
    },
    // ... other family members
  ]
}


# Contributions
Explanation of how other family members or contributors can contribute to the project. You can include guidelines for submitting pull requests, issue reports, or suggestions for improving the graph.
