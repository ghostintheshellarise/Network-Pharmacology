# Drug efficacy
Using graph network to evaluate drug efficacy.

I am using several public databases to extract information about cancer treatement.  A network "Inhibition of Apoptosis" is extracted from Cytoscape.  This forms the base network to evaluate the efficacy of cancer drugs identified from KEGG.  The interaction between the drugs and the network nodes are reviewed using relevant extracts provided by PubMed. The ineraction rules are then incorporated into the network as additional nodes to evaluate the trajectory of the network when these interactions are activated in that network

Jupyter Notebooks:

1. Inhibition of Apoptosis.ipynb -> Curation of a interaction network downloaded from Cytoscape
2. 


# Reaction pathways enrichment
Using graph embedding to generate hypothesis on new reactions

I am extracting list of articles from public database PubMed about different enzyme-driven reactions.  The collected sentences would be converted to a graph structure in order to learn the embeddings between different action and reactant(s)/substrate(s).  

Jupyter Notebooks:
1. 
