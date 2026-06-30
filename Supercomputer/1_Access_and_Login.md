# Supercomputer and HPC

## Table of Contents

1: What is an HPC?

2: HPC in the lab

3: Logging into your account!

## 1: What is HPC?
HPC stands for [High-performance computing](https://www.nvidia.com/en-us/glossary/high-performance-computing/). An HPC/supercomputing system is made up of many computers combined that work together to perform complex tasks. Some terminology to note:
* An HPC Cluster is a group/system of computers
* These computers are individually known as nodes
* Each node may have [CPU (Central Processing Unit) or GPU (Graphics Processing Unit)]([https://www.cdw.com/content/cdw/en/articles/hardware/cpu-vs-gpu.html](https://www.weka.io/learn/hpc/gpu-and-hpc-explained/)). 
* Each CPU and GPU have cores, which are essentially the processor of a CPU/GPU. CPU can have 2-64 cores, while GPU can have thousands. The more cores, the more processing power and thus the better the [performance and efficiency](https://www.cdw.com/content/cdw/en/articles/hardware/cpu-vs-gpu.html#5).
* General organization/hierarchy: Cluster -> Nodes (Computers) -> CPU/GPU -> cores

### More basic details on [CPU and GPU:]([https://www.cdw.com/content/cdw/en/articles/hardware/cpu-vs-gpu.html](https://www.weka.io/learn/hpc/gpu-and-hpc-explained/)).
CPU and GPU are both hardware components with different functionalities. CPUs are like the "brain" of the computer, running all the computations and RAM. GPUs were made to handle graphics and visual displays (as implied by the name), which are more complex operations. 

The difference between CPU and GPU is that CPU runs "serially" (one process after another), whereas GPU runs "in parallel" (multiple processes at the same time). When handling large amounts of data or heavy computations, GPU can be more efficient and is better able to handle certain operations.

## 2: HPC in the lab
Next generation sequencing (NGS) have given researchers the possibility of capturing the entirety of the human genome from a tissue sample, known as Whole Genome Sequencing. Oftentimes, the output files of these sequencing processes may be up to hundreds of gigabytes worth of data; regular computers will not be able to handle this. 

Many downstream analyses on WGS files will thus need to be run via a supercomputing/HPC cluster! We have the privilege of being right next to the San Diego Supercomputing Center (SDSC), located on campus at UCSD. The HPC cluster hosted at the SDSC is known as [Expanse](https://www.sdsc.edu/systems/expanse/index.html). In the past, the lab has used supercomputing resources to mine WGS genomic data for microbes and associations with clinical outcomes- analyses that require lots of computing resources that are only feasible with a supercomputer.

Access to supercomputing resources requires applications for resource "allocations". Only limited amounts are provided (rather than open access to resources) because of the computationally intensive nature of supercomputing services. They want to know that researchers have a goal in mind for supercomputing resources and are able to use these resources correctly and efficiently. So far, we only have CPU allocations.

## 3: Logging into your account

