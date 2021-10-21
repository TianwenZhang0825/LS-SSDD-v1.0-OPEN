# LS-SSDD-v1.0-OPEN
This is a Large-Scale SAR Ship Detection Dataset-v1.0 (LS-SSDD-v1.0) from Sentinel-1, for small ship detection under large-scale backgrounds. LS-SSDD-v1.0 contains 15 large-scale SAR images whose ground truths are correctly labeled by SAR experts by drawing support from Automatic Identification System (AIS) and Google Earth. To facilitate network training, the large-scale images are directly cut into 9,000 sub-images without bells and whistles, providing convenience for subsequent detection result presentation in large-scale SAR images. 

LS-SSDD-v1.0 is publicly available at:

Google Cloud: https://drive.google.com/file/d/1-fSKYsKr5wuYuXJE2CDX_Yfr4Ylwjfqm/view?usp=sharing

Baidu Cloud:  https://pan.baidu.com/s/1VzqyQHIZL1uPaHmSnRLxPg (Extraction code: 2020)


Detailed dataset description can be found in the following reference [1]. 
# When using LS-SSDD-v1.0, please welcome to cite the following references [1-13]. Many thanks.

[1] Tianwen Zhang, Xiaoling Zhang, Xiao Ke, Xu Zhan, Jun Shi, Shunjun Wei, Dece Pan, Jianwei Li, Hao Su, Yue Zhou and Durga Kumar. “LS-SSDD-v1.0: A Deep Learning Dataset Dedicated to Small Ship Detection from Large-Scale Sentinel-1 SAR Images,” Remote Sensing, 2020.

[2] Zhang, Tianwen, Zhang, Xiaoling, Shi, Jun, & Wei, Shunjun (2020). HyperLi-Net: A hyper-light deep learning network for high-accurate and high-speed ship detection from synthetic aperture radar imagery. ISPRS Journal of Photogrammetry and Remote Sensing, 167, 123-153

[3] Zhang, Tianwen, & Zhang, Xiaoling (2020). ShipDeNet-20: An Only 20 Convolution Layers and <1-MB Lightweight SAR Ship Detector. IEEE Geoscience and Remote Sensing Letters, 1-5, early access.

[4] Tianwen Zhang, Xiaoling Zhang, Jun Shi, Shunjun Wei, Jianguo Wang, Jianwei Li, Hao Su, and Yue Zhou. Balance Scene Learning Mechanism for Offshore and Inshore Ship Detection in SAR Images. IEEE Geoscience and Remote Sensing Letters, 1-5, early access.

[5] Zhang, Tianwen, & Zhang, Xiaoling (2019). High-Speed Ship Detection in SAR Images Based on a Grid Convolutional Neural Network. Remote Sensing, 11, 1206.

[6] Zhang, Tianwen, Zhang, Xiaoling, Shi, Jun, & Wei, Shunjun (2019). Depthwise Separable Convolution Neural Network for High-Speed SAR Ship Detection. Remote Sensing, 11, 2483.

+ [7] Zhang, Tianwen; Zhang, Xiaoling. 2021. "Injection of Traditional Hand-Crafted Features into Modern CNN-based Models for SAR Ship Classification: What, Why, Where, and How" Remote Sensing, 13, no. 11: 2091.

+ [8] Zhang, Tianwen; Zhang, Xiaoling; Ke, X.; Liu, C.; Xu, X.; Zhan, X.; Wang, C.; Ahmad, I.; Zhou, Y.; Pan D.; Li, J.; Su, H.; Shi, J.; Wei, S. HOG-ShipCLSNet: A Novel Deep Learning Network with HOG Feature Fusion for SAR Ship Classification. IEEE Trans. Geosci. Remote. Sens. 2021, 1–21, doi:10.1109/TGRS.2021.3082759.

+ [9] 张晓玲, 张天文, 师君, 等. 基于深度分离卷积神经网络的高速高精度SAR舰船检测[J]. 雷达学报, 2019, 8(6): 841–851. doi: 10.12000/JR19111.
       ZHANG Xiaoling, ZHANG Tianwen, SHI Jun, et al. High-speed and High-accurate SAR ship detection based on a depthwise separable convolution neural network[J]. Journal of Radars, 2019, 8(6): 841–851. doi: 10.12000/JR19111.

+ + [10] Zhang, Tianwen; Zhang, Xiaoling; Ke, Xiao. Quad-FPN: A Novel Quad Feature Pyramid Network for SAR Ship Detection. Remote Sens. 2021, 13 (14), 2771.

+ + [11] Tianwen Zhang , Xiaoling Zhang , A Polarization Fusion Network with Geometric Feature Embedding for SAR Ship Classification, Pattern Recognition (2021), doi: https://doi.org/10.1016/j.patcog.2021.108365
+ + [12] T. Zhang, and X. Zhang, “Squeeze-and-Excitation Laplacian Pyramid Network with Dual-Polarization Feature Fusion for Ship Classification in SAR Images”, IEEE Geoscience and Remote Sensing Letters, early access, 2021, https://doi.org/10.1109/LGRS.2021.3119875
+ + **[13] Tianwen Zhang, Xiaoling Zhang, Chang Liu, Jun Shi, Shunjun Wei, Israr Ahmad, Xu Zhan, Yue Zhou, Dece Pan, Jianwei Li, and Hao Su, "Balance Learning for Ship Detection from Synthetic Aperture Radar Remote Sensing Imagery", ***ISPRS Journal of Photogrammetry and Remote Sensing***, in press, 2021.

# Warning! Warning! Warning!

(1) The baselines of LS-SSDD-v1.0 are run under MMDetection 1.0 version. MMDetection 2.0 version is unknown on LS-SSDD-1.0.

(2) All baselines are slightly adjusted according to actual experiments so as to ensure training success.

++ (3) In reference [1], you should remove the pure background image samples and XML files, so as to verify the effectiveness of PBHT-Mechanism.

# Official-SSDD

https://github.com/TianwenZhang0825/Official-SSDD

T. Zhang, X. Zhang, J. Li, X. Xu, B. Wang, X. Zhan, Y. Xu, X. Ke, T. Zeng, H. Su, I. Ahmad, D. Pan, C. Liu, Y. Zhou, J. Shi, and S. Wei, “SAR Ship Detection Dataset (SSDD): Official Release and Comprehensive Data Analysis,” Remote Sensing, vol. 13, no. 18, 2021.
