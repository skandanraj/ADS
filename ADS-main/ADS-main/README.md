1.(i)Named Entity Recognition.

A natural language processing (NLP) technique called Named Entity Recognition (NER) attempts to recognize and categorize named entities in a text into specified categories, like names of people, places, organizations, times, amounts, monetary values, percentages, and so on. 
NER's main objective is to identify entities and their types in order to extract structured information from unstructured text. For many NLP applications, including document summarization, information retrieval, and responding systems, this task is essential.
Tokenizing the input text into words or phrases and then categorizing each token into preset entity categories are the usual steps involved in NER. For NER, a variety of deep learning and machine learning techniques are used, such as neural network-based models 
like Bidirectional LSTMs, statistical models like Conditional Random Fields (CRF), and rule-based techniques.

1.(ii).Python code to recognize named entities in a document. 

This Python script performs Named Entity Recognition (NER) on a text document provided as input. 
The input is  a text file containing 200-300 words. 
The script utilizes the spaCy library for NER and writes the recognized named entities along with their labels to an output file.
Ensure that spaCy is installed (`pip install spacy`) and the English language model "en_core_web_sm" is downloaded (`python -m spacy download en_core_web_sm`). 
To use this script, we specified  the input and output file paths in the code.
Also we have uploaded the input and output text files in this repository.

**2.Zachary's karate club network, accessible as karate.gml via NetworkX, analyzes group conflicts and fission. 
It comprises 34 nodes representing club members and edges indicating interactions outside club activities.**

This Python script analyzes Zachary's karate club network from the "karate.gml" file using NetworkX, a graph analysis library. It performs the following tasks:

i. Creates a graph from the "karate.gml" file and displays basic information about the network.

ii. Stores metadata of actors in the network.

iii. Calculates various centrality measures (degree, betweenness, closeness, eigenvector, and pagerank centrality) and provides an analysis based on the centrality values.

iv. Finds possible k-components of the network and computes the clustering coefficient.

v. Identifies communities using the Girvan-Newman algorithm and Louvain method.

Ensure NetworkX is installed (`pip install networkx`) and the "karate.gml" file is downloaded from the repository and  Update the file path accordingly.

