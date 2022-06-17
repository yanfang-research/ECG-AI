##  简介

 🚀 记录用于ECG-AI的数据集描述。
 
 📢 动态更新中...

##  数据集描述和小结
📘 小结 (推荐版)：
- 疾病种类最多
	- [x] [*PTB-XL 12导联10s 5大类71小类 ECG数据集](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia_MI_other/ptbxl.txt)
	- [x] [BUT PDB 2分钟2导联 22类 ECG数据集](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/BUT-PTB.txt)
	- [x] [(受限) 同济医院12导联10s 20+种心律失常 ECG数据集](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(20)30107-2/fulltext)
	- [x] [(暂无法访问) KURIAS-ECG 12导联10s 10类 高质量ECG数据](https://www.physionet.org/content/kurias-ecg/1.0/)
- 样本量最多
	- [x] [*(私有已授权) S12L-ECG 6类ECG异常 来自811个国家160万人200万ECG](https://www.nature.com/articles/s41467-020-15432-4)
- 导联数最多 (暂未找到公开18导联)
	- [x] [PTB Diagnostic 15导联ECG数据集](https://www.physionet.org/content/ptbdb/1.0.0/)

🔥 详细的数据集描述 (整理版)：
- [心律失常](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Arrhythmia)
- [心律失常+心梗+其它](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Arrhythmia_MI_other)
- [高血压](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Hypertension)
- [心力衰竭](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Heart_failure)
- [心源性猝死 SCD](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Sudden_Cardiac_Death)
- [挑战赛](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Challenge)
- [其它数据](https://github.com/yanfang-research/ECG-AI/tree/main/aux/Other)

🏃 其它综述总结 (参考版)：
- 心律失常
	-  [Paper'2019: Opportunities and Challenges of Deep Learning for ECG Data Database](https://arxiv.org/pdf/2001.01550.pdf)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_paper_1.jpg)

	- [Paper'2021: Deep learning and the electrocardiogram: review ofthe current state-of-the-art](https://academic.oup.com/europace/article/23/8/1179/6132071)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_paper_2.jpg)

	- [Paper'2021: Artificial intelligence-enhanced electrocardiography in cardiovascular disease management](https://www.nature.com/articles/s41569-020-00503-2.pdf)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_paper_3.png)

- 心肌梗死+心律失常+其它
	- Paper'2022: AI for Detecting and Locating Myocardial Infarction by Electrocardiogram
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_paper_4.jpg)

   -  [Paper'2021: Application of artificial intelligencetechniques for automated detection of myocardial infarction: A review](https://arxiv.org/pdf/2107.06179.pdf)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_MI_paper_1.jpg)

    - [Paper'2021: Deep learning analysis of resting electrocardiograms for the detection of myocardial dysfunction,hypertrophy, and ischaemia: a systematic review](https://academic.oup.com/ehjdh/article/2/3/416/6345343?login=true)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_MI_paper_2.jpg)


- 高血压
	- [Paper'2021: A review of machine learning in hypertension detection and blood pressure estimation based on clinical and physiological data](https://www.sciencedirect.com/science/article/pii/S1746809421004109)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_hypertension_paper_1.jpg)

- 心力衰竭
	- [Paper'2019: Computer-aided diagnosis of congestive heart failure using ECG signals -A review](https://www.sciencedirect.com/science/article/abs/pii/S1120179719301115)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_heat_failure_paper_1.png)

- 心源性猝死 SCD
	- [Paper'2020: Identification of Classification Method for Sudden Cardiac Death: A Review](https://ieeexplore.ieee.org/abstract/document/8984465)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_SCD_paper_1.png)

	- [Paper'2021: Automated detection of shockable ECG signals: A review](https://www.sciencedirect.com/science/article/abs/pii/S0020025521004953)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_SCD_paper_2.png)   

- 其他
	- [Paper'2018: Non-Adaptive Methods for Fetal ECG Signal Processing: A Review and Appraisal](https://www.mdpi.com/1424-8220/18/11/3648)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_fecg_paper_1.png)
    
	- [Paper'2021: Towards deep phenotyping pregnancy: a systematic review on artificial intelligence and machine learning methods to improve pregnancy outcomes](https://academic.oup.com/bib/article/22/5/bbaa369/6065792?login=false)
![]()
    
	- [Paper'2021: Deep Learning Methods for Heart Sounds Classification: A Systematic Review](https://www.mdpi.com/1099-4300/23/6/667)
![]()
    - [Paper'2018: Localization and classification of heart beats in phonocardiography signals a comprehensive review](https://link.springer.com/article/10.1186/s13634-018-0545-9)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_PCG_paper_1.png)
    
	- [Paper'2020: Bio-signal Analysis for StressDetection Using Machine Learning Methods: A Review](https://ieeexplore.ieee.org/abstract/document/9277314)
![]()
    - [Paper'2018: A Review of Obstructive Sleep Apnea Detection Approaches](https://ieeexplore.ieee.org/document/8331075)
![]()
    - [Paper'2020: Deep Learning in Physiological Signal Data: A Survey(including:brain disease,function/sleep stage/motion ect.)](https://www.mdpi.com/1424-8220/20/4/969/htm)
![](https://github.com/yanfang-research/ECG-AI/blob/main/aux/Arrhythmia/PNG/Databases_summary_sleep_paper_1.png)
