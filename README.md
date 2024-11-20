# Itemset_mining_algorithm
This is a list of papers about itemset mining method.

## 1.Frequent itemset mining

| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| SIGMOD-1993 | - | Mining association rules between sets of items in large databases| |[R. Agrawal](https://doi.org/10.1145/170036.170072)|
| ESWA-2014 | - | Fast mining frequent itemsets using nodesets|  | [Z.-H. Deng](http://dx.doi.org/10.1016/j.eswa.2014.01.025) |  
| Appl. Soft Comput.-2016 | - | DiffNodesets: An efficient structure for fast mining frequent itemsets | | [Z.-H. Deng](https://doi.org/10.1016/j.asoc.2016.01.010) |   
| SIGMOD-2000 | - | Mining frequent patterns without candidate generation | |[J. Han](http://dx.doi.org/10.1145/335191.335372)|

## 2.High utility itemset mining
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| Knowl. Discovery and Data Min.-2005 | | A two-phase algorithm for fast discovery of high utility itemsets |. |[Y. Liu](http://dx.doi.org/10.1007/11430919_79)|
| SIGKDD-2010 | UP-growth:an efficient algorithm for high utility itemset mining |. |[[V. S. Tseng](https://doi.org/10.1145/1835804.1835839)|
| CIKM-2012 | | Mining high utility itemsets without candidate generation |. |[M. Liu](https://doi.org/10.1145/2396761.2396773)|
| TKDE-2013 | | Efficient algorithms for mining high utility itemsets from transactional databases |. |[V. S. Tseng](https://doi.org/10.1109/tkde.2012.59)|
| Lect. Notes in Comput. Sci.-2014 |FHM| FHM: Faster highutility itemset mining using estimated utility co-occurrence pruning|. |[P. Fournier-Viger](https://doi.org/10.1007/978-3-319-08326-1_9)|
| ESWA-2015 | | Pruning strategies for mining high utility itemsets |. |[S. Krishnamoorthy](https://doi.org/10.1016/j.eswa.2014.11.001)| 
| TKDE-2016 | | Mining high utility patterns in one phase without generating candidates |. |[J. Liu](https://doi.org/10.1109/tkde.2015.2510012.)|
| Knowl. Inf. Syst-2016 | EFIM | EFIM: a fast and memory efficient algorithm for high-utility itemset mining |. |[S. Zida](https://doi.org/10.1007/s10115-016-0986-0)| 
| Knowl. Inf. Syst-2016 |  | Indexed list-based high utility pattern mining with utility upper-bound reduction and pattern combination techniques |. |[H. Ryang](https://dl.acm.org/doi/10.1007/s10115-016-0989-x)| 
| Knowl. Inf. Syst-2017 | mHUIMiner | mHUIMiner: A fast high utility itemset mining algorithm for sparse datasets |. |[A. Y. Peng](https://doi.org/10.1007/978-3-319-57529-2_16)| 
| ESWA-2017 | Hminer | Hminer: Efficiently mining high utility itemsets |. |[S. Krishnamoorthy](http://dx.doi.org/10.1016/j.eswa.2017.08.028)|
| KBS-2022 | Ubp-miner | Ubp-miner: An efficient bit based high utility itemset mining algorithm |. |[P. Wu](http://dx.doi.org/10.1016/j.knosys.2022.108865)|
| TKDE-2023 |  | Mining high utility itemsets using prefix trees and utility vectors |. |[J.-F. Qu](http://dx.doi.org/10.1109/TKDE.2023.3256126)|
| TKDE-2024 |  | Efficient high utility itemset mining without the join operation |. |[Y. Yan](http://dx.doi.org/10.1016/j.ins.2024.121218)|

### 2.1 Dynamic and Incremental Databases
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| KBS-2019 | | Mining high-utility itemsets in dynamic profit databases |. |[L. T. Nguyen](http://dx.doi.org/10.1016/j.knosys.2019.03.022)|
| KBS-2023 |  |Efficient approach for mining high-utility patterns on incremental databases with dynamic profits |.| [S. Kim](http://dx.doi.org/10.1016/j.knosys.2023.111060)|
| DSE-2023 |  |A reinduction-based approach for efficient high utility itemset mining from incremental datasets|.| [P. Sra](http://dx.doi.org/10.1007/s41019-023-00229-4)|
| IEEE Access-2024 |  | Incremental top-k high utility pattern mining and analyzing over the entire accumulated dynamic database|. |[C. Lee](http://dx.doi.org/10.1109/ACCESS.2024.3406562)|

### 2.2 High average-efficiency itemsets
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
|  |  |  |. |[S. Krishnamoorthy](https://doi.org/10.1016/j.knosys.2017.12.035)|

### 2.3 High Utility Occupancy Itemset Mining 
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| IEEE Access-2018 |  |Tub-haupm: Tighter upper bound for mining high average-utility patterns|. |[J. M.-T. Wu](http://dx.doi.org/10.1109/ACCESS.2018.2820740)|
| IEEE Access-2019 |  |  An efficient tree-based algorithm for mining high average-utility itemset|. |[I. Yildirim](http://dx.doi.org/10.1109/ACCESS.2019.2945840)|
| Appl. Intell.-2024 | | Efficient algorithms to mine concise representations of frequent high utility occupancy patterns |. |[H. Duong](http://dx.doi.org/10.1007/s10489-024-05296-2)|


### 2.4 High-efficiency Itemset Mining 
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| KBS-2023 | Hepm | Hepm: High-efficiency pattern mining |. |[X. Zhang](http://dx.doi.org/10.1016/j.knosys.2023.111068)|
| KBS-2024 |  | An efficient strategy for mining high-efficiency itemsets in quantitative databases |. |[S. Krishnamoorthy](https://doi.org/10.1016/j.knosys.2017.12.035)|


## 3. Negative itemset mining
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| Expert Syst-2018 |  | Mining of high-utility itemsets with negative utility |  | [K. Singh](https://doi.org/10.1111/exsy.12296) | 
| New Gener. Comput.-2020 |  | Mining high-average utility itemsets with positive and negative external utilities |  | [I. Yildirim](http://dx.doi.org/10.1007/s00354-019-00078-8) | 
| Big Data-2020 | Top-HUI |  |  |  | 
| INS-2022 | TKN | An efficient approach for discovering top-k high utility itemsets with positive or negative profits |. |[Paper](https://www.sciencedirect.com/science/article/pii/S0020025521012457)|
| ESWA-2022 | EHMIN | EHMIN Efficient approach of list based high-utility pattern mining with negative utility profit | |[Paper](https://www.sciencedirect.com/science/article/pii/S0957417422013689)|
| 2022| SMNU |Faster Approximation of Probabilistic and Distributional Values via Least Squares| |[Paper](https://openreview.net/pdf?id=lvSMIsztka)|
| 2023 | negSPUC | 

## 4.Correlated Itemset Mining 
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| IEEE Access-2020 |  | Mining correlated high utility itemsets in one phase |. |[B. Vo](http://dx.doi.org/10.1109/ACCESS.2020.2994059)|


## Survey
| Source | Paper | Description |Links|Code|
| --- | --- | --- | --- |--- |
| Nature Machine Intelligence-2022 | Algorithms to estimate Shapley value feature attributions |. |[Paper](https://dl.acm.org/doi/abs/10.1145/3588728)|[code](https://github.com/suinleelab/shapley_algorithms)|
| IJCAI-2022 | The Shapley Value in Machine Learning |. |[Paper](https://www.ijcai.org/proceedings/2022/0778.pdf)|[code](https://github.com/AstraZeneca/awesome-shapley-value)|
| Data Mining and Knowledge Discovery-2024 | A comparative study of methods for estimating model-agnostic Shapley value explanations |. |[Paper](https://link.springer.com/content/pdf/10.1007/s10618-024-01016-z.pdf)||