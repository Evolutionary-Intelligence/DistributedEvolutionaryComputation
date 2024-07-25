# AIAA Journal (AIAAJ)

* Longobardo, G., Catalano, P., Quagliarella, D. and Tognaccini, R., 2024. Modeling laminar separation bubbles by field inversion method. AIAA Journal, 62(1), pp.175-192. <**CMA-ES**>
  * "The CMAES does not require gradient evaluation, which can be extremely computationally expensive for the field inversion technique. A key feature is the ability to work as a blackbox, and its implementation does not rely on the specific CFD solver."
  * **Conclusion**: "A gradient-free optimization algorithm, namely, CMAES, was instead tested. This algorithm does not require the computation of the gradient of the flow variables and allows for searching within the solution space avoiding the issues related to local minima. The significantly increased computational cost is compensated by the decoupling of the solver from the optimization algorithm, guaranteeing a blackbox approach for the field inversion procedure. This critical feature enables quick adaptation to different applications of modeling enhancement."
  * Hansen, N., “The CMA Evolution Strategy: A Tutorial,” CoRR, Vol. abs/1604.00772, 2016, http://arxiv.org/abs/1604.00772 [retrieved 15 April 2023].
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
* Kody, F., Corle, E., Maughmer, M.D. and Schmitz, S., 2016. Higher-harmonic deployment of trailing-edge flaps for rotor-performance enhancement and vibration reduction. Journal of Aircraft, 53(2), pp.333-342.
  * 
* Fusi, F., Guardone, A., Quaranta, G. and Congedo, P.M., 2015. Multifidelity physics-based method for robust optimization applied to a hovering rotor airfoil. AIAA Journal, 53(11), pp.3448-3465.
* Molinari, G., Arrieta, A.F. and Ermanni, P., 2014. [Aero-structural optimization of three-dimensional adaptive wings with embedded smart actuators](https://arc.aiaa.org/doi/full/10.2514/1.J052715). AIAA Journal, 52(9), pp.1940-1951. <**CMA-ES**>
  * ""
* Muller, S.D., Walther, J.H. and **Koumoutsakos, P.D.**, 2001. [Evolution strategies for film cooling optimization]((https://arc.aiaa.org/doi/10.2514/2.1342)). AIAA Journal, 39(3), pp.537-539. <**CMA-ES**>
  * "An evolutionary algorithm is implemented in a realistic automated design cycle of turbine blade film cooling."
  * "Schwefel, H.-P., Evolution and Optimum Seeking, Wiley, New York, 1995, pp. 105–164."
  * "Hansen, N., and Ostermeier, A., “Convergence Properties of Evolution Strategies with the Derandomized Covariance Matrix Adaptation: The CMA-ES,” Proceedings of the 5th European Congress on Intelligent Techniques and Soft Computing (EUFIT’97), Verlag Mainz, Aachen, Germany, 1997, pp. 650–654."

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.DistributedEvolutionaryComputation-AIAAJ)
