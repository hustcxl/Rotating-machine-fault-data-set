# 美国辛辛那提大学 IMS 轴承数据集

## 1.简介
* 数据链接https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
* IMS链接： http://www.iucrc.org/center/nsf-iucrc-intelligent-maintenance-systems  
  http://imscenter.net/


## 2.实验介绍

An  AC  motor,  coupled  by  a  rub  belt,  keeps  the  rotation  speed  constant.  The  four 
bearings are  in  the  same  shaft  and  are  forced lubricated  by  a  circulation  system  that 
regulates  the  flow  and  the  temperature.  It  is  announced on  the  provided  “Readme 
Document  for  IMS  Bearing  Data”  in  the  downloaded  file, that  the  test was  stopped 
when the accumulation of debris on a magnetic plug exceeded a certain level indicating 
the possibility of an impending failure.
The four bearings are all of the same type. There are double range pillow blocks 
rolling elements bearing. 

Three (3) data  sets  are  included in the data  packet  (IMS-Rexnord Bearing Data.zip). Each data  set 
describes  a  test-to-failure  experiment.  Each  data  set  consists  of  individual  files  that  are  1-second 
vibration  signal  snapshots  recorded  at  specific  intervals.  Each  file  consists  of  20,480  points  with  the 
sampling rate set at 20 kHz.  The file name indicates when the data was collected. Each record (row) in 
the data file is a data point.  Data collection was facilitated by NI DAQ Card 6062E.  Larger intervals of 
time stamps (showed in file names) indicate resumption of the experiment in the next working day.

### Table 1. Bearing characteristics
- Rexnord ZA-2115 Characteristics 

| Parameter name | imperial | metric|
| :---: | :----- | :---- |
| Pitch diameter | 2.815 inch  | 71.5mm  |
| Rolling element diameter |  0.331 inch | 8.4mm |
| Number of rolling element per row | 16 | 16 |
| Contact angle  | 15.17° | 15.17° |
| Static load | 6000 lbs | 26690 N |




### Set No. 1:
- Recording Duration:   October 22, 2003 12:06:24 to November 25, 2003 23:39:56
- No. of Files:  2,156
- No. of Channels:   8 
- Channel Arrangement:   Bearing 1 – Ch 1&2; Bearing 2 – Ch 3&4; 
                         Bearing 3 – Ch 5&6; Bearing 4 – Ch 7&8.
- File Recording Interval:   Every 10 minutes (except the first 43 files were taken every 5 minutes)
- File Format:   ASCII
- Description:  At  the  end  of  the  test-to-failure  experiment,  inner  race  defect  occurred  in bearing 3 and roller element defect in bearing 4.

### Set No. 2:
- Recording Duration:   February 12, 2004 10:32:39 to February 19, 2004 06:22:39
- No. of Files:  984
- No. of Channels:   4
- Channel Arrangement:   Bearing 1 – Ch 1; Bearing2 – Ch 2; Bearing3 – Ch3; Bearing 4 – Ch 4.
- File Recording Interval:   Every 10 minutes
- File Format:   ASCII
- Description:  At  the  end  of  the  test-to-failure  experiment,  outer  race  failure  occurred  in 
bearing 1.

### Set No. 3
- Recording Duration:   March 4, 2004 09:27:46 to April 4, 2004 19:01:57
- No. of Files:  4,448
- No. of Channels:   4
- Channel Arrangement:   Bearing1 – Ch 1; Bearing2 – Ch 2; Bearing3 – Ch3; Bearing4 – Ch4;
- File Recording Interval:   Every 10 minutes
- File Format:   ASCII
- Description:  At  the  end  of  the  test-to-failure  experiment,  outer  race  failure  occurred  in 
bearing 3.

### Table 2. Datasets description
|  | Number of files | Number of channels | Endurance duration | Duration of  recorded signal | Announced damages at the end of the endurance  |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| Dataset 1 | 2156 | 8 |  49680 min 34 days 12h | 36 min | Bearing 3: inner race Bearing 4: rolling element |
| Dataset 2 | 984  | 4 |  9840 min 6 days 20h | 16 min | Bearing 1: outer race |
| Dataset 3 | 4448 | 4 | 44480 min 31 days 10h | 74 min | Bearing 3: outer race |

