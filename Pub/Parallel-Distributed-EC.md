# Parallel/Distributed Evolutionary Computation

* Weber, J., Huckaby, E.D. and Straub, D., 2023. Comparison of shape optimization methods for heat exchanger fins using computational fluid dynamics. International Journal of Heat and Mass Transfer, 207, p.124003. [ **US Department of Energy, National Energy Technology Laboratory** ]
  * "A custom server-client chitecture was constructed. The server, implemented with Flask, hosts the optimization algorithm, collects results, generates new samples, and displays progress through a dashboard using Dash."
  * "Since the server and clients talk to each other using https, this framework could also handle evaluations distributed over a local network or internet."
  * "All models and optimization campaigns are run on NETL’s Joule 2.0 supercomputer. Each node contains two 20 core Intel Xeon Gold 6148 CPUs clocked at 2.40GHz. The optimization campaigns each use four nodes, for a total of 160 cores. 20 simultaneous models are allowed to run on each node, totaling 80 concurrent simulations."
