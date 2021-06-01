# Distributed Evolutionary Computation

This is a *growing* paper list for **parallel and distributed** evolutionary computation (PDEC). Currently we are **actively** updating this paper list (at least from 2021 to 2023). Owing to the abundance of the related literature, however, we believe that much interesting work is still missed here. If you find them missed in this paper list, welcome to contact with us via [Issues](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/issues) or [Pull requests](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/pulls) (and we will be very happy to add them).

## Systematical Searching

| Publication | Starting Year | EC vs PDEC | Searchers |
|:-----------:|:-------------:|:----------:|:---------:|
| **[Nature](https://www.nature.com/)** | 2015 | EC | Mingyang Feng, Youkui Zhang, Qiqi Duan |
| **[IEEE-TPDS](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=71)** | 2015 | PDEC | Youkui Zhang, Mingyang Feng, Qiqi Duan |
| **[JMLR](https://jmlr.org/)** | 2000 | EC | Mingyang Feng, Minghan Zhang, Qiqi Duan |
| **[ECJ](https://direct.mit.edu/evco)** | 1993 | PDEC | Chang Shao, Minghan Zhang, Qiqi Duan |
| **[IJCV](https://www.springer.com/journal/11263)** | 2010 | EC | Minghan Zhang, Mingyang Feng, Qiqi Duan |

## Local Searching

### Evolutionary Computation (EC)

* Domingos, P., 2015. The five tribes of machine learning and what you can take from each. ACM Learning Center. [ [www](https://learning.acm.org/techtalks/machinelearning) | [pdf](https://learning.acm.org/binaries/content/assets/leaning-center/webinar-slides/2015/five-tribes-ml_112415.pdf) ]

* Vie, A., 2021. Qualities, challenges and future of genetic algorithms: A literature review. arXiv preprint arXiv:2011.05277. [ [www](https://arxiv.org/abs/2011.05277) | [pdf](https://arxiv.org/pdf/2011.05277.pdf) ] (-> 7)

* Papavasileiou, E., Cornelis, J. and Jansen, B., 2021. A systematic literature review of the successors of ‘NeuroEvolution of Augmenting Topologies’. Evolutionary Computation, 29(1), pp.1-73. [ [www](https://direct.mit.edu/evco/article/29/1/1/97341/A-Systematic-Literature-Review-of-the-Successors) | [pdf](https://watermark.silverchair.com/evco_a_00282.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAnswggJ3BgkqhkiG9w0BBwagggJoMIICZAIBADCCAl0GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQM5IknuF7Uj1N04MU0AgEQgIICLsDHBvkrfQqhOBZ1OMP265Bi3eSYgxgaz6fefWRi4pQ0fRTM-R8DCnym2-ya-i91SIvHYef_bT_wCfpGIOwJFfTrTvn62Aek1MSufQK4V37jnB2iLeS2raDBjFeKub8EtYVtqjklYX7IRkptwIJ1Fzw_lWnKQVP2hFGCAd_hq4NI4Qog00WeDgXX-kXJpKzeqiyPQ9VxzzRygnRJy8atHHpLbkdcdiKFgSHpvE8Sbcj47M8ojqF8cbFnkHJQhYrtpI_I6wFdLpRreosIvis2NrL9iX8wds2BVpQGO7PmRsOzbvjGeVqBbyP3pHv7YxiFJ2nPHZTnQFj4NMfLhQUonjZuZfIT4SZ3gdjeGvMMUE6Nrrif3yFUw-fwQ7CFCCHtvugwzdTIBukT9GqrROhzUBL37pLZxPympkGlcyLSro2pu9KC7YN0r4EhKBJSvfrkSLjYXbW9wXzVhs_1GFMGsX3jxwxWE1Y7i2iOj2IuqSM444_HKirAklnNEXue6r5FZuXt5Z2nowcjvwv4WW-v3Yvwp6ioehqDMR34hUP98jVQg6x5gQ9xTFnleyKH1NTIWl1AeDza9_wWfdjiOwhITtTMvEYwkhhJCMhf1j-yq7EVo7jGZ9d2WWs8Il7Bxtmc5XETi89NCKJcxtTVgpKez6x8C7XduYbjYXTqjdgRtvcWtLfui9NQoridCtx9AuRGRf8GZdL5ScOi35-pnINwgG7wj3dtYf8jjrH2lqoHrA) ]

* Real, E., Moore, S., Selle, A., Saxena, S., Suematsu, Y.L., Tan, J., Le, Q.V. and Kurakin, A., 2017, July. Large-scale evolution of image classifiers. In International Conference on Machine Learning (pp. 2902-2911). PMLR. [ [www](http://proceedings.mlr.press/v70/real17a.html) | [pdf](http://proceedings.mlr.press/v70/real17a/real17a.pdf) ]

* Levine, D., 1996. Users guide to the PGAPack parallel genetic algorithm library. Argonne National Laboratory, Technical Report. [ [pdf](https://ftp.mcs.anl.gov/pub/tech_reports/reports/ANL9518.pdf) | [C](https://ftp.mcs.anl.gov/pub/pgapack/) ]

#### Genetic Programming (GP)

* da Silva, C.P., Dias, D.M., Bentes, C., Pacheco, M.A.C. and Cupertino, L.F., 2015. Evolving GPU machine code. Journal of Machine Learning Research, 16, pp.673-712. (**-> 3, <- 1**)

* Harding, S. and Banzhaf, W., 2007, April. Fast genetic programming on GPUs. In European Conference on Genetic Programming (pp. 90-101). Springer, Berlin, Heidelberg. (**-> 1, <- 3**)

### PDEC for Evolutionary Neural Architecture Search (NAS)

* Ye, Q., Sun, Y., Zhang, J. and Lv, J.C., 2021. A distributed framework for EA-based NAS. IEEE Transactions on Parallel and Distributed Systems, 32(7), pp.975-987. (-> 8)

### PDEC for Evolutionary Multi-Objective Optimization (MOO)

Santander-Jimenez, S. and Vega-Rodriguez, M.A., 2019. Comparative analysis of intra-algorithm parallel multiobjective evolutionary algorithms: Taxonomy implications on bioinformatics scenarios. IEEE Transactions on Parallel and Distributed Systems, 30(1), pp.63-78. (-> 12)

### PDEC on Apache Spark

* Wen, Z., Lin, T., Yang, R., Ji, S., Ranjan, R., Romanovsky, A., Lin, C. and Xu, J., 2020. Ga-par: Dependable microservice orchestration framework for geo-distributed clouds. IEEE Transactions on Parallel and Distributed Systems, 31(1), pp.129-143. (-> 4)

## Research Support

This *ongoing* review for PDEC is now supported by the **Shenzhen NSF** research project (from 2021 to 2023), granted to **Prof. Yuhui Shi** (CSE, SUSTech @ Shenzhen, China).
