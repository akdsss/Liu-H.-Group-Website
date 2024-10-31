---
title: "Employing multi-GPU power for molecular dynamics simulation:an extension of GALAMOST"
authors:
- 朱有亮
- Deng Pan
- Zhan-Wei Li
- Hong Liu
- Hu-Jun Qian
- Yang Zhao
- Zhong-Yuan Lu
- Zhao-Yan Sun
date: "2018-04-18"
doi: "10.1080/00268976.2018.1434904"
publish_types: ["期刊文章"]
publication: "Molecular Physics"
publication_short: "Molecular Physics"
abstract: "We describe the algorithm of employing multi-GPU power on the  basis of Message Passing Interface (MPI) domain decomposition in a  molecular dynamics code, GALAMOST, which is designed for the  coarse-grained simulation of soft matters. The code of multi-GPU version  is developed based on our previous single-GPU version. In multi-GPU  runs, one GPU takes charge of one domain and runs single-GPU code path.  The communication between neighbouring domains takes a similar algorithm  of CPU-based code of LAMMPS, but is optimised specifically for GPUs. We  employ a memory-saving design which can enlarge maximum system size at  the same device condition. An optimisation algorithm is employed to  prolong the update period of neighbour list. We demonstrate good  performance of multi-GPU runs on the simulation of Lennard–Jones liquid,  dissipative particle dynamics liquid, polymer and nanoparticle  composite, and two-patch particles on workstation. A good scaling of  many nodes on cluster for two-patch particles is presented."
url_pdf: "https://www.tandfonline.com/doi/full/10.1080/00268976.2018.1434904"
---