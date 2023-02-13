# Ourdataset

```
·HCC肝细胞癌（华工医学院）
·肝癌动脉期（广西医科大学二附院）
·肝癌静脉期（广西医科大学二附院）
·肺小结节影像数据
·LITS2017肝脏肿瘤分割挑战数据集（公开数据集）
·CHASEDB1（公开数据集）
·tnbc细胞核（公开数据集）
```
## HCC肝细胞癌（华工医学院）
  HCC肝细胞癌数据集采集于华工医学院，原发性肝细胞癌患者肝癌病灶动脉血供丰富，因此肝癌患者在行肝脏增强CT或增强MRI检查动脉期时，病灶往往表现为明显强化。并且造影剂会随着动脉血快速流出，在门静脉期及延迟期表现为强化明显减弱，在医学上称为“快进快出”，是诊断肝细胞癌的典型影像学表现。
## 数据展示
  该数据集目录下包含动脉期原始图像80张，对应分割图80张；包含静脉期原始图24张，无对应分割图：
  ### 动脉期
```
[original] 
├── patientV1.nii.gz
├── patientV2.nii.gz
├── patientV3.nii.gz
├── patientV4.nii.gz
├── patientV5.nii.gz
├── patientV6.nii.gz
...
├── patientV79.nii.gz
├── patientV80.nii.gz
```  
```
[label] 
├── patientV01_merge.nii.gz
├── patientV02_merge.nii.gz
├── patientV03_merge.nii.gz
├── patientV04_merge.nii.gz
├── patientV05_merge.nii.gz
├── patientV06_merge.nii.gz
...
├── patientV79_merge.nii.gz
├── patientV80_merge.nii.gz
```
### 静脉期
```
[original] 
├── patientV1.nii.gz
├── patientV2.nii.gz
├── patientV3.nii.gz
├── patientV4.nii.gz
├── patientV5.nii.gz
├── patientV6.nii.gz
...
├── patientV23.nii.gz
├── patientV24.nii.gz
```  

## 肝癌动(静)脉期（广西医科大学二附院）
  肝癌动（静）脉期图像收集于广西医科大学二附院：
  动脉期时造影剂通过人体动脉血管，因此动脉血管以及含动脉血管丰富的组织、器官以及病表现为强化显影。
  门静脉期是门静脉血管充盈显影期，这个时期看门静脉比较清晰。
  ## 数据展示
  ### 动脉期
   该数据集目录下包含670张原始图像以及对应的670与之对应的分割图:
```
[original] 
├── patientA1.nii
├── patientA2.nii
├── patientA3.nii
├── patientA4.nii
├── patientA5.nii
├── patientA6.nii
...
├── patientA669.nii
├── patientA670.nii
```  
```
[label] 
├── patientA1_merge.nii
├── patientA2_merge.nii
├── patientA3_merge.nii
├── patientA4_merge.nii
├── patientA5_merge.nii
├── patientA6_merge.nii
...
├── patientA669_merge.nii
├── patientA670_merge.nii
```
### 静脉期
该数据集目录下包含670张原始图像以及对应的670与之对应的分割图:
```
[original] 
├── patientV1.nii
├── patientV2.nii
├── patientV3.nii
├── patientV4.nii
├── patientV5.nii
├── patientV6.nii
...
├── patientV669.nii
├── patientV670.nii
```  
```
[label] 
├── patientV1_merge.nii
├── patientV2_merge.nii
├── patientV3_merge.nii
├── patientV4_merge.nii
├── patientV5_merge.nii
├── patientV6_merge.nii
...
├── patientV669_merge.nii
├── patientV670_merge.nii
```
## 肺小结节影像数据
肺部小结节是一个影像概念，是指直径在三公分以内的实行或非实行病灶在胸片或CT上的表现
## 数据展示
  该数据集目录下包含574个原始图像以及对应的574个分割图：

```
├── xxxxxxx     
│   ├── xxxxxx.nrrd
│   ├── nodule.nii.gz
├── xxxxxxx       
│   ├── xxxxxx.nrrd
│   ├── nodule.nii.gz
├── xxxxxxx       
│   ├── xxxxxx.nrrd
│   ├── nodule.nii.gz
```
## LITS2017肝脏肿瘤分割挑战数据集（公开数据集）

MICCAI 2017 肝脏肿瘤分割挑战数据集，LITS 数据集。LITS 数据集是目前CT图像肝脏与肿瘤分割领域最大也是最为权威的公开数据集，自提出以来几乎所有的先进算法都会使用该数据集进行训练与测试，LITS 数据集中共包含来自6个医疗中心，从不同型号以及不同协议的CT机采样得到的共计201个病例的腹部CT体数据，其中官方训练集包含 131个病例的CT体数据以及肝脏与肝脏肿瘤标注体数据，标注体数据由专业影像科医生完成，具有较高的可信度。官方测试集由剩余的70个病例的体数据组成，标注未公开。
## 数据展示
 这里只有训练集中包含的131个病例的CT体数据以及肝脏与肝脏肿瘤标注体数据
```
[original] 
├── volume-0.nii
├── volume-1.nii
├── volume-2.nii
├── volume-3.nii
├── volume-4.nii
├── volume-5.nii
...
├── volume-129.nii
├── volume-130.nii
```  
```
[label] 
├── segmentation-0.nii
├── segmentation-1.nii
├── segmentation-2.nii
├── segmentation-3.nii
├── segmentation-4.nii
├── segmentation-5.nii
...
├── segmentation-129.nii
├── segmentation-130.nii
```
## Chasedb1（公开数据集）
  Chasedb1 是一个轻量的用于视网膜血管分割的图像数据集。其用于识别和自动分类关键的视网膜特征，分析视网膜血管形态与视网膜及全身性疾病的关系，以便在疾病处于早期阶段时得到及时检测和治疗。
## 数据展示
  CHASEDB1目录下包含14个人的左右眼共28张视网膜原始图像，每张原图对应1张视网膜血管分割图像:
```
[original] 
├── Image_01L.jpg
├── Image_01R.jpg
├── Image_02L.jpg
├── Image_02R.jpg
├── Image_03L.jpg
├── Image_03R.jpg
...
├── Image_14L.jpg
├── Image_14R.jpg
```  
```
[label] 
├── Image_01L_1stHO.png
├── Image_01R_1stHO.png
├── Image_02L_1stHO.png
├── Image_02R_1stHO.png
├── Image_03L_1stHO.png
├── Image_03R_1stHO.png
...
├── Image_14L_1stHO.png
├── Image_14R_1stHO.png
```
使用过程中可自己决定训练集、测试集以及验证集的各自分配数量




