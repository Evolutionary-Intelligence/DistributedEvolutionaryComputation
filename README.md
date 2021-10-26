# Distributed Evolutionary Computation (EC)

This is a *growing* paper list for **parallel and distributed** evolutionary computation (PDEC). Currently we are **actively** updating it (at least from 2021 to 2023). Owing to the abundance of the related literature, however, we believe that much interesting work is still missed here. If you find them missed, welcome to contact with us via [Issues](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/issues) or [Pull requests](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/pulls).

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
  
    * CoOperative co-Evolutionary Algorithms (COEA)
    
    * CoMpetitive co-Evolutionary Algorithms (CMEA)
  
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
| Multidisciplinary Journal | [Nature](https://www.nature.com/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Nature.md)
| Multidisciplinary Journal | [Science](https://science.sciencemag.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Science.md)
| Multidisciplinary Journal | [PRL (Physical Review Letters)](https://journals.aps.org/prl/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/PRL.md)
| Multidisciplinary Journal | [PNAS (Proceedings of the National Academy of Sciences)](https://www.pnas.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/PNAS.md)
| Multidisciplinary Journal | [PIEEE (Proceedings of the IEEE)](http://proceedingsoftheieee.ieee.org/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/PIEEE.md)
| Journal for CS | [CACM (Communications of the ACM)](https://dl.acm.org/magazine/cacm) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/CACM.md)
| Journal for AI/ML | [JMLR (Journal of Machine Learning Research)](https://jmlr.csail.mit.edu/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/JMLR.md)
| Journal for AI/ML | [AIJ (Artificial Intelligence Journal)](https://www.sciencedirect.com/journal/artificial-intelligence) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/AIJ.md)
| Journal for AI/ML | [IEEE-TPAMI (IEEE Transactions on Pattern Analysis and Machine Intelligence)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TPAMI.md)
| Journal for AI/ML | [IJCV (International Journal of Computer Vision)](https://www.springer.com/journal/11263) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IJCV.md)
| Journal for AI/ML | [Nature Machine Intelligence](https://www.nature.com/natmachintell/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TPAMI.md)
| Conference for AI/ML | [ICLR (International Conference on Learning Representations)](https://iclr.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ICLR.md)
| Conference for AI/ML | [NeurIPS (Neural Information Processing Systems)](https://neurips.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/NeurIPS.md)
| Conference for AI/ML | [ICML (International Conference on Machine Learning)](https://icml.cc/) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ICML.md)
| Journal for EC | [ECJ (Evolutionary Computation Journal)](https://direct.mit.edu/evco) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ECJ.md)
| Journal for EC | [IEEE-TEVC (IEEE Transactions on Evolutionary Computation)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4235) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TEVC.md)
| Journal for Parallel / Distributed Systems | [IEEE-TPDS (IEEE Transactions on Parallel and Distributed Systems)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=71) | PDEC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TPDS.md)
| Journal for Robotics | [Science Robotics](https://www.science.org/journal/scirobotics) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/ScienceRobotics.md)
| Journal for Robotics | [IEEE-TRO (IEEE Transactions on Robotics)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8860) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/IEEE-TRO.md)
| Conference for Robotics | [RSS (Robotics: Science and Systems)](http://www.roboticsproceedings.org/index.html) | EC | [www](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/RSS.md)

## Research Support

This *ongoing* paper list for PDEC is now supported by **Shenzhen Fundamental Research Program under Grant No. JCYJ20200109141235597** (￥2,000,000), granted to **Prof. Yuhui Shi** (CSE, SUSTech @ Shenzhen, China), and actively maintained/updated (from 2021 to 2023) by his group members (e.g., **Qiqi Duan**, *Chang Shao*, Mingyang Feng, Minghan Zhang, Youkui Zhang, and Qi Zhao).

We also acknowledge the additional contributions from [Vincent A. Cicirello](https://github.com/cicirello).
