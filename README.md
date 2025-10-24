# Itemset_mining_algorithm
This is a list of papers about itemset mining method.

## 1.Frequent itemset mining

| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| SIGMOD-1993 | - | Mining association rules between sets of items in large databases| |[R. Agrawal](https://doi.org/10.1145/170036.170072)|
| ESWA-2014 | - | Fast mining frequent itemsets using nodesets|  | [Z.-H. Deng](http://dx.doi.org/10.1016/j.eswa.2014.01.025) |  
| Appl. Soft Comput.-2016 | - | DiffNodesets: An efficient structure for fast mining frequent itemsets | | [Z.-H. Deng](https://doi.org/10.1016/j.asoc.2016.01.010) |   
| SIGMOD-2000 | - | Mining frequent patterns without candidate generation | |[J. Han](http://dx.doi.org/10.1145/335191.335372)|
|DSE-2024|| Efficient Top-k Frequent Itemset Mining on Massive Data  || [X. Han](https://link.springer.com/article/10.1007/s41019-024-00241-2)|

## 2.High utility itemset mining
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| PAKDD-2005 | | A two-phase algorithm for fast discovery of high utility itemsets | first two-phase algorithm |[Y. Liu](http://dx.doi.org/10.1007/11430919_79)|
| SIGKDD-2010 |UP-growth | UP-growth:an efficient algorithm for high utility itemset mining |. |[V. S. Tseng](https://doi.org/10.1145/1835804.1835839)|
| CIKM-2012 | HUI-Mine| Mining high utility itemsets without candidate generation |. |[M. Liu](https://doi.org/10.1145/2396761.2396773)|
| TKDE-2013 | UP-growth+| Efficient algorithms for mining high utility itemsets from transactional databases |. |[V. S. Tseng](https://doi.org/10.1109/tkde.2012.59)|
| Lect. Notes in Comput. Sci.-2014 |FHM| FHM: Faster highutility itemset mining using estimated utility co-occurrence pruning|. |[P. Fournier-Viger](https://doi.org/10.1007/978-3-319-08326-1_9)|
| ESWA-2015 | HUP-Miner| Pruning strategies for mining high utility itemsets |. |[S. Krishnamoorthy](https://doi.org/10.1016/j.eswa.2014.11.001)| 
| TKDE-2016 |d2HUP | Mining high utility patterns in one phase without generating candidates |. |[J. Liu](https://doi.org/10.1109/tkde.2015.2510012.)|
| Knowl. Inf. Syst-2016 | EFIM | EFIM: a fast and memory efficient algorithm for high-utility itemset mining |. |[S. Zida](https://doi.org/10.1007/s10115-016-0986-0)| 
| Knowl. Inf. Syst-2016 | IMHUP | Indexed list-based high utility pattern mining with utility upper-bound reduction and pattern combination techniques |. |[H. Ryang](https://dl.acm.org/doi/10.1007/s10115-016-0989-x)| 
| Knowl. Inf. Syst-2017 | mHUIMiner | mHUIMiner: A fast high utility itemset mining algorithm for sparse datasets |. |[A. Y. Peng](https://doi.org/10.1007/978-3-319-57529-2_16)| 
| ESWA-2017 | HMiner | Hminer: Efficiently mining high utility itemsets |. |[S. Krishnamoorthy](http://dx.doi.org/10.1016/j.eswa.2017.08.028)|
|INS-2021 | |Efficient Top-k High Utility Itemset Mining on Massive Data|prefix partition|[X. Han]|
| KBS-2022 | UBP-Miner | Ubp-miner: An efficient bit based high utility itemset mining algorithm |. |[P. Wu](http://dx.doi.org/10.1016/j.knosys.2022.108865)|
| TKDE-2023 | Hamm | Mining high utility itemsets using prefix trees and utility vectors |. |[J.-F. Qu](http://dx.doi.org/10.1109/TKDE.2023.3256126)|
| INS-2024 |  | Efficient high utility itemset mining without the join operation |. |[Y. Yan](http://dx.doi.org/10.1016/j.ins.2024.121218)|
|TKDE-2024 | PHA-HUIM | GPU-Based Efficient Parallel Heuristic Algorithm  for High-Utility Itemset Mining in Large  Transaction Datasets | Parallel & Heuristic|[W. Fang](https://ieeexplore.ieee.org/document/10167780?arnumber=10167780)|

### 2.1 Dynamic and Incremental Databases
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| KBS-2019 |iMEFIM| Mining high-utility itemsets in dynamic profit databases |. |[L. T. Nguyen](http://dx.doi.org/10.1016/j.knosys.2019.03.022)|
| KBS-2023 |  |Efficient approach for mining high-utility patterns on incremental databases with dynamic profits |.| [S. Kim](http://dx.doi.org/10.1016/j.knosys.2023.111060)|
| DSE-2023 |  |A reinduction-based approach for efficient high utility itemset mining from incremental datasets|.| [P. Sra](http://dx.doi.org/10.1007/s41019-023-00229-4)|
| IEEE Access-2024 |  | Incremental top-k high utility pattern mining and analyzing over the entire accumulated dynamic database|. |[C. Lee](http://dx.doi.org/10.1109/ACCESS.2024.3406562)|

### 2.2 High average-efficiency itemsets
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| TKDE-2019 |  | Efficient Vertical Mining of High Average-Utility Itemsets Based on Novel Upper-Bounds | |[Truong](https://doi.org/10.1016/j.knosys.2017.12.035)|

### 2.3 High Utility Occupancy Itemset Mining 
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| IEEE Access-2018 |  |Tub-haupm: Tighter upper bound for mining high average-utility patterns|. |[J. M.-T. Wu](http://dx.doi.org/10.1109/ACCESS.2018.2820740)|
| IEEE Access-2019 |  |  An efficient tree-based algorithm for mining high average-utility itemset|. |[I. Yildirim](http://dx.doi.org/10.1109/ACCESS.2019.2945840)|
| Appl. Intell.-2024 | | Efficient algorithms to mine concise representations of frequent high utility occupancy patterns |. |[H. Duong](http://dx.doi.org/10.1007/s10489-024-05296-2)|
| ESWA-2022 | SHO | Efficient high-utility occupancy itemset mining algorithm on massive dat |. |[Jingxuan He](https://www.sciencedirect.com/science/article/pii/S0957417422014543c)|

### 2.4 High-efficiency Itemset Mining 
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| KBS-2023 | Hepm | Hepm: High-efficiency pattern mining |. |[X. Zhang](http://dx.doi.org/10.1016/j.knosys.2023.111068)|
| KBS-2024 |  | An efficient strategy for mining high-efficiency itemsets in quantitative databases |. |[S. Krishnamoorthy](https://doi.org/10.1016/j.knosys.2017.12.035)|


## 3. Negative itemset mining
| Source |Method | Paper | Description |Links|
| --- | --- | --- | --- |--- |
| Appl Math Comput.-2009 |HUINIV| An efficient algorithm for mining high utility itemsets with negative item values in large databases | first negative HUIM |[C. Chu](https://www.sciencedirect.com/science/article/pii/S009630030900561X) | 
| Knowl. Inf. Syst-2011 | MHUI-BIT & MHUI-TID | Fast and memory efficient mining of high-utility itemsets from data streams: with and without negative item profits | mining high-utility itemsets from data streams | [K. Singh] | 
| ESWA-2014 |TS-HOUN| On-shelf utility mining with negative item values| On-shelf utility mining | [Guo-Cheng Lan] |
| KBS-2016 |FHN | FHN: Efficient Mining of High-Utility Itemsets with Negative Unit Profits | | [P. Fournier-Viger]|
|2015 |FOSHU|FOSHU: Faster On-Shelf High Utility Itemset Mining with or without Negative Unit Profit |  | [P. Fournier-Viger]|
|2015 |UP-GNIV| UP-GNIV: an expeditious high utility pattern mining algorithm for itemsets with negative utility values ||[Kannimuthu Subramanian]|
|2016 |HUN-Max|Mining High Utility Itemsets with Negative Utility Values in Transactional Databases|| [Priyanka D. Patil]|
| Knowl. Inf. Syst-2017| KOSHU |An efficient algorithm for mining top-k on-shelf high utility itemsets|top-K on-shelf high utility itemset | [Thu-Lan Dam]|
|2017| EHUFIM | An Enhanced Algorithm for Retrieving High Utility-Frequent Item Sets with Negative Utility Values|  | [C. Sivamathi]|
| PAKDD-2017| HUPNU | Mining High-Utility Itemsets with Both Positive and Negative Unit Profits from Uncertain Databases |Uncertain Databases| [W. Gan]
| TKDE-2018| CHN| CHN: an efficient algorithm for mining closed high utility itemsets with negative utility | closed high utility itemset | [Kuldeep Singh] Retracted. |
| Expert Syst-2018 | EHIN | Mining of high-utility itemsets with negative utility |  | [K. Singh](https://doi.org/10.1111/exsy.12296) | 
| KBS-2018| GHUM | Efficiently mining high utility itemsets with negative unit profits| utility list | [Srikumar Krishnamoorthy]|
| INS-2019| EHNL | EHNL: An efficient algorithm for mining high utility itemsets with negative utility value and length constraints| length constraints | [K. Singh] |
| New Gener. Comput.-2020 |  | Mining high-average utility itemsets with positive and negative external utilities |  | [I. Yildirim](http://dx.doi.org/10.1007/s00354-019-00078-8) | 
| Big Data-2020 | Top-HUI | TopHUI: Top-k high-utility itemset mining with negative utility | first top-k negative HUIM | [W. Gan](https://ieeexplore.ieee.org/abstract/document/9378288) | 
|J. Comp. Sci.-2020| | Extracting High Utility Itemset with Positive and Negative Utilities Using High Utility Itemset Mining Algorithm| | [N Umadevi]|
|J. Intell Syst.-2021 | | Mining high utility pattern with negative items in dynamic databases | dynamic databases (first)| [M. Han]|
| 2021| | Mining of High Utility Itemsets with Negative Utility values for Incremental Datasets | Incremental Datasets |[Pushp]| 
| 2021|TOPIC |TOPIC: Top-k High-Utility Itemset Discovering| | [J. Chen]|
| INS-2022 | TKN | An efficient approach for discovering top-k high utility itemsets with positive or negative profits |. |[M. Ashraf](https://www.sciencedirect.com/science/article/pii/S0020025521012457)|
| ESWA-2022 | EHMIN | EHMIN: Efficient approach of list based high-utility pattern mining with negative utility profit |. |[H. Kim](https://www.sciencedirect.com/science/article/pii/S0957417422013689)|
|J. Intell. Fuzzy Syst.-2021 | THN | Mining of top-k high utility itemsets with negative utility |. |[R. Sun](https://content.iospress.com/articles/journal-of-intelligent-and-fuzzy-systems/ifs201357)|
| 2022| SMNU |Support-Based High Utility Mining with Negative Utility Values|. |[Pushp](https://link.springer.com/chapter/10.1007/978-981-19-0604-6_18)|
| 2023 | negSPUC | negSPUC: Trees-Based Single-Phase High-Utility Itemset Mining Algorithm with Negative Profit Values |  | [B. Anup. Bhat](https://link.springer.com/book/10.1007/978-981-19-5868-7#page=718)|

## 4.Correlated Itemset Mining  
| Source |Method | Paper | Correlation Description |Links|
| --- | --- | --- | --- |--- |
|TKDE-2003|  |Alternative interest measures for mining associations in databases | Definitions |[Omiecinski](http://ieeexplore.ieee.org/document/1161582/)|
|J. IGPL-2020| FCHM |Mining correlated high-utility itemsets using various measures|AllConf & Bond |[P. Fournier-Viger](https://academic.oup.com/jigpal/article/28/1/19/5700705)|
|J. Inf. Tele.-2021| GMCHM | A General Method for mining high-Utility itemsets with correlated measures|AllConf & Bond |[N.M.Hung](https://www.tandfonline.com/doi/epdf/10.1080/24751839.2021.1937465?needAccess=true)|
|ICDM workshops-2021|CHUQI-Miner|CHUQI-Miner: Mining Correlated Quantitative High Utility Itemsets|Q-itemset & Bond | [M. Nouioua](https://ieeexplore.ieee.org/document/9679886/)|
|KBS-2018|CoHUIM|Extracting non-redundant correlated purchase behaviors by utility measure|Kulc| [W. Gan](https://linkinghub.elsevier.com/retrieve/pii/S0950705117305750)|
|IEEE Big Data-2018 & INS-2019| CoUPM |CoUPM:Correlated utility-based pattern mining | Kulc |[18-W. Gan](https://ieeexplore.ieee.org/document/8622242/) \\ [19-W. Gan](https://linkinghub.elsevier.com/retrieve/pii/S0020025519306139)|
|IEEE Access-2020 |CoHUI-Mine| Mining correlated high utility itemsets in one phase |Kulc|[B. Vo](http://dx.doi.org/10.1109/ACCESS.2020.2994059)|
|ICInPro-2021|ECHUM|Positive Correlation Based Efficient High Utility Pattern Mining Approach| |[Ramesh, D](https://www.springerprofessional.de/en/positive-correlation-based-efficient-high-utility-pattern-mining/19983244) \\ [Code](https://www.philippe-fournier-viger.com/spmf/ECHUM_correlation.php)|
|ICT Res.-2023| |A Method Mining Correlation High Utility Itemsets with Negative Profits|Kulc|[Cao](https://ictmag.ictvietnam.vn/ict/article/view/1228)|
|KBS-2024||Effective approaches for mining correlated and low-average-cost patterns|Kulc low-average-cost|[X. Liu](https://www.sciencedirect.com/science/article/pii/S0950705124010104)|

## 5.Local High-utility Itemset Mining 
| Source |Method | Paper |Links | Code|
| --- | --- | --- | --- | --- | 
|EAAI-2025| fast-LHUIM |Fast mining local high-utility itemsets |[Song et. al](https://linkinghub.elsevier.com/retrieve/pii/S0952197624021195) | [code](https://linkinghub.elsevier.com/retrieve/pii/S0952197624021195)|
|INS-2019| LHUIM |Mining local and peak high utility itemsets |[Fournier-Viger](https://linkinghub.elsevier.com/retrieve/pii/S0020025518310284)|[code](https://www.philippe-fournier-viger.com/spmf/index.php?link=algorithms.php)|

## Survey
| Source | Paper | Description |Links|
| --- | --- | --- | --- |
| J. Intell. Fuzzy Syst.-2018 | High utility itemsets mining with negative utility value: A survey |. |[K. Singh](https://www.researchgate.net/profile/Kuldeep-Singh-122/publication/328844143_High_utility_itemsets_mining_with_negative_utility_value_A_survey/links/65223d96d717ef1293d69005/High-utility-itemsets-mining-with-negative-utility-value-A-survey.pdf)|
|2020|Utility Mining Algorithms: A Bird’s Eye View |.| [D. Aarthi]
|TKDE-2021| A survey of utility-oriented pattern mining|  |  [W. Gan](https://ieeexplore.ieee.org/abstract/document/8845637) |
|IEEE Access-2021|A Survey of Correlated High Utility Pattern Mining |[Almoqbily](https://ieeexplore.ieee.org/document/9374911/)|
