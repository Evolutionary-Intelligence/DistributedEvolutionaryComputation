# AIAA Journal (AIAAJ)

* Fasel, U., Tiso, P., Keidel, D. and Ermanni, P., 2021. Concurrent design and flight mission optimization of morphing airborne wind energy wings. AIAA Journal, 59(4), pp.1254-1268.
  * "The optimization is performed using the algorithm CMA-ES, which was previously used to optimize morphing wings, because it satisfies the requirements of being able to treat nonsmooth objective functions and to deal with a large number of design variables. Compared to other genetic algorithms, CMA-ES uses information related to the Hessian of the objective function, adapting the covariance matrix and sampling the search space along a preferential direction, leading to faster convergence."
    * Hansen, N., and Ostermeier, A., “Completely Derandomized Self-Adaptation in Evolution Strategies,” Evolutionary Computation, Vol. 9, No. 2, 2001, pp. 159–195.
    * Igel, C., Hansen, N., and Roth, S., “Covariance Matrix Adaptation for Multi-Objective Optimization,” Evolutionary Computation, Vol. 15, No. 1, 2007, pp. 1–28.
* Keidel, D., Fasel, U. and Ermanni, P., 2021. Concept investigation of a lightweight composite lattice morphing wing. AIAA Journal, 59(6), pp.2242-2250.
  * "In contrast to wing studies with optimizations relying on gradient-based methods, different actuation levels of the wing are considered, resulting in a nonconvex, nonsmooth objective function. Therefore, the CMA-ES evolutionary optimization algorithm was chosen for the optimization due to its superior performance compared to benchmark algorithms. It is able to treat nonsmooth objective functions and can handle a large number of variables: both characteristics of this optimization."
  * "The optimization goals and constraints are combined into one function by weighting each factor since the performance of the CMA-ES algorithm is greatly reduced when introducing constraints."
    * Hansen, N., “The CMA Evolution Strategy: A Tutorial,” Evolutionary Computation, 2005, https://hal.inria.fr/hal-01297037/document.
    * Hansen, N., and Ostermeier, A., “Completely Derandomized Self-Adaptation in Evolution Strategies,” Evolutionary Computation, Vol. 9, No. 2, 2001, pp. 159–195. https://doi.org/10.1162/106365601750190398
* Satria Palar, P., Rizki Zuhal, L. and Shimoyama, K., 2020. Gaussian process surrogate model with composite kernel learning for engineering design. AIAA journal, 58(4), pp.1864-1880.
  * "In this paper, we use a covariance matrix adaptation evolution strategy (CMA-ES) with 10 restarts to train the GP model for both single kernel and CKL cases."
  * "Using fewer restarts of the CMA-ES is beneficial; however, it might run the risk of missing the global optimum. Studies are then needed on the effective implementation of the CMA-ES or other optimizers for training the GP-CKL model."
    * Hansen, N., Müller, S. D., and Koumoutsakos, P., “Reducing the Time Complexity of the Derandomized Evolution Strategy with Covariance Matrix Adaptation (CMA-ES),” Evolutionary Computation, Vol. 11, No. 1, 2003, pp. 1–18. https://doi.org/10.1162/106365603321828970
* Muller, S.D., Walther, J.H. and **Koumoutsakos, P.D.**, 2001. [Evolution strategies for film cooling optimization]((https://arc.aiaa.org/doi/10.2514/2.1342)). AIAA Journal, 39(3), pp.537-539. <**CMA-ES**>
  * "An evolutionary algorithm is implemented in a realistic automated design cycle of turbine blade film cooling."
  * "Schwefel, H.-P., Evolution and Optimum Seeking, Wiley, New York, 1995, pp. 105–164."
  * "Hansen, N., and Ostermeier, A., “Convergence Properties of Evolution Strategies with the Derandomized Covariance Matrix Adaptation: The CMA-ES,” Proceedings of the 5th European Congress on Intelligent Techniques and Soft Computing (EUFIT’97), Verlag Mainz, Aachen, Germany, 1997, pp. 650–654."
