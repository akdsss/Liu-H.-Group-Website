---
title: GPU-Accelerated Molecular Dynamics Simulation to Study Liquid  Crystal Phase Transition Using Coarse-Grained Gay-Berne Anisotropic  Potential
authors:
- Wenduo Chen
- Youliang Zhu
- Fengchao Cui
- Lunyang Liu
- Zhaoyan Sun
- Jizhong Chen
- Yunqi Li
date: '2016-3-17'
doi: 10.1371/journal.pone.0151704
publish_types: 期刊文章
publication: PLOS ONE
publication_short: PLoS ONE
abstract: Gay-Berne (GB) potential is regarded as an accurate model in  the simulation of anisotropic particles, especially for liquid crystal  (LC) mesogens. However, its computational complexity leads to an  extremely time-consuming process for large systems. Here, we developed a  GPU-accelerated molecular dynamics (MD) simulation with coarse-grained  GB potential implemented in GALAMOST package to investigate the LC phase  transitions for mesogens in small molecules, main-chain or side-chain  polymers. For identical mesogens in three different molecules, on  cooling from fully isotropic melts, the small molecules form a  singledomain smectic-B phase, while the main-chain LC polymers prefer a  single-domain nematic phase as a result of connective restraints in  neighboring mesogens. The phase transition of side-chain LC polymers  undergoes a two-step process:nucleation of nematic islands and  formation of multi-domain nematic texture. The particular behavior  originates in the fact that the rotational orientation of the mesogenes  is hindered by the polymer backbones. Both the global distribution and  the local orientation of mesogens are critical for the phase transition  of anisotropic particles. Furthermore, compared with the MD simulation  in LAMMPS, our GPU-accelerated code is about 4 times faster than the GPU  version of LAMMPS and at least 200 times faster than the CPU version of  LAMMPS. This study clearly shows that GPU-accelerated MD simulation  with GB potential in GALAMOST can efficiently handle systems with  anisotropic particles and interactions, and accurately explore phase  differences originated from molecular structures.
url_pdf: https://dx.plos.org/10.1371/journal.pone.0151704
---