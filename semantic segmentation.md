## Semantic Segmentation
**Higher resoution or denser feature map**

* dilated convolution
* encoder-decoder structure

**Multi-scale contextual information**
* image pyramid
* feature pyramid --- dilation based(DeepLab), pooling based(PSPNet)
* skip connection --- Segnet, Unet, Tiramisu
* multi layer prediction or feature fusion --- FCN, Hypercolumn
* long range dependencies capturing --- MRF, CRF, RNN, self-attentation model

### Fully Supervised Segmentation

&nbsp;&nbsp;&nbsp;&nbsp;**2015**
1. Fully Convolutional Networks for Semantic Segmentation, *Jonathan Long et al, CVPR.* [pdf](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) 
2. Learning Deconvolution Network for Semantic Segmentation, *Hyeonwoo Noh et al, ICCV.* [pdf](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) 
3. Hypercolumns for Object Segmentation and Fine Grained Localization, *Bharath Harihara et al, ICCV.* [pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hariharan_Hypercolumns_for_Object_2015_CVPR_paper.pdf)
4. Semantic Image Segmentation via Deep Parsing Network, *Ziwei Liu et al, ICCV.* [pdf](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Liu_Semantic_Image_Segmentation_ICCV_2015_paper.pdf)
5. SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation, *Vijay Badrinarayanan et al, TPAMI.* [journal pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7803544)
6. DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs , *Liang-Chieh Chen et al, TPAMI.* [journal pdf](https://arxiv.org/pdf/1606.00915.pdf), [conference pdf](https://arxiv.org/pdf/1412.7062.pdf), [slides](http://www.cs.jhu.edu/~ayuille/courses/Stat271-Fall15/ACFrOgDuAYV_m-r3w03VUrSyxI_LUuKsARgO1_3oFZ1ZoGCRfzTcd7hwy2uam1U9e3dQFAFiATizZ6IGoH2jEzla4FsqFEmNhs39CBfYNl4HrEwW9bmEbi8AwfpmioE=_print=true.pdf)
7. ParseNet: Looking Wider to See Better, *Wei Liu et al, ICLR workshop.* [pdf](http://www.cs.unc.edu/~wliu/papers/parsenet.pdf)
8. Deep Hierarchical Parsing for Semantic Segmentation, *Abhishek Sharma et al, CVPR.* [pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sharma_Deep_Hierarchical_Parsing_2015_CVPR_paper.pdf)
9. Semantic Image Segmentation via Deep Parsing Network, *Ziwei Liu et al, ICCV.* [journal pdf](https://arxiv.org/pdf/1606.07230.pdf), [conference pdf](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Liu_Semantic_Image_Segmentation_ICCV_2015_paper.pdf)
10. Conditional Random Fields as Recurrent Neural Networks, *Shuai Zheng et al, ICCV.* [pdf](https://www.robots.ox.ac.uk/~szheng/papers/CRFasRNN.pdf)
11. DeepContour: A Deep Convolutional Feature Learned by Positive-sharing Loss for Contour Detection, *Wei Shen et al, CVPR.* [pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Shen_DeepContour_A_Deep_2015_CVPR_paper.pdf)
12. DeepEdge: A Multi-Scale Bifurcated Deep Network for Top-Down Contour Detection, *Gedas Bertasius et al, CVPR.* [pdf](https://arxiv.org/pdf/1412.1123.pdf)
13. Holistically-Nested Edge Detection, *Saining Xie et al, ICCV.* [pdf](https://arxiv.org/pdf/1504.06375.pdf)
1. Learning High-level Prior with Convolutional Neural Networks for Semantic Segmentation, *Haitian Zheng et al, Arxiv.* [pdf](https://arxiv.org/pdf/1511.06988v1.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2016**
1. Multi-Scale Context Aggregation by Dilated Convolutions, *Fisher Yu et al, ICLR.* [pdf](http://vladlen.info/papers/dilated-convolutions.pdf)
1. Iterative Instance Segmentation, *Ke Li et al, CVPR*. [pdf](https://arxiv.org/pdf/1511.08498.pdf)
2. Bayesian SegNet: Model Uncertainty in Deep Convolutional Encoder-Decoder Architectures for Scene Understanding, *Alex Kendall et al, BMVC.* [pdf](https://arxiv.org/pdf/1511.02680.pdf)
3. Attention to Scale: Scale-aware Semantic Image Segmentation, *Liang-Chieh Chen et al, CVPR.* [pdf](https://arxiv.org/pdf/1511.03339.pdf)
4. RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation, *Guosheng Lin et al, CVPR.* [pdf](https://arxiv.org/pdf/1611.06612.pdf)
5. Laplacian Pyramid Reconstruction and Refinement for Semantic Segmentation, *Golnaz Ghiasi et al, ECCV.* [pdf](https://arxiv.org/pdf/1605.02264.pdf)
6. Attention to Scale: Scale-aware Semantic Image Segmentation, *Liang-Chieh Chen et al, CVPR.* [pdf](https://arxiv.org/pdf/1511.03339.pdf)
7. ENet: A Deep Neural Network Architecture for Real-Time Semantic Segmentation, *Adam Paszke et al, Arxiv.* [pdf](https://arxiv.org/pdf/1606.02147.pdf) &#x1F680;&#x1F680;&#x23F0;
8. Flood-Filling Networks, *Michał Januszewski et al, CoRR*. [pdf](https://arxiv.org/pdf/1611.00421.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2017**
1. Rethinking Atrous Convolution for Semantic Image Segmentation, *Liang-Chieh Chen et al, Technical report.* [pdf](https://arxiv.org/pdf/1706.05587.pdf)
1. Large Kernel Matters —— Improve Semantic Segmentation by Global Convolutional Network, *Chao Peng et al, CVPR.* [pdf](https://arxiv.org/pdf/1703.02719.pdf)
1. Pyramid Scene Parsing Network, *Hengshuang Zhao et al, CVPR.* [pdf](https://arxiv.org/pdf/1612.01105.pdf) &#x1F33E;&#x1F33E;&#x1F349;
1. The One Hundred Layers Tiramisu: Fully Convolutional DenseNets for Semantic Segmentation, *Simon Jegou et al, CVPR.* [pdf](https://arxiv.org/pdf/1611.09326.pdf) &#x1F35A;&#x1F35A;
1. LinkNet: Exploiting Encoder Representations for Efficient Semantic Segmentation, *Abhishek Chaurasia et al, Arxiv.* [pdf](https://arxiv.org/pdf/1707.03718.pdf)
1. Not All Pixels Are Equal: Difficulty-Aware Semantic Segmentation via Deep Layer Cascade, *Xiaoxiao Li et al, CVPR.* [pdf](https://arxiv.org/pdf/1704.01344.pdf) &#x1F340;&#x1F340;&#x1F340;
![img](https://github.com/Zakiyi/Paper-lists/blob/master/figures/2017_Not_All.png)
1. Scale-adaptive Convolutions for Scene Parsing, *Rui Zhang et al, ICCV*. [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhang_Scale-Adaptive_Convolutions_for_ICCV_2017_paper.pdf)
1. Dilated Residual Networks, *Fisher Yu et al, CVPR*. [pdf](https://arxiv.org/pdf/1705.09914.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2018**
1. Deep Layer Aggregation, *Fisher Yu et al, CVPR.* [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Deep_Layer_Aggregation_CVPR_2018_paper.pdf)
1. Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation, *L.C. Chen et al, ECCV.* [pdf](https://arxiv.org/pdf/1802.02611.pdf)
![img](https://github.com/Zakiyi/Paper-lists/blob/master/figures/2018_DeepLab_V3%2B.png)
1. Searching for Efficient Multi-Scale Architectures for Dense Image Prediction, *Liang-Chieh Chen et al, NIPS.* [pdf](https://arxiv.org/pdf/1809.04184.pdf)
1. Pyramid Attention Network for Semantic Segmentation, *Hanchao Li et al, BMVC.* [pdf](https://arxiv.org/pdf/1805.10180.pdf)
1. Learning a Discriminative Feature Network for Semantic Segmentation, *Changqian Yu et al, CVPR.* [pdf](https://arxiv.org/pdf/1804.09337.pdf) &#x1F340;
1. BiSeNet: Bilateral Segmentation Network for Real-time Semantic Segmentation, *Changqian Yu et al, ECCV.* [pdf](https://arxiv.org/pdf/1808.00897.pdf)
1. The Lovasz-Softmax loss: A tractable surrogate for the optimization of the intersection-over-union measure in neural networks, *Maxim Berman et al, CVPR.* [pdf](https://arxiv.org/pdf/1705.08790.pdf)
1. Context Contrasted Feature and Gated Multi-scale Aggregation for Scene Segmentation, *Henghui Ding et al, CVPR.* [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ding_Context_Contrasted_Feature_CVPR_2018_paper.pdf) &#x1F340;&#x1F340;&#x1F349;
1. CCNet: Criss-Cross Attention for Semantic Segmentation, *Zilong Huang et al, Arxiv.* [pdf](https://arxiv.org/pdf/1811.11721.pdf)
<img src="https://github.com/Zakiyi/Paper-lists/blob/master/figures/ccnet.png" alt="drawing" width="600"/>
1. DenseASPP for Semantic Segmentation in Street Scenes, *Maoke Yang et al, CVPR.* [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_DenseASPP_for_Semantic_CVPR_2018_paper.pdf) &#x1F33E;&#x1F33E;
<img src="https://github.com/Zakiyi/Paper-lists/blob/master/figures/2018_Dense_ASPP.png" alt="drawing" width="600"/>
1. MultiNet: Real-time Joint Semantic Reasoning for Autonomous Driving, *Marvin Teichmann, IV.* [pdf](https://arxiv.org/pdf/1612.07695v2.pdf)
1. Context Encoding for Semantic Segmentation, *Hang Zhang et al, CVPR.* [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Context_Encoding_for_CVPR_2018_paper.pdf)
1. PSANet: Point-wise Spatial Attention Network for Scene Parsing, *Hengshuang Zhao et al, ECCV.* [pdf](https://hszhao.github.io/papers/eccv18_psanet.pdf)
1. Multi-Scale Context Intertwining for Semantic Segmentation, *Di Lin et al, ECCV.* [pdf](http://openaccess.thecvf.com/content_ECCV_2018/papers/Di_Lin_Multi-Scale_Context_Intertwining_ECCV_2018_paper.pdf)
1. Path Aggregation Network for Instance Segmentation, *Shu Liu et al, CVPR.* [pdf](https://arxiv.org/pdf/1803.01534.pdf)
1. Understanding Convolution for Semantic Segmentation, *Panqu Wang et al, WACV.* [pdf](https://arxiv.org/pdf/1702.08502.pdf)
<img src="https://github.com/Zakiyi/Paper-lists/blob/master/figures/2018_HDC_DUC.png" alt="drawing" width="600"/>
1. The Devil is in the Decoder: Classification, Regression and GANs, *Zbigniew Wojna et al, BMVC* [pdf](https://arxiv.org/pdf/1707.05847.pdf)
1. ESPNet: Efficient Spatial Pyramid of Dilated Convolutions for Semantic Segmentation, *Sachin Mehta et al, ECCV.* [pdf](https://arxiv.org/pdf/1803.06815.pdf) &#x1F680;&#x1F680;&#x23F0;
1. CU-Net: Coupled U-Nets, *Zhiqiang Tang et al, BMVC*. [pdf](https://arxiv.org/pdf/1808.06521.pdf)
<img src="https://github.com/Zakiyi/Paper-lists/blob/master/figures/2018_CUnet.png" alt="drawing" width="600"/>
1. Stacked U-Nets: A No-Frills Approach to Natural Image Segmentation, *Sohil Shah et al, Arxiv*. [pdf](https://arxiv.org/pdf/1804.10343v1.pdf)
1. Smoothed Dilated Convolutions for Improved Dense Prediction, *Zhengyang Wang et al, KDD*. [pdf](https://arxiv.org/pdf/1808.08931.pdf)
1. CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes, *Yuhong Li et al, CVPR*. [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_CSRNet_Dilated_Convolutional_CVPR_2018_paper.pdf)
1. Concurrent Spatial and Channel Squeeze & Excitation in Fully Convolutional Networks, *Abhijit G.R. et al, Arxiv*. [pdf](https://arxiv.org/pdf/1803.02579.pdf)
 ![img](https://github.com/Zakiyi/UNet-family/blob/master/pictures/SCSE.png)
1. A Pyramid CNN for Dense-Leaves Segmentation, *Daniel D. Morris et al, Arxiv.* [pdf](https://arxiv.org/pdf/1804.01646v1.pdf)
1. ExFuse: Enhancing Feature Fusion for Semantic Segmentation, *Zhenli Zhang et al, ECCV.* [pdf](https://arxiv.org/pdf/1804.03821.pdf)
1. Guided Upsampling Network for Real-Time Semantic Segmentation, *Davide Mazzini et al, Arxiv.* [pdf](https://arxiv.org/pdf/1807.07466v1.pdf)
1. Imperfect Segmentation Labels: How Much Do They Matter? *Nicholas Heller et al, Arxiv.* [pdf](https://arxiv.org/pdf/1806.04618.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2019**
1. Hybrid Task Cascade for Instance Segmentation, *Kai Chen et al, CVPR.* [pdf](https://arxiv.org/pdf/1901.07518.pdf)
1. Efficient Smoothing of Dilated Convolutions for Image Segmentation, *Thomas Ziegler et al, Arxiv*. [pdf](https://arxiv.org/pdf/1903.07992.pdf)
1. Decoders Matter for Semantic Segmentation: Data-Dependent Decoding Enables Flexible Feature Aggregation, *Zhi Tian et al, CVPR.* [pdf](https://arxiv.org/pdf/1903.02120v3.pdf)
1. CaseNet: Content-Adaptive Scale Interaction Networks for Scene Parsing, *Xin Jin et al, Arxiv.* [pdf](https://arxiv.org/pdf/1904.08170.pdf)
1. GFF: Gated Fully Fusion for Semantic Segmentation, *Xiangtai Li et al, Arxiv.* [pdf](https://arxiv.org/pdf/1904.01803.pdf)
1. OCNet: Object Context Network for Scene Parsing， *Yuhui Yuan et al, Arxiv.* [pdf](https://arxiv.org/pdf/1809.00916.pdf)
1. A Probabilistic U-Net for Segmentation of Ambiguous Images, *Simon A. A. Kohl et al, Arxiv.* [pdf](https://arxiv.org/pdf/1806.05034.pdf)
1. Multi-scale Autoencoders in Autoencoder for Semantic Image Segmentation, *John Paul T. Yusiong et al, ACIIDS*. [pdf](https://link.springer.com/content/pdf/10.1007%2F978-3-030-14799-0_51.pdf)
1. FastFCN: Rethinking Dilated Convolution in the Backbone for Semantic Segmentation, *Huikai Wu et al, Arxiv.* [pdf](https://arxiv.org/pdf/1903.11816.pdf)
1. CaseNet: Content-Adaptive Scale Interaction Networks for Scene Parsing, *Xin Jin et al, Arxiv.* [pdf](https://arxiv.org/pdf/1904.08170.pdf)
1. Penalizing Top Performers: Conservative Loss for Semantic Segmentation Adaptation, *Xinge Zhu et al, Arxiv*. [pdf](https://arxiv.org/pdf/1809.00903v2.pdf)
1. PyramNet: Point Cloud Pyramid Attention Network and Graph Embedding Module for Classification and Segmentation, *Kang Zhiheng et al, Arxiv*. [pdf](https://arxiv.org/pdf/1906.03299v1.pdf)
1. Self-Supervised Model Adaptation for Multimodal Semantic Segmentation, *Abhinav Valada et al, Arxiv.* [pdf](https://arxiv.org/pdf/1808.03833v3.pdf)
1. Knowledge Adaptation for Efficient Semantic Segmentation, *Tong He et al, Arxiv*. [pdf](https://arxiv.org/pdf/1903.04688.pdf)
1. Gated-SCNN: Gated Shape CNNs for Semantic Segmentation， *Towaki Takikawa et al, Arxiv.* [pdf](https://arxiv.org/pdf/1907.05740.pdf)
1. Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation, *Chenxi Liu et al, CVPR.* [pdf](https://arxiv.org/pdf/1901.02985.pdf)
<img src="https://github.com/Zakiyi/Paper-lists/blob/master/figures/2019_auto_deeplab.png" alt="drawing" width="600"/>
1. ZigZagNet: Fusing Top-Down and Bottom-Up Context for Object Segmentation, *Di Lin et al, CVPR.*[pdf](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lin_ZigZagNet_Fusing_Top-Down_and_Bottom-Up_Context_for_Object_Segmentation_CVPR_2019_paper.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2020**
1. Modeling the Background for Incremental Learning in Semantic Segmentation, *Fabio Cermelli et al, CVPR*.[pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cermelli_Modeling_the_Background_for_Incremental_Learning_in_Semantic_Segmentation_CVPR_2020_paper.pdf)

### Weakly & Semi Supervised Segmentation
&nbsp;&nbsp;&nbsp;&nbsp;**2018**
1. Revisiting Dilated Convolution: A Simple Approach for Weakly- and SemiSupervised Semantic Segmentation, *Y. Wei et al, CVPR*.[pdf](https://arxiv.org/pdf/1805.04574.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;**2020**
1. Semi-Supervised Semantic Segmentation with Cross-Consistency Training, *Yassine Ouali et al, CVPR*.[pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ouali_Semi-Supervised_Semantic_Segmentation_With_Cross-Consistency_Training_CVPR_2020_paper.pdf)
