# 文章--脑血管分割和脑动脉瘤分割  

查到的一些论文，这方面工作很多，后面会继续更新。

文章都没看，看完会写进一步的笔记。

Sci-Hub地址：[http://sci-hub.tw/](http://sci-hub.tw/)

## 动脉瘤  

>**Brain aneurysm segmentation in CTA and 3DRA using Geodesic Active Regions based on second order prototype features and non parametric density estimation**  
>来源：Proc. SPIE 5747, Medical Imaging 2005: Image Processing, (29 April 2005); doi: 10.1117/12.596237;   
>问题：CTA和3DRA的动脉瘤分割  
>方法：用密度估计和GAR(geodesic active regions)  

>**Development of Image Segmentation Methods for Intracranial Aneurysms**  
>来源：Computational and Mathematical Methods in Medicine Volume 2013, Article ID 715325  
>问题：CTA的动脉瘤分割  
>方法：使用已有的Region Growing Threshold和Chan-Vese model方法，提出新的Threshold-Based Level Set方法  

>**Segmentation and Separation of Cerebral Aneurysms : A Multi-Phase Approach**  
>来源：8th International Symposium on Image and Signal Processing and Analysis (ISPA 2013)  
>问题：CTA的动脉瘤分割  
>方法：先分割血管，手动指定动脉瘤内部的seed，形态学方法分割动脉瘤，水平集方法refine  

>**Intracranial aneurysm segmentation in 3D CT angiography: Method and quantitative validation with and without prior noise filtering**  
>来源：European Journal of Radiology Volume 79, Issue 2, August 2011, Pages 299-304  
>问题：CTA动脉瘤分割  
>方法：GAC(Geodesic Active Contours)  

>**Intracranial Aneurysm Segmentation in 3D CT Angiography: Method and Quantitative Validation**  
>来源：Proceedings of SPIE - The International Society for Optical Engineering 7623 · March 2010  
>问题：CTA的动脉瘤分割  
>方法：GAC(Geodesic Active Contours)  

>**Automatedand segmentation of cerebral vasculature with aneurysms in 3DRA and TOF-MRA using geodesic active regions: An evaluation study**  
>来源：Med Phys. 2011 Jan;38(1):210-22.  
>问题：3DRA和TOF-MRA的动脉瘤分割  
>方法：改进的GAR(geodesic active regions)  

>**A PCA-based approach for brain aneurysm segmentation**  
>来源：Multidimensional Systems and Signal Processing, January 2018, Volume 29, Issue 1, pp 257–277   
>问题：MRA和CTA的动脉瘤分割  
>方法：计算梯度场，然后PCA  

>**Study of the lattice Boltzmann method application to cerebral aneurysm segmentation**  
>来源：博士论文，Medical Imaging. INSA de Lyon, 2014. English.  
>问题：CTA的动脉瘤分割(ch5)  
>方法：栅格Boltzman机分割大的动脉瘤，水平集refine  

>**Segmentation of Intracranial Vessels and Aneurysms in Phase Contrast Magnetic Resonance Angiography Using Multirange Filters and Local Variances**  
>来源：IEEE Trans Image Process. 2013 Mar;22(3):845-59. doi: 10.1109/TIP.2012.2216274. Epub 2012 Aug 30.  
>问题：PC-MRA的动脉瘤分割  
>方法：use multirange filters and local variances to extract intensity-based image features  

>**Vessel and Intracranial Aneurysm Segmentation Using Multi-range Filters and Local Variances**  
>来源：MICCAI 2007: Medical Image Computing and Computer-Assisted Intervention – MICCAI 2007 pp 866-874（上面一篇的会议版）  
>问题：PC-MRA的动脉瘤分割  
>方法：use multirange filters and local variances to extract intensity-based image features  

>**Semi-automatic detection and segmentation algorithm of saccular aneurysms in 2D cerebral DSA images**  
>来源：The Egyptian Journal of Radiology and Nuclear Medicine (2016) 47, 859–865  
>问题：2D投影DSA的动脉瘤分割  
>方法：使用Frangi filter和形态学方法划分区域，对区域分类  

>**Feasibility of Quantification of Intracranial Aneurysm Pulsation with 4D CTA with Manual and Computer-Aided Post-Processing**  
>来源：PLoS One. 2016 Nov 23;11(11):e0166810. doi: 10.1371/journal.pone.0166810. eCollection 2016.  
>问题：讨论手动和计算机辅助后处理4DCTA动脉瘤的可行性  

>**Applying machine learning and image feature extraction techniques to the problem of cerebral aneurysm rupture**  
>来源：这只是一个研究计划，正在实施中  
>问题：用机器学习方法预测动脉瘤破裂  


## 脑血管  

>**A Review on Segmentation and Modeling of Cerebral Vasculature for Surgical Planning**  
>来源：IEEE Access, vol. 5, pp. 15222–15240,2017  
>问题：脑血管分割的review  

>**DeepVesselNet: Vessel Segmentation, Centerline Prediction, and Bifurcation Detection in 3-D Angiographic Volumes**  
>来源：arXiv:1803.09340, 2018 
>问题：MRA血管分割和分支点检测  
>方法：CNN  

>**Cerebral Artery Segmentation with Level Set Methods**  
>来源：Proceedings of Image and Vision Computing New Zealand 2007, pp. 300–304,  
>问题：CTA脑血管分割  
>方法：水平集方法  

>**Brain blood vessel segmentation using line-shaped profiles**  
>来源：Physics in Medicine and Biology 58(22):8041-8061 · October 2013   
>问题：CTA血管和血管畸形分割  
>方法：直线轮廓  

>**Vessel Tortuosity and Brain Tumor Malignancy: A Blinded Study**  
>来源：Academic Radiology Volume 12, Issue 10, October 2005, Pages 1232-1240  
>问题：MRA分割肿瘤处的血管  
>方法：手动给seed，自动得到血管skeleton，然后确定半径，用血管形状的统计特征判断是否是肿瘤  

>**Semi-Supervised Cerebrovascular Segmentation by Hierarchical Convolutional Neural Network**  
>来源：Access IEEE, vol. 6, pp. 67841-67852, 2018  
>问题：MRA的脑血管分割  
>方法：CNN  

>**Atlas-based method for segmentation of cerebral vascular trees from phase-contrast magnetic resonance angiography**  
>来源： SPIE. Medical Imaging, 2004, San Diego, United States. 5370, pp.420-431, 2004  
>问题：PC-MRA脑血管分割  
>方法：区域生长、阈值、Atlas  
