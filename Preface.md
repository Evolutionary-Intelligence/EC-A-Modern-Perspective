# Preface

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.ECAMP-Preface)

As shown by Frances H. Arnold, Prof. of California Institute of Technology, in her Nobel Lecture,
"[Responsible for adaptation, optimization, and innovation in the living world, evolution executes
a simple algorithm of diversifcation and natural selection, an algorithm that works at all levels
of complexity from single protein molecules to whole ecosystems.
](https://www.nobelprize.org/uploads/2018/10/arnold-lecture.pdf)" 

An important yet difficult research question to be answered is the (underlying) assumptions behind [Evolutionary Algorithms (EAs)](https://www.nature.com/articles/nature14544). Since the black-box (or more generally, complex) nature of most hard (e.g., NP-hard) problems tackled by EAs, it is very difficult (if not impossible) to mathematically quantitize these (typically *implicit*) assumptions behind different EAs, followed closely by their working principles. In this book we first discuss and analyze the hard-to-clarify relationships between underlying assumptions and black-box applications. Although initially (at the beginning stage) their biological evolution-based inspirations (in a form of metaphors) are an attractive/interesting point to readers, researchers, and practitioners, undoubtedly their **mathematical foundations (theoretical insights), algorithmic frameworks (implementation softwares), and practical usefulness (real-world successes)**, which are of our great interest in this book, play three cornerstone roles in the increasing maturity of the well-known [Evolutionary Computation/Computing (EC)](https://link.springer.com/book/10.1007/978-3-662-44874-8) field.

Our modest goal for this open book is to provide basic information regarding to EC and some (unfortunately *not all*) advanced topics, in order to help the novices foster the ability of judging whether or not it is a [good](https://link.springer.com/article/10.1007/s11721-021-00202-9) research practice for EC, which we think is very crucial especially for novices in the [explosion of of metaphor-centred methods](https://publications.aston.ac.uk/id/eprint/44574/1/ALIFE_LLCS.pdf) and the rise of [Large Language Models (LLMs)](https://chat.openai.com/). Our main focus on EC is (and should be) **general principles** of designing and analyzing EAs (that is, *when, why, and how to use EC*) and their **real-world applications**, rather than only their [biological metaphors](https://github.com/Evolutionary-Intelligence/DistributedEvolutionaryComputation/blob/main/Summary/EvolutionaryComputation.md#metaheuristics) (though some metaphors played an interesting/important role in their early formation stage). Although we still believe there may be little [opportunities](https://www.nature.com/articles/s42256-020-00278-8) to significantly extend the basic EC framework (such as [Quality-Diversity](https://www.nature.com/articles/nature14422)), most of EC's *fundamental* algorithmic structures have been fixed/unchanged over the past 20 years, to some extents. For effectiveness and efficiency, ["leveraging (or learning) the statistical and computational structure of problem"](https://www.nowpublishers.com/article/Details/MAL-070) no matter *explicitly* or *implicitly* is now one of main research goals when desiging different EA versions/variants/improvements for different kinds of hard problems (such as [EDA](), [CMA-ES](), [NES](), [Surrogate Models](), just to name a few).

Up to now, there have been several *wonderful* books devoted to EC, such as [[Eiben&Smith, 2015]](https://link.springer.com/book/10.1007/978-3-662-44874-8), [[De Jong, 2006]](https://ieeexplore.ieee.org/book/6267245), [[Fogel, 2006]](https://ieeexplore.ieee.org/book/5237910)/[[Fogel, 1998]](https://ieeexplore.ieee.org/book/5263042), [[Mitchell, 1998]](https://direct.mit.edu/books/book/4675/An-Introduction-to-Genetic-Algorithms), [[Back, 1996]](https://academic.oup.com/book/40791), [[Koza, 1990]](http://infolab.stanford.edu/pub/cstr/reports/cs/tr/90/1314/CS-TR-90-1314.pdf), to name a few. Furthermore, there have been a number of *well-written* review/survey/perspective papers for EC or one particular class of EAs: e.g., [[Miikkulainen&Forrest, 2021, Nature MI]](https://www.nature.com/articles/s42256-020-00278-8), [[Lehman et al., 2020, ALJ]](https://direct.mit.edu/artl/article/26/2/274/93255/The-Surprising-Creativity-of-Digital-Evolution-A), [[Eiben&Smith, 2015, Nature]](https://www.nature.com/articles/nature14544), [[Schoenauer, 2015]](https://link.springer.com/chapter/10.1007/978-94-017-9014-7_28), [[De Jong&Fogel&Schwefel, 1997]](https://www.taylorfrancis.com/chapters/edit/10.1201/9781482268713-13/history-evolutionary-computation), [[Koza, 1994]](), [[Forrest, 1993, Science]](https://www.science.org/doi/10.1126/science.8346439), just to name a few. Undoubtedly, all of these above works provide multiple *good* starting points to learn EAs or one particular algorithm class for practice and to enter the EC research community.

With the renaissance of [neural networks](https://www.sciencedirect.com/science/article/abs/pii/S0893608014002135) (now also called [deep learning](https://www.nature.com/articles/nature14539)) for AI/ML, the interesting interactions between **learning and evolution** (e.g., [[Hinton&Nowlan, 1987]](https://www.cs.toronto.edu/~hinton/absps/baldwin.pdf), [[Maynard Smith, 1987, Nature]](https://www.cs.toronto.edu/~hinton/absps/maynardsmith.pdf)) are worthwhile to be further investigated.

Finally, we thank very much for Prof. Shi and Prof. Yao which provide our Ph.D. opportunities to study AI/ML and in particular EC. We also acknowledge all authors (Yuwei Huang) and reviewers (Guochen Zhou) from each (relatively independent) chapters.

************** *** **************
Written/Edited by Qiqi Duan (@HIT&SUSTech, Shenzhen),
Qi Zhao @SUSTech (@SUSTech, China),
and Yijun Yang (@Tencent AI Lab, Shenzhen).

From 2023 to 2027.
************** *** **************

## Some Well-Written Books Which Have Inspired this Book

* [https://probml.github.io/pml-book/](https://probml.github.io/pml-book/):
  This **very popular** book (**Machine Learning: A Probabilistic Perspective**)
  directly motivated the name of this open-access book.
* [https://aima.cs.berkeley.edu/](https://aima.cs.berkeley.edu/):
  This **very popular** book (**Artificial Intelligence: A Modern Approach**)
  directly motivated the name of our open-access book.
* [Eiben, A.E.]() and [Smith, J.E.](), 2015.
  [Introduction to evolutionary computing](https://link.springer.com/book/10.1007/978-3-662-44874-8).
  Springer.
* [Fogel, D.B.](), 2006.
  [Evolutionary computation: Toward a new philosophy of
  machine intelligence](https://tinyurl.com/yc2b2hau).
  John Wiley & Sons.
* [De Jong, K.A.](), 2006.
  Evolutionary computation: A unified approach.
  MIT Press.
* [Mitchell, M.](), 1998.
  An introduction to genetic algorithms.
  MIT Press.
* [Bäck, T.](), [Fogel, D.B.]() and Michalewicz, Z., 1997.
  Handbook of evolutionary computation.
  Oxford University Press.
* [Back, T.](), 1996.
  Evolutionary algorithms in theory and practice: evolution strategies,
  evolutionary programming, genetic algorithms.
  Oxford University Press.
* [Schwefel, H.P.](), 1993.
  Evolution and optimum seeking: The sixth generation.
  John Wiley & Sons.
  [Schwefel, H.P.: [IEEE Frank Rosenblatt Award]() +
  [IEEE Evolutionary Computation Pioneer Award]()]
* [Koza, J.R.](https://www.genetic-programming.org/), 1990.
  [Genetic programming: A paradigm for genetically breeding populations of
  computer programs to solve problems](https://tinyurl.com/wxy2n6vy).
  Department of Computer Science, Stanford University.
  [John Koza: [IEEE Evolutionary Computation Pioneer Award
  2024](https://tinyurl.com/ya8s24d9)]

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.ECAMP)
