# LS-SSDD-v1.0-OPEN
This is a Large-Scale SAR Ship Detection Dataset-v1.0 (LS-SSDD-v1.0) from Sentinel-1, for small ship detection under large-scale backgrounds. LS-SSDD-v1.0 contains 15 large-scale SAR images whose ground truths are correctly labeled by SAR experts by drawing support from Automatic Identification System (AIS) and Google Earth. To facilitate network training, the large-scale images are directly cut into 9,000 sub-images without bells and whistles, providing convenience for subsequent detection result presentation in large-scale SAR images. 

LS-SSDD-v1.0 is publicly available at:

Google Cloud: https://drive.google.com/file/d/1-fSKYsKr5wuYuXJE2CDX_Yfr4Ylwjfqm/view?usp=sharing

Baidu Cloud:  https://pan.baidu.com/s/1VzqyQHIZL1uPaHmSnRLxPg (Extraction code: 2020)


Detailed dataset description can be found in the following reference [1]. When using LS-SSDD-v1.0, please cite the following references [1-6].

[1] Tianwen Zhang, Xiaoling Zhang, Xiao Ke, Xu Zhan, Jun Shi, Shunjun Wei, Dece Pan, Jianwei Li, Hao Su, Yue Zhou and Durga Kumar. “LS-SSDD-v1.0: A Deep Learning Dataset Dedicated to Small Ship Detection from Large-Scale Sentinel-1 SAR Images,” Remote Sensing, 2020.

[2] Zhang, Tianwen, Zhang, Xiaoling, Shi, Jun, & Wei, Shunjun (2020). HyperLi-Net: A hyper-light deep learning network for high-accurate and high-speed ship detection from synthetic aperture radar imagery. ISPRS Journal of Photogrammetry and Remote Sensing, 167, 123-153

[3] Zhang, Tianwen, & Zhang, Xiaoling (2020). ShipDeNet-20: An Only 20 Convolution Layers and <1-MB Lightweight SAR Ship Detector. IEEE Geoscience and Remote Sensing Letters, 1-5, early access.

[4] Tianwen Zhang, Xiaoling Zhang, Jun Shi, Shunjun Wei, Jianguo Wang, Jianwei Li, Hao Su, and Yue Zhou. Balance Scene Learning Mechanism for Offshore and Inshore Ship Detection in SAR Images. IEEE Geoscience and Remote Sensing Letters, 1-5, early access.

[5] Zhang, Tianwen, & Zhang, Xiaoling (2019). High-Speed Ship Detection in SAR Images Based on a Grid Convolutional Neural Network. Remote Sensing, 11, 1206.

[6] Zhang, Tianwen, Zhang, Xiaoling, Shi, Jun, & Wei, Shunjun (2019). Depthwise Separable Convolution Neural Network for High-Speed SAR Ship Detection. Remote Sensing, 11, 2483.

Warning! Warning! Warning!
(1) The baselines of LS-SSDD-v1.0 are run under MMDetection 1.0 version. MMDetection 2.0 version is unknown on LS-SSDD-1.0.
(2) All baselines are slightly adjusted according to actual experiments so as to ensure training success.
