# CWRU数据说明
## 1.概述

  由美国凯斯西储大学提供。试验中使用2马力Reliance Electric电动机进行实验，并且在靠近和远离电动机轴承的位置处测量加速度数据。每个实验都仔细记录了电机的实际测试条件以及轴承故障状态。
使用电火花加工（EDM）为电机轴承提供故障。在内滚道，滚动元件（即滚珠）和外滚道处分别引入直径0.007英寸至0.040英寸直径的故障。将故障轴承重新安装到测试电机中，并记录0至3马力（电机速度为1797至1720 RPM）的电机负载的振动数据。


* 数据下载连接(https://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website)
CWRU数据集是使用最为广泛的，文献较多。不一一举例。其中University of New South Wales 的Wade A. Smith在2015年进行了比较全面的总结和对比。比较客观的综述和分析了使用数据进行诊断和分析研究的情况。官方网站提供的是.mat格式的数据，MATLAB直接使用比较方便。
* Github上有人分享了在python中自动下载和使用的方法。https://github.com/Litchiware/cwru
* R语言中使用的方法：https://github.com/coldfir3/bearing_fault_analysis


## 2.试验条件
For the tests, faults ranging in diameter from 0.007 to 0.028 in. (0.18−0.71 mm) were seeded on the drive- and fan-end bearings (SKF deep-groove ball bearings: 6205-2RS JEM and 6203-2RS JEM, respectively) of the motor using electro-discharge machining (EDM). The faults were seeded on the rolling elements and on the inner and outer races, and each faulty bearing was reinstalled (separately) on the test rig, which was then run at constant speed for motor loads of 0−3 horsepower (approximate motor speeds of 1797−1720 rpm). Table 2 shows the relevant bearing details and fault frequencies. During each test, acceleration was measured in the vertical direction on the housing of the drive-end bearing (DE), and in some tests acceleration was also measured in the vertical direction on the fan-end bearing housing (FE) and on the motor supporting base plate (BA). The sample rates used were 12 kHz for some tests and 48 kHz for others, as explained further in Section 3.2. Further details regarding the test set-up can be found at the CWRU Bearing Data Center website.

### Table 2. Bearing details and fault frequencies.
Fault frequencies (multiple of shaft speed)
 
| Position on rig | Model number | BPFI |	BPFO	| FTF | BSF |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Drive end	| SKF 6205-2RS JEM |	5.415	| 3.585 |	0.3983	| 2.357 |
| Fan end	| SKF 6203-2RS JEM	| 4.947	| 3.053	| 0.3816	| 1.994 |

## 3.数据使用情况
选了一些发表在优秀刊物上比较有代表性的论文。当前尚且按照入手的角度不同从基准综述研究，信号处理与特征增强以及分类与模式识别三个方向分类。但是很多论文实际上是相互交叉的。
### 基准研究
* Smith W A, Randall R B. Rolling element bearing diagnostics using the Case Western Reserve University data: A benchmark study[J]. Mechanical Systems and Signal Processing, 2015,64-65:100-131.[论文链接](https://www.sciencedirect.com/science/article/pii/S0888327015002034)
* Boudiaf A, Moussaoui A, Dahane A, et al. A comparative study of various methods of bearing faults diagnosis using the case Western Reserve University data[J]. Journal of Failure Analysis and Prevention, 2016, 16(2): 271-284. [论文链接](https://link.springer.com/article/10.1007/s11668-016-0080-7)
### 信号处理与特征工程

 * Su W, Wang F, Zhu H, et al. Rolling element bearing faults diagnosis based on optimal Morlet wavelet filter and autocorrelation enhancement[J]. Mechanical systems and signal processing, 2010, 24(5): 1458-1472.[论文链接](https://www.sciencedirect.com/science/article/pii/S0888327009003835)  
 基于最优小波滤波和自相关增强的滚动轴承故障诊断方法
 
 * Saidi L, Ali J B, Fnaiech F. Bi-spectrum based-EMD applied to the non-stationary vibration signals for bearing faults diagnosis[J]. ISA transactions, 2014, 53(5): 1650-1660.[论文链接](https://www.sciencedirect.com/science/article/pii/S0019057814001220)  
 基于双谱的emd应用于非平稳振动信号的轴承故障诊断  
 
 * Zhu K, Song X, Xue D. A roller bearing fault diagnosis method based on hierarchical entropy and support vector machine with particle swarm optimization algorithm[J]. Measurement, 2014, 47: 669-675.[论文链接](https://www.sciencedirect.com/science/article/pii/S0263224113004569)  
 提出了一种基于层次熵和支持向量机的滚动轴承故障诊断方法
 
 * Li Y, Wang X, Si S, et al. Entropy based fault classification using the Case Western Reserve University data: A benchmark study[J]. IEEE Transactions on Reliability, 2019.[论文链接](https://ieeexplore.ieee.org/abstract/document/8662701)  
 基于熵的故障分类利用西储大学案例数据:一项基准研究  
 
 * Kedadouche M, Liu Z, Vu V H. A new approach based on OMA-empirical wavelet transforms for bearing fault diagnosis[J]. Measurement, 2016, 90: 292-308.[论文链接](https://www.sciencedirect.com/science/article/pii/S0263224116301361)  
 提出了一种基于经验小波变换的轴承故障诊断方法 
 
 
### 分类与识别

* Raj A S, Murali N. Early classification of bearing faults using morphological operators and fuzzy inference[J]. IEEE Transactions on Industrial Electronics, 2012, 60(2): 567-574.[论文链接](https://ieeexplore.ieee.org/abstract/document/6153367)  
利用形态算子和模糊推理对轴承故障进行早期分类

* Afrasiabi S, Afrasiabi M, Parang B, et al. Real-Time Bearing Fault Diagnosis of Induction Motors with Accelerated Deep Learning Approach[C]//2019 10th International Power Electronics, Drive Systems and Technologies Conference (PEDSTC). IEEE, 2019: 155-159.[论文链接](https://ieeexplore.ieee.org/abstract/document/8697244)  
采用加速深度学习方法对异步电机轴承故障进行实时诊断 

* Zhang R, Tao H, Wu L, et al. Transfer learning with neural networks for bearing fault diagnosis in changing working conditions[J]. IEEE Access, 2017, 5: 14347-14357.[论文链接](https://ieeexplore.ieee.org/abstract/document/7961149)  
基于神经网络的轴承故障转移学习方法，用于轴承在不同工况下的故障诊断

## 3.数据特点
 人为制造的故障，特征明显，诊断相对容易。使用广泛，认可度高。可以作为算法检验的基础数据集。


[<<返回主目录](../README.md)
