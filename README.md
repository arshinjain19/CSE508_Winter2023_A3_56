# CSE508_Winter2023_A3_56


INFORMATION RETRIEVAL
Q1) Link Analysis
libraries used - pandas , numpy , matplotlib.pyplot

Dataset chosen: Wikipedia Vote Network

Nodes in the network: Wikipedia users 
Edges in the network: user i voted on user j

Dataset was downloaded as a tab-separated txt file; we iterated over each line.
Created the Adjacency Matrix and  Edge list for the data set.

Number of Nodes: 7115
Number of Edges: 103689
Avg In-degree: 14.573295853829936
Avg Out-degree: 14.573295853829936
Node with Max In-degree: 4037
Node with Max Out-degree: 2565
The density of the network: 0.0020485375110809584

Avg. In-Degree = Sum of the number of incoming edges of every node / total number of nodes 
Avg. Out-Degree = Sum of the number of outgoing edges of every node / total number of nodes 
Network Density (D) = E / (N*(N-1)) for directed networks;E = a number of edges,N = a number of nodes



Since the data set in directed graph,Plotted the a scatted graph of  degree distribution of the network for a directed graph, plot in-degree, and out-degree.
 
The local clustering coefficient of each node: 
Local Clustering Coefficient of each node = Number of pairs of neighbors of the node that are connected / number of pairs of neighbors of the node 
The clustering coefficient lies between 0 and 1. The clustering coefficient is more skewed towards 1, giving higher certainty.
The overall clustering coefficient of the network:


Q2)PageRank, Hubs and Authority

libraries used - pandas , numpy , matplotlib.pyplot and networkx

In this report, we will compare the Pagerank and the HITS algorithms, discussing their similarities and differences, strengths, weaknesses, and application areas.
PageRank
The Pagerank algorithm evaluates the web's link structure and rates each page according to the quantity and quality of links. Higher-scoring pages are considered more reliable and more likely to appear at the top of search engine results pages.

Hits
HITS (Hyperlink-Induced Topic Search) is another algorithm used in web search engines to rank web pages based on their relevance and authority. The HITS algorithm works by analyzing the link structure of the web and identifying pages that are both authoritative and relevant to a user's search query.

