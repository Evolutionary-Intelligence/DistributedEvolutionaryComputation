# Nature

* Romera-Paredes, B., Barekatain, M., Novikov, A., Balog, M., Kumar, M.P., Dupont, E., Ruiz, F.J., Ellenberg, J.S., Wang, P., Fawzi, O. and Kohli, P., 2024. [Mathematical discoveries from program search with large language models](https://www.nature.com/articles/s41586-023-06924-6). Nature, 625(7995), pp.468-475.
* Melis, J.M., Siwanowicz, I. and Dickinson, M.H., 2024. [Machine learning reveals the control mechanics of an insect wing hinge](https://www.nature.com/articles/s41586-024-07293-4). Nature, pp.1-9. { **California Institute of Technology + Howard Hughes Medical Institute** }
  * "To reconstruct the wing kinematics from high-speed images, we developed an automated tracking algorithm that used a trained convolutional neural network and particle swarm optimization."
  * "We developed an automated tracking system to extract body and wing pose, called Flynet, which consists of two steps: (1) a trained CNN that predicts pose vectors of the body and wing; and (2) a PSO step that refines the CNN prediction via 3D model fitting."
  * "flynet-optimizer is a particle swarm optimization extension module used by Flynet."
  * Kennedy, J. & Eberhart, R. Particle swarm optimization. In Proc. ICNN’95—International Conference on Neural Networks Vol. 4, 1942–1948 (1995).
* Tong, K., Zhang, X., Li, Z., Wang, Y., Luo, K., Li, C., Jin, T., Chang, Y., Zhao, S., Wu, Y. and Gao, Y., 2024. [Structural transition and migration of incoherent twin boundary in diamond](https://www.nature.com/articles/s41586-023-06908-6). Nature, pp.1-7.
  * "To verify configuration diversity, we performed a structure search of diamond {112} ITB with an evolutionary algorithm and estimated excess energy with first-principles calculations."
  * "The structure search of diamond {112} ITB was performed using our structure search code based on the evolutionary algorithm. In this process, the algorithm samples a diverse population of different configurations and improves them over many generations on the basis of the selection criterion. Excess energy was used as the principal selection criterion (see next section for calculation details). For ITB configurations, because the crossover operation of multiple parents usually produces a high-energy configuration, all child configurations were generated from a single parent via mutation in our search. The evolutionary search evolved 44 generations at 0 K. Following the search, clustering analysis was performed using the k-medoids algorithm to cluster distinct ITB configurations."
    * Zhu, Q., Samanta, A., Li, B., Rudd, R. E. & Frolov, T. Predicting phase behavior of grain boundaries with evolutionary search and machine learning. Nat. Commun. 9, 467 (2018).
    * Michalewicz, Z. & Fogel, D. B. How to Solve It: Modern Heuristics (Springer, 2004).
* Mouret, J.B., 2024. Large language models help computer programs to evolve. Nature.
* Slade, P., Kochenderfer, M.J., Delp, S.L. and Collins, S.H., 2022. [Personalizing exoskeleton assistance while walking in the real world](https://www.nature.com/articles/s41586-022-05191-1). Nature, 610(7931), pp.277-282. [ [Nature Video](https://www.nature.com/articles/d41586-022-03262-x) | [news.stanford](https://news.stanford.edu/press-releases/2022/10/12/exoskeleton-makester-less-tiring/) | [engineering.stanford](https://engineering.stanford.edu/magazine/untethered-exoskeleton-walks-out-real-world) | [biomechatronics.stanford](https://biomechatronics.stanford.edu/papers) ] { **CMA-ES** }
  * "A fixed number of exoskeleton control laws, comprising one generation of the evolution-inspired optimizer, were then ranked using the data-driven classifier. The optimizer then updated its estimate of the optimal parameters and generated a new set of control laws to evaluate."
    * Hansen, N. in Towards a New Evolutionary Computation (eds Lozano, J. A. et al.) 75–102 (Springer, 2006). [ [IEEE-EMBS-2013](https://www.cs.cmu.edu/~hgeyer/Publications/SongEA13aIEEE_EMBC.pdf) ]
* De Croon, G.C., Dupeyroux, J.J., De Wagter, C., Chatterjee, A., Olejnik, D.A. and Ruffier, F., 2022. [Accommodating unobservability to control flight attitude with optic flow](https://www.nature.com/articles/s41586-022-05182-2). Nature, 610(7932), pp.485-490. [ [news&views](https://www.nature.com/articles/d41586-022-03217-2) ] { **CMA-ES** }
  * "we obtained the best results by using an evolutionary optimization algorithm, covariance matrix adaptation evolutionary strategy (CMA-ES). Specifically, we performed seven flights in which we made a high-frequency log of all onboard sensor data. This allowed to run the EKF offline on the data sets. Then, CMA-ES optimized the parameters of the EKF, with as cost function the sum of squared errors of the estimates (comparing EKF estimates with the logged ‘ground truth’ from the complementary filter for attitude and motion-tracking system for height and velocities)."
    * Hansen, N., Müller, S. D. & Koumoutsakos, P. Reducing the time complexity of the derandomized evolution strategy with covariance matrix adaptation (CMA-ES). Evol. Comput. 11, 1–18 (2003).
* Vaishnav, E.D., de Boer, C.G., Molinet, J., Yassour, M., Fan, L., Adiconis, X., Thompson, D.A., Levin, J.Z., Cubillos, F.A. and Regev, A., 2022. The evolution, evolvability and engineering of gene regulatory DNA. Nature, 603(7901), pp.455-463. [ [www](https://www.nature.com/articles/s41586-022-04506-6) ] ( **GA** )
  * "To design new sequences with desired expression, a genetic algorithm was implemented with the distributed evolutionary algorithms in Python (DEAP package). The mutation probability and the two-point crossover probability were set to 0.1 and the selection tournament size was 3. The initial population size was 100,000 and the genetic algorithm was run for 10 generations. The convolutional model was used as the basis for the objective function for the genetic algorithm, which was maximized for high expression and minimized for low expression (maximizing negative predicted expression)."
    * Sinai, S. et al. AdaLead: a simple and robust adaptive greedy search algorithm for sequence design. Preprint at https://arxiv.org/abs/2010.02141 (2020).
    * Linder, J., Bogard, N., Rosenberg, A. B. & Seelig, G. A generative neural network for maximizing fitness and diversity of synthetic DNA and protein sequences. Cell Syst. 11, 49–62 (2020).
    * Brookes, D., Park, H. & Listgarten, J. Conditioning by adaptive sampling for robust design. Proc. Mach. Learn. Res. 97, 773–782 (2019).
    * Killoran, N., Lee, L. J., Delong, A., Duvenaud, D. & Frey, B. J. Generating and designing DNA with deep generative models. Neurips Computational Biology Workshop (2017).
    * Fortin, F.-A., Rainville, F.-M. D., Gardner, M.-A., Parizeau, M. & Gagné, C. DEAP: evolutionary algorithms made easy. J. Mach. Learn. Res. 13, 2171–2175 (2012).
* Temmam, S., Vongphayloth, K., Baquero, E., Munier, S., Bonomi, M., Regnault, B., Douangboubpha, B., Karami, Y., Chrétien, D., Sanamxay, D. and Xayaphet, V., 2022. Bat coronaviruses related to SARS-CoV-2 and infectious for human cells. Nature, 604(7905), pp.330-336. [ [www](https://www.nature.com/articles/s41586-022-04532-4) ] ( **GA** )
  * "Following analysis using a genetic algorithm for recombination detection (GARD), we identified 14 recombinant breakpoints during the evolutionary history of sarbecoviruses, which were further confirmed by phylogenetic analyses performed on the 15 fragments of sequences defined by the breakpoints."
    * Kosakovsky Pond, S. L., Posada, D., Gravenor, M. B., Woelk, C. H. & Frost, S. D. W. Automated phylogenetic detection of recombination using a genetic algorithm. Mol. Biol. Evol. 23, 1891–1901 (2006).
    * Kosakovsky Pond, S. L., Posada, D., Gravenor, M. B., Woelk, C. H. & Frost, S. D. W. GARD: a genetic algorithm for recombination detection. Bioinformatics 22, 3096–3098 (2006).
* Ricciardi, S., Guarino, A.M., Giaquinto, L., Polishchuk, E.V., Santoro, M., Di Tullio, G., Wilson, C., Panariello, F., Soares, V.C., Dias, S.S. and Santos, J.C., 2022. The role of NSP6 in the biogenesis of the SARS-CoV-2 replication organelle. Nature, 606(7915), pp.761-768. [ [www](https://www.nature.com/articles/s41586-022-04835-6) ] ( **GA** )
  * https://heliquest.ipmc.cnrs.fr/ : "The mutation module, (available from the sequence analysis module), allows the user to mutate helices manually or automatically using a genetic algorithm, to create analogues with specific properties."
* Ping, Y.Q., Xiao, P., Yang, F., Zhao, R.J., Guo, S.C., Yan, X., Wu, X., Zhang, C., Lu, Y., Zhao, F. and Zhou, F., 2022. Structural basis for the tethered peptide activation of adhesion GPCRs. Nature, 604(7907), pp.763-770. [ [www](https://www.nature.com/articles/s41586-022-04619-y) ] ( **GA** )
* Grissonnanche, G., Fang, Y., Legros, A., Verret, S., Laliberté, F., Collignon, C., Zhou, J., Graf, D., Goddard, P.A., Taillefer, L. and Ramshaw, B.J., 2021. Linear-in temperature resistivity from an isotropic Planckian scattering rate. Nature, 595(7869), pp.667-672. [ [www](https://www.nature.com/articles/s41586-021-03697-8) ] ( **GA** )
* Ecoffet, A., Huizinga, J., Lehman, J., Stanley, K.O. and Clune, J., 2021. First return then explore. Nature, pp.580-586. [ [www](https://www.nature.com/articles/s41586-020-03157-9) | [pdf](https://www.nature.com/articles/s41586-020-03157-9.epdf?sharing_token=fVSAoXFGOipXiv03jaRGFtRgN0jAjWel9jnR3ZoTv0M2nmoar2g6_K5n8IBFPE90s2PCF4tYuP4UnEffP83tohRanjcxryz9Usln4Rw7idY6ufIsQYVgwwD0B8UgE7JYzmgOuMdgNqvVMg7GsfFiI2ZBi9PjjmJtJGEDwzRPFWc%3D) | [Python](https://github.com/uber-research/go-explore) ] ( **QD** )
* Yang, F., Guo, L., Li, Y., Wang, G., Wang, J., Zhang, C., Fang, G.X., Chen, X., Liu, L., Yan, X. and Liu, Q., 2021. Structure, function and pharmacology of human itch receptor complexes. Nature, 600(7887), pp.164-169. [ [www](https://www.nature.com/articles/s41586-021-04077-y) ] ( **GA** )
* Zhang, Y., Ye, F., Zhang, T., Lv, S., Zhou, L., Du, D., Lin, H., Guo, F., Luo, C. and Zhu, S., 2021. Structural basis of ketamine action on human NMDA receptors. Nature, 596(7871), pp.301-305. [ [www](https://www.nature.com/articles/s41586-021-03769-9) ] ( **GA** )
* Xu, P., Huang, S., Zhang, H., Mao, C., Zhou, X.E., Cheng, X., Simon, I.A., Shen, D.D., Yen, H.Y., Robinson, C.V. and Harpsøe, K., 2021. Structural insights into the lipid and ligand regulation of serotonin receptors. Nature, 592(7854), pp.469-473. [ [www](https://www.nature.com/articles/s41586-021-03376-8) ] ( **GA** )
* Draper-Joyce, C.J., Bhola, R., Wang, J., Bhattarai, A., Nguyen, A.T., Cowie-Kent, I., O’Sullivan, K., Chia, L.Y., Venugopal, H., Valant, C. and Thal, D.M., 2021. Positive allosteric mechanisms of adenosine A1 receptor-mediated analgesia. Nature, 597(7877), pp.571-576. [ [www](https://www.nature.com/articles/s41586-021-03897-2) ] ( **GA** )
* Squair, J.W., Gautier, M., Mahe, L., Soriano, J.E., Rowald, A., Bichat, A., Cho, N., Anderson, M.A., James, N.D., Gandar, J. and Incognito, A.V., 2021. Neuroprosthetic baroreflex controls haemodynamics after spinal cord injury. Nature, 590(7845), pp.308-314. [ [www](https://www.nature.com/articles/s41586-020-03180-w) ] ( **GA** )
  * "We used personalized computational modelling and a genetic algorithm to predict the ideal spatial configurations to activate the lower thoracic spinal segments."
* Heeg, K.P., Kaldun, A., Strohm, C., Ott, C., Subramanian, R., Lentrodt, D., Haber, J., Wille, H.C., Goerttler, S., Rüffer, R. and Keitel, C.H., 2021. Coherent X-ray− optical control of nuclear excitons. Nature, 590(7846), pp.401-404. [ [www](https://www.nature.com/articles/s41586-021-03276-x) | [Matters Arising](https://www.nature.com/articles/s41586-022-04870-3) | [Reply to](https://www.nature.com/articles/s41586-022-04871-2) ]
  * "Using an evolutionary algorithm, we fitted the applied motional sequence to the measured data without imposing a particular model for the motion."
* Hatfield, P.W., Gaffney, J.A., Anderson, G.J., Ali, S., Antonelli, L., Başeğmez du Pree, S., Citrin, J., Fajardo, M., Knapp, P., Kettle, B. and Kustowski, B., 2021. The data-driven future of high-energy-density physics. Nature, 593(7859), pp.351-361.
* Han, S., Deng, R., Gu, Q., Ni, L., Huynh, U., Zhang, J., Yi, Z., Zhao, B., Tamura, H., Pershin, A. and Xu, H., 2020. Lanthanide-doped inorganic nanoparticles turn molecular triplet excitons bright. Nature, 587(7835), pp.594-599. [ [www](https://www.nature.com/articles/s41586-020-2932-2) ] ( **GA** )
  * "To identify different components from the transient absorption data, a genetic algorithm analysis was also used to distinguish different spectral species and the corresponding kinetics."
* Chen, T., van Gelder, J., van de Ven, B., Amitonov, S.V., de Wilde, B., Euler, H.C.R., Broersma, H., Bobbert, P.A., Zwanenburg, F.A. and van der Wiel, W.G., 2020. Classification with a disordered dopant-atom network in silicon. Nature, 577(7790), pp.341-345. [ [www](https://www.nature.com/articles/s41586-019-1901-0) | [news & views](https://www.nature.com/articles/d41586-020-00002-x) ] ( **GA** + **Continuous Optimization** #)
  * "We exploit the nonlinearity of hopping conduction through an electrically tunable network of boron dopant atoms in silicon, reconfiguring the network through artificial evolution to realize different computational functions."
    * Bose, S. K. et al. Evolution of a designless nanoparticle network into reconfigurable Boolean logic. Nat. Nanotechnol. 10, 1048–1052 (2015).
    * Miller, J. F. & Downing, K. Evolution in materio: looking beyond the silicon box. In Proc. 2002 NASA/DoD Conference on Evolvable Hardware 167–176 (IEEE, 2002).
    * Harding, S. & Miller, J. F. Evolution in materio: a tone discriminator in liquid crystal. In Proc. 2004 Congress on Evolutionary Computation 1800–1807 (IEEE, 2004).
    * Mohid, M. & Miller, J. F. Evolving robot controllers using carbon nanotubes. In Proc. 13th European Conference on Artificial Life 106–113 (MIT Press, 2015).
    * Such, F. P. et al. Deep neuroevolution: genetic algorithms are a competitive alternative for training deep neural networks for reinforcement learning. Preprint at http://arxiv.org/abs/1712.06567 (2017).
* Meiners, T., Frolov, T., Rudd, R.E., Dehm, G. and Liebscher, C.H., 2020. Observations of grain-boundary phase transformations in an elemental metal. Nature, 579(7799), pp.375-378. [ [www](https://www.nature.com/articles/s41586-020-2082-6)
  * "The 0 K GB structure search was performed using an evolutionary algorithm based on the USPEX code."
    * Zhu, Q., Samanta, A., Li, B., Rudd, R. E. & Frolov, T. Predicting phase behavior of grain boundaries with evolutionary search and machine learning. Nat. Commun. 9, 467 (2018).
    * Oganov, A. R. & Glass, C. W. Crystal structure prediction using ab initio evolutionary techniques: principles and applications. J. Chem. Phys. 124, 244704 (2006).
    * yakhov, A. O., Oganov, A. R., Stokes, H. T. & Zhu, Q. New developments in evolutionary structure prediction algorithm USPEX. Comput. Phys. Commun. 184, 1172–1182 (2013).
* Karageorgi, M., Groen, S.C., Sumbul, F., Pelaez, J.N., Verster, K.I., Aguilar, J.M., Hastings, A.P., Bernstein, S.L., Matsunaga, T., Astourian, M. and Guerra, G., 2019. Genome editing retraces the evolution of toxin resistance in the monarch butterfly. Nature, 574(7778), pp.409-412. [ [www](https://www.nature.com/articles/s41586-019-1610-8) ] ( **GA** )
  * "We ran a Lamarckian genetic algorithm (LGA) to search for the best conformers during the calculations, keeping the docked ouabain coordinates closest to the coordinates of the ouabain ligand in the co-crystal structure as best conformer for each set of docking calculations. Autodock4 was run at default parameter settings for all docking simulations with the exception of the number of GA runs, which was set to 100."
    * Morris, G. M. et al. AutoDock4 and AutoDockTools4: Automated docking with selective receptor flexibility. J. Comput. Chem. 30, 2785–2791 (2009).
* Li, S., Batra, R., Brown, D., Chang, H.D., Ranganathan, N., Hoberman, C., Rus, D. and Lipson, H., 2019. Particle robotics based on statistical mechanics of loosely coupled components. Nature, 567(7748), pp.361-365. [ [www](https://www.nature.com/articles/s41586-019-1022-9) ] ( **SR** )
* Giammichele, N., Charpinet, S., Fontaine, G., Brassard, P., Green, E.M., Van Grootel, V., Bergeron, P., Zong, W. and Dupret, M.A., 2018. A large oxygen-dominated core from the seismic cartography of a pulsating white dwarf. Nature, 554(7690), pp.73-76.
* Dou, J., Vorobieva, A.A., Sheffler, W., Doyle, L.A., Park, H., Bick, M.J., Mao, B., Foight, G.W., Lee, M.Y., Gagnon, L.A. and Carter, L., 2018. De novo design of a fluorescence-activating β-barrel. Nature, 561(7724), pp.485-491.
* Manukyan, L., Montandon, S.A., Fofonjka, A., Smirnov, S. and Milinkovitch, M.C., 2017. A living mesoscopic cellular automaton made of skin scales. Nature, 544(7649), pp.173-179. [ [www](https://www.nature.com/articles/nature22031) ] ( **GA/ES** )
* Sollars, E.S., Harper, A.L., Kelly, L.J., Sambles, C.M., Ramirez-Gonzalez, R.H., Swarbreck, D., Kaithakottil, G., Cooper, E.D., Uauy, C., Havlickova, L. and Worswick, G., 2017. Genome sequence and genetic diversity of European ash trees. Nature, 541(7636), pp.212-216.
* Biamonte, J., Wittek, P., Pancotti, N., Rebentrost, P., Wiebe, N. and Lloyd, S., 2017. Quantum machine learning. Nature, 549(7671), pp.195-202.
  * "Genetic algorithms have been employed to reduce digital and experimental errors in quantum gates. They have been used to simulate controlled-NOT gates by means of ancillary qubits and imperfect gates. Besides outperforming protocols for digital quantum simulations, it has been shown that genetic algorithms are also useful for suppressing experimental errors in gates."
    * Zeidler, D., Frey, S., Kompa, K.-L. & Motzkus, M. Evolutionary algorithms and their application to optimal control studies. Phys. Rev. A 64, 023420 (2001).
    * Las Heras, U., Alvarez-Rodriguez, U., Solano, E. & Sanz, M. Genetic algorithms for digital quantum simulations. Phys. Rev. Lett. 116, 230504 (2016).
  * "Genetic algorithms have been proposed for the control of quantum molecules to overcome the problem caused by changing environmental parameters during an experiment. Reinforcement learning algorithms using heuristic global optimization, like the algorithm used for designing circuits, have been widely successful, particularly in the presence of noise and decoherence, scaling well with the system size."
    * Amstrup, B., Toth, G. J., Szabo, G., Rabitz, H. & Loerincz, A. Genetic algorithm with migration on topology conserving maps for optimal control of quantum systems. J. Phys. Chem. 99, 5206–5213 (1995).
    * Lovett, N. B., Crosnier, C., Perarnau-Llobet, M. & Sanders, B. C. Differential evolution for many-particle adaptive quantum metrology. Phys. Rev. Lett. 110, 220501 (2013).
* Van Saders, J.L., Ceillier, T., Metcalfe, T.S., Aguirre, V.S., Pinsonneault, M.H., García, R.A., Mathur, S. and Davies, G.R., 2016. Weakened magnetic braking as the origin of anomalously rapid rotation in old field stars. Nature, 529(7585), pp.181-184.
* Lorenzo-Redondo, R., Fryer, H.R., Bedford, T., Kim, E.Y., Archer, J., Kosakovsky Pond, S.L., Chung, Y.S., Penugonda, S., Chipman, J.G., Fletcher, C.V. and Schacker, T.W., 2016. Persistent HIV-1 replication maintains the tissue reservoir during therapy. Nature, 530(7588), pp.51-56.
* Cully, A., Clune, J., Tarapore, D. and Mouret, J.B., 2015. Robots that can adapt like animals. Nature, 521(7553), pp.503-507. [ [www](https://www.nature.com/articles/nature14422) ] ( **QD** )
  * "An evolutionary algorithm has been developed that allows robots to adapt to unforeseen change. The robots learn behaviours quickly and instinctively by mining the memory of their past achievements." ---[news & views](https://www.nature.com/articles/521426a)
* **Eiben, A.E. and Smith, J., 2015.
  [From evolutionary computation to the evolution of things](https://www.nature.com/articles/nature14544).
  Nature, 521(7553), pp.476-482.** {**EC**}
* Rus, D. and Tolley, M.T., 2015. Design, fabrication and control of soft robots. Nature, 521(7553), pp.467-475. [ [www](https://www.nature.com/articles/nature14543) ] ( **ER** )
  * "Researchers have used design automation algorithms inspired by evolution to design soft robots. Soft-robot designs have been automatically generated using custom finite element analysis software (VoxCAD), which accommodates materials with a large range of moduli, coupled with design optimization using an evolutionary algorithm. In addition, evolutionary algorithms have been used to automatically generate soft-robot designs."
    * Lipson, H., 2014. Challenges and opportunities for design, simulation, and fabrication of soft robots. Soft Robotics, 1(1), pp.21-27.
    * Hiller, J. and Lipson, H., 2011. Automatic design and manufacture of soft robots. IEEE Transactions on Robotics, 28(2), pp.457-466.
    * Rieffel, J., Knox, D., Smith, S. and Trimmer, B., 2014. Growing and evolving soft robots. Artificial Life, 20(1), pp.143-162.
* Laganowsky, A., Reading, E., Allison, T.M., Ulmschneider, M.B., Degiacomi, M.T., Baldwin, A.J. and Robinson, C.V., 2014. Membrane proteins bind lipids selectively to modulate their structure and function. Nature, 510(7503), pp.172-175. [ [www](https://www.nature.com/articles/nature13419) ] ( **DE** )
  * "The fitting surface was rugged and required a sophisticated minimization procedure to maximize the chance of finding global minimum. First the 3D model was minimized using quasi-Newton method of Broyden, Fletcher, Goldfarb, and Shanno (BFGS) available in Scipy50. This provided the boundaries for bio-inspired algorithms. The 3D model was minimized using the modified differential algorithm (de_1220) available in PyGMO."
    * Izzo, D., Ruciński, M. and Biscani, F., 2012. The generalized island model. In Parallel Architectures and Bioinspired Algorithms (pp. 151-169). Springer, Berlin, Heidelberg.
* Rao, A., Chow, P.C., Gélinas, S., Schlenker, C.W., Li, C.Z., Yip, H.L., Jen, A.K.Y., Ginger, D.S. and Friend, R.H., 2013. The role of spin in the kinetic control of recombination in organic photovoltaics. Nature, 500(7463), pp.435-439. [ [www](https://www.nature.com/articles/nature12339) ] ( **GA** )
  * "To deconvolve the overlapping signatures of individual excited states and obtain their kinetics, we use numerical methods based on a genetic algorithm."
* Kim, H.J., Kim, N.C., Wang, Y.D., Scarborough, E.A., Moore, J., Diaz, Z., MacLea, K.S., Freibaum, B., Li, S., Molliex, A. and Kanagaraj, A.P., 2013. Mutations in prion-like domains in hnRNPA2B1 and hnRNPA1 cause multisystem proteinopathy and ALS. Nature, 495(7442), pp.467-473. [ [www](https://www.nature.com/articles/nature11922) ] ( **GA** )
  * "Phylogenetic trees of the codon alignment including 21 genes from only human and Drosophila were generated using the genetic algorithm-based GARLI method."
    * Zwickl, D. J. Genetic Algorithm Approaches for the Phylogenetic Analysis of Large Biological Sequence Datasets Under the Maximum Likelihood Criterion. PhD thesis, Univ. Texas at Austin. (2006)
* Wu, H., Wacker, D., Mileni, M., Katritch, V., Han, G.W., Vardy, E., Liu, W., Thompson, A.A., Huang, X.P., Carroll, F.I. and Mascarella, S.W., 2012. Structure of the human κ-opioid receptor in complex with JDTic. Nature, 485(7398), pp.327-332. [ [www](https://www.nature.com/articles/nature10939) ] ( **GA** )
  * "The GoldScore fitness function was used with early termination disabled for 30 genetic algorithm runs."
  * https://www.ccdc.cam.ac.uk/solutions/software/gold/ : GOLD stands for Genetic Optimisation for Ligand Docking. It is a software based on a genetic algorithm, for docking flexible ligands into protein binding sites.
* Ouyang, W., Liao, W., Luo, C.T., Yin, N., Huse, M., Kim, M.V., Peng, M., Chan, P., Ma, Q., Mo, Y. and Meijer, D., 2012. Novel Foxo1-dependent transcriptional programs control Treg cell function. Nature, 491(7425), pp.554-559. [ [www](https://www.nature.com/articles/nature11581) ] ( **GA** )
  * "We further substantiated the over-representation of consensus Foxo1 motifs by performing de novo motif prediction from the top 500 ranked candidate binding site sequences using the GADEM40 motif-discovery algorithm, compared to shuffled sequences with similar di-nucleotide composition as background."
    * Li, L. GADEM: a genetic algorithm guided formation of spaced dyads coupled with an EM algorithm for motif discovery. J. Comput. Biol. 16, 317–329 (2009).
* Maisel, S.B., Höfler, M. and Müller, S., 2012. A canonical stability–elasticity relationship verified for one million face-centred-cubic structures. Nature, 491(7426), pp.740-743. [ [www](https://www.nature.com/articles/nature11609) ] ( **GA** )
  * "The expansion coefficients of the four different cluster expansions have been obtained by fitting to density functional theory input calculations, employing an evolutionary approach using genetic algorithms."
    * Blum, V., Hart, G. L. W., Walorski, M. J. & Zunger, A. Using genetic algorithms to map first-principles results to model Hamiltonians: application to the generalized Ising model for alloys. Phys. Rev. B 72, 165113 (2005).
    * Hart, G. L. W., Blum, V., Walorski, M. J. & Zunger, A. Evolutionary approach for determining first-principles hamiltonians. Nature Mater. 4, 391–394 (2005).
* Dumusque, X., Pepe, F., Lovis, C., Ségransan, D., Sahlmann, J., Benz, W., Bouchy, F., Mayor, M., Queloz, D., Santos, N. and Udry, S., 2012. An Earth-mass planet orbiting α Centauri B. Nature, 491(7423), pp.207-211. [ [www](https://www.nature.com/articles/nature11572) ] ( **GA** )
  * "Using a Markov chain Monte Carlo algorithm coupled to a genetic algorithm to characterize the Keplerian solution, we obtained a signal with a well-constrained period and amplitude."
  * "To fit a Keplerien solution to our data, we use a genetic algorithm to retrieve multiple Keplerian orbital solutions. The main advantage of genetic algorithm compared to other advanced methods such as “Markov chain Monte Carlo” (MCMC) with parallel tempering is that it allows probing the full model parameters space in an extremely efficient way. However, the population at the end of the evolution is not statistically reliable owing the intrinsic nature of genetic algorithm based on genome crossover and mutation. We therefore add a MCMC module with Metropolis hasting to overcome this problem."
* Zinzen, R.P., Girardot, C., Gagneur, J., Braun, M. and Furlong, E.E., 2009. Combinatorial binding predicts spatio-temporal cis-regulatory activity. Nature, 462(7269), pp.65-70. [ [www](https://www.nature.com/articles/nature08531) ] ( **GA** )
  * "Initial position weight matrices (PWMs) were gathered either from the literature or by de novo motif discovery using the software RSAT and GAPWM."
    * Li, L., Liang, Y. & Bass, R. L. GAPWM: a genetic algorithm method for optimizing a position weight matrix. Bioinformatics 23, 1188–1194 (2007).
* Stayrook, S., Jaru-Ampornpan, P., Ni, J., Hochschild, A. and Lewis, M., 2008. Crystal structure of the λ repressor and a model for pairwise cooperative operator binding. Nature, 452(7190), pp.1022-1025.
  * "Previously determined structures of CTD (1F39) and NTD (1LMB) were fitted to the density using a genetic algorithm."
    * Chang, G. & Lewis, M. Molecular replacement using genetic algorithms. Acta Crystallogr. D 53, 279–289 (1997).
* Juhás, P., Cherba, D.M., Duxbury, P.M., Punch, W.F. and Billinge, S.J.L., 2006. Ab initio determination of solid-state nanostructure. Nature, 440(7084), pp.655-658. [ [www](https://www.nature.com/articles/nature04556) ] ( **GA** )
  * "Genetic or evolutionary algorithms have been very successful in finding the ground state of many types of clusters using theoretical interatomic potentials."
* Lovis, C., Mayor, M., Pepe, F., Alibert, Y., Benz, W., Bouchy, F., Correia, A.C., Laskar, J., Mordasini, C., Queloz, D. and Santos, N.C., 2006. An extrasolar planetary system with three Neptune-mass planets. Nature, 441(7091), pp.305-309.
  * "In our case, the genetic algorithm yields orbital parameters that are undistinguishable from those we have found with the simple least-squares minimization, and confirms that the three-planet solution gives a superior fit compared to the two-planet model."
* Lenski, R.E., Ofria, C., Pennock, R.T. and Adami, C., 2003. The evolutionary origin of complex features. Nature, 423(6936), pp.139-144. [ [www](https://www.nature.com/articles/nature01568) ] (  **AL** )
* Yedid, G. and Bell, G., 2002. Macroevolution simulated with autonomously replicating computer programs. Nature, 420(6917), pp.810-812. [ [www](https://www.nature.com/articles/nature01151) ] (  **AL** )
* Bond, A.B. and Kamil, A.C., 2002. Visual predators select for crypticity and polymorphism in virtual prey. Nature, 415(6872), pp.609-613. [ [www](https://www.nature.com/articles/415609a) ] ( **GA** )
  * "Moth phenotypes evolved via a genetic algorithm in which individuals detected by the jays were much less likely to reproduce."
    * Bäck, T. Evolutionary Algorithms in Theory and Practice (Oxford Univ. Press, New York, 1996).
* Peterson, A.T., Ortega-Huerta, M.A., Bartley, J., Sánchez-Cordero, V., Soberón, J., Buddemeier, R.H. and Stockwell, D.R., 2002. Future projections for Mexican faunas under global climate change scenarios. Nature, 416(6881), pp.626-629. [ [www](https://www.nature.com/articles/416626a) ] ( **GA** )
  * "Here, using a genetic algorithm and museum specimen occurrence data, we develop ecological niche models for 1,870 species occurring in Mexico and project them onto two climate surfaces modelled for 2055."
* Wilke, C.O., Wang, J.L., Ofria, C., Lenski, R.E. and Adami, C., 2001. Evolution of digital organisms at high mutation rates leads to survival of the flattest. Nature, 412(6844), pp.331-333. [ [www](https://www.nature.com/articles/35085569) ] (  **AL** )
* Floyd, J.S., Mutter, J.C., Goodliffe, A.M. and Taylor, B., 2001. Evidence for fault weakness and fluid flow within an active low-angle normal fault. Nature, 411(6839), pp.779-783. [ [www](https://www.nature.com/articles/35081040) ] ( **GA** )
  * "Here we present results from a genetic algorithm inversion of seismic reflection data, which shows that the fault at 4–5 km depth contains a 33-m-thick layer with seismic velocities of about 4.3 km s-1, which we interpret to be composed of serpentinite fault gouge."
* Bonabeau, E., Dorigo, M. and Theraulaz, G., 2000. Inspiration for optimization from social insect behaviour. Nature, 406(6791), pp.39-42. [ [www](https://www.nature.com/articles/35017500) ] ( **SI** | **ACO** )
  * "Most instances of most problems are not readily 'linearly' decomposable into building blocks."
* Lipson, H. and Pollack, J.B., 2000. Automatic design and manufacture of robotic lifeforms. Nature, 406(6799), pp.974-978. [ [www](https://www.nature.com/articles/35023115) | [news & views](https://www.nature.com/articles/35023200) | [Golem](http://demo.cs.brandeis.edu/golem/) ] ( **ES/EP** | **Parallel** | **Distributed** )
* Lenski, R.E., Ofria, C., Collier, T.C. and Adami, C., 1999. Genome complexity, robustness and genetic interactions in digital organisms. Nature, 400(6745), pp.661-664. [ [www](https://www.nature.com/articles/23245) ] ( **AL** )
  * Holland, J.H., 1992. Adaptation in natural and artificial systems: An introductory analysis with applications to biology, control, and artificial intelligence. MIT Press.
  * Koza, J.R., 1992. Genetic programming: On the programming of computers by means of natural selection. MIT Press.
* Viswanathan, G.M., Buldyrev, S.V., Havlin, S., Da Luz, M.G.E., Raposo, E.P. and Stanley, H.E., 1999. Optimizing the success of random searches. Nature, 401(6756), pp.911-914. [ [www](https://www.nature.com/articles/44831) ] ( **RS** )
* Ho, K.M., Shvartsburg, A.A., Pan, B., Lu, Z.Y., Wang, C.Z., Wacker, J.G., Fye, J.L. and Jarrold, M.F., 1998. Structures of medium-sized silicon clusters. Nature, 392(6676), pp.582-585. [ [www](https://www.nature.com/articles/33369) ]
  * "Here we report geometries calculated for medium-sized silicon clusters using an unbiased global search with a genetic algorithm."
    * Deaven, D. M. & Ho, K. M. Molecular geometry optimization with a genetic algorithm. Phys. Rev. Lett. 75, 288–291 (1995).
* Desmet, J., Maeyer, M.D., Hazes, B. and Lasters, I., 1992. The dead-end elimination theorem and its use in protein side-chain positioning. Nature, 356(6369), pp.539-542. [ [www](https://www.nature.com/articles/356539a0) ] ( **GA** )
  * "For larger systems other strategies had to be developped, such as the Monte Carlo Procedure and the genetic algorithm and clustering approach."
* Smith, J.M., 1992. Byte-sized evolution. Nature, 355(6363), pp.772-773. [ [www](https://www.nature.com/articles/355772a0) ] ( **AL** )
  * Holland John, H., 1975. Adaptation in natural and artificial systems: An introductory analysis with applications to biology, control, and artificial intelligence. Ann Arbor: University of Michigan Press.
* Bounds, D.G., 1987. New optimization methods from physics and biology. Nature, 329(6136), pp.215-219. [ [www](https://www.nature.com/articles/329215a0) ] ( **GA** )
* Brady, R.M., 1985. [Optimization strategies gleaned from biological evolution](https://www.nature.com/articles/317804a0). Nature, 317(6040), pp.804-806. (**GA**)

# Research Highlights + News & Views + Books & Arts

* [Phase transformations observed at the interfaces between crystalline grains in pure metals](https://www.nature.com/articles/d41586-020-00765-3)
  * "The authors therefore obtained further proof using a machine-learning approach (an evolutionary algorithm) in atomic computer simulations of a grain boundary that had the same geometry as the experimentally observed boundaries."
* [Robotics: Enter the evolvabot](https://www.nature.com/articles/484449a)
  * Darwin's Devices: What Evolving Robots Can Teach Us About the History of Life and the Future of Technology
* [Exploiting elephants in the room](https://www.nature.com/articles/464839a)
  * "Reporting in the Journal of the American Chemical Society, Kreutz et al. describe their use of an 'evolutionary' algorithm, implemented in a microfluidic system, to discover active catalysts."
* [Astrophysics: Far off fly-by](https://www.nature.com/articles/455005d)
  * "Kirsten Howley of the University of California at Santa Cruz and her colleagues have used what is known as a genetic algorithm to determine that NGC 205 is actually swinging around M31."
* [Google tool identifies linchpin species](https://www.nature.com/articles/news.2008.1010)
  * "The gold-standard method for dealing with what happens when a prey species is removed from the system is to use a genetic algorithm in which randomly generated possible solutions are assigned a greater or lesser degree of fitness. Fitter solutions are then combined to create a next-generation algorithm that benefits from their superior elements. The idea is to ultimately ‘evolve’ an optimal solution."
* [Storage of the fittest](https://www.nature.com/articles/news010329-5)
* [Book Review: Nature's way](https://www.nature.com/articles/363222a0)

## Biological Evolution

* Long-term studies provide unique insights into evolution
* Bozdag, G.O., Zamani-Dahaj, S.A., Day, T.C., Kahn, P.C., Burnetti, A.J., Lac, D.T., Tong, K., Conlin, P.L., Balwani, A.H., Dyer, E.L. and Yunker, P.J., 2023.
  De novo evolution of macroscopic multicellularity.
  Nature, 617(7962), pp.747-754.
* Grant, P.R. and Grant, B.R., 2002.
  [Unpredictable evolution in a 30-year study of Darwin's finches]().
  Science, 296(5568), pp.707-711.

###

@article{2015-Nature-EibenSmith,
  title={From evolutionary computation to the evolution of things},
  author={Eiben, Agoston E and Smith, Jim},
  journal={Nature},
  volume={521},
  number={7553},
  pages={476--482},
  year={2015},
  publisher={Nature Publishing Group}
}

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.DistributedEvolutionaryComputation)
