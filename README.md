# Tree-Based Intrusion Detection System

This repository contains the implementation of a **Tree-Based Intelligent Intrusion Detection System** for Internet of Vehicles (IoV) applications. The system utilizes tree-based machine learning algorithms in an ensemble approach for effective network intrusion detection.

**Published Paper:**  
L. Yang, A. Moubayed, I. Hamieh and A. Shami, "[Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles](https://arxiv.org/pdf/1910.08635.pdf)," in 2019 IEEE Global Communications Conference (GLOBECOM), 2019, pp. 1-6, doi: 10.1109/GLOBECOM38437.2019.9013892.

This implementation focuses on **tree-based machine learning algorithms** including **decision tree, random forest, extra trees, and XGBoost**, combined in a **stacking ensemble** approach for robust intrusion detection.

## Paper Abstract
### Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles
&emsp; The use of autonomous vehicles (AVs) is a promising technology in Intelligent Transportation Systems (ITSs) to improve safety and driving efficiency. Vehicle-to-everything (V2X) technology enables communication among vehicles and other infrastructures. However, AVs and Internet of Vehicles (IoV) are vulnerable to different types of cyber-attacks such as denial of service, spoofing, and sniffing attacks. An intelligent IDS is proposed in this paper for network attack detection that can be applied to not only Controller Area Network (CAN) bus of AVs but also on general IoVs. The proposed IDS utilizes tree-based ML algorithms including decision tree (DT), random forest (RF), extra trees (ET), and Extreme Gradient Boosting (XGBoost). The results from the implementation of the proposed intrusion detection system on standard data sets indicate that the system has the ability to identify various cyber-attacks in the AV networks. Furthermore, the proposed ensemble learning and feature selection approaches enable the proposed system to achieve high detection rate and low computational cost simultaneously.

**<p align="center">Figure 1: The overview of the tree-based IDS model.</p>**
<p align="center">
<img src="./Figures/Tree-based_IDS_Overview.jpg" width="280" />
</p>

## Implementation 
### Dataset 
CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
* Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html  
* For the purpose of displaying the experimental results in Jupyter Notebook, the sampled subsets of CICIDS2017 is used in the sample code. The subsets are in the "data" folder.

CAN-intrusion dataset, a benchmark network security dataset for intra-vehicle intrusion detection
* Publicly available at: https://ocslab.hksecurity.net/Datasets/CAN-intrusion-dataset  
* Can be processed using the same code

### Code  
* [Tree-based_IDS_GlobeCom19.ipynb](Tree-based_IDS_GlobeCom19.ipynb): Implementation of the tree-based intelligent intrusion detection system

### Machine Learning Algorithms  
* Decision Tree (DT)
* Random Forest (RF)
* Extra Trees (ET)
* XGBoost  
* Stacking Ensemble

### Requirements & Libraries  
* Python 3.6+ 
* [scikit-learn](https://scikit-learn.org/stable/)  
* [XGBoost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [pandas](https://pandas.pydata.org/)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)
* [imbalanced-learn](https://imbalanced-learn.org/)

## Contact-Info
Please feel free to contact us for any questions or cooperation opportunities. We will be happy to help.
* Email: [liyanghart@gmail.com](mailto:liyanghart@gmail.com)
* GitHub: [LiYangHart](https://github.com/LiYangHart) and [Western OC2 Lab](https://github.com/Western-OC2-Lab/)
* LinkedIn: [Li Yang](https://www.linkedin.com/in/li-yang-phd-65a190176/)  
* Google Scholar: [Li Yang](https://scholar.google.com.eg/citations?user=XEfM7bIAAAAJ&hl=en) and [OC2 Lab](https://scholar.google.com.eg/citations?user=oiebNboAAAAJ&hl=en)

## Citation
If you find this repository useful in your research, please cite the following article:  

L. Yang, A. Moubayed, I. Hamieh and A. Shami, "Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles," 2019 IEEE Global Communications Conference (GLOBECOM), 2019, pp. 1-6, doi: 10.1109/GLOBECOM38437.2019.9013892.  
```
@INPROCEEDINGS{9013892,
  author={Yang, Li and Moubayed, Abdallah and Hamieh, Ismail and Shami, Abdallah},
  booktitle={2019 IEEE Global Communications Conference (GLOBECOM)}, 
  title={Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles}, 
  year={2019},
  pages={1-6},
  doi={10.1109/GLOBECOM38437.2019.9013892}
  }
```