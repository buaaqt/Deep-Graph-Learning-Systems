
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
    

[comment]: <> (## 1 Deep Graph Learning Framework)

[comment]: <> (---)

[comment]: <> (### 1.1 Static Graph Library)

[comment]: <> (#### [1] [Deep Graph Library: Towards Efficient and Scalable Deep Learning on Graphs]&#40;https://arxiv.org/abs/1909.01315v2&#41;)

[comment]: <> (> - Minjie Wang, Lingfan Yu, Da Zheng, Quan Gan, Yu Gai, Zihao Ye, Mufei Li, Jinjing Zhou, Qi Huang, Chao Ma, Ziyue Huang, Qipeng Guo, Hao Zhang, Haibin Lin, Junbo Zhao, Jinyang Li, Alexander Smola, Zheng Zhang.)

[comment]: <> (> - CoRR 2019)




[comment]: <> (### 1.2 Dynamic Graph Library)

[comment]: <> (#### [1] [PyTorch Geometric Temporal: Spatiotemporal Signal Processing with Neural Machine Learning Models]&#40;https://arxiv.org/abs/2104.07788&#41;)

[comment]: <> (> - Benedek Rozemberczki, Paul Scherer, Yixuan He, George Panagopoulos, Alexander Riedel, Maria Astefanoaei, Oliver Kiss, Ferenc Beres, Guzmán López, Nicolas Collignon, Rik Sarkar.)

[comment]: <> (> - Arxiv 2021)



[comment]: <> (## 2 Deep Graph Learning System Design)

[comment]: <> (---)

[comment]: <> (### 2.1 GPU System Design)

[comment]: <> (#### [1] [NeuGraph: Parallel Deep Neural Network Computation on Large Graphs]&#40;https://www.usenix.org/conference/atc19/presentation/ma&#41;)

[comment]: <> (> - Lingxiao Ma, Zhi Yang, Youshan Miao, Jilong Xue, Ming Wu, Lidong Zhou, Yafei Dai.)

[comment]: <> (> - USENIX ATC 2019)


[comment]: <> (### 2.2 Distributed Sytem Design)

[comment]: <> (#### [1] [Improving the Accuracy, Scalability, and Performance of  Graph Neural Networks with Roc]&#40;https://www-cs.stanford.edu/people/matei/papers/2020/mlsys_roc.pdf&#41;)

[comment]: <> (> - Zhihao Jia, Sina Lin, Mingyu Gao, Matei Zaharia, and Alex Aiken.)

[comment]: <> (> - MLSys 2020)


[comment]: <> (## 3 Graph System Optimization)

[comment]: <> (---)

[comment]: <> (### 3.1 Training Algorithm)

[comment]: <> (#### [1] [Reducing Communication in Graph Neural Network Training]&#40;https://arxiv.org/abs/2005.03300&#41;)

[comment]: <> (> - Alok Tripathy, Katherine Yelick, Aydin Buluc.)

[comment]: <> (> - SC 2020)


[comment]: <> (### 3.2 Memory Access Optimization)

[comment]: <> (#### [1] [Optimizing Memory Efficiency of Graph Neural Networks on Edge Computing Platforms]&#40;https://arxiv.org/abs/2104.03058&#41;)

[comment]: <> (> - Ao Zhou, Jianlei Yang, Yeqi Gao, Tong Qiao, Yingjie Qi, Xiaoyi Wang, Yunli Chen, Pengcheng Dai, Weisheng Zhao, Chunming Hu.)

[comment]: <> (> - RTAS 2021)



[comment]: <> (### 3.3 Kernel Optimization)

[comment]: <> (#### [1] [fuseGNN: accelerating graph convolutional neural network training on GPGPU]&#40;https://ieeexplore.ieee.org/document/9256702&#41;)

[comment]: <> (> - Zhaodong Chen, Mingyu Yan, Maohua Zhu, Lei Deng, Guoqi Li, Shuangchen Li, Yuan Xie.)

[comment]: <> (> - ICCAD 2020)