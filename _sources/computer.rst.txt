.. |br| raw:: html

   <br />



**Visualization, exploitation and dissemination tools**
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

|br|


  .. dropdown:: Cuenca, E., Docquier, F., Nijssen, S., & Schaus, P. *EvoFlows: an Interactive Approach for Visualizing Spatial and Temporal Trends in Origin-Destination Data*. 
    
    Origin-Destination (OD) datasets provide insights into how entities shift across different geographic locations over time. The visualization of these spatio-temporal patterns can pose a challenge due to 
    the time-bound context and fluctuating dynamics between locations. Addressing this, we present EvoFlows, a tool equipped with two synergistic views. MultiStream focuses on the temporal aspect, expressing 
    data through stacked, aggregated time series, while FlowMaps emphasize the geographical dimension and the intensity of flows at distinct time points. With EvoFlows, users can interactively explore flows at 
    varying levels of detail through an array of interaction techniques and synchronized animations. The tool's utility is exemplified by an analysis of data covering 59 years of refugee migration.

    `Link to the article <https://www.info.ucl.ac.be/~pschaus/assets/publi/2020-evoflows.pdf>`_

|br|

  .. dropdown:: Mattenet, A., Davidson, I., Nijssen, S., & Schaus, P. (2021). *Generic constraint-based block modeling using constraint programming*. **Journal of Artificial Intelligence Research**, 70, 597-630.
    
    Block modeling has been used extensively in many domains including social science, spatial temporal data analysis and even medical imaging. Original formulations of the problem modeled it as a mixed integer 
    programming problem, but were not scalable. Subsequent work relaxed the discrete optimization requirement, and showed that adding constraints is not straightforward in existing approaches. In this work, we 
    present a new approach based on constraint programming, allowing discrete optimization of block modeling in a manner that is not only scalable, but also allows the easy incorporation of constraints. We 
    introduce a new constraint filtering algorithm that outperforms earlier approaches, in both constrained and unconstrained settings, for an exhaustive search and for a type of local search called Large 
    Neighborhood Search. We show its use in the analysis of real datasets. Finally, we show an application of the CP framework for model selection using the Minimum Description Length principle.

    `Link to the article <https://www.jair.org/index.php/jair/article/view/12280>`_ 

    `Link to the application <https://erickedu85.github.io/app/evoflows/>`_ 

|br|

  .. dropdown:: Golenvaux, N., Gillard, X., Schaus, P., & Nijssen, S. (2023). *Partitioning a Map into Homogeneous Contiguous Regions: A Branch-and-Bound Approach Using Decision Diagrams*.  
    
    Regionalization is a crucial spatial analysis technique used for partitioning a map divided into zones into $k$ continuous areas, optimizing the similarity of zone attributes within each area.
    This technique has a variety of applications in fields like urban planning, environmental management, and geographic information systems. 
    The REDCAP algorithm is a well-known approach for addressing the regionalization problem.
    It consists of two main steps: first, it generates a spatially contiguous tree (SCT) representing the neighborhood structure of the set of spatial objects using a contiguity-constrained hierarchical clustering method. 
    Second, it greedily removes $k-1$ edges from the SCT to create $k$ regions. 
    While this approach has proven to be effective, it may not always produce the most optimal solutions.
    We propose an alternative method for the second step, an exact dynamic programming (DP) formulation for the k-1 edges removal problem. 
    This DP is solved using a multi-decision-diagram (MDD)-based branch and bound solver leading to a more optimal solution. 
    We compared our proposed method with the REDCAP state-of-the-art technique on real data and synthetic ones, using different instances of the regionalization problem and different supervised and unsupervised metrics. Our results indicate that our approach provides higher quality partitions than those produced by REDCAP at acceptable computational costs. 
    This suggests that our method could be a viable alternative for addressing the regionalization problem in various applications.
    
    *Link to the paper*

|br|

|br|



:doc:`See the Computer Science Team <computerteam>`
