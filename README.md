# Joint-Distribution-Weighted-Alignment

<img src="JDWA.png" width="80%">

Pytorch code for the work "Joint Distribution Weighted Alignment for Multi-Source Domain Adaptation via Kernel Relative Entropy Estimation" published in IEEE Transactions on Multimedia.


This repository provides the Pytorch codes for the work "Joint Weight Optimization for Partial Domain Adaptation via Kernel Statistical Distance Estimation" published in Neural Networks, 2024. The video for introducing this work is available at the Bilibili platform via the link https://www.bilibili.com/video/BV1d9C8Y8EfG/?spm_id_from=333.337.search-card.all.click. Fig. 1 illustrates the main idea of this work. 

Briefly speaking, this work develops a fundamental technique to estimate the statistical distance between the weighted source joint distribution and the target joint distribution from samples. The estimated statistical distance is expressed as a function of the source sample weights, such that the weights can be optimized to minimize the statistical distance and align the joint distributions for the partial domain adaptation problem. 

This repository provides two versions of Pytorch codes. One is with the shallow network model and the pre-extracted deep learning features. Users can run it with the Jupyter notebook "A Quick Demo for the JWO Algorithm.ipynb" and the folder "OfficeHome" (remember to unzip the datasets in the folder). The other is with the deep ResNet50 model and the raw images. See below for instructions on how to run the code.


For the details of this work,  please refer to the paper below: 

@article{Chen2025Joint,  
  author={Sentao Chen},  
  journal={IEEE Transactions on Multimedia},   
  title={Joint Distribution Weighted Alignment for Multi-Source Domain Adaptation via Kernel Relative Entropy Estimation},   
  year={2025},      
  volume = {},      
  pages = {},     
  issn = {},       
  doi = {}     
  }

The Pytorch code is currently maintained by Lisheng Wen. If you have any questions regarding the code, please contact Lisheng Wen via the email lishengwenmail@126.com.
