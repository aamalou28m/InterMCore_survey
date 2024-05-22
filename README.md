# Papers related to InterMCore project 

A curated list of related research papers and tools for around InterMcore project


## Contents
- [Papers](#papers)
   - [Survey on interferences](#survey)
   - [Microbenchmarking techniques](#microbechmark)
   - [Model checking techniques](#formal-methods)
   - [Interference reduction techniques](#interference-reductions)
   - [Task model](#Task-model)
- [Books](#books)
- [Talks and Tutorials](#talks-and-tutorials)
- [Software](#software)
- [Benchmarks, Traces, Datasets and Case study](#benchmarks-and-datasets)
- [Conferences](#conferences)
- [Journals](#journals)
- [How to Contribute](#how-to-contribute)

## Papers
#### Survey on interferences

- <img src="https://img.shields.io/badge/30-pages-green.svg" alt="30-pages" align="top"> [A survey of techniques for reducing interference in real-time applications on multicore platforms](https://ieeexplore.ieee.org/abstract/document/9714355/) - Tamara Lugo, Santiago Lozano, Javier Fernández, and Jesus Carretero. IEEE Access 2022.

- <img src="https://img.shields.io/badge/23-pages-green.svg" alt="23-pages" align="top"> [A Survey of Timing Verification Techniques for Multi-Core Real-Time Systems](https://dl.acm.org/doi/abs/10.1145/3323212) - Claire Maiza, Hamza Rihani, Juan M. Rivas and Joël Goossens, Sébastian Altmeyer, Robert I. Davis. ACM Computing Surveys 2018.

- <img src="https://img.shields.io/badge/unknown-pages-green.svg" alt="unknown-pages" align="top"> [Program semantics in model-based WCET analysis: A state of the art perspective](https://drops.dagstuhl.de/opus/volltexte/2013/4120/) - Mihail Asavoae, Claire Maiza, and Pascal Raymond. 13th International Workshop on Worst-Case Execution Time Analysis, Schloss Dagstuhl-Leibniz-Zentrum fuer Informatik 2013.

- <img src="https://img.shields.io/badge/8-pages-green.svg" alt="8-pages" align="top"> [A survey of WCET analysis of real-time operating systems](https://ieeexplore.ieee.org/abstract/document/5066632/) - Mingsong Lv, Nan Guan, Yi Zhang, Qingxu Deng, Ge Yu, and Jianming Zhang. 2009 International Conference on embedded software and systems, IEEE 2009.


#### Microbenchmarking techniques
- <img src="https://img.shields.io/badge/14-pages-green.svg" alt="14-pages" align="top"> [uiCA: Accurate throughput prediction of basic blocks on recent Intel microarchitectures](https://dl.acm.org/doi/abs/10.1145/3524059.3532396) - Andreas Abel and Jan Reineke. Proceedings of the 36th ACM International Conference on Supercomputing, 2022.

- <img src="https://img.shields.io/badge/123-pages-green.svg" alt="123-pages" align="top"> [Palmed: Throughput characterization for superscalar architectures](https://arxiv.org/abs/2012.11473) - Nicolas Derumigny, Fabian Gruber, Théophile Bastian, Guillaume Iooss, Christophe Guillon, Louis-Noël Pouchet, and Fabrice Rastello, January 2022.

- <img src="https://img.shields.io/badge/0-pages-green.svg" alt="0-pages" align="top"> [Instruction tables: Lists of instruction latencies, throughputs and micro-operation breakdowns for Intel, AMD and VIA CPUs](http://www.agner.org/optimize/instruction_tables.pdf) - Agner Fog, March 2021.

- <img src="https://img.shields.io/badge/14-pages-green.svg" alt="14-pages" align="top"> [Improving prediction accuracy of memory interferences for multicore platforms](https://ieeexplore.ieee.org/abstract/document/9052176/) - Cédric Courtaud, Julien Sopena, Gilles Muller, and Daniel Gracia Pérez. 2019 IEEE Real-Time Systems Symposium (RTSS), IEEE 2019.


#### Model checking techniques

- <img src="https://img.shields.io/badge/12-pages-green.svg" alt="12-pages" align="top"> [The role of causality in a formal definition of timing anomalies](https://ieeexplore.ieee.org/abstract/document/9904748/) - Benjamin Binder, Mihail Asavoae, Florian Brandner, Belgacem Ben Hedia, and Mathieu Jan. 2022 IEEE 28th International Conference on Embedded and Real-Time Computing Systems and Applications (RTCSA), IEEE 2022.

- <img src="https://img.shields.io/badge/10-pages-green.svg" alt="10-pages" align="top"> [Using model checking to identify timing interferences on multicore processors](https://inria.hal.science/hal-02462085/document) - Viet Anh Nguyen, Eric Jenn, Wendelin Serwe, Frederic Lang, and Radu Mateescu. ERTS 2020-10th European Congress on Embedded Real Time Software and Systems, 2020.

- <img src="https://img.shields.io/badge/10-pages-green.svg" alt="10-pages" align="top"> [Timing analysis of binary programs with UPPAAL](https://ieeexplore.ieee.org/abstract/document/6598339/) - Franck Cassez and Jean-Luc Béchennec. 2013 13th International Conference on Application of Concurrency to System Design, IEEE 2013.

- <img src="https://img.shields.io/badge/unknown-pages-green.svg" alt="unknown-pages" align="top"> [Computation of wcet using program slicing and real-time model-checking](https://arxiv.org/abs/1105.1633) - Jean-Luc Béchennec and Franck Cassez.


#### Interference reduction
- <img src="https://img.shields.io/badge/0-pages-green.svg" alt="0-pages" align="top"> [Low-overhead online assessment of timely progress as a system commodity](https://drops.dagstuhl.de/storage/00lipics/lipics-vol262-ecrts2023/LIPIcs.ECRTS.2023.13/LIPIcs.ECRTS.2023.13.pdf
) - Weifan Chen, Ivan Izhibirdeev, Denis Hoornaert, Shahin Roozkhosh, Patrick Carpanedo, Sanskriti Sharma, and Renato Mancuso. 35th Euromicro Conference on Real-Time Systems (ECRTS 2023), Schloss Dagstuhl-Leibniz-Zentrum f{"u}r Informatik, 2023.

- <img src="https://img.shields.io/badge/11-pages-green.svg" alt="11-pages" align="top"> [A predictable execution model for COTS-based embedded systems](https://ieeexplore.ieee.org/document/5767117) - Rodolfo Pellizzoni, Emiliano Betti, Stanley Bak, Gang Yao, John Criswell, Marco Caccamo, and Russell Kegley. 2011 17th IEEE Real-Time and Embedded Technology and Applications Symposium, IEEE, 2011.

#### Interference analysis
- <img src="https://img.shields.io/badge/22-pages-green.svg" alt="22-pages" align="top"> [Kryptonite: Worst-Case Program Interference Estimation on Multi-Core Embedded Systems](https://dl.acm.org/doi/full/10.1145/3609128
) - Nikhilesh Singh, Karthikeyan Renganathan, Chester Rebeiro, Jithin Jose, and Ralph Mader. ACM Transactions on Embedded Computing Systems, 2023.

- <img src="https://img.shields.io/badge/0-pages-green.svg" alt="0-pages" align="top"> [StAMP: Static Analysis of Memory access Profiles for real-time tasks](https://drops.dagstuhl.de/entities/document/10.4230/OASIcs.WCET.2022.1
) - Théo Degioanni and Isabelle Puaut. 20th International Workshop on Worst-Case Execution Time Analysis (WCET 2022), Schloss Dagstuhl-Leibniz-Zentrum f{"u}r Informatik, 2022.

- <img src="https://img.shields.io/badge/0-pages-green.svg" alt="0-pages" align="top"> [Compiler-based extraction of event arrival functions for real-time systems analysis] (https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECRTS.2018.4) - Dominic Oehlert, Selma Saidi, and Heiko Falk. 30th Euromicro Conference on Real-Time Systems (ECRTS 2018), Schloss-Dagstuhl-Leibniz Zentrum für Informatik, 2018.
  
- <img src="https://img.shields.io/badge/15-pages-green.svg" alt="15-pages" align="top"> [Static extraction of memory access profiles for multi-core interference analysis of real-time tasks](https://link.springer.com/chapter/10.1007/978-3-030-81682-7_2) - Thomas Carle and Hugues Cass{'e}. Architecture of Computing Systems: 34th International Conference, ARCS 2021, Virtual Event, June 7--8, 2021, Proceedings 34, Springer, 2021.

#### Task Model
- <img src="https://img.shields.io/badge/15-pages-green.svg" alt="15-pages" align="top">  [A Variable Rate Execution Model] (https://cse.unl.edu/~goddard/Papers/Conference/ECRTS04GoddardLiu.pdf) - Steve Goddard and Xin Liu. ECRTS 2004.

## Books


## Talks and Tutorials
- Link to CEA talkspirit : [InterMCore kickoff](https://cea.talkspirit.com/#/l/drives/oos8uu?clip=all&type=drive)


## Software
- [Phylog model language PML](https://github.com/IITH-Compilers/ML-Compiler-Bridge) - PML ([paper](https://hal.science/hal-02441353/document)).


## Benchmarks, Traces, Datasets and Case study
- [The ROSACE Case Study](https://svn.onera.fr/schedmcore/branches/ROSACE_CaseStudy) - From Simulink Specification to Multi/Many-Core Execution. Claire Pagetti, David Saussié, Romain Gratia, Eric Noulard, and Pierre Siron. 20th IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS'14).[paper](https://openreview.net/pdf?id=aIfp8kLuvc9).

- [ACAS Xu Case Study](https://svn.onera.fr/schedmcore/branches/ACAS_CaseStudy/) - Description ([site need a login](https://forge.onera.fr/projects/schedmcore/wiki/ACAS_Xu_simulator)). [other version](https://github.com/lf-lang/playground-lingua-franca/tree/acas/Python/src/acas).

- [VBL Case Study -ongoing-](TODO)

## Conferences
- <img src="https://img.shields.io/badge/Conference-RTSS-blue.svg" alt="RTSS" align="top"> [RTSS](https://2024.rtss.org/)

- <img src="https://img.shields.io/badge/Conference-RTAS-blue.svg" alt="RTAS" align="top"> [RTAS](https://2024.rtas.org/)

- <img src="https://img.shields.io/badge/Conference-ECRTS-blue.svg" alt="ECRTS" align="top"> [ECRTS](https://www.ecrts.org/)

- <img src="https://img.shields.io/badge/Conference-RTCSA-blue.svg" alt="RTCSA" align="top"> [RTCSA](https://rtcsa2024.github.io/)

- <img src="https://img.shields.io/badge/Conference-RTNS-blue.svg" alt="RTNS" align="top"> [RTNS](https://cister-labs.pt/rtns24/)

- <img src="https://img.shields.io/badge/Conference-ERTS-blue.svg" alt="RTNS" align="top"> [ERTS](https://erts2024.org/)

- <img src="https://img.shields.io/badge/Conference-DATE-blue.svg" alt="DATE" align="top"> [DATE](https://www.date-conference.com/)

## Journals
- <img src="https://img.shields.io/badge/Journal-ACM-blue.svg" alt="RTS" align="top"> [RTS](https://link.springer.com/journal/11241)

## How to Contribute (TODO)
## TODO RTSS, RTAS, ECRTS papers to add by year (till 2020)
