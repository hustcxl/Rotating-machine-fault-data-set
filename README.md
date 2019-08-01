# Rotating-machine-fault-data-set
Open rotating mechanical fault data set
## 1.简介
众所周知，当下做机械故障诊断研究最基础的就是数据，再先进的方法也离不开数据的检验。笔者通过文献资料收集到如下几个比较常用的数据集并进行整理。鉴于目前尚未见比较全面的数据集整理介绍。数据来自原始研究方，笔者只整理数据获取途径。如果研究中使用了数据集，请按照版权方要求作出相应说明和引用。在此，公开研究数据的研究者表示感谢和致敬。如涉及侵权，请联系我删除（787452269@qq.com）。欢迎相关领域同仁一起交流。很多优秀的论文都有数据分享，本项目保持更新。星标是比较通用的数据集。个别数据集下载可能比较困难，需要的可以邮件联系我，如版权方有要求，述不提供。


注：给索要数据的朋友，希望是真的试过了无法获取再来索要。伸手党确实不受欢迎。另外，也欢迎修改提供公开的新数据源。


## 2.☆CWRU（凯斯西储大学轴承数据中心）
 
* 数据下载连接（https://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website）
CWRU数据集是使用最为广泛的，文献较多。不一一举例。其中University of New South Wales 的Wade A. Smith在2015年进行了比较全面的总结和对比[1]。比较客观的综述和分析了使用数据进行诊断和分析研究的情况。官方网站提供的是.mat格式的数据，MATLAB直接使用比较方便。
* Github上有人分享了在python中自动下载和使用的方法。https://github.com/Litchiware/cwru
* R语言中使用的方法：https://github.com/coldfir3/bearing_fault_analysis
* Smith W A, Randall R B. Rolling element bearing diagnostics using the Case Western Reserve University data: A benchmark study[J]. Mechanical Systems and Signal Processing, 2015,64-65:100-131.
	
## 3.☆MFPT（机械故障预防技术学会）
NRG Systems总工程师Eric Bechhoefer博士代表MFPT组装和准备数据。
* 数据链接：（https://mfpt.org/fault-data-sets/）
* 声学和振动数据库链接（http://data-acoustics.com/measurements/bearing-faults/bearing-2/）
* MATLAB 文档关于MFPT轴承数据的故障诊断举例。
连接（https://ww2.mathworks.cn/help/predmaint/examples/Rolling-Element-Bearing-Fault-Diagnosis.html）
使用该数据集的相比于CWRU少一些。2012年更新。
一些对数据描述的论文[2]。
* Lee D, Siu V, Cruz R, et al. Convolutional neural net and bearing fault analysis[C]//Proceedings of the International Conference on Data Mining (DMIN). The Steering Committee of The World Congress in Computer Science, Computer Engineering and Applied Computing (WorldComp), 2016: 194.

## 4.☆德国Paderborn大学
* 链接：https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter/
* 相关说明及论文[3, 4]。
* Bin Hasan M. Current based condition monitoring of electromechanical systems. Model-free drive system current monitoring: faults detection and diagnosis through statistical features extraction and support vector machines classification.[D]. University of Bradford, 2013.
* Lessmeier C, Kimotho J K, Zimmer D, et al. Condition monitoring of bearing damage in electromechanical drive systems by using motor current signals of electric motors: a benchmark data set for data-driven classification: Proceedings of the European conference of the prognostics and health management society, 2016[C].
## 5.☆FEMTO-ST轴承数据集
* 由FEMTO-ST研究所建立的PHM IEEE 2012数据挑战期间使用的数据集[5-7]。
* FEMTO-ST网站：https://www.femto-st.fr/en
* github链接：https://github.com/wkzs111/phm-ieee-2012-data-challenge-dataset
http://data-acoustics.com/measurements/bearing-faults/bearing-6/
* Porotsky S, Bluvband Z. Remaining useful life estimation for systems with non-trendability behaviour: Prognostics & Health Management, 2012[C].
* Nectoux P, Gouriveau R, Medjaher K, et al. PRONOSTIA: An experimental platform for bearings accelerated degradation tests.: IEEE International Conference on Prognostics and Health Management, PHM'12., 2012[C]. IEEE Catalog Number: CPF12PHM-CDR.
* E. S, H. O, A. S S V, et al. Estimation of remaining useful life of ball bearings using data driven methodologies: 2012 IEEE Conference on Prognostics and Health Management, 2012[C].2012
18-21 June 2012.
## 6.☆辛辛那提IMS
* 数据链接https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
* 相关论文[8, 9]。
* Gousseau W, Antoni J, Girardin F, et al. Analysis of the Rolling Element Bearing data set of the Center for Intelligent Maintenance Systems of the University of Cincinnati: CM2016, 2016[C].
* Qiu H, Lee J, Lin J, et al. Wavelet filter-based weak signature detection method and its application on rolling element bearing prognostics[J]. Journal of Sound and Vibration, 2006,289(4):1066-1090.

