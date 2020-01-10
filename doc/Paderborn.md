# 德国 帕德博恩大学 Bearing DataCenter

## 1.简介
数据下载链接：https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter/
研究所和KAt-DataCenter链接的名称：Christian Lessmeier等，KAt-DataCenter：mb.uni-paderborn.de/kat/datacenter，
设计和驱动技术主席，帕德博恩大学。如需商业用途，请联系作者。


## 2.试验条件

The  test  rig  consists  of  several  modules:  an  electric  motor
(1),  a  torque-measurement  shaft  (2),  a  rolling  bearing  test 
module  (3),  a  flywheel  (4)  and  a  load  motor  (5),  see 
Figure  4.  The ball bearings with different  types of  damage
are  mounted  in  the  bearing  test  module  to  generate  the 
experimental data.
The rolling bearing module provides the possibility of using 
a  test  bearing  under  a  constant  radial  load,  which  can  be 
continuously  adjusted up to 10 kN before each experiment. 
An adapter gives the possibility to measure the  vibration of 
the inner housing, which holds the test bearing in the main 
direction  of  the  load.  The  precise  design  of  the  bearing 
module  and  additional  features,  such  as  the  possibility  to 
simulate  tilting  faults  or  the  use  of  roller  bearings,  are 
described  by  Lessmeier,  Enge-Rosenblatt,  Bayer,  & 
Zimmer, 2014.
The motor  (1)  is  a 425 W Permanent Magnet Synchronous 
Motor  (PMSM)  with  a  nominal  torque  of  T = 1.35 Nm,  a 
nominal  speed  of  n  =  3,000  rpm,  a  nominal  current  of
I = 2.3 A and  a pole pair number  p = 4 (Type SD4CDu8S-009,  Hanning  Elektro-Werke GmbH  &  Co.  KG).  It  is 
operated  by  a  frequency  inverter  (KEB  Combivert  07F5E 
1D-2B0A)  with  a  switching  frequency  of  16 kHz.  This 
standard  industrial  inverter  is  used  to  provide  conditions
similar  to  motors  used  in  the  industry  because  the  current 
signals  show  significant  noise  due  to  the  pulse-width 
modulation  of  the  inverter.  (Lessmeier,  Piantsop  Mbo'o, 
Coenen, Zimmer, & Hameyer, 2012) 
Figure  5  shows  the  schema  of  the  measurement  procedure 
and the  recorded  measurands.  The motor phase currents  are
measured  by  a  current  transducer  of  the  type  LEM  CKSR 
15-NP with an accuracy of 0.8 % of I
PN  = 15 A. The  MCS
are  then filtered by a 25 kHz low-pass filter and converted 
from an analogue to a digital signal with a sampling rate of 
64 kHz.  The  current  transducers  are  used  instead  of  the 
internal  ammeters  of  the  inverter  because  of  their  easy 
signal  access  as  the  currents  can  be  measured  externally 
between motor and inverter. 

At this scientific level of development, a high sampling rate 
and  accuracy  are  additional  advantages  of  this  setup. 
Nevertheless,  the  used  transducers  are  similar  to  the  ones 
commonly  used  in  industry  applications,  so  that  few 
difficulties are expected transferring the research outcomes 
to industrial CM systems. 

The acceleration of the  bearing  housing is  measured at the
adapter at the  top end of  the  rolling bearing module  using a 
piezoelectric  accelerometer  (Model  No.  336C04,  PCB 
Piezotronics,  Inc.)  and  a  charge  amplifier  (Type  5015A, 
Kistler Group) with a low-pass filter at 30 kHz. The signal 
is  digitalized  and  saved  synchronously  to  the  MCS  with  a 
sampling rate of 64 kHz.

The flywheel and the load machine simulate inertia and load 
of the driven equipment,  respectively. The load  motor is a 
PMSM with a nominal torque of 6 Nm (power of 1.7 kW). 
To record the  operating  conditions the following  additional 
parameters  are  measured  synchronously  to  the  motor 
currents and vibration signal  but with lower sampling rates: 
the radial force on the bearings  (Compression and Tension 
Force Sensor  Type K11, Lorenz,  10 kN), the load torque at 
the  torque-measuring  shaft,  the  rotational  speed  (Torque 
Transducer  Model  305,  Magtrol,  2  Nm)  and  the  oil 
temperature in the bearing module. 

