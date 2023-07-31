# Evolution Strategies (ES)

**Evolution Strategies (ES)** were originally proposed in the 1960s by two students [Rechenberg](https://web.archive.org/web/20180425010001/http://www.bionik.tu-berlin.de/institut/xstart.htm) and [Schwefel](https://ls11-www.cs.tu-dortmund.de/people/schwefel/) at the Technical University of Berlin ([TUB](https://www.tu.berlin/en/)), Germany. For a detailed introduction to the (relatively long) history of ES, we strongly suggest to refer to e.g. [[Hansen et al., 2015]](), [[Bäck et al., 2013]](https://link.springer.com/book/10.1007/978-3-642-40137-4), [[Beyer&Schwefel, 2002]](https://link.springer.com/article/10.1023/A:1015059928466), especially from two early pioneers(e.g., [[ACM SIGEVOlution, 2008]](https://dl.acm.org/doi/abs/10.1145/1621943.1621944), [[ACM SIGEVOlution, 2010]](https://dl.acm.org/doi/abs/10.1145/1810132.1810133)). In this book, we mainly focus on **modern** ES versions and variants: Covariance Matrix Adaptation ES (**CMA-ES**), **NES**, **LM-CMA**, **OpenAI-ES**, **Persistent ES**, and **Meta-ES/Distributed ES**.

## Self-Adaptation and Covariance Matrix Adaptation ES (CMA-ES)

CMA-ES could provide a **strong baseline** on *many* challenging BBO problems, such as [offline design of biological sequences](https://arxiv.org/pdf/2306.03111.pdf) where ["for TFbind8, which has a relatively small search space, the classical method of CMA-ES gave pretty good performances"](https://arxiv.org/pdf/2306.03111.pdf), [informative path planning](https://proceedings.mlr.press/v205/cao23b/cao23b.pdf) where ["CMA-ES finds a good trade-off between exploration and exploitation, resulting in the best overall performance among non-learning solvers"](https://proceedings.mlr.press/v205/cao23b/cao23b.pdf), [reinforcement learning with human feedback (RLHF)](https://arxiv.org/pdf/2303.03751.pdf).

[Surrogate-assisted CMA-ES](), for e.g., [computational chemistry](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c01231).

## Typical Optimization Applications of ES

* [Exoskeleton assistance](https://www.nature.com/articles/s41586-022-05191-1): A team from Stanford University (**Nature, 2022**).
* [Flying robots](https://www.nature.com/articles/s41586-022-05182-2): A joint team from Delft University of Technology and Aix Marseille Université (**Nature, 2022**).
* [Abstract art](https://arxiv.org/pdf/2304.12932.pdf): Google Research, Brain Team (**2023**).
* [Robotic caregivers](https://arxiv.org/pdf/2304.04822.pdf): A joint team from Carnegie Mellon University and Google X (**2023**).
* [Reactive robot](https://arxiv.org/pdf/2210.04067.pdf): A joint team from Idiap Research Institute, Ecole Polytechnique Federale de Lausanne (EPFL), and University of Oxford (**2023**).
* [Adversarial robustness in discontinuous spaces](https://openaccess.thecvf.com/content/WACV2023/papers/Venkatesh_Adversarial_Robustness_in_Discontinuous_Spaces_via_Alternating_Sampling__Descent_WACV_2023_paper.pdf): A joint team from Stanford University, University of Pennsylvania, Carnegie Mellon University, and Bosch Center for AI (WACV, 2023).
* [Target specific peptide design](https://arxiv.org/pdf/2302.01435.pdf): A joint team from Carnegie Mellon University and Ohio State University (**2023**).
* [Dexterous manipulation](https://arxiv.org/pdf/2304.05141.pdf): A joint team from Tencent Robotics X, University of Edinburgh, and University College London (**2023**).
* [Muscle-driven miniature robots](https://www.science.org/doi/full/10.1126/scirobotics.add1053): A joint team from University of Illinois at Urbana-Champaign, Northwestern University, Massachusetts Institute of Technology, University of Houston, Dalian University of Technology, and University of Southern California (**Science Robotics, 2023**). 
* [Adaptable materials](https://www.pnas.org/doi/abs/10.1073/pnas.2219558120): A joint team from University of Chicago and Yale University (**PNAS, 2023**).
* [Combination treatment optimization](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009689): A joint team from Carnegie Mellon University, University of Pittsburgh, and Harvard Medical School + Strategy Robot, Inc., Optimized Markets, Inc., Strategic Machine, Inc. (PLOS Computational Biology, 2021).
* [Atmospheric methane](https://www.pnas.org/doi/10.1073/pnas.1616020114): A joint team from Harvard University, California Instituteof Technology, and Jet Propulsion Laboratory (**PNAS, 2017**).
* Robotics: [[Wang et al., 2023, ICRA]](https://ieeexplore.ieee.org/abstract/document/10160303), [[Wochner et al., 2022, CoRL]](https://proceedings.mlr.press/v205/wochner23a/wochner23a.pdf)
* Computer Vision: [[Tian et al., 2023, CVPR]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tian_Multi-Object_Manipulation_via_Object-Centric_Neural_Scattering_Functions_CVPR_2023_paper.pdf)
* Graphics: [[Lee et al., 2022, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/3550454.3555489), [[Geijtenbeek et al., 2013, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/2508363.2508399), [[Stoll et al., 2010, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1882261.1866161), [[Wang et al., 2009, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1661412.1618514), [[Wampler&Popović, 2009, ACM-TOG]](https://dl.acm.org/doi/abs/10.1145/1531326.1531366)
  * [[Fei et al., 2023]](https://arxiv.org/pdf/2304.05818.pdf)
* Language Models: [Shen et al., 2023](https://arxiv.org/pdf/2305.00593.pdf) 

## Notes

1. Sometimes **Evolutionary Strategies** are used in the literature.
2. We are very sorry that in this book we do not give the original German references of ES, since here we only consider English.

## Reference

* [https://www.paulvicol.com/pdfs/ES-Single-Slides.pdf](https://www.paulvicol.com/pdfs/ES-Single-Slides.pdf)
* Hansen, N., Arnold, D.V. and Auger, A., 2015. Evolution strategies. In Springer Handbook of Computational Intelligence (pp. 871-898). Springer, Berlin, Heidelberg.
* Bäck, T., Foussette, C. and Krause, P., 2013. Contemporary evolution strategies. Berlin: Springer.
* Beyer, H.G. and Schwefel, H.P., 2002. Evolution strategies–A comprehensive introduction. Natural Computing, 1(1), pp.3-52.
* Rechenberg, I., 2000. Case studies in evolutionary experimentation and computation. Computer Methods in Applied Mechanics and Engineering, 186(2-4), pp.125-140.
* Rechenberg, I., 1984. The evolution strategy. A mathematical model of darwinian evolution. In Synergetics—from Microscopic to Macroscopic Order (pp. 122-132). Springer, Berlin, Heidelberg.
* Schwefel, H.P., 1981. Numerical optimization of computer models. John Wiley & Sons, Inc..
