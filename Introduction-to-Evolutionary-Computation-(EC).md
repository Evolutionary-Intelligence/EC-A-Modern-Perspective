# Introduction to Evolutionary Computation (EC)

[directed evolution](https://iopscience.iop.org/article/10.1088/2632-2153/accacd)

## Some Useful and Interesting Applications

### Open-Source Softwares

Note that the following order regarding a set of open-source EC libraries makes no sense (just from a download statistic perspective).

* [cmaes](https://github.com/CyberAgentAILab/cmaes): Python library for CMA ES ([![Downloads](https://static.pepy.tech/badge/cmaes)](https://pepy.tech/project/cmaes)).
* [DEAP](https://github.com/deap/deap): Distributed EAs in Python (*> 2000 Citations* + [![Downloads](https://static.pepy.tech/badge/deap)](https://pepy.tech/project/deap)).
  * **Fortin, F.A., De Rainville, F.M., Gardner, M.A.G., Parizeau, M. and Gagné, C., 2012. DEAP: Evolutionary algorithms made easy. Journal of Machine Learning Research, 13(1), pp.2171-2175.**
* [pycma](https://github.com/CMA-ES/pycma): Python implementation of CMA-ES ([![Downloads](https://static.pepy.tech/badge/cma)](https://pepy.tech/project/cma)).
* [pymoo](https://github.com/anyoptimization/pymoo): Multi-objective Optimization in Python ([![Downloads](https://static.pepy.tech/badge/pymoo)](https://pepy.tech/project/pymoo)).
* [TPOT](https://github.com/EpistasisLab/tpot): A Python AutoML tool that optimizes ML pipelines using GP ([![Downloads](https://static.pepy.tech/badge/tpot)](https://pepy.tech/project/tpot)).
* [nevergrad](https://github.com/facebookresearch/nevergrad): A Python toolbox for performing gradient-free optimization ([![Downloads](https://static.pepy.tech/badge/nevergrad)](https://pepy.tech/project/nevergrad)).
* [PyBrain](https://github.com/pybrain/pybrain): The Python ML Library ([![Downloads](https://static.pepy.tech/badge/pybrain)](https://pepy.tech/project/pybrain)).
* [pygmo2](https://esa.github.io/pygmo2/): A scientific Python library for massively parallel optimization ([![Downloads](https://static.pepy.tech/badge/pygmo)](https://pepy.tech/project/pygmo)).
* [PySR](https://github.com/MilesCranmer/PySR): High-Performance Symbolic Regression in Python and Julia ([![Downloads](https://static.pepy.tech/badge/PySR)](https://pepy.tech/project/PySR)).
* [PyPop7](https://github.com/Evolutionary-Intelligence/pypop): A Pure-Python Library for POPulation-based Black-Box Optimization (BBO), especially their Large-Scale versions/variants ([![Downloads](https://static.pepy.tech/badge/pypop7)](https://pepy.tech/project/pypop7)).
* [Platypus](https://github.com/Project-Platypus/Platypus): A framework for EC in Python with a focus on Multi-Objective EAs ([![Downloads](https://static.pepy.tech/badge/platypus)](https://pepy.tech/project/platypus)).
* [evosax](https://github.com/RobertTLange/evosax): ES in JAX ([![Downloads](https://static.pepy.tech/badge/evosax)](https://pepy.tech/project/evosax)).
* [EvolutionaryForest](https://github.com/hengzhe-zhang/EvolutionaryForest): An open source python library for automated feature engineering based on GP ([![Downloads](https://static.pepy.tech/badge/evolutionary_forest)](https://pepy.tech/project/evolutionary_forest))
* [EvoTorch ](https://github.com/nnaisense/evotorch): Advanced EC library built directly on top of PyTorch, created at NNAISENSE ([![Downloads](https://static.pepy.tech/badge/evotorch)](https://pepy.tech/project/evotorch)).
* [EC-KitY](https://www.sciencedirect.com/science/article/pii/S2352711023000778): A Python library for doing EC compatible with scikit-learn ([![Downloads](https://static.pepy.tech/badge/eckity)](https://pepy.tech/project/eckity)).
* [QDax](https://github.com/adaptive-intelligent-robotics/QDax): A Python tool to accelerate QD and neuro-evolution algorithms through hardware accelerators and massive parallelization ([![Downloads](https://static.pepy.tech/badge/qdax)](https://pepy.tech/project/qdax)).
* [pyribs](https://github.com/icaros-usc/pyribs): A Python library for QD optimization ([![Downloads](https://static.pepy.tech/badge/pyribs)](https://pepy.tech/project/pyribs)).
* [paradiseo](https://github.com/nojhan/paradiseo): An EC framework to (automatically) build fast parallel stochastic optimization solvers.

###

* [Astronomy & Astrophysics]()
  * [Calibration of Dark Energy Model (with a 10-dimensional parameter space) for Observational Cosmology](https://www.aanda.org/articles/aa/full_html/2021/12/aa41744-21/aa41744-21.html): [DES Collaboration: Jet Propulsion Laboratory, California Institute of Technology + Fermi National Accelerator Laboratory + University College London + National Center for Supercomputing Applications + University of Illinois at Urbana-Champaign + University of Wisconsin-Madison + University of Michigan + University of Chicago + Stanford University + SLAC National Accelerator Laboratory + Ludwig-Maximilians-Universität + Harvard & Smithsonian + University of Cambridge + Princeton University + Oak Ridge National Laboratory + etc.]
* [Biology]()
  * [Stochastic Model Optimization for Microtubule Motors](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000623): [ETH Zürich + University of Zurich]
* [Control]()
  * [Learning to School](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/learning-to-school-in-the-presence-of-hydrodynamic-interactions/22EE6D99862DB3F3882F287361C8E16A): [Harvard University + SPACEX + ETH Zürich + etc.] ( [Swimming](https://journals.biologists.com/jeb/article/209/24/4841/16413/Simulations-of-optimized-anguilliform-swimming) + [Swimmer](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/cstart-optimal-start-of-larval-fish/1D69338D18E0748C24D9B0B07D0C233A) + [Swimmers](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/optimal-shapes-for-anguilliform-swimmers-at-intermediate-reynolds-numbers/82B0F4B119815A9AB0508E67A582A285) + [Undulatory Swimmers](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/optimal-morphokinematics-for-undulatory-swimmers-at-intermediate-reynolds-numbers/A89113257A5A14C1C67331EA7922EF7B) + [Swimming Schools](https://cse-lab.seas.harvard.edu/publications/evolutionary-optimization-scalar-transport-cylinder-arrays-multigpumulticore) | [Collective Behavior](https://arxiv.org/abs/2305.10548) )
* [Engineering]()
  * Physics-supervised DL–based Optimization: [[Li et al., 2023, PNAS]](https://www.pnas.org/doi/abs/10.1073/pnas.2309062120)
* [Medicine]()
  * [PharmacoKinetic and PharmacoDynamic Modelling Optimization for Model-Informed Precision Dosing](https://www.biorxiv.org/content/10.1101/2023.07.31.551404v1): [University of Oxford + University of Exeter +  F. Hoffmann-La Roche AG]
* [Physical Science](): e.g., in [cosmology](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.107.043509)
  * [Higgs-boson measurement](https://arxiv.org/pdf/2303.12018.pdf)
* [Chemical Science]()
  * [Crystal structure prediction](https://pubs.aip.org/aip/jcp/article-abstract/124/24/244704/567275/Crystal-structure-prediction-using-ab-initio): e.g. [[Yang et al., 2023, Science]](https://www.science.org/doi/full/10.1126/science.abm5134), [[Mannix et al., 2015, Science]](https://www.science.org/doi/full/10.1126/science.aad1080), [[Zhang et al., 2013, Science]](https://www.science.org/doi/10.1126/science.1244989) [([Insa, 2013, Science])](https://www.science.org/doi/10.1126/science.1247699).
  * [Constructing first-principles phase diagrams of amorphous LixSi](https://pubs.aip.org/aip/jcp/article/148/24/241711/960040)
* [Materials Science]()
  * [Granular materials](https://link.springer.com/article/10.1007/s10035-022-01282-y): A joint team from California Institute of Technology and ETH Zurich.
  * [Grain boundaries in 2D materials](https://pubs.acs.org/doi/full/10.1021/acsami.3c01161)
  * [Energy-efficient 4D printing](https://onlinelibrary.wiley.com/doi/10.1002/advs.202206607): A joint team from Singapore Institute of Manufacturing Technology, City University of Hong Kong, and Pennsylvania State University.
* [Control](https://evotorch.ai/)
  * [Active flow control](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/abs/comparative-analysis-of-machine-learning-methods-for-active-flow-control/DF06699ACFFCCD1B5778ED63DFDADCFF)
  * [Autonomous cars](https://www.sciencedirect.com/science/article/pii/S0743731522002507)
* [NeuroScience](https://www.pnas.org/doi/abs/10.1073/pnas.2213034120): A joint team from Harvard Medical School and Washington University, St. Louis (**PNAS, 2023**)
* [Designs of Computer Architectures](https://dl.acm.org/doi/10.1145/3579371.3589049):
  * [Geneva](https://link.springer.com/article/10.1007/s41781-023-00098-6)
  * Analog Circuit Design and Optimization: [[Zhou et al., TCAD, 2022]](https://ieeexplore.ieee.org/document/9756017)
* [Quantumn Computing]()
  * [Quantum optimal control](https://www.sciencedirect.com/science/article/pii/S0010465523001273)
  * Global optimization of model fitting: [[Villeneuve et al., 2017, Science]](https://www.science.org/doi/full/10.1126/science.aam8393)
  * [State preparation on quantum computers](https://www.nature.com/articles/s41598-023-37767-w): [Physics Letters A](https://www.sciencedirect.com/science/article/pii/S0375960123002402)
* Hyper-Parameter Optimization (HPO): e.g., for [Reinforcement Learning](https://openreview.net/forum?id=0Vm8Ghcxmp), [Environmental Research](https://pubs.acs.org/doi/full/10.1021/acs.est.3c00026)
  * [Baidu Inc.](https://assets.researchsquare.com/files/rs-2408527/v1_covered.pdf?c=1673942367)
  * [Algolux + Mercedes-Benz + Princeton University](https://openaccess.thecvf.com/content/CVPR2023/papers/Goudreault_LiDAR-in-the-Loop_Hyperparameter_Optimization_CVPR_2023_paper.pdf)
* [Search-Based Software Engineering (SBSE)](https://dl.acm.org/doi/abs/10.1145/3514233) and [Adversarial ML](https://dl.acm.org/doi/10.1145/3134599): https://evademl.org/
  * [Arachne](https://dl.acm.org/doi/10.1145/3563210)
  * [DeLag](https://ieeexplore.ieee.org/abstract/document/10098585)
* [AI for Infectious Diseases](https://www.science.org/doi/full/10.1126/science.adh1114)
* [Scientific Computing]()
  * [Reduced order modelling for inverse problems](https://link.springer.com/article/10.1007/s10915-023-02142-4)
* [Aeronautics and Astronautics]()
  * [Design nonsymmetric satellite constellations](https://arc.aiaa.org/doi/full/10.2514/1.A35515): Georgia Institute of Technology
* [Environmental and Energy Science]()
  * [Wind turbine locations](https://www.sciencedirect.com/science/article/pii/S1462901123000497)
  * [Fuel cell and nuclear reactor design](https://www.sciencedirect.com/science/article/pii/S0029549323002728): A joint team from Massachusetts Institute of Technology, University of Michigan (Ann Arbor), and  Shanghai Jiao Tong University
  * [Kinetics model optimization of fuel-rich methane/NG oxidation with ozone addition](https://www.sciencedirect.com/science/article/pii/S2666352X23000468)
* Data mining: [[KDD-2023]](https://dl.acm.org/doi/10.1145/3580305.3599253)

Although we have given **many** problem instances where EAs showed **satisfactory** (*not necessarily optimal*) performance, *NOT all problems* could be best solved by EAs: e.g., [[1]](https://www.sciencedirect.com/science/article/pii/S2590238522006622), just to name a few. We believe that the amount of problem instances tackled effectively by EA will still keep increasing in the future.

* https://psyarxiv.com/9f4k3/
