## Lighting the Darkness in the Deep Learning Era: A Survey, An Online Platform, A New Dataset
This repository provides a unified online platform, **DarkPlatform**, that covers many popular deep learning-based LLIE methods, of which the results can be produced through a user-friend web interface, contains a low-light image and video dataset, **LLIVPhone**, in which the images and videos are taken by various phones' cameras under diverse illumination conditions, and collects deep learning-based low-light image and video enhancement **methods, datasets, and evaluation metrics**. More content and details can be found in our Survey Paper: [Lighting the Darkness in the Deep Learning Era]().

✌We will periodically update the content.  It is welcome to let us know if we miss your work that is published in top-tier Journal or conference. We will add it.✌


## Contents
1. [DarkPlatform](#DarkPlatform)
3. [LLIVPhone Dataset](#LLIVPhone)
4. [Methods](#Methods)
5. [Datasets](#Datasets)
6. [Metrics](#Metrics)
7. [Citation](#Citation)

### DarkPlatform
Currently, the DarkPlatform covers 13 popular deep learning-based LLIE methods including LLNet, LightenNet, Retinex-Net, EnlightenGAN, MBLLEN, KinD, KinD++, TBEFN, DSLR, DRBN, ExCNet, Zero-DCE, and  RRDNet,  where the results of any inputs can be produced through a user-friend web interface. Have fun: [DarkPlatform]().

### LLIVPhone
LLIVPhone dataset contains 78 videos (23,631 images) taken by 11 different phones' cameras including iPhone 6s, iPhone 7, iPhone7 Plus, iPhone8 Plus, iPhone 11, iPhone 11 Pro, iPhone XS, iPhone XR, iPhone SE, Mi 9, OnePlus 5T under diverse illumination conditions (e.g., weak illumination, underexposure, dark, extremely dark, back-lit, non-uniform light, color light sources, etc.) in the indoor and outdoor scenes. The images and videos in LLIVPhone dataset are saved in PNG and MOV formats, respectively.  Anyone can access the [LLIVPhone dataset](). 

### Methods
![Overview](/chronology.png)
|Date|Publication|Title|Abbreviation|Code|Platform|
|---|---|---|---|---|---|
|2017|PR|LLNet: A deep autoencoder approach to natural low-light image enhancement [paper](https://www.sciencedirect.com/science/article/abs/pii/S003132031630125X)|LLNet|[Code](https://github.com/kglore/llnet_color)|Theano|
|20200821|Nick Byrne|A persistent homology-based **topological loss** function for multi-class CNN segmentation of cardiac MRI [arxiv](https://arxiv.org/abs/2008.09585)|STACOM|
|20200720|Boris Shirokikh|**Universal Loss Reweighting** to Balance Lesion Size Inequality in 3D Medical Image Segmentation [arxiv](https://arxiv.org/abs/2007.10033) [(pytorch)](https://arxiv.org/abs/2007.10033)|MICCAI 2020|
|20200708|Gonglei Shi|**Marginal loss and exclusion loss** for partially supervised multi-organ segmentation [(arXiv)](https://arxiv.org/abs/2007.03868)|MedIA|
|20200706|Yuan Lan|An **Elastic Interaction-Based Loss** Function for Medical Image Segmentation [(pytorch)](https://github.com/charrywhite/elastic_interaction_based_loss) [(arXiv)](https://arxiv.org/abs/2007.02663)|MICCAI 2020|
|20200615|Tom Eelbode|Optimization for Medical Image Segmentation: Theory and Practice when evaluating with Dice Score or Jaccard Index|[TMI](https://ieeexplore.ieee.org/document/9116807)|
|20200605|Guotai Wang|**Noise-robust Dice loss:** A Noise-robust Framework for Automatic Segmentation of COVID-19 Pneumonia Lesions from CT Images [(pytorch)](https://github.com/HiLab-git/COPLE-Net)|[TMI](https://ieeexplore.ieee.org/document/9109297)|
|202004|J. H. Moltz|**Contour Dice coefficient (CDC) Loss:** Learning a Loss Function for Segmentation: A Feasibility Study|[ISBI](https://ieeexplore.ieee.org/abstract/document/9098557)|
|202003|Suprosanna Shit|**clDice** -- a Topology-Preserving Loss Function for Tubular Structure Segmentation [(pytorch)](https://github.com/dmitrysarov/clDice)|[arXiv](https://arxiv.org/abs/2003.07311)|
|202002|TBD|**Uncertainty-weighted Loss:** Function for Medical Image Segmentation using Deep Convolutional Neural Network [(paper)](https://openreview.net/forum?id=cJnTwSNBdE)|[MIDL 2020](https://2020.midl.io/)|
|201912|Yuan Xue|Shape-Aware Organ Segmentation by Predicting Signed Distance Maps [(arxiv)](https://arxiv.org/abs/1912.03849) [(pytorch)](https://github.com/JunMa11/SegWithDistMap/blob/master/code/train_LA_AAAISDF.py)|AAAI 2020|
|201912|Xiaoling Hu|**Topology-Preserving** Deep Image Segmentation [(paper)](https://papers.nips.cc/paper/8803-topology-preserving-deep-image-segmentation.pdf) [(pytorch)](https://github.com/HuXiaoling/TopoLoss)|[NeurIPS](https://papers.nips.cc/paper/8803-topology-preserving-deep-image-segmentation)|
|201912|JohannesC.Paetzold|clDice-a Novel Connectivity-Preserving Loss Function for Vessel Segmentation [(paper)](https://profs.etsmtl.ca/hlombaert/public/medneurips2019/27_CameraReadySubmission_cl_dice_neurips_med.pdf)|[MedNeurIPS2019](https://sites.google.com/view/med-neurips-2019)|
|201910|Shuai Zhao|Region Mutual Information Loss for Semantic Segmentation [(paper)](https://papers.nips.cc/paper/9291-region-mutual-information-loss-for-semantic-segmentation) [(pytorch)](https://github.com/ZJULearning/RMI)|[NeurIPS 2019](https://papers.nips.cc/paper/9291-region-mutual-information-loss-for-semantic-segmentation)|
|201910|Shuai Zhao|Correlation Maximized Structural Similarity Loss for Semantic Segmentation [(paper)](https://arxiv.org/abs/1910.08711)|arxiv|
|201908|Pierre-AntoineGanaye|Removing Segmentation Inconsistencies with Semi-Supervised Non-Adjacency Constraint [(paper)](https://www.sciencedirect.com/science/article/pii/S1361841519300866?dgcid=raven_sd_aip_email) [(official pytorch)](https://github.com/trypag/NonAdjLoss)|[Medical Image Analysis](https://www.sciencedirect.com/science/article/pii/S1361841519300866?dgcid=raven_sd_aip_email)|
|201906|Xu Chen|Learning **Active Contour Models** for Medical Image Segmentation [(paper)](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Learning_Active_Contour_Models_for_Medical_Image_Segmentation_CVPR_2019_paper.pdf) [(official-keras)](https://github.com/xuuuuuuchen/Active-Contour-Loss/blob/master/Active-Contour-Loss.py)|CVPR 2019|
|20190422|Davood Karimi|Reducing the **Hausdorff Distance** in Medical Image Segmentation with Convolutional Neural Networks [(paper)](https://arxiv.org/pdf/1904.10030v1.pdf) [(pytorch)](https://github.com/JunMa11/SegWithDistMap/blob/5a67153bc730eb82de396ef63f57594f558e23cd/code/train_LA_HD.py#L106)|[TMI 201907](https://ieeexplore.ieee.org/document/8767031)|
|20190417|Francesco Caliva|**Distance Map Loss** Penalty Term for Semantic Segmentation [(paper)](https://openreview.net/forum?id=B1eIcvS45V)|[MIDL 2019](http://2019.midl.io/)|
|20190411|Su Yang|Major Vessel Segmentation on X-ray Coronary Angiography using Deep Networks with a Novel **Penalty Loss Function** [(paper)](https://openreview.net/forum?id=H1lTh8unKN)|[MIDL 2019](http://2019.midl.io/)|
|20190405|Boah Kim|Multiphase **Level-Set Loss** for Semi-Supervised and Unsupervised Segmentation with Deep Learning [(paper)](https://arxiv.org/pdf/1904.02872.pdf)|arxiv|
|201901|[Seyed Raein Hashemi](https://scholar.google.ca/citations?user=4VEP0fsAAAAJ&hl=en&oi=sra)|**Asymmetric Loss** Functions and Deep Densely Connected Networks for Highly Imbalanced Medical Image Segmentation: Application to Multiple Sclerosis Lesion Detection [(paper)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8573779)|IEEE Access|
|201812|[Hoel Kervadec](https://scholar.google.ca/citations?user=yeFGhfgAAAAJ&hl=zh-CN&oi=sra)|**Boundary loss** for highly unbalanced segmentation [(paper)](https://arxiv.org/pdf/1812.07032.pdf), [(pytorch 1.0)](https://github.com/LIVIAETS/surface-loss)|[MIDL 2019](http://2019.midl.io/)|
|201810|[Nabila Abraham](https://scholar.google.ca/citations?user=OOvooSMAAAAJ&hl=zh-CN&oi=sra)|A Novel **Focal Tversky loss** function with improved Attention U-Net for lesion segmentation [(paper)](https://arxiv.org/pdf/1810.07842.pdf) [(keras)](https://github.com/nabsabraham/focal-tversky-unet)|[ISBI 2019](https://biomedicalimaging.org/2019/)|
|201809|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|**CE+Dice:** nnU-Net: Self-adapting Framework for U-Net-Based Medical Image Segmentation [(paper)](https://arxiv.org/abs/1809.10486)|arxiv|
|20180831|[Ken C. L. Wong](https://scholar.google.ca/citations?hl=zh-CN&user=XjnODToAAAAJ&view_op=list_works&sortby=pubdate)|3D Segmentation with **Exponential Logarithmic Loss** for Highly Unbalanced Object Sizes [(paper)](https://arxiv.org/abs/1809.00076)|MICCAI 2018|
|20180815|[Wentao Zhu](https://www.ics.uci.edu/~wentaoz1/)|**Dice+Focal:** AnatomyNet: Deep Learning for Fast and Fully Automated Whole-volume Segmentation of Head and Neck Anatomy [(arxiv)](https://arxiv.org/abs/1808.05238) [(pytorch)](https://github.com/wentaozhu/AnatomyNet-for-anatomical-segmentation)|[Medical Physics](https://aapm.onlinelibrary.wiley.com/doi/full/10.1002/mp.13300)|
|201806|[Javier Ribera](https://scholar.google.ca/citations?user=TAaovakAAAAJ&hl=zh-CN&oi=sra)|**Weighted Hausdorff Distance:** Locating Objects Without Bounding Boxes [(paper)](https://arxiv.org/abs/1806.07564), [(pytorch)](https://github.com/HaipengXiong/weighted-hausdorff-loss)|CVPR 2019|
|201805|Saeid Asgari Taghanaki|**Combo Loss:** Handling Input and Output Imbalance in Multi-Organ Segmentation [(arxiv)](https://arxiv.org/pdf/1805.02798.pdf) [(keras)](https://github.com/asgsaeid/ComboLoss/blob/master/combo_loss.py)|[Computerized Medical Imaging and Graphics](https://www.sciencedirect.com/science/article/abs/pii/S0895611118305688)|
|201709|[S M Masudur Rahman AL ARIF](https://scholar.google.ca/citations?user=6bgRPC8AAAAJ&hl=en&oi=sra)|**Shape-aware** deep convolutional neural network for vertebrae segmentation [(paper)](http://www.gregslabaugh.net/publications/ArifMSKI-MICCAI2017.pdf)|[MICCAI 2017 Workshop](https://link.springer.com/chapter/10.1007/978-3-319-74113-0_2)|
|201708|[Tsung-Yi Lin](https://scholar.google.ca/citations?user=_BPdgV0AAAAJ&hl=zh-CN&oi=sra)|**Focal Loss** for Dense Object Detection [(paper)](https://arxiv.org/abs/1708.02002), [(code)](https://github.com/facebookresearch/Detectron)|ICCV, TPAMI|
|20170711|[Carole Sudre](https://scholar.google.ca/citations?user=14GfvB4AAAAJ&hl=zh-CN&oi=sra)|**Generalised Dice** overlap as a deep learning loss function for highly unbalanced segmentations [(paper)](https://arxiv.org/abs/1707.03237)|DLMIA 2017|
|20170703|[Lucas Fidon](https://scholar.google.ca/citations?user=GORojioAAAAJ&hl=zh-CN&oi=sra)|**Generalised Wasserstein Dice** Score for Imbalanced Multi-class Segmentation using Holistic Convolutional Networks [(paper)](https://arxiv.org/abs/1707.00478)|MICCAI 2017 BrainLes|
|201705|[Maxim Berman](https://scholar.google.ca/citations?user=RoOng2wAAAAJ&hl=zh-CN&oi=sra)|The **Lovász-Softmax loss:** A tractable surrogate for the optimization of the intersection-over-union measure in neural networks [(paper)](https://arxiv.org/abs/1705.08790), [(code)](https://github.com/bermanmaxim/LovaszSoftmax)|CVPR 2018|
|201701|[Seyed Sadegh Mohseni Salehi](https://scholar.google.ca/citations?user=hTWINokAAAAJ&hl=zh-CN&oi=sra)|**Tversky loss** function for image segmentation using 3D fully convolutional deep networks [(paper)](https://arxiv.org/abs/1706.05721)|MICCAI 2017 MLMI|
|201612|[Md Atiqur Rahman](https://scholar.google.ca/citations?user=tLPerVUAAAAJ&hl=zh-CN&oi=sra)|Optimizing **Intersection-Over-Union** in Deep Neural Networks for Image Segmentation [(paper)](https://www.cs.umanitoba.ca/~ywang/papers/isvc16.pdf)|[2016 International Symposium on Visual Computing](https://link.springer.com/chapter/10.1007/978-3-319-50835-1_22)|
|201608|[Michal Drozdzal](https://scholar.google.es/citations?user=XK_ktwQAAAAJ&hl=en)|**"Dice Loss (without square)"** The Importance of Skip Connections in Biomedical Image Segmentation [(arxiv)](https://arxiv.org/abs/1608.04117)|[DLMIA 2016](https://link.springer.com/chapter/10.1007/978-3-319-46976-8_19)|
|201606|[Fausto Milletari](https://faustomilletari.github.io/)|**"Dice Loss (with square)"** V-net: Fully convolutional neural networks for volumetric medical image segmentation [(arxiv)](https://arxiv.org/abs/1606.04797), [(caffe code)](https://github.com/faustomilletari/VNet)|International Conference on 3D Vision|
|201605|Zifeng Wu|**TopK loss** Bridging Category-level and Instance-level Semantic Image Segmentation [(paper)](https://arxiv.org/abs/1605.06885)|arxiv|
|201511|[Tom Brosch](https://scholar.google.ca/citations?user=KChq7WIAAAAJ&hl=zh-CN&oi=sra)|**"Sensitivity-Specifity loss"** Deep Convolutional Encoder Networks for Multiple Sclerosis Lesion Segmentation [(paper)](http://www.rogertam.ca/Brosch_MICCAI_2015.pdf) [(code)](https://github.com/NifTK/NiftyNet/blob/df0f86733357fdc92bbc191c8fec0dcf49aa5499/niftynet/layer/loss_segmentation.py#L392)|[MICCAI 2015](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_1)|
|201505|[Olaf Ronneberger](https://scholar.google.ca/citations?user=7jrO1NwAAAAJ&hl=zh-CN&oi=sra)|**"Weighted cross entropy"** U-Net: Convolutional Networks for Biomedical Image Segmentation [(paper)](https://arxiv.org/abs/1505.04597)|[MICCAI 2015](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28)|
|201309|[Gabriela Csurka](https://scholar.google.ca/citations?user=PXm1lPAAAAAJ&hl=zh-CN&oi=sra)|What is a good evaluation measure for semantic segmentation? [(paper)](http://www.bmva.org/bmvc/2013/Papers/paper0032/paper0032.pdf)|BMVA 2013|



