# Understanding Graph Convolutional Networks

By Sidney Arcidiacono

*A companion to the [AICamp Webinar: "Understanding Graph Convolutional Networks"](https://www.aicamp.ai/event/eventdetails/W2021090710) given by Sidney Arcidiacono, September 7th, 2021*

### Abstract

We often encounter interconnected data in our work—from molecular structure, to gene and protein interactions to addresses and streets on a map, to connections in a social network–so much of the world is better understood when we address its connections.
Since the so-called “deep learning revolution”, remarkable improvements have been made by RNNs, CNNs, GANs, and more – driving fields such as computer vision and natural language processing forward by leaps and bounds. We often encounter instances, though, where it’s the relationships between our data as well as the data itself that we need to consider fully, and sometimes Euclidean representations fall short.

Graph Neural Networks have become a hotter and hotter topic in recent years. Since 2014, approaching deep learning with graph-structured data has become less and less niche, and many improvements have been made in algorithms that make predicting on graph-structured data possible. However, even within the term “Graph Neural Networks”, there are a variety of vastly different approaches, and lots of hype. So, what can GNNs do for you?

## Predicting on Biological Datasets

### Data

[PROTEINS benchmark dataset](https://ls11-www.cs.tu-dortmund.de/staff/morris/graphkerneldatasets)


### How to Use the Notebooks

```zsh
git clone https://github.com/sidneyarcidiacono/UnderstandingGCNs
```

1. You can open the [notebook](https://github.com/sidneyarcidiacono/UnderstandingGCNs/blob/main/PROTEINS_Embedding.ipynb) in Jupyter Notebook
2. You can open a new Colab document and select "From Jupyter Notebook" in the dropdown

### Citations

1. https://towardsdatascience.com/an-introduction-to-graph-neural-network-gnn-for-analysing-structured-data-afce79f4cfdc
2. https://tkipf.github.io/graph-convolutional-networks/
3. https://towardsdatascience.com/graph-convolutional-networks-deep-99d7fee5706f
4. https://arxiv.org/pdf/2003.11702.pdf
5. https://en.wikipedia.org/wiki/Degree_matrix
6. https://computationalsocialnetworks.springeropen.com/articles/10.1186/s40649-019-0069-y
7. https://papers.nips.cc/paper/2017/file/f507783927f2ec2737ba40afbd17efb5-Paper.pdf
8. Predicting Multicellular Function Through Multi-Layer Tissue Networks
