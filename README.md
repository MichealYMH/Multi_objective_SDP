# Multi-objective Software Defect Prediction
Code for the paper "Multi-objective Software Defect Prediction via Multi-source Uncertain Information Fusion and Multi-task Multi-view Learning",
proposed by Minghao Yang, Shunkun Yang, and W. Eric Wong.

Publication: IEEE Transactions on Software Engineering ( Early Access )  
Date of Publication: 03 July 2024  
Paper link: https://ieeexplore.ieee.org/document/10584421  
DOI: 10.1109/TSE.2024.3421591
## Abtract
Effective software defect prediction (SDP) is important for software quality assurance. Numerous advanced SDP methods have been proposed recently. However, how to consider the task correlations and achieve multi-objective SDP accurately and efficiently still remains to be further explored. In this paper, we propose a novel multi-objective SDP method via multi-source uncertain information fusion and multi-task multi-view learning (MTMV) to accurately and efficiently predict the proneness, location, and type of defects. Firstly, multi-view features are extracted from multi-source static analysis results, reflecting uncertain defect location distribution and semantic information. Then, a novel MTMV model is proposed to fully fuse the uncertain defect information in multi-view features and realize effective multi-objective SDP. Specifically, the convolutional GRU encoders capture the consistency and complementarity of multi-source defect information to automatically filter the noise of false and missed alarms, and reduce location and type uncertainty of static analysis results. A global attention mechanism combined with the hard parameter sharing in MTMV fuse features according to their global importance of all tasks for balanced learning. Then, considering the latent task and feature correlations, multiple task-specific decoders jointly optimize all SDP tasks by sharing the learning experience. Through the extensive experiments on 14 datasets, the proposed method significantly improves the prediction performance over 12 baseline methods for all SDP objectives. The average improvements are 30.7%, 31.2%, and 32.4% for defect proneness, location, and type prediction, respectively. Therefore, the proposed multi-objective SDP method can provide more sufficient and precise insights for developers to significantly improve the efficiency of software analysis and testing.
## Detailed Information
### Dataset
The original datasets can be referenced at https://samate.nist.gov/SARD/test-suites.  
The processed datasets are included in this repository.
### Environment
Python == 3.7.5  
Keras == 2.4.3  
numpy == 1.19.1
pandas == 1.3.4  
scikit-learn == 0.24.2  
tensorflow == 2.3.0
## Citation
Minghao Yang, Shunkun Yang, and W. Eric Wong. "Multi-objective Software Defect Prediction via Multi-source Uncertain Information Fusion and Multi-task Multi-view Learning." IEEE Transactions on Software Engineering (2024).
