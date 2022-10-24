# Distributed Evolutionary Computation (EC)

This is a *growing* paper list for **parallel and distributed** evolutionary computation (PDEC). Currently we are **actively** updating it (at least from 2021 to 2023). Owing to the abundance of the related literature, however, we believe that much interesting work is still missed here. If you find them missed, welcome to contact with us via [Issues](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/issues) or [Pull requests](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/pulls) to add.

## A (Relatively Big) Family of [Evolutionary Algorithms (EAs)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md)

Here, we consider a *relatively big* family of evolutionary algorithms (and also several closely related techniques, e.g., *random search* and *simulated annealing*), as presented below. Since here we focus primarily on their parallel/distributed versions and variants, we also provide a [ reference list](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md) for their original / seminal / landmark / survey / review papers, in order to help better understand them (especially for newcomers). We strongly suggest to see e.g. [2015's Review paper in **Nature** or 1993's Review paper in **Science**](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#popular-naturescience-reviews) for more details.

* Four Conventional EAs

  * [Genetic Algorithms (GA)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#genetic-algorithm-ga)
  
  * [Evolution Strategies (ES)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#evolution-strategies-es)
  
    * Covariance Matrix Adaptation ES (CMA-ES)

  * [Evolutionary Programming (EP)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#evolutionary-programming-ep)
  
  * [Genetic Programming (GP)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#genetic-programming-gp)

* Two [Swarm Intelligence (SI)](https://www.springer.com/journal/11721) Siblings

  * [Ant Colony Optimization (ACO)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#ant-colony-optimization-aco)

  * [Particle Swarm Optimization (PSO)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#particle-swarm-optimization-pso)

* Two Representative Multi-Objective Optimization (MOO) Evolutionary Frameworks

  * [Non-dominated Sorting Genetic Algorithm II (NSGA-II)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#non-dominated-sorting-genetic-algorithm-ii-nsga-ii)
  
  * [Multi-Objective Evolutionary Algorithm based on Decomposition (MOEA/D)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#multi-objective-evolutionary-algorithm-based-on-decomposition-moead)

* Several Relatively New Extensions/Improvements/Variants

  * Co-Evolutionary Algorithms (CEA)
  
    * [CoOperative co-Evolutionary Algorithms (COEA)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#cooperative-coevolutionary-algorithms-coea)
    
    * [CoMpetitive co-Evolutionary Algorithms (CMEA)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#competitive-co-evolutionary-algorithms-cmea)
  
  * Differential Evolution (DE)
  
  * Memetic Algorithms (MA)
  
  * [Estimation of Distribution Algorithms (EDA)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#estimation-of-distribution-algorithms-edas)
  
  * [Natural Evolution Strategies (NES)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#natural-evolution-strategies-nes)
  
  * [Quality-Diversity (QD)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#quality-diversity-qd)
  
    * Multidimensional Archive of Phenotypic Elites (MAP-Elites)

* [NeuroEvolution (aka Evolving Neural Networks)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#neuroevolution-aka-evolving-neural-networks)

* [Evolutionary/Swarm Robotics (ER/SR)](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#evolutionaryswarm-robotics)

* [Artificial Life (AL)](https://direct.mit.edu/artl)

  * Open-Ended Evolution

* Common Individual-based Counterparts/Baselines/Competitors (especially for their *stochastic* versions)

  * Random Search (RS)
  
  * Local Search (LS)
    
    * Hill Climbers (HC)
  
  * Simulated Annealing (SA)

## Review Scope

| Publication Type  | Publication Name | Search Range | Collection |
| :---: | :---: | :---: | :---: |
| Multidisciplinary Journals | [Nature](https://www.nature.com/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Nature.md)
| Multidisciplinary Journals | [Science](https://science.sciencemag.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Science.md)
| Multidisciplinary Journals | [PRL (Physical Review Letters)](https://journals.aps.org/prl/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Physical-Review-Letters_PRL.md)
| Multidisciplinary Journals | [PNAS (Proceedings of the National Academy of Sciences)](https://www.pnas.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/PNAS.md)
| Multidisciplinary Journals | [PIEEE (Proceedings of the IEEE)](http://proceedingsoftheieee.ieee.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/PIEEE.md)
| Multidisciplinary Journals | [Nature Machine Intelligence](https://www.nature.com/natmachintell/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Nature-Machine-Intelligence.md)
| Journals for CS | [JACM (Journal of the ACM)](https://dl.acm.org/journal/jacm) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/JACM.md)
| Journals for CS | [CACM (Communications of the ACM)](https://dl.acm.org/magazine/cacm) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/CACM.md)
| Journals for CS | [SICOMP (SIAM Journal on Computing)](https://epubs.siam.org/journal/smjcat) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/SIAM-Journal-on-Computing_SICOMP.md)
| Journals for AI/ML | [JMLR (Journal of Machine Learning Research)](https://jmlr.csail.mit.edu/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/JMLR.md)
| Journals for AI/ML | [AIJ (Artificial Intelligence Journal)](https://www.sciencedirect.com/journal/artificial-intelligence) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/AIJ.md)
| Journals for AI/ML | [IEEE-TPAMI (IEEE Transactions on Pattern Analysis and Machine Intelligence)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TPAMI.md)
| Journals for AI/ML | [IJCV (International Journal of Computer Vision)](https://www.springer.com/journal/11263) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IJCV.md)
| Conferences for AI/ML | [ICLR (International Conference on Learning Representations)](https://iclr.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ICLR.md)
| Conferences for AI/ML | [NeurIPS (Neural Information Processing Systems)](https://neurips.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Neural-Information-Processing-Systems_NeurIPS.md)
| Conferences for AI/ML | [ICML (International Conference on Machine Learning)](https://icml.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/International-Conference-on-Machine-Learning_ICML.md)
| Conferences for AI/ML | [COLT (Conference on Learning Theory)](https://learningtheory.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Conference-on-Learning-Theory_COLT.md)
| Journals for EC | [ECJ (Evolutionary Computation Journal)](https://direct.mit.edu/evco) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ECJ.md)
| Journals for EC | [ACM-TELO (ACM Transactions on Evolutionary Learning and Optimization)](https://dl.acm.org/journal/telo) | PDEC | [www](https://dl.acm.org/journal/telo)
| Journals for EC | [IEEE-TEVC (IEEE Transactions on Evolutionary Computation)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4235) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TEVC.md)
| Journals for Neural Networks | [NECO (Neural Computation)](https://direct.mit.edu/neco) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Neural-Computation_NECO.md)
| Journals for Neural Networks | [NN (Neural Networks)](https://www.sciencedirect.com/journal/neural-networks) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/NN.md)
| Journal for Parallel/Distributed Systems | [IEEE-TPDS (IEEE Transactions on Parallel and Distributed Systems)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=71) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TPDS.md)
| Conference for Parallel/Distributed Systems | [OSDI (USENIX Symposium on Operating Systems Design and Implementation)](https://www.usenix.org/conferences/byname/179) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/OSDI.md)
| Journals for Control/Robotics | [Science Robotics](https://www.science.org/journal/scirobotics) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Science-Robotics.md)
| Journals for Control/Robotics | [IEEE-TAC (IEEE Transactions on Automatic Control)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TAC.md)
| Journals for Control/Robotics | [IEEE-TRO (IEEE Transactions on Robotics)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8860) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TRO.md)
| Conferences for Control/Robotics | [RSS (Robotics: Science and Systems)](http://www.roboticsproceedings.org/index.html) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/RSS.md)

## Research Support

This *ongoing* paper list for PDEC is now supported by **Shenzhen Fundamental Research Program under Grant No. JCYJ20200109141235597** (￥2,000,000), granted to **Prof. Yuhui Shi** (CSE, SUSTech @ Shenzhen, China), and actively maintained/updated (from 2021 to 2023) by his group members (e.g., **Qiqi Duan**, *Chang Shao*, *Guocheng Zhou*, Mingyang Feng, Minghan Zhang, Youkui Zhang, and Qi Zhao).

We also acknowledge the additional contributions from [Vincent A. Cicirello](https://github.com/cicirello). We welcome the recent (from 2022) contributions from Jian Zeng (focusing on data mining).