The  rotational  speed  of  the  drive  system,  the  radial  force 
onto the test bearing  and the  load torque in the drive  train 
are the main operation  parameters.  To ensure comparability 
of  the  experiments,  fixed  levels  were  defined  for  each 
parameter  (Table  6).  All  three  parameters  were  kept 
constant  for  the  time  of  each  measurement.  At  the  basic 
setup  (Set  no.  0)  of  the  operation  parameters,  the  test  rig
runs at n = 1,500 rpm with a load torque of M = 0.7 Nm and 
a  radial  force  on  the  bearing  of  F  =  1,000  N.  Three 
additional settings are used  by reducing the parameters one 
by one to  n = 900 rpm, M = 0.1 Nm and F = 400 N (set No. 
1-3), respectively. For each of the settings, 20 measurements 
of 4 seconds each were recorded.  Another parameter is the 
temperature, which was kept roughly at 45 -50 °C during all 
experiments.

### Table 6. Operating parameters

| No. | Rotational speed [rpm] | Load Torque [Nm] | Radial force [N] | Name of  Setting |
| :---: |  :---: |  :---: |  :---: |  :---: | 
| 0 | 1500 | 0.7 | 1000 | N15_M07_F10 |
| 1 | 900 | 0.7 | 1000 | N09_M07_F10 | 
| 2 | 1500 | 0.1 | 1000 | N15_M01_F10 |
| 3 | 1500 | 0.7 | 400 | N15_M07_F04 |

### Table 7. Operating parameter of healthy (undamaged)  bearings during run-in period.

| Bearing Code | Run-in Period [h] | Radial Load [N] | Speed [min^-1] |
|  :---: |  :---: |  :---: |  :---: | 
| K001 | >50 |  1000-3000 | 1500-2000 |
| K002 | 19 | 3000 | 2900 |
| K003 | 1 | 3000 | 3000 | 
| K004 | 5 | 3000 | 3000 | 
| K005 | 10 | 3000 | 3000 |
| K006 | 16 | 3000 | 2900  |

## 3.使用情况
* Bin Hasan M. Current based condition monitoring of electromechanical systems. Model-free drive system current monitoring: faults detection and diagnosis through statistical features extraction and support vector machines classification.[D]. University of Bradford, 2013.
* Lessmeier C, Kimotho J K, Zimmer D, et al. Condition monitoring of bearing damage in electromechanical drive systems by 
using motor current signals of electric motors: a benchmark data set for data-driven classification: Proceedings of the
European conference of the prognostics and health management society, 2016[C].[论文链接](https://mb.uni-paderborn.de/fileadmin/kat/PDF/Veroeffentlichungen/20160703_PHME16_CM_bearing.pdf)

* Pandhare V, Singh J, Lee J. Convolutional Neural Network Based Rolling-Element Bearing Fault Diagnosis for Naturally Occurring and Progressing Defects Using Time-Frequency Domain Features[C]//2019 Prognostics and System Health Management Conference (PHM-Paris). IEEE, 2019: 320-326.[论文链接](https://ieeexplore.ieee.org/abstract/document/8756423)

* Zhu Z, Peng G, Chen Y, et al. A convolutional neural network based on a capsule network with strong generalization for bearing fault diagnosis[J]. Neurocomputing, 2019, 323: 62-75.[论文链接](https://www.sciencedirect.com/science/article/pii/S0925231218311238)  
基于强泛化胶囊网络的卷积神经网络用于轴承故障诊断

* Chen Y, Peng G, Xie C, et al. ACDIN: Bridging the gap between artificial and real bearing damages for bearing fault diagnosis[J]. Neurocomputing, 2018, 294: 61-71.[论文链接](https://www.sciencedirect.com/science/article/pii/S092523121830300X)
ACDIN:弥补人工与真实轴承损伤之间的差距，用于轴承故障诊断  

* Wu, J., et al., Sensors Information Fusion System with Fault Detection Based on Multi-Manifold Regularization Neighborhood Preserving Embedding. Sensors, 2019. 19(6): p. 1440. [论文链接](https://www.mdpi.com/1424-8220/19/6/1440)
基于多流形正则化保邻域嵌入的传感器信息融合系统  


## 4.数据特点


[<<返回主目录](../README.md)
