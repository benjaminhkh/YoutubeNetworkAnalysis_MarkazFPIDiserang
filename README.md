# Network Analysis of Youtube Video: Markaz FPI Diserang (Beta)

Graph that shows the network of Youtube videos connected and stemming from the source video - "Markaz Besar DPP FPI Petamburan di serang polisi (Markaz FPI Diserang)", made with the [Sigmajs](http://sigmajs.org) plugin for [Gephi](http://gephi.org).

**> Interactive version of the graph (Beta): https://benjaminhkh.github.io/YoutubeNetworkAnalysis_MarkazFPIDiserang/

**> Source youtube video: https://www.youtube.com/watch?v=H1ffRyk8n9I

<a href="https://benjaminhkh.github.io/YoutubeNetworkAnalysis_MarkazFPIDiserang/ "><img src="https://raw.githubusercontent.com/nebnebnebneb/YoutubeNetworkMarkazFPIDiserang/master/images/illustration.png" alt="Network Analysis of Youtube Video: Markaz FPI Diserang"></a>


# Description 

The output graph shows the network of relations between videos stemming from the source video, based on similar relations. If a video from one channel points to the video of another channel, an edge is created and the more often that happens, the more weight the connection gets. 

"With the recommendation algorithms, we can visualize the path from video to video that the viewer can be taken on via the various levels of recommendations. In addition, we would be able to see any jumps in genre that might illustrate problematic paths that a user could take when going from video to video (e.g. from news to entertainment to satire/conspiracy) without realizing the shift." (Temple University)

Curved lines (edges) on the graphs show direction. Clockwise edges denote source youtube video connecting to target youtube video and vice versa.

**Node size:** Betweenness Centrality 

**Max Betweenness Centrality:** 124.18
(Komentar Ketua FPI Terkait Ricuh di Kawasan Petamburan)

>*Betweeness centrality* is the number of times a node falls along the shortest paths between two other nodes, representing the influence  of a node over the flow of information in a network.

**Label size:** Node Degree

**Max Degree:** 43 (out-degree 43, in-degree 0)
* (Markaz Besar DPP FPI Petamburan di serang polisi / Markaz FPI Diserang)

**Crawl Depth:** 1

**Video Categories in Legend**
* Group 1 - People and Blogs
* Group 2 - Gaming
* Group 3 - News and Politics
* Group 4 - Entertainment
* Group 5 - Music

# Credits

ISEAS - Yusof Ishak Institute. (2019) ISEAS - Yusof Ishak Institute.

Graph generated based on the Video Network Module produced by Temple University https://sites.temple.edu/tudsc/2019/03/26/network-analysis-on-youtube/

Template provided by InteractiveVis project
http://blogs.oii.ox.ac.uk/vis/
https://github.com/oxfordinternetinstitute/InteractiveVis/



