# Self-Supervised-depth
by kalilia.

# Contents

* [Overview](#0-depth-estimation-overview)
* [Datasets](#*-datasets)
* [SfM based monocular depth](#2-Mono-SfM)
  *  [2017-2019](#2017)
  *  [2020](#2020)
  *  [2021](#2021)
* [Multi-view-Stereo](#3-Multi-view-stereo)
* [SLAM-Odometry](#4-SLAM-Visual-Odometry)
* [depth complementation](#6-depth-estimation-and-complementation)
# 0-depth-estimation-overview
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:------------------------------------------------------------------------------------------:|----|----|----|----|
|      | [ Single Image Depth Estimation: An Overview](https://arxiv.org/pdf/2104.06456.pdf)  ||Istanbul Technical University|:hear_no_evil:||
# *-datasets
|     Tittle                                                                              |yaer|mark|note|
|:------------------------------------------------------------------------------------------:|----|----|----|
| [ nuScenes: A multimodal dataset for autonomous driving](https://arxiv.org/pdf/1903.11027.pdf)        |2018||nuTonomy: an APTIV company|:hear_no_evil:||

# 1-Monocular-depth with Cost Volume
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:------------------------------------------------------------------------------------------:|----|----|----|----|
|NIPS2020      | [ Forget About the LiDAR: Self-Supervised Depth Estimators with MED Probability Volumes](https://arxiv.org/pdf/2008.03633.pdf)  ||Korea Advanced Institute of Science and Technology|:hear_no_evil:|link|
| CVPR2021     |                 [DRO: Deep Recurrent Optimizer for Structure-from-Motion](https://arxiv.org/pdf/2103.13201.pdf)                 ||Alibaba A.I. Labs|:see_no_evil:|link|
|CVPR2021     | [The Temporal Opportunist: Self-Supervised Multi-Frame Monocular Depth](https://arxiv.org/pdf/2104.14540.pdf)|[link](https://github.com/nianticlabs/manydepth)|Niantic|:see_no_evil:||
|CVPR2020   |[Self-supervised Monocular Trained Depth Estimation using Self-attention and Discrete Disparity Volume](https://arxiv.org/pdf/2003.13951.pdf)|[link](https://github.com/sjsu-smart-lab/Self-supervised-Monocular-Trained-Depth-Estimation-using-Self-attention-and-Discrete-Disparity-Volum)|Australian Institute for Machine Learning|:see_no_evil:||
|ECCV2020   |[Feature-metric Loss for Self-supervised Learning of Depth and Egomotion](https://arxiv.org/pdf/2007.10603.pdf)|[link](https://github.com/sconlyshootery/FeatDepth)||:see_no_evil:||

# 2-Mono-SfM
## 2017
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|----|----|
| CVPR2017    |[Semi-Supervised Deep Learning for Monocular Depth Map Prediction](http://arxiv.org/abs/1702.02706)                 ||RWTH Aachen University|:see_no_evil:|
| CVPR2017    |[SfMLearner: Unsupervised Learning of Depth and Ego-Motion from Video](http://arxiv.org/abs/1704.07813)                 |[link](https://github.com/tinghuiz/SfMLearner)|UC Berkeley|:star:|[link](https://www.yuque.com/kalilia/amcd6z/qcevce)|
## 2018
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|----|----|
| CVPR2018    |[DVO: Learning Depth from Monocular Videos using Direct Methods](http://arxiv.org/abs/1712.00175)                 ||Carnegie Mellon University|:see_no_evil:|
| CVPR2018    |[GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose](http://arxiv.org/abs/1803.02276)                 |[link](https://github.com/yzcjtr/GeoNet)|SenseTime Research|:see_no_evil:|
| ECCV2018    |[DF-Net: Unsupervised Joint Learning of Depth and Flow using Cross-Task Consistency](http://arxiv.org/abs/1809.01649)                 |)|Virginia Tech|:see_no_evil:|
| ECCV2018    |[Supervising the new with the old: learning SFM from SFM](https://www.robots.ox.ac.uk/~vedaldi/assets/pubs/klodt18supervising.pdf)                 |)|University of Oxford|:see_no_evil:|
## 2019
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|----|----|
|2019   | [Self-Supervised 3D Keypoint Learning for Ego-motion Estimation](http://arxiv.org/abs/1912.03426)||Toyota Research Institute (TRI)|:see_no_evil:|
|ICRA2019     | [SuperDepth: Self-Supervised, Super-Resolved Monocular Depth Estimation](http://arxiv.org/abs/1810.01849)||Toyota Research Institute (TRI)|:see_no_evil:|
|AAAI2019     | [Depth prediction without the sensors: Leveraging structure for unsupervised learning from monocular videos](http://arxiv.org/abs/1811.06152)||Harvard University/Google Brain|:see_no_evil:|
|ICCV2019     | [Unsupervised High-Resolution Depth Learning From Videos With Dual Networks](http://arxiv.org/abs/2105.02195)||Tsinghua University|:see_no_evil:|
|ICCV2019  | [Self-Supervised Monocular Depth Hints](https://arxiv.org/pdf/1909.09051.pdf)|[link](www.github.com/nianticlabs/depth-hints)|Niantic|:see_no_evil:|
|ICCV2019  | [Monodepth2: Digging into self-supervised monocular depth estimation](http://arxiv.org/abs/1806.01260)|[link](www.github.com/nianticlabs/monodepth2)|UCL/niantic|:star2:|
|NIPS2019   | [SC-SfMLearner: Unsupervised scale-consistent depth and ego-motion learning from monocular video](http://arxiv.org/abs/1908.10553)||University of Adelaide, Australia|:see_no_evil:|
|CVPR2019  | [Competitive Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical Flow and Motion Segmentation](http://arxiv.org/abs/1805.09806)||Max Planck Institute for Intelligent Systems|:see_no_evil:|
|CoRL2019  | [Robust Semi-Supervised Monocular Depth Estimation with Reprojected Distances](https://arxiv.org/pdf/1910.01765.pdf)||Toyota Research Institute (TRI)|:see_no_evil:|
## 2020
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|----|----|
|ECCV2020   | [DeepSFM: Structure From Motion Via Deep Bundle Adjustment](http://arxiv.org/abs/1912.09697)||Fudan University|:see_no_evil:|
|CoRL2020   | [Unsupervised Monocular Depth Learning in Dynamic Scenes](http://arxiv.org/abs/2010.16404)||Google Research|:see_no_evil:|
|CoRL2020   | [Attentional Separation-and-Aggregation Network for Self-supervised Depth-Pose Learning in Dynamic Scenes](http://arxiv.org/abs/2011.09369)||Tsinghua University|:hear_no_evil:|
|3DV2020   | [Neural Ray Surfaces for Self-Supervised Learning of Depth and Ego-motion](http://arxiv.org/abs/2008.06630)||Toyota Research Institute (TRI)|
|ICLR2020   | [Semantically-Guided Representation Learning for Self-Supervised Monocular Depth](http://arxiv.org/abs/2002.12319)||Toyota Research Institute (TRI)|
|CVPR2020   | [On the uncertainty of self-supervised monocular depth estimation](http://arxiv.org/abs/2005.06209)|[link](https://github.com/mattpoggi/mono-uncertainty)|University of Bologna, Italy|:see_no_evil:|
|CVPR2020   | [Towards Better Generalization: Joint Depth-Pose Learning without PoseNet](http://arxiv.org/abs/2004.01314)|[link](https://github.com/B1ueber2y/TrianFlow)|Tsinghua University|:see_no_evil:|[link](https://www.yuque.com/kalilia/amcd6z/ztlpsr)|
|CVPR2020   | [3D Packing for Self-Supervised Monocular Depth Estimation](http://arxiv.org/abs/1905.02693)||Toyota Research Institute (TRI)|:star2:|[link](https://www.yuque.com/kalilia/amcd6z/sfenyx)|
|CVPR2020   | [Self-supervised monocular trained depth estimation using self-attention and discrete disparity volume](http://arxiv.org/abs/2003.13951)||University of Adelaide|:see_no_evil:|
|2020   | [SAFENet: Self-Supervised Monocular Depth Estimation with Semantic-Aware Feature Extraction](http://arxiv.org/abs/2010.02893)|[link](https://github.com/TRI-ML/packnet-sfm)|Toyota Research Institute (TRI)|:see_no_evil:|
|2020   | [Self-Supervised Monocular Depth Estimation : Solving the Dynamic Object Problem by Semantic Guidance](http://arxiv.org/abs/2007.06936)||Technische Universit¨at Braunschweig, Germany|:see_no_evil:|
|IROS2020  | [Toward Hierarchical Self-Supervised Monocular Absolute Depth Estimation for Autonomous Driving Applications](https://arxiv.org/pdf/2004.05560.pdf)|[link](https://github.com/TJ-IPLab/DNet)|Tongji University|:see_no_evil:|
## 2021
| Conference   |     Tittle                                                                              |code|Author|mark|note|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|----|----|
|AAAI2021|HR-Depth : High Resolution Self-Supervised Monocular Depth Estimation|[link](https://github.com/shawLyu/HR-Depth)|Zhejiang University|:star:|[link](https://www.yuque.com/kalilia/amcd6z/ekrber)|
|AAAI2021|[Learning Monocular Depth in Dynamic Scenes via Instance-Aware Projection Consistency](http://arxiv.org/abs/2102.02629)||KAIST|:star:|[link](https://www.yuque.com/kalilia/amcd6z/oz1hqh)|
|CVPR2021     | [Manydepth:The Temporal Opportunist: Self-Supervised Multi-Frame Monocular Depth](https://arxiv.org/pdf/2104.14540.pdf)|[link](http://arxiv.org/abs/2106.03505)|Niantic|:see_no_evil:|
|CVPR2021     | [MonoRec: Semi-Supervised Dense Reconstruction in Dynamic Environments from a Single Moving Camera](http://arxiv.org/abs/2011.11814)|[link](https://vision.in.tum.de/research/monorec)|TUM|:see_no_evil:|
|IROS2021     | [Self-Supervised Scale Recovery for Monocular Depth and Egomotion Estimation](https://arxiv.org/pdf/2009.03787.pdf)||University of Toronto|:see_no_evil:|
|2021     | [Self-supervised Depth Estimation Leveraging Global Perception and Geometric Smoothness Using On-board Videos](http://arxiv.org/abs/2011.11814)||Hong Kong Polytechnic University|:see_no_evil:|
|2021     | [Self-Supervised Structure-from-Motion through Tightly-Coupled Depth and Egomotion Networks](https://arxiv.org/pdf/2106.04007.pdf)||University of Toronto|:see_no_evil:|
|2021     | [Moving SLAM: Fully Unsupervised Deep Learning in Non-Rigid Scenes](http://arxiv.org/abs/2105.02195)||HKUST|:see_no_evil:|
|2021     | [Unsupervised Joint Learning of Depth, Optical Flow, Ego-motion from Video](https://arxiv.org/pdf/2105.14520.pdf)||Tongji University|:see_no_evil:|
|2021     | [Monocular Depth Estimation through Virtual-world Supervision and Real-world SfM Self-Supervision](https://arxiv.org/pdf/2103.12209v1.pdf)|||:see_no_evil:|
|2021     | [Self-Supervised Learning of Depth and Ego- Motion from Video by Alternative Training and Geometric Constraints from 3D to 2D](https://arxiv.org/pdf/2108.01980.pdf)|||:see_no_evil:|
||-update-time-09-13-2021-||||
|ICCV2021     | [Fine-grained Semantics-aware Representation Enhancement for Self-supervised Monocular Depth Estimation](http://arxiv.org/abs/2108.08829)||Seoul National University|:see_no_evil:|
|ICCV2021     | [Regularizing Nighttime Weirdness: Efficient Self-supervised Monocular Depth Estimation in the Dark](https://github.com/w2kun/RNW)||Nanjing University of Science and Technology|:see_no_evil:|
|ICCV2021     | [Self-supervised Monocular Depth Estimation for All Day Images using Domain Separation](http://arxiv.org/abs/2108.07628)||Zhejiang University|:see_no_evil:|
|ICCV2021     | [StructDepth: Leveraging the structural regularities for self-supervised indoor depth estimation](http://arxiv.org/abs/2108.08574)||Shanghai Jiao Tong University|:see_no_evil:|
|Sensors Journal 2021     | [Unsupervised Monocular Depth Perception: Focusing on Moving Objects](http://arxiv.org/abs/2108.13062)||Chinese University of Hong Kong|:see_no_evil:|
|2021     | [R4Dyn: Exploring Radar for Self-Supervised Monocular Depth Estimation of Dynamic Scenes](https://github.com/w2kun/RNW)||TUM|:star:|
|2021     | [Unsupervised Monocular Depth Estimation in Highly Complex Environments](http://arxiv.org/abs/2107.13137)||East China University of Science and Technology|:see_no_evil:|
# 3-Multi-view-stereo
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
|PAMI2008|                 [SGM：Stereo processing by Semi-Global matching and Mutual Information](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=54679C33E714E9151BE8BC102B19A29E?doi=10.1.1.386.5238&rep=rep1&type=pdf)                 ||German Aerospace Cente|:see_no_evil:|
|ECCV2016|                 [Unsupervised CNN for Single View Depth Estimation: Geometry to the Rescue](http://arxiv.org/abs/1603.04992)                 ||University of Adelaide|:see_no_evil:|
|CVPR2017|                 [DispNet: Unsupervised Monocular Depth Estimation with Left-Right Consistency](https://arxiv.org/pdf/1609.03677.pdf)                 ||University College London|:see_no_evil:|
||                 [Cost Volume Pyramid Based Depth Inference for Multi-View Stereo Jiayu](http://arxiv.org/abs/2104.04314)                 |[link](https://github.com/BaiFree/CVP-MVSNet)|Northwestern Polytechnical University|:see_no_evil:|
| CVPR2020    |[Semi-Supervised Deep Learning for Monocular Depth Map Prediction](http://arxiv.org/abs/1912.08329)                 ||Australian National University|:see_no_evil:|
# 4-SLAM-Visual-Odometry
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
| ECCV2014    |                 [LSD-SLAM: Large-Scale Direct Monocular SLAM](https://link.springer.com/content/pdf/10.1007%2F978-3-319-10605-2_54.pdf)                 ||TUM|:see_no_evil:|
| TR2015    |                 [ORB-SLAM: A Versatile and Accurate Monocular SLAM System](http://arxiv.org/abs/1502.00956)                 ||Universidad de Zaragoza|:see_no_evil:|
| 2016    |                 [Direct Visual Odometry using Bit-Planes](https://arxiv.org/pdf/1604.00990.pdf)                 ||Carnegie Mellon University|:see_no_evil:|
| TR2017    |                 [ORB-SLAM2: An Open-Source SLAM System for Monocular, Stereo, and RGB-D Cameras](http://arxiv.org/abs/1610.06475)                 ||Universidad de Zaragoza|:see_no_evil:|
|2016|                 [A Photometrically Calibrated Benchmark For Monocular Visual Odometry](http://arxiv.org/abs/1607.02555)                 ||TUM|:see_no_evil:|

## 2018
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
|PAMI2018|                 [DSO: Direct Sparse Odometry](http://arxiv.org/abs/1607.02565)                 ||TUM|:see_no_evil:|
|IROS2018|                 [LDSO: Direct Sparse Odometry with Loop Closure](http://arxiv.org/abs/1808.01111)                 ||TUM|:see_no_evil:|
| ECCV2018    |                 [Deep Virtual Stereo Odometry:Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry](https://arxiv.org/pdf/1807.02570)                 ||TUM|:see_no_evil:|
|2018|                 [Self-improving visual odometry](http://arxiv.org/abs/1812.03245)                 ||Magic Leap, Inc.|:see_no_evil:|

## 2019
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
|ICLR2019|                 [BA-NET: DENSE BUNDLE ADJUSTMENT NETWORKS](http://arxiv.org/abs/1806.04807)                 ||Simon Fraser University|:see_no_evil:|
|     |                 [TartanVO: A Generalizable Learning-based VO](https://arxiv.org/pdf/2011.00359.pdf)                 |[link](https://github.com/castacks/tartanvo)|Carnegie Mellon University|:see_no_evil:|
| IROS     |                 [D2VO: Monocular Deep Direct Visual Odometry](https://arxiv.org/pdf/2103.13201.pdf)                 |||:see_no_evil:|

## 2020
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
| ECCV2020     |                 [Pseudo RGB-D for Self-Improving Monocular SLAM and Depth Prediction](http://arxiv.org/abs/2004.10681)                 ||IIIT-Delhi|:see_no_evil:|
| CVPR2020     |                 [VOLDOR: Visual Odometry from Log-logistic Dense Optical flow Residuals](http://arxiv.org/abs/2104.06789)                 ||Stevens Institute of Technology|:see_no_evil:|
| 2021    |                 [Generalizing to the Open World: Deep Visual Odometry with Online Adaptation](http://arxiv.org/abs/2103.15279)                 ||Peking University|:see_no_evil:|
| ICRA2021    |                 [SA-LOAM: Semantic-aided LiDAR SLAM with Loop Closure](http://arxiv.org/abs/2106.11516)                 ||Zhejiang University|:see_no_evil:|

# Light-Filed-based-depth


# 6-depth-estimation-and-complementation
| Conference   |     Tittle                                                                              |code|Author|mark|
|--------------|:-------------------------------------------------------------------------------------------:|----|-----|-----|
|| [Sparse Auxiliary Networks for Unified Monocular Depth Prediction and Completion Vitor](http://arxiv.org/abs/2103.16690)   ||Toyota Research Institute (TRI)|:see_no_evil:|
|3DV2019| [Enhancing self-supervised monocular depth estimation with traditional visual odometry](http://arxiv.org/abs/1908.03127)   ||Univrses AB|:see_no_evil:|
|ECCV2020     |[S3Net: Semantic-aware self-supervised depth estimation with monocular videos and synthetic data](https://arxiv.org/pdf/2007.14511.pdf)||UCSD|:see_no_evil:|
