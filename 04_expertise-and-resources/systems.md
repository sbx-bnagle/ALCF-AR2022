---
layout: page

title: ALCF Systems

theme: white
permalink: /expertise-and-resources/systems/
---
## Supercomputing Resources

ALCF supercomputing resources support large-scale, computationally intensive projects aimed
at solving some of the world's most complex and challenging scientific problems.

| System Name     | Polaris       | Theta: KNL Nodes   | Theta: GPU Nodes   | Cooley   |
| :---------- | :---------- | :-------------- | :-------------- | :-------------- |
| Purpose    | Science Campaigns    | Science Campaigns       | Science Campaigns       |  Data Analysis and Visualization
| Architecture    | HPE Apollo 6500 Gen10+   | Intel-Cray XC40        | NVIDIA DGX A100        |  Intel Haswell
| Peak Performance    | 44 PF (Tensor Core double precision)    | 11.7 PF       | 3.9 PF        |  293 TF
| Processors per Node   | 3rd Gen AMD EPYC   | 64-core, 1.3-GHz Intel Xeon Phi 7230      | 2 AMD EPYC 7742        |  2 6-core, 2.4-GHz Intel E5–2620
| GPUs per Node    | 4 NVIDIA A100 Tensor Core   | --     | 8 NVIDIA A100 Tensor Core        |  NVIDIA Tesla K80
| Nodes   | 560    | 4,392      | 24        |  126
| Cores   | 17,920    | 281,088       | 3,072        |  1,512
| Memory    | 280 TB (DDR4); 87.5 TB (HBM)    | 843 TB (DDR4); 70 TB (HBM)       | 26 TB (DDR4); 8.32 TB (GPU)      |  47 TB (DDR4); 3 TB (GDDR5)
| Interconnect    | HPE Slingshot 10 with Dragonfly configuration    | Aries network with Dragonfly configuration      | NVIDIA QM8700 InfiniBand       |  FDR InfiniBand
| Racks    | 40    | 24       | 7     |  6

##ALCF AI Testbed

The ALCF AI Testbed provides an infrastructure of next-generation AI-accelerator machines
that allows researchers to evaluate the usability and performance of machine learning-based
applications running on the systems. AI testbeds include:


## Data Storage Systems

ALCF disk storage systems provide intermediate-term storage for users to access,
analyze, and share computational and experimental data. Tape storage is used to
archive data from completed projects.

| System Name     | Eagle       | Grand   | Theta-FSO  | Swift   | Tape Storage
| :---------- | :---------- | :-------------- | :-------------- | :-------------- | :-------------- |
| File System    | Lustre   | Lustre       | Lustre       |  Lustre   |  -- 
| Storage System   | HPE ClusterStor E1000   | HPE ClusterStor E1000       | HPE Sonexion L300        |  All NVMe Flash Storage Array  | LT06 and LT08 Tape Technology

