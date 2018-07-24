# HPC-Document
## 主要的参考文献： 
<font size="10">加“★”的为主要的参考资料</font><br>
###  [1.《HPL测试性能仿真与预测》](https://github.com/luluteam-342/HPC-Document/blob/master/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99/1.%E2%98%85HPL%E6%B5%8B%E8%AF%95%E6%80%A7%E8%83%BD%E4%BB%BF%E7%9C%9F%E4%B8%8E%E9%A2%84%E6%B5%8B_%E5%BC%A0%E6%96%87%E5%8A%9B.caj)
	主要介绍了HPL的分块大小NB的理论确定，并对问题规模矩阵的LU分解，包括对各个步骤的时间计算公式进行介绍和性能测试。
### [2.《A Flexible and Portable Large-Scale DGEMM Library for Linpack on Next-Generation Multi-GPU Systems》](https://github.com/luluteam-342/HPC-Document/blob/master/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99/2.%E2%98%85A%20Flexible%20and%20Portable%20Large-Scale%20DGEMM%20Library%20for%20Linpack%20on%20Next-Generation%20Multi-GPU%20Systems.pdf)
	主要介绍了DGEMM在多Gpu中的优化。
### [3.《并行Linpack分析与优化探讨》](https://github.com/luluteam-342/HPC-Document/blob/master/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99/3.%E2%98%85%E5%B9%B6%E8%A1%8Clinpack%E5%88%86%E6%9E%90%E4%B8%8E%E4%BC%98%E5%8C%96%E6%8E%A2%E8%AE%A8.pdf)
	主要介绍Linpack中的LU分解算法的并行思想，对HPL中各个函数的时间占比进行统计。
### [4.《Software Libraries for Linear Algebra Computations on High Performance Computers》](https://github.com/luluteam-342/HPC-Document/blob/master/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99/4.%E2%98%85Software%20Libraries%20for%20Linear%20Algebra%20Computations%20on%20High%20Performance%20Computers.pdf)
	详细介绍了Linpack中矩阵分块的具体算法，包括迭代过程中，矩阵的更新计算和并行化实施。
### [5.《单节点多GPU集群下HPL动态负载均衡优化》](https://github.com/luluteam-342/HPC-Document/blob/master/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99/18.%E5%8D%95%E8%8A%82%E7%82%B9%E5%A4%9AGPU%E9%9B%86%E7%BE%A4%E4%B8%8BHPL%E5%8A%A8%E6%80%81%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E4%BC%98%E5%8C%96.pdf)
	主要介绍了通过对CPU与GPU协同完成DGEMM计算实现加速，并在迭代过程中基于上一次的比例因子R来计算下一次的R。
	
