# System Design For Deep Graph Learning

[Sort by topic](#System-Design-For-Deep-Graph-Learning)\
[Sort by time](./sort_time_system.md)
- [1 Deep Graph Learning Framework](#1-Deep-Graph-Learning-Framework)
  * [1.1 Static Graph Library](#1.1-Static-Graph-Library)
  * [1.2 Dynamic Graph Library](#1.2-Dynamic-Graph-Library)
    
- [2 Deep Graph Learning System Design](#2-Deep-Graph-Learning-System-Design)
  * [2.1 GPU System Design](#2.1-GPU-System-Design)
  * [2.2 Distributed Sytem Design](#2.2-Distributed-Sytem-Design)
  
- [3 Graph System Optimization](#3-Graph-System-Optimization)
  * [3.1 Training Algorithm](#3.1-Training-Algorithm)
  * [3.2 Memory Access Optimization](#3.2-Memory-Access-Optimization)
  * [3.3 Kernel Optimization](#3.3-Kernel-Optimization)
    





## 1 Deep Graph Learning Framework


---

### 1.1 Static Graph Library

#### [1] [Deep Graph Library: Towards Efficient and Scalable Deep Learning on Graphs](https://arxiv.org/abs/1909.01315v2)
> - Minjie Wang, Lingfan Yu, Da Zheng, Quan Gan, Yu Gai, Zihao Ye, Mufei Li, Jinjing Zhou, Qi Huang, Chao Ma, Ziyue Huang, Qipeng Guo, Hao Zhang, Haibin Lin, Junbo Zhao, Jinyang Li, Alexander Smola, Zheng Zhang.
> - CoRR 2019




### 1.2 Dynamic Graph Library

#### [1] [PyTorch Geometric Temporal: Spatiotemporal Signal Processing with Neural Machine Learning Models](https://arxiv.org/abs/2104.07788)
> - Benedek Rozemberczki, Paul Scherer, Yixuan He, George Panagopoulos, Alexander Riedel, Maria Astefanoaei, Oliver Kiss, Ferenc Beres, Guzmán López, Nicolas Collignon, Rik Sarkar.
> - Arxiv 2021

## 2 Deep Graph Learning System Design

---

### 2.1 GPU System Design

#### [1] [NeuGraph: Parallel Deep Neural Network Computation on Large Graphs](https://www.usenix.org/conference/atc19/presentation/ma)
> - Lingxiao Ma, Zhi Yang, Youshan Miao, Jilong Xue, Ming Wu, Lidong Zhou, Yafei Dai.
> - USENIX ATC 2019


### 2.2 Distributed Sytem Design

#### [1] [Improving the Accuracy, Scalability, and Performance of  Graph Neural Networks with Roc](https://www-cs.stanford.edu/people/matei/papers/2020/mlsys_roc.pdf)
> - Zhihao Jia, Sina Lin, Mingyu Gao, Matei Zaharia, and Alex Aiken.
> - MLSys 2020


## 3 Graph System Optimization

---

### 3.1 Training Algorithm
#### [1] [Reducing Communication in Graph Neural Network Training](https://arxiv.org/abs/2005.03300)
> - Alok Tripathy, Katherine Yelick, Aydin Buluc.
> - SC 2020


### 3.2 Memory Access Optimization
#### [1] [Optimizing Memory Efficiency of Graph Neural Networks on Edge Computing Platforms](https://arxiv.org/abs/2104.03058)
> - Ao Zhou, Jianlei Yang, Yeqi Gao, Tong Qiao, Yingjie Qi, Xiaoyi Wang, Yunli Chen, Pengcheng Dai, Weisheng Zhao, Chunming Hu.
> - RTAS 2021



### 3.3 Kernel Optimization

#### [1] [fuseGNN: accelerating graph convolutional neural network training on GPGPU](https://ieeexplore.ieee.org/document/9256702)
> - Zhaodong Chen, Mingyu Yan, Maohua Zhu, Lei Deng, Guoqi Li, Shuangchen Li, Yuan Xie.
> - ICCAD 2020