## 7.University of Connecticut
* 数据链接：https://figshare.com/articles/Gear_Fault_Data/6127874/1
* 数据描述：
Time domain gear fault vibration data (DataForClassification_TimeDomain)
And Gear fault data after angle-frequency domain synchronous analysis (DataForClassification_Stage0)
Number of gear fault types=9={'healthy','missing','crack','spall','chip5a','chip4a','chip3a','chip2a','chip1a'}
Number of samples per type=104
Number of total samples=9x104=903
The data are collected in sequence, the first 104 samples are healthy, 105th ~208th samples are missing, and etc.
* 相关论文[10]。
* P. C, S. Z, J. T. Preprocessing-Free Gear Fault Diagnosis Using Small Datasets With Deep Convolutional Neural Network-Based Transfer Learning[J]. IEEE Access, 2018,6:26241-26253.

## 8.XJTU-SY Bearing Datasets（西安交通大学 轴承数据集）
由西安交通大学雷亚国课题组王彪博士整理。
* 链接：http://biaowang.tech/xjtu-sy-bearing-datasets/
* 使用数据集的论文[11]。
* B. W, Y. L, N. L, et al. A Hybrid Prognostics Approach for Estimating Remaining Useful Life of Rolling Element Bearings[J]. IEEE Transactions on Reliability, 2018:1-12.  

## 9.东南大学
* github连接：https://github.com/cathysiyu/Mechanical-datasets
由东南大学严如强团队博士生邵思雨完成[12]。“Highly Accurate Machine Fault Diagnosis Using Deep Transfer Learning”
Gearbox dataset is from Southeast University, China. These data are collected from Drivetrain Dynamic Simulator. This dataset contains 2 subdatasets, including bearing data and gear data, which are both acquired on Drivetrain Dynamics Simulator (DDS). There are two kinds of working conditions with rotating speed - load configuration set to be 20-0 and 30-2. Within each file, there are 8rows of signals which represent: 1-motor vibration, 2,3,4-vibration of planetary gearbox in three directions: x, y, and z, 5-motor torque, 6,7,8-vibration of parallel gear box in three directions: x, y, and z. Signals of rows 2,3,4 are all effective.
## 10.Acoustics and Vibration Database（振动与声学数据库）
提供一个收集振动故障数据集的公益性网站链接：http://data-acoustics.com/


## 11.机械设备故障诊断数据集及技术资料大全
有比较多的机械设备故障数据资料：https://mekhub.cn/machine-diagnosis


## 12.CoE Datasets美国宇航局预测数据存储库
* 链接：https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
[藻类跑道数据集] [CFRP复合材料数据集] [铣削数据集] [轴承数据集] [电池数据集] [涡轮风扇发动机退化模拟数据集] [PHM08挑战数据集] [IGBT加速老化Sata集] [投石机]数据集] [FEMTO轴承数据组] [随机电池使用数据组] [电容器电应力数据组] [MOSFET热过载时效数据组] [电容器电应力数据组 -  2] [HIRF电池数据组]

