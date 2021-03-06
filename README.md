# Learned-Index-Archive
Arrange&amp;Categorize recent Learned Index Papers


## Primary Index

### One-Dimensional

Learned Index Cases, [The_Case_for_Learned_Index_Structures](/Notes/Learned_Index_Presentation_2020_6_28.pptx) \[[Paper](/Papers/The_Case_for_Learned_Index_Structures.pdf)\], SIGMOD17. <br>
Ada-Bloom Filter, Adaptive Learned Bloom Filter (Ada-BF):
Efficient Utilization of the Classifier, \[[Paper](/Papers/Adaptive_Learned_Bloom_Filter_Efficient_Utilization_of_the_Classifier.pdf)\], preprint19.<br>
Sandwiching Bloom Filter, A Model for Learned Bloom Filters, and Optimizing by Sandwiching, \[[Paper](/Papers/A_Model_for_Learned_Bloom_Filters_and_Optimizing_by_Sandwiching.pdf)\], NIPS20.<br>
Partitioned Learned Bloom Filters(PLBF), Partitioned Learned Bloom Filters. \[[Paper](/Papers/Partitioned_Learned_Bloom_Filters.pdf)\], preprint20.<br>
RadixSpline(RS), RadixSpline: A Single-Pass Learned Index. \[[Paper](/Papers/RadixSpline_A_Single-Pass_Learned_Index.pdf)\], preprint20<br>

[SIndex A Scalable Learned Index for String Keys](https://dl.acm.org/doi/abs/10.1145/3409963.3410496).  SIGOPS20 workshop
> current learned indexes primarily focus on integer-key workloads and failed to efficiently index variable-length string keys. We introduce SIndex, a concurrent learned index specialized in variable-length string key workloads. To reduce the cost of model inference and data accesses, SIndex groups keys with shared prefixes and use each key's unique part for model training. We evaluate SIndex with both real-world and synthesized datasets. The result shows that SIndex can achieve up to 91% better performance compared with other state-of-the-art index structures. We have open-sourced our implementation
> Pure for String Key


[A Pluggable Learned Index Method via Sampling and Gap Insertion](https://arxiv.org/abs/2101.00808). Preprint2021
> With the guidance of the formal learning objective, we can efficiently learn index by incorporating the proposed sampling technique, and learn precise index with enhanced generalization ability brought by the proposed result-driven gap insertion technique.


### Multi-Dimensional

Multi-Dim Learned index, [The_ML-Index_A_Multidimensional_Learned_Index](/Notes/Learned_Index_Presentation_2020_6_28.pptx),  \[[Paper](/Papers/The_ML-Index_A_Multidimensional_Learned_Index.pdf)\], EDBT20.<br>
Grid & Flood operation, [Flood: Learning_Multi-dimensional_Indexes](/Notes/Learned_Index_Presentation_2020_6_28.pptx), \[[Paper](/Papers/Learning_Multi-dimensional_Indexes.pdf)\], SIGMOD20.<br>
Tsunami, Tsunami: A Learned Multi-dimensional Index for Correlated Data and SkewedWorkloads, \[[Paper](/Papers/Tsunami_A_Learned_Multi-dimensional_Index_for_Correlated_Data_and_SkewedWorkloads.pdf)\], Preprint. <br>
Learned Bloom Filter, [Lifting_the_Curse_of_Multidimensional_Data_with_Learned_Existence_Indexes](/Notes/Learned_Index_Presentation_2020_6_28.pptx),  \[[Paper](/Papers/Lifting_the_Curse_of_Multidimensional_Data_with_Learned_Existence_Indexes.pdf)\], Nips18 workshop.<br>
LISA, LISA: A Learned Index Structure for Spatial Data, \[[Paper](/Papers/LISA_A_Learned_Index_Structure_for_Spatial_Data.pdf)\], SIGMOD20.<br>
Qd-Tree, Qd-tree: Learning Data Layouts for Big Data Analytics, \[[Paper](/Papers/Qd-tree.pdf)\], SIGMOD20.<br>

#### RSMI, Effectively Learning Spatial Indices  \[[Paper](/Papers/Effectively_Learning_Spatial_Indices.pdf)\], VLDB20.
> A recent study shows that a neural network can not only learn to predict the disk address of the data value associated with a one-dimensional search key but also outperform B-tree-based indexing, thus promises to speed up a broad range of database queries that rely on B-trees for efficient data access. We consider the problem of learning an index for two-dimensional spatial data. A direct application of a neural network is unattractive because there is no obvious ordering of spatial point data. Instead, we introduce a rank space based ordering technique to establish an ordering of point data and group the points into blocks for index learning. To enable scalability, we propose a recursive strategy that partitions a large point set and learns indices for each partition. Experiments on real and synthetic data sets with more than 100 million points show that our learned indices are highly effective and efficient. Query processing using our indices is more than an order of magnitude faster than the use of R-trees or a recently proposed learned index.

#### [The Case for Learned Spatial Indexes](https://arxiv.org/abs/2008.10349), preprint  (Experimental work with Flood)
> In this work, we use techniques proposed from a state-of-the art learned multi-dimensional index structure (namely, Flood) and apply them to five classical multi-dimensional indexes to be able to answer spatial range queries.

## Secondary Index

### Multi-Dimensional
Hermit Structure \(TRS-Tree\), Designing Succinct Secondary Indexing Mechanism by Exploiting Column Correlations, \[[Paper](/Papers/Designing_Succinct_Secondary_Indexing_Mechanism_by_Exploiting_Column_Correlations.pdf)\], SIGMOD19. <br>
Hermit\(A demonstration\), HERMIT in Action: Succinct Secondary Indexing Mechanism via Correlation Exploration, \[[Paper](/Papers/HERMIT_in_Action_Succinct_Secondary_Indexing_Mechanism_via_Correlation_Exploration.pdf)\], PVLDB20. <br>


