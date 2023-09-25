# Evolution Strategies (ES)

**Evolution Strategies (ES)** were originally proposed in the 1960s by two students [Rechenberg](https://web.archive.org/web/20180425010001/http://www.bionik.tu-berlin.de/institut/xstart.htm) and [Schwefel](https://ls11-www.cs.tu-dortmund.de/people/schwefel/) at the Technical University of Berlin ([TUB](https://www.tu.berlin/en/)), Germany. For a detailed introduction to the (relatively long) history of ES, we strongly suggest to refer to e.g., [[Beyer, 2023, GECCO]](https://dl.acm.org/doi/abs/10.1145/3583133.3595041), [[Hansen et al., 2015]](), [[Bäck et al., 2013]](https://link.springer.com/book/10.1007/978-3-642-40137-4), [[Beyer&Schwefel, 2002]](https://link.springer.com/article/10.1023/A:1015059928466), especially from two early pioneers(e.g., [[ACM SIGEVOlution, 2008]](https://dl.acm.org/doi/abs/10.1145/1621943.1621944), [[ACM SIGEVOlution, 2010]](https://dl.acm.org/doi/abs/10.1145/1810132.1810133)). In this book, we mainly focus on **modern** ES versions and variants: Covariance Matrix Adaptation ES (**CMA-ES**/**MA-ES**), Nature ES (**NES**), Limited-Memory CMA (**LM-CMA**), **OpenAI-ES**, Persistent ES (**PES**), and Meta-/Distributed ES (**DES**). Despite as one of the three *earliest* (from 1960s) families of [evolutionary algorithms](https://www.nature.com/articles/nature14544) with [genetic algorithms]() and [evolutionary programming](), now ES are still studied widely in the [evolutionary computation](https://www.nature.com/articles/nature14544) community and are still applied to approximate the global/local optimum of many (though not all) real-world problems. Note that if novel and powerful ES variants emerge in the future, we will expect to add them as soon as possible (reflecting the open nature of this book).

## Self-Adaptation and Covariance Matrix Adaptation ES (CMA-ES)

**Self-adaptation** is widely recognized as the essential feature of ES, which has resulted in (at least) one powerful ES version called Covariance Matrix Adaptation (CMA-ES).

CMA-ES could be used as a **strong baseline** on some BBO problems, such as [offline design of biological sequences](https://arxiv.org/pdf/2306.03111.pdf) where ["for TFbind8, which has a relatively small search space, CMA-ES gave pretty good performances"](https://arxiv.org/pdf/2306.03111.pdf), [informative path planning](https://proceedings.mlr.press/v205/cao23b/cao23b.pdf) where ["CMA-ES finds a good trade-off between exploration and exploitation, resulting in the best overall performance among non-learning solvers"](https://proceedings.mlr.press/v205/cao23b/cao23b.pdf), [task constrained planner for robot manipulator in confined environment](https://arxiv.org/pdf/2304.09260.pdf), [reinforcement learning with human feedback (RLHF)](https://arxiv.org/pdf/2303.03751.pdf), if not the state-of-the-art. On **many** (though not all) hard BBO problems, CMA-ES has shown very competitive (and sometimes even state-of-the-art) performance (see the following section for some of its representative applications).

[Surrogate-assisted CMA-ES](), for e.g., [computational chemistry](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c01231).

[synthesizability-constrained molecular design](https://openreview.net/pdf?id=rKfvMyWVO0L)

## Natural Gradients and Natural Evolution Strategies (NES)

## Gradient Estimation (OpenAI-ES) and Variance Reduction (Persistent ES)

## Meta-ES and Distributed ES (DES)

## Typical Optimization Applications of ES

* [Exoskeleton assistance](https://www.nature.com/articles/s41586-022-05191-1): A team from Stanford University (**Nature, 2022**).
* [Flying robots](https://www.nature.com/articles/s41586-022-05182-2): A joint team from Delft University of Technology and Aix Marseille Université (**Nature, 2022**).
* [Abstract art](https://arxiv.org/pdf/2304.12932.pdf) + [Evolving collective AI](https://direct.mit.edu/isal/proceedings/isal/35/112/116826): Google Research, Brain Team + University of Tokyo (**2023**).
* [Robotic caregivers](https://arxiv.org/pdf/2304.04822.pdf): A joint team from [Carnegie Mellon University](https://rchi-lab.github.io/robust-body-exposure/) and [Google X](https://github.com/RCHI-Lab/robust-body-exposure) (2023). [ [IEEE-LRA, 2022](https://ieeexplore.ieee.org/abstract/document/9681203) + [CVPR, 2020](https://openaccess.thecvf.com/content_CVPR_2020/papers/Clever_Bodies_at_Rest_3D_Human_Pose_and_Shape_Estimation_From_CVPR_2020_paper.pdf) + [IEEE-LRA, 2020](https://ieeexplore.ieee.org/abstract/document/8988245) + [Autonomous Robots, 2019](https://link.springer.com/article/10.1007/s10514-019-09865-0) + [Autonomous Robots, 2019](https://link.springer.com/article/10.1007/s10514-019-09847-2) + [ICRA, 2018](https://ieeexplore.ieee.org/abstract/document/8460656) + [IROS, 2019](https://ieeexplore.ieee.org/abstract/document/8968053) + [ICRA, 2017](https://ieeexplore.ieee.org/abstract/document/7989718) + [ICRA, 2017](https://ieeexplore.ieee.org/abstract/document/7989716) ]
* [Stochastic trajectory optimization for reactive robot](https://ieeexplore.ieee.org/document/10160214): A joint team from Idiap Research Institute, [Ecole Polytechnique Federale de Lausanne (EPFL)](https://github.com/JuJankowski/vp-sto), and [University of Oxford](https://sites.google.com/oxfordrobotics.institute/vp-sto) (ICRA, 2023).
* [Adversarial robustness in discontinuous spaces](https://openaccess.thecvf.com/content/WACV2023/papers/Venkatesh_Adversarial_Robustness_in_Discontinuous_Spaces_via_Alternating_Sampling__Descent_WACV_2023_paper.pdf): A joint team from Stanford University, University of Pennsylvania, Carnegie Mellon University, and Bosch Center for AI (WACV, 2023).
* [Target specific peptide design](https://arxiv.org/pdf/2302.01435.pdf): A joint team from Carnegie Mellon University and Ohio State University (**2023**).
* [Dexterous manipulation](https://arxiv.org/pdf/2304.05141.pdf): A joint team from Tencent Robotics X, University of Edinburgh, and University College London (**2023**).
* [Path synthesis](https://asmedigitalcollection.asme.org/mechanicaldesign/article/145/7/073303/1160180/GCP-HOLO-Generating-High-Order-Linkage-Graphs-for): Carnegie Mellon University (Journal of Mechanical Design, 2023).
* [Biogeochemical model optimization](https://gmd.copernicus.org/articles/16/3581/2023/gmd-16-3581-2023.html): University of California Los Angeles (Geoscientific Model Development, 2023).
* [Muscle-driven miniature robots](https://www.science.org/doi/full/10.1126/scirobotics.add1053): A joint team from University of Illinois at Urbana-Champaign, Northwestern University, Massachusetts Institute of Technology, University of Houston, Dalian University of Technology, and University of Southern California (**Science Robotics, 2023**). 
* [Adaptable materials](https://www.pnas.org/doi/abs/10.1073/pnas.2219558120): A joint team from University of Chicago and Yale University (**PNAS, 2023**).
* [Image quality optimization in augmented reality](https://ieeexplore.ieee.org/abstract/document/10115525):  U.S. Food and Drug Administration (IEEE-TMI, 2023).
* [Combination treatment optimization](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009689): A joint team from Carnegie Mellon University, University of Pittsburgh, and Harvard Medical School + Strategy Robot, Inc., Optimized Markets, Inc., Strategic Machine, Inc. (PLOS Computational Biology, 2021).
* [Atmospheric methane](https://www.pnas.org/doi/10.1073/pnas.1616020114): A joint team from Harvard University, California Instituteof Technology, and Jet Propulsion Laboratory (**PNAS, 2017**).
* [Optimization of an omnidirectional humanoid walk](https://ojs.aaai.org/index.php/AAAI/article/view/8317): [University of Texas at Austin](https://www.cs.utexas.edu/~AustinVilla/sim/3dsimulation/) (AAAI, 2012 / [[AAMAS 2011]](https://ifaamas.org/Proceedings/aamas2011/papers/A6_B69.pdf)): A winning approach at the RoboCup 2011 3D simulation competition.
* Robotics: [[Klar et al., 2023, ACM-TOCHI]](https://dl.acm.org/doi/full/10.1145/3577016), [[Wang et al., 2023, ICRA]](https://ieeexplore.ieee.org/abstract/document/10160303), [[Wochner et al., 2022, CoRL]](https://proceedings.mlr.press/v205/wochner23a/wochner23a.pdf), [[Kim&Oh, 2021, NeurIPS]](https://proceedings.neurips.cc/paper/2021/file/92dfa194391a59dc65b88b704599dbd6-Paper.pdf), [[Thatte&Geyer, 2016, IEEE-TBME]](https://ieeexplore.ieee.org/abstract/document/7222383), [[Song&Geyer, 2012, ICRA]](https://ieeexplore.ieee.org/abstract/document/6225307)
* Computer Vision: [[Tian et al., 2023, CVPR]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tian_Multi-Object_Manipulation_via_Object-Centric_Neural_Scattering_Functions_CVPR_2023_paper.pdf), [[Huang et al., 2022, CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Huang_Neural_MoCon_Neural_Motion_Control_for_Physically_Plausible_Human_Motion_CVPR_2022_paper.pdf)
* Graphics: [[Lee et al., 2022, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/3550454.3555489), [[Geijtenbeek et al., 2013, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/2508363.2508399), [[Stoll et al., 2010, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1882261.1866161), [[Wang et al., 2009, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1661412.1618514), [[Wampler&Popović, 2009, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1531326.1531366)
  * [[Fei et al., 2023]](https://arxiv.org/pdf/2304.05818.pdf)
* Operations Research: [[Jacquet, 2023, EJOR]](https://www.sciencedirect.com/science/article/pii/S0377221723003508)
* Language Models: [[Cao et al., 2023, NSR]](https://academic.oup.com/nsr/article/10/6/nwad124/7152626), [[Shen et al., 2023]](https://arxiv.org/pdf/2305.00593.pdf) 
* Noisy Intermediate-Scale Quantum: [[Hu et al., 2023]](https://arxiv.org/pdf/2309.06327.pdf) from George Mason University, Kent State University, Oak Ridge National Laboratory

## Notes

1. Sometimes **Evolutionary Strategies** are used in the literature.
2. We are very sorry that in this book we do not give the original German references of ES, since here we only consider English.

## Reference

* [https://www.paulvicol.com/pdfs/ES-Single-Slides.pdf](https://www.paulvicol.com/pdfs/ES-Single-Slides.pdf)
* [Beyer, H.G.](https://homepages.fhv.at/hgb/), 2023, July. [What you always wanted to know about evolution strategies, but never dared to ask](https://dl.acm.org/doi/abs/10.1145/3583133.3595041). In Proceedings of ACM Conference on Genetic and Evolutionary Computation Companion (pp. 878-894).
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 2002. [Deep insight from simple models of evolution](https://www.sciencedirect.com/science/article/abs/pii/S0303264701001861). BioSystems, 64(1-3), pp.189-198.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1994. On the evolution of evolutionary computation. Computational Intelligence: Imitating Life, pp.116-124.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1993. [Evolution and optimum seeking: The sixth generation](https://www.amazon.co.uk/Evolution-Optimum-Generation-Computer-Technologies/dp/0471571482). John Wiley & Sons, Inc..
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1992. [Natural evolution and collective optimum seeking](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=7221f5be8ca17ee9cd8fe638cf2ad4886bd66262). Computational Systems Analysis–Topics and Trends, pp.5-14.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1988. [Evolutionary learning optimum-seeking on parallel computer architectures](https://link.springer.com/chapter/10.1007/978-1-4684-6389-7_46). In Systems Analysis and Simulation I (pp. 217-225). Springer, New York, NY.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1988. [Collective intelligence in evolving systems](https://link.springer.com/chapter/10.1007/978-3-642-73953-8_8). In Ecodynamics (pp. 95-100). Springer, Berlin, Heidelberg.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1984. [Evolution strategies: A family of non-linear optimization techniques based on imitating some principles of organic evolution](https://link.springer.com/article/10.1007/BF01876146). Annals of Operations Research, 1(2), pp.165-167.
* [Schwefel, H.P.](https://ls11-www.cs.tu-dortmund.de/people/schwefel/), 1981. [Numerical optimization of computer models](https://www.amazon.com/Numerical-optimization-computer-Hans-Paul-Schwefel/dp/0471099880). John Wiley & Sons, Inc..
* Hansen, N., Arnold, D.V. and Auger, A., 2015. Evolution strategies. In Springer Handbook of Computational Intelligence (pp. 871-898). Springer, Berlin, Heidelberg.
* Bäck, T., Foussette, C. and Krause, P., 2013. Contemporary evolution strategies. Berlin: Springer.
* [2012] A Comparison of Global Search Algorithms for Continuous Black Box Optimization [EC]
* Beyer, H.G. and Schwefel, H.P., 2002. Evolution strategies–A comprehensive introduction. Natural Computing, 1(1), pp.3-52.
* [2000] Evolutionary algorithms in noisy environments - Theoretical issues and guidelines for practice [Beyer]
* Rechenberg, I., 2000. Case studies in evolutionary experimentation and computation. Computer Methods in Applied Mechanics and Engineering, 186(2-4), pp.125-140.
* Rechenberg, I., 1984. The evolution strategy. A mathematical model of darwinian evolution. In Synergetics—from Microscopic to Macroscopic Order (pp. 122-132). Springer, Berlin, Heidelberg.