### Table 3. Characteristic frequencies of the test rig

| Characteristic frequencies | |
| :--- | :--- |
| Shaft frequency |  33.3 Hz |
| Ball Pass Frequency Outer race (BPFO)  | 236 Hz |
| Ball Pass Frequency Inner race (BPFI)  | 297 Hz |
| Ball Spin Frequency (BSF)   | 278Hz (2x139 Hz) |
| Fundamental Train Frequency (FTF) | 15 Hz |


## 3.使用情况

* Gousseau W, Antoni J, Girardin F, et al. Analysis of the Rolling Element Bearing data set of the Center for Intelligent Maintenance Systems of the University of Cincinnati: CM2016, 2016[C].
* Qiu H, Lee J, Lin J, et al. Wavelet filter-based weak signature detection method and its application on rolling element bearing prognostics[J]. Journal of Sound and Vibration, 2006,289(4):1066-1090.

* A data-driven failure prognostics method based on mixture of Gaussians hidden Markov models, Tobon-Mejia, Diego Alejandro and Medjaher, Kamal and Zerhouni, Noureddine and Tripot, Gerard, Reliability, IEEE Transactions on, Vol. 61 No. 2, 491--503, 2012

* Health condition monitoring of machines based on hidden markov model and contribution analysis, Yu, Jianbo, Instrumentation and Measurement, IEEE Transactions on, Vol. 61 No. 8, 2200--2211, 2012

* Local and nonlocal preserving projection for bearing defect classification and performance assessment, Yu, Jianbo, Industrial Electronics, IEEE Transactions on, Vol. 59 No. 5, 2363--2376, 2012

* Major Challenges in Prognostics: Study on Benchmarking Prognostics Datasets, Eker, OF and Camci, F and Jennions, IK, European Conference of Prognostics and Health Management Society, 2012

* Remaining useful life estimation for systems with non-trendability behaviour, Porotsky, Sergey and Bluvband, Zigmund, Prognostics and Health Management (PHM), 2012 IEEE Conference on, 1--6, 2012

* Logical analysis of maintenance and performance data of physical assets, ID34, Yacout, S, Reliability and Maintainability Symposium (RAMS), 2012 Proceedings-Annual, 1--6, 2012

* Power wind mill fault detection via one-class $\nu$-SVM vibration signal analysis, Martinez-Rego, David and Fontenla-Romero, Oscar and Alonso-Betanzos, Amparo, Neural Networks (IJCNN), The 2011 International Joint Conference on, 511--518, 2011

* cbmLAD-using Logical Analysis of Data in Condition Based Maintenance, Mortada, M-A and Yacout, Soumaya, Computer Research and Development (ICCRD), 2011 3rd International Conference on, 30--34, 2011

* Hidden Markov Models for failure diagnostic and prognostic, Tobon-Mejia, DA and Medjaher, Kamal and Zerhouni, Noureddine and Tripot, G{\'e}rard, Prognostics and System Health Management Conference (PHM-Shenzhen), 2011, 1--8, 2011

* Application of Wavelet Packet Sample Entropy in the Forecast of Rolling Element Bearing Fault Trend, Wang, Fengtao and Zhang, Yangyang and Zhang, Bin and Su, Wensheng, Multimedia and Signal Processing (CMSP), 2011 International Conference on, 12--16, 2011

* A Mixture of Gaussians Hidden Markov Model for failure diagnostic and prognostic, Tobon-Mejia, Diego Alejandro and Medjaher, Kamal and Zerhouni, Noureddine and Tripot, Gerard, Automation Science and Engineering (CASE), 2010 IEEE Conference on, 338--343, 2010

* Wavelet filter-based weak signature detection method and its application on rolling element bearing prognostics, Qiu, Hai and Lee, Jay and Lin, Jing and Yu, Gang, Journal of Sound and Vibration, Vol. 289 No. 4, 1066--1090, 2006

[<<返回主目录](../README.md)
