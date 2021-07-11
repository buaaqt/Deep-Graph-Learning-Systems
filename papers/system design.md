
# System Design For Deep Graph Learning


[comment]: <> ([Sort by topic]&#40;#System Design For Deep Graph Learning&#41;\)

[comment]: <> ([Sort by time]&#40;./sort_time_system.md&#41;)

[comment]: <> (- [1  Deep Graph Learning Framework]&#40;#1 Deep Graph Learning Framework&#41;)

[comment]: <> (  * [1.1 Static Graph Library]&#40;#1.1 Static Graph Library&#41;)

[comment]: <> (  * [1.2 Dynamic Graph Library]&#40;#1.2 Dynamic Graph Library&#41;)
    
[comment]: <> (- [2  Deep Graph Learning System Design]&#40;#2 Deep Graph Learning System Design&#41;)

[comment]: <> (  * [2.1 GPU System Design]&#40;#2.1 GPU System Design&#41;)

[comment]: <> (  * [2.2 Distributed Sytem Design]&#40;#2.2 Distributed Sytem Design&#41;)
  
[comment]: <> (- [3  Graph System Optimization]&#40;#3 Graph System Optimization&#41;)

[comment]: <> (  * [3.1 Training Algorithm]&#40;#3.1 Training Algorithm&#41;)

[comment]: <> (  * [3.2 Memory Access Optimization]&#40;#3.2 Memory Access Optimization&#41;)

[comment]: <> (  * [3.3 Kernel Optimization]&#40;#3.3 Kernel Optimization&#41;)
    

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