## 13.第三届工业大数据创新竞赛
  需要参赛才能下载数据，数据使用需要获得版权方授权。多台压缩机，汽轮机的转子部件脱落数据。很实用。
   [工业大数据创新平台](http://industrial-bigdata.com/competition/competitionAction!showDetail2019.action?competition.competitionId=5)

## 14.加拿大渥太华大学  
该数据包含在时变转速条件下从不同健康状况的轴承收集的振动信号。总共有36个数据集。对于每个数据集，有两个实验设置：轴承健康状况和变化速度条件。轴承的健康状况包括（i）健康，（ii）内圈缺陷有缺陷，以及（iii）外圈缺陷有缺陷。操作转速条件是（i）增加速度，（ii）减小速度，（iii）增加然后减小速度，以及（iv）减小然后增加速度。因此，设置有12种不同的情况。为了确保数据的真实性，每个实验设置收集3个试验，总共产生36个数据集。每个数据集包含两个通道：'Channel_1' 是由加速度计测量的振动数据，'Channel_2'是由编码器测量的转速数据。所有这些数据都以200,000Hz采样，采样持续时间为10秒。

  * 论文链接：(https://www.sciencedirect.com/science/article/pii/S2352340918314124?via%3Dihub)
  * 数据链接：(https://data.mendeley.com/datasets/v43hmbwxpm/1)
  * 已经发表的论文：[Bearing fault diagnosis under unknown time-varying rotational speed conditions via multiple time-frequency curve extraction](https://www.sciencedirect.com/science/article/pii/S0022460X17307678?via%3Dihub)
  * [A method for tachometer-free and resampling-free bearing fault diagnostics under time-varying speed conditions](https://www.sciencedirect.com/science/article/pii/S026322411831011X)
  
 ## 15. 意大利都灵理工大学轴承数据DIRG_BearingData
 在都灵理工大学机械和航空航天工程系 DIRG实验室设置的钻机收集的数据，专门用于测试高速航空轴承，其加速度采集在可变转速，径向载荷和损伤水平，与温度测量一起，可作为开放存取数据提供。
 * 数据链接:(ftp://ftp.polito.it/people/DIRG_BearingData/)
 * 论文链接:[The Politecnico di Torino rolling bearing test rig: Description and analysis of open access data](https://www.sciencedirect.com/science/article/pii/S0888327018306800?via%3Dihub)
 
 


## 参考文献
* [1]mith W A, Randall R B. Rolling element bearing diagnostics using the Case Western Reserve University data: A benchmark study[J]. Mechanical Systems and Signal Processing, 2015,64-65:100-131.
* [2]rstraete D, Ferrada A, Droguett E L, et al. Deep learning enabled fault diagnosis using time-frequency image analysis of rolling element bearings[J]. Shock and Vibration, 2017,2017.
* [3]	Bin Hasan M. Current based condition monitoring of electromechanical systems. Model-free drive system current monitoring: faults detection and diagnosis through statistical features extraction and support vector machines classification.[D]. University of Bradford, 2013.
* [4]	Lessmeier C, Kimotho J K, Zimmer D, et al. Condition monitoring of bearing damage in electromechanical drive systems by using motor current signals of electric motors: a benchmark data set for data-driven classification: Proceedings of the European conference of the prognostics and health management society, 2016[C].
* [5]	Porotsky S, Bluvband Z. Remaining useful life estimation for systems with non-trendability behaviour: Prognostics & Health Management, 2012[C].
* [6]	Nectoux P, Gouriveau R, Medjaher K, et al. PRONOSTIA: An experimental platform for bearings accelerated degradation tests.: IEEE International Conference on Prognostics and Health Management, PHM'12., 2012[C]. IEEE Catalog Number: CPF12PHM-CDR.
* [7]	E. S, H. O, A. S S V, et al. Estimation of remaining useful life of ball bearings using data driven methodologies: 2012 IEEE Conference on Prognostics and Health Management, 2012[C].2012
18-21 June 2012.
* [8]	Gousseau W, Antoni J, Girardin F, et al. Analysis of the Rolling Element Bearing data set of the Center for Intelligent Maintenance Systems of the University of Cincinnati: CM2016, 2016[C].
* [9]	Qiu H, Lee J, Lin J, et al. Wavelet filter-based weak signature detection method and its application on rolling element bearing prognostics[J]. Journal of Sound and Vibration, 2006,289(4):1066-1090.
* [10]	P. C, S. Z, J. T. Preprocessing-Free Gear Fault Diagnosis Using Small Datasets With Deep Convolutional Neural Network-Based Transfer Learning[J]. IEEE Access, 2018,6:26241-26253.
* [11]	B. W, Y. L, N. L, et al. A Hybrid Prognostics Approach for Estimating Remaining Useful Life of Rolling Element Bearings[J]. IEEE Transactions on Reliability, 2018:1-12.
* [12]	S. S, S. M, R. Y, et al. Highly Accurate Machine Fault Diagnosis Using Deep Transfer Learning[J]. IEEE Transactions on Industrial Informatics, 2019,15(4):2446-2455.

