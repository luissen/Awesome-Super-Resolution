# Awesome-Super-Resolution（in progress）

Collect some super-resolution related papers, data and repositories.



## repositories

#### Awesome paper list:

[Single-Image-Super-Resolution](https://github.com/YapengTian/Single-Image-Super-Resolution)

[Super-Resolution.Benckmark](https://github.com/huangzehao/Super-Resolution.Benckmark)

[Video-Super-Resolution](https://github.com/flyywh/Video-Super-Resolution)

[VideoSuperResolution](https://github.com/LoSealL/VideoSuperResolution)

#### Awesome repos:

|                             repo                             | Framework  |
| :----------------------------------------------------------: | :--------: |
| [EDSR-PyTorch](https://github.com/thstkdgus35/EDSR-PyTorch)  |  PyTorch   |
| [Image-Super-Resolution](https://github.com/titu1994/Image-Super-Resolution) |   Keras    |
| [image-super-resolution](https://github.com/idealo/image-super-resolution) |   Keras    |
| [Super-Resolution-Zoo](https://github.com/WolframRhodium/Super-Resolution-Zoo) |   MxNet    |
| [super-resolution](https://github.com/krasserm/super-resolution) |   Keras    |
|  [neural-enhance](https://github.com/alexjc/neural-enhance)  |   Theano   |
|          [srez](https://github.com/david-gpu/srez)           | Tensorflow |
|        [waifu2x](https://github.com/nagadomi/waifu2x)        |   Torch    |
|        [BasicSR](https://github.com/xinntao/BasicSR)         |  PyTorch   |
| [super-resolution](https://github.com/icpm/super-resolution) |  PyTorch   |
| [VideoSuperResolution](https://github.com/LoSealL/VideoSuperResolution) | Tensorflow |
| [video-super-resolution](https://github.com/thangvubk/video-super-resolution) |  Pytorch   |



## Datasets

Note this table is referenced from [here](https://github.com/LoSealL/VideoSuperResolution#link-of-datasets).

|     Name     |   Usage    |                             Link                             |                        Comments                        |
| :----------: | :--------: | :----------------------------------------------------------: | :----------------------------------------------------: |
|     Set5     |    Test    | [download](https://uofi.box.com/shared/static/kfahv87nfe8ax910l85dksyl2q212voc.zip) | [jbhuang0604](https://github.com/jbhuang0604/SelfExSR) |
|    SET14     |    Test    | [download](https://uofi.box.com/shared/static/igsnfieh4lz68l926l8xbklwsnnk8we9.zip) | [jbhuang0604](https://github.com/jbhuang0604/SelfExSR) |
|    BSD100    |    Test    | [download](https://uofi.box.com/shared/static/qgctsplb8txrksm9to9x01zfa4m61ngq.zip) | [jbhuang0604](https://github.com/jbhuang0604/SelfExSR) |
|   Urban100   |    Test    | [download](https://uofi.box.com/shared/static/65upg43jjd0a4cwsiqgl6o6ixube6klm.zip) | [jbhuang0604](https://github.com/jbhuang0604/SelfExSR) |
|   Manga109   |    Test    |       [website](http://www.manga109.org/ja/index.html)       |                                                        |
|   SunHay80   |    Test    | [download](https://uofi.box.com/shared/static/rirohj4773jl7ef752r330rtqw23djt8.zip) | [jbhuang0604](https://github.com/jbhuang0604/SelfExSR) |
|    BSD300    | Train/Val  | [download](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/BSDS300-images.tgz) |                                                        |
|    BSD500    | Train/Val  | [download](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz) |                                                        |
|   91-Image   |   Train    | [download](http://www.ifp.illinois.edu/~jyang29/codes/ScSR.rar) |                          Yang                          |
|  DIV2K2017   | Train/Val  |     [website](https://data.vision.ee.ethz.ch/cvl/DIV2K/)     |                       NTIRE2017                        |
|   Real SR    | Train/Val  | [website](https://competitions.codalab.org/competitions/21439#participate) |                       NTIRE2019                        |
|   Waterloo   |   Train    |   [website](https://ece.uwaterloo.ca/~k29ma/exploration/)    |                                                        |
|     VID4     |    Test    | [download](https://people.csail.mit.edu/celiu/CVPR2011/videoSR.zip) |                        4 videos                        |
|    MCL-V     |   Train    |        [website](http://mcl.usc.edu/mcl-v-database/)         |                       12 videos                        |
|    GOPRO     | Train/Val  | [website](https://github.com/SeungjunNah/DeepDeblur_release) |                   33 videos, deblur                    |
|    CelebA    |   Train    | [website](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  |                      Human faces                       |
|    Sintel    | Train/Val  |       [website](http://sintel.is.tue.mpg.de/downloads)       |                      Optical flow                      |
| FlyingChairs |   Train    | [website](https://lmb.informatik.uni-freiburg.de/resources/datasets/FlyingChairs.en.html#flyingchairs) |                      Optical flow                      |
|  Vimeo-90k   | Train/Test |           [website](http://toflow.csail.mit.edu/)            |                     90k HQ videos                      |

#### Dataset collections

[Benckmark and DIV2K](https://drive.google.com/drive/folders/1-99XFJs_fvQ2wFdxXrnJFcRRyPJYKN0K): Set5, Set14, B100, Urban100, Manga109, DIV2K2017 include bicubic downsamples with x2,3,4,8

[SR_testing_datasets](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip): Test: Set5, Set14, B100, Urban100, Manga109, Historical; Train: T91,General100, BSDS200



## paper

### Non-DL based approach

SCSR: TIP2010, Jianchao Yang et al.[paper](https://ieeexplore.ieee.org/document/5466111/?arnumber=5466111), [code](http://www.ifp.illinois.edu/~jyang29/)

ANR: ICCV2013, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-ICCV-2013.pdf), [code](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)

A+: ACCV 2014, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-ACCV-2014.pdf), [code](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)

IA: CVPR2016, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-CVPR-2016.pdf)

SelfExSR: CVPR2015, Jia-Bin Huang et al. [paper](https://uofi.box.com/shared/static/8llt4ijgc39n3t7ftllx7fpaaqi3yau0.pdf), [code](https://github.com/jbhuang0604/SelfExSR)

NBSRF: ICCV2015, Jordi Salvador et al. [paper](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Salvador_Naive_Bayes_Super-Resolution_ICCV_2015_paper.pdf)

RFL: ICCV2015, Samuel Schulter et al [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Schulter_Fast_and_Accurate_2015_CVPR_paper.pdf), [code](<https://www.tugraz.at/institute/icg/research/team-bischof/samuel-schulter/>)

### DL based approach

Note this table is referenced from [here](https://github.com/LoSealL/VideoSuperResolution/blob/master/README.md#network-list-and-reference-updating)

| Model       | Published                                                    | Code                                                         | Keywords                      |
| ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------- |
| SRCNN       | [ECCV14](https://arxiv.org/abs/1501.00092)                   | [Keras](https://github.com/qobilidop/srcnn)                  | Kaiming                       |
| RAISR       | [arXiv](https://arxiv.org/abs/1606.01299)                    | -                                                            | Google, Pixel 3               |
| ESPCN       | [CVPR16](https://arxiv.org/abs/1609.05158)                   | [Keras](https://github.com/qobilidop/srcnn)                  | Real time/SISR/**VideoSR**    |
| VDSR        | [CVPR16](https://arxiv.org/abs/1511.04587)                   | [Matlab](http://cv.snu.ac.kr/research/VDSR/)                 | Deep, Residual                |
| DRCN        | [CVPR16](https://arxiv.org/abs/1511.04491)                   | [Matlab](http://cv.snu.ac.kr/research/DRCN/)                 | Recurrent                     |
| DRRN        | [CVPR17](http://cvlab.cse.msu.edu/pdfs/Tai_Yang_Liu_CVPR2017.pdf) | [Caffe](https://github.com/tyshiwo/DRRN_CVPR17), [PyTorch](https://github.com/jt827859032/DRRN-pytorch) | Recurrent                     |
| LapSRN      | [CVPR17](http://vllab.ucmerced.edu/wlai24/LapSRN/)           | [Matlab](https://github.com/phoenix104104/LapSRN)            | Huber loss                    |
| IRCNN       | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Learning_Deep_CNN_CVPR_2017_paper.pdf) | [Matlab](https://github.com/cszn/IRCNN)                      |                               |
| EDSR        | [CVPR17](https://arxiv.org/abs/1707.02921)                   | [PyTorch](https://github.com/thstkdgus35/EDSR-PyTorch)       | NTIRE17 Champion              |
| BTSRN       | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Fan_Balanced_Two-Stage_Residual_CVPR_2017_paper.pdf) | -                                                            | NTIRE17                       |
| SelNet      | [CVPR17](https://ieeexplore.ieee.org/document/8014887)       | -                                                            | NTIRE17                       |
| TLSR        | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Xu_Fast_and_Accurate_CVPR_2017_paper.pdf) | -                                                            | NTIRE17                       |
| SRGAN       | [CVPR17](https://arxiv.org/abs/1609.04802)                   | [Tensorflow](https://github.com/tensorlayer/srgan)           | 1st proposed GAN              |
| VESPCN      | [CVPR17](https://arxiv.org/abs/1611.05250)                   | -                                                            | **VideoSR**                   |
| MemNet      | [ICCV17](https://arxiv.org/abs/1708.02209)                   | [Caffe](https://github.com/tyshiwo/MemNet)                   |                               |
| SRDenseNet  | [ICCV17](http://openaccess.thecvf.com/content_ICCV_2017/papers/Tong_Image_Super-Resolution_Using_ICCV_2017_paper.pdf) | -, [PyTorch](https://github.com/wxywhu/SRDenseNet-pytorch)   | Dense                         |
| SPMC        | [ICCV17](https://arxiv.org/abs/1704.02738)                   | [Tensorflow](https://github.com/jiangsutx/SPMC_VideoSR)      | **VideoSR**                   |
| EnhanceNet  | [ICCV17](https://arxiv.org/abs/1612.07919)                   | [TensorFlow](https://github.com/msmsajjadi/EnhanceNet-Code)  | Perceptual Loss               |
| PRSR        | [ICCV17](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dahl_Pixel_Recursive_Super_ICCV_2017_paper.pdf) | [TensorFlow](https://github.com/nilboy/pixel-recursive-super-resolution) | an extension of PixelCNN      |
| AffGAN      | [ICLR17](https://arxiv.org/pdf/1610.04490.pdf)               | -                                                            |                               |
| MS-LapSRN   | [TPAMI18](https://ieeexplore.ieee.org/document/8434354)      | [Matlab](https://github.com/phoenix104104/LapSRN)            | Fast LapSRN                   |
| DCSCN       | [arXiv](https://arxiv.org/abs/1707.05425)                    | [Tensorflow](https://github.com/jiny2001/dcscn-super-resolution) |                               |
| IDN         | [CVPR18](https://arxiv.org/abs/1803.09454)                   | [Caffe](https://github.com/Zheng222/IDN-Caffe)               | Fast                          |
| DSRN        | [CVPR18](http://openaccess.thecvf.com/content_cvpr_2018/papers/Han_Image_Super-Resolution_via_CVPR_2018_paper.pdf) | [TensorFlow](https://github.com/WeiHan3/dsrn/tree/db21d57dfab57de3608f0372e749c6488b6b305d) | Dual state，Recurrent         |
| RDN         | [CVPR18](https://arxiv.org/abs/1802.08797)                   | [Torch](https://github.com/yulunzhang/RDN)                   | Deep, BI-BD-DN                |
| SRMD        | [CVPR18](https://arxiv.org/abs/1712.06116)                   | [Matlab](https://github.com/cszn/SRMD)                       | Denoise/Deblur/SR             |
| DBPN        | [CVPR18](https://arxiv.org/abs/1803.02735)                   | [PyTorch](https://github.com/alterzero/DBPN-Pytorch)         | NTIRE18 Champion              |
| WDSR        | [CVPR18](https://arxiv.org/abs/1808.08718)                   | [PyTorch](https://github.com/JiahuiYu/wdsr_ntire2018)，[TensorFlow](https://github.com/ychfan/tf_estimator_barebone/blob/master/docs/super_resolution.md) | NTIRE18 Champion              |
| ProSRN      | [CVPR18](https://arxiv.org/abs/1804.02900)                   | [PyTorch](https://github.com/fperazzi/proSR)                 | NTIRE18                       |
| ZSSR        | [CVPR18](http://www.wisdom.weizmann.ac.il/~vision/zssr/)     | [Tensorflow](https://github.com/assafshocher/ZSSR)           | Zero-shot                     |
| FRVSR       | [CVPR18](https://arxiv.org/abs/1801.04590)                   | [PDF](https://github.com/msmsajjadi/FRVSR)                   | **VideoSR**                   |
| DUF         | [CVPR18](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jo_Deep_Video_Super-Resolution_CVPR_2018_paper.pdf) | [Tensorflow](https://github.com/yhjo09/VSR-DUF)              | **VideoSR**                   |
| TDAN        | [arXiv](https://arxiv.org/pdf/1812.02898.pdf)                | -                                                            | **VideoSR**，Deformable Align |
| SFTGAN      | [CVPR18](https://arxiv.org/abs/1804.02815)                   | [PyTorch](https://github.com/xinntao/SFTGAN)                 |                               |
| CARN        | [ECCV18](https://arxiv.org/abs/1803.08664)                   | [PyTorch](https://github.com/nmhkahn/CARN-pytorch)           | Lightweight                   |
| RCAN        | [ECCV18](https://arxiv.org/abs/1807.02758)                   | [PyTorch](https://github.com/yulunzhang/RCAN)                | Deep, BI-BD-DN                |
| MSRN        | [ECCV18](http://openaccess.thecvf.com/content_ECCV_2018/papers/Juncheng_Li_Multi-scale_Residual_Network_ECCV_2018_paper.pdf) | [PyTorch](https://github.com/MIVRC/MSRN-PyTorch)             |                               |
| SRFeat      | [ECCV18](http://openaccess.thecvf.com/content_ECCV_2018/papers/Seong-Jin_Park_SRFeat_Single_Image_ECCV_2018_paper.pdf) | [Tensorflow](https://github.com/HyeongseokSon1/SRFeat)       | GAN                           |
| ESRGAN      | [ECCV18](https://arxiv.org/abs/1809.00219)                   | [PyTorch](https://github.com/xinntao/ESRGAN)                 | PRIM18 region 3 Champion      |
| FEQE        | [ECCV18](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Vu_Fast_and_Efficient_Image_Quality_Enhancement_via_Desubpixel_Convolutional_Neural_ECCVW_2018_paper.pdf) | [Tensorflow](https://github.com/thangvubk/FEQE)              | Fast                          |
| NLRN        | [NIPS18](https://papers.nips.cc/paper/7439-non-local-recurrent-network-for-image-restoration.pdf) | [Tensorflow](https://github.com/Ding-Liu/NLRN)               | Non-local, Recurrent          |
| SRCliqueNet | [NIPS18](https://arxiv.org/abs/1809.04508)                   | -                                                            | Wavelet                       |
| CBDNet      | [arXiv](https://arxiv.org/abs/1807.04686)                    | [Matlab](https://github.com/GuoShi28/CBDNet)                 | Blind-denoise                 |
| TecoGAN     | [arXiv](http://arxiv.org/abs/1811.09393)                     | [Tensorflow](https://github.com/thunil/TecoGAN)              | **VideoSR** GAN               |
| RBPN        | [CVPR19](https://arxiv.org/abs/1903.10128)                   | [PyTorch](https://github.com/alterzero/RBPN-PyTorch)         | **VideoSR**                   |
| SRFBN       | [CVPR19](https://arxiv.org/abs/1903.09814)                   | [PyTorch](https://github.com/Paper99/SRFBN_CVPR19)           | Feedback                      |
| MoreMNAS    | [arXiv](https://arxiv.org/pdf/1901.01074.pdf)                | -                                                            | Lightweight，NAS              |
| FALSR       | [arXiv](https://arxiv.org/pdf/1901.07261.pdf)                | [TensorFlow](https://ieeexplore.ieee.org/document/8434354)   | Lightweight，NAS              |
| Meta-SR     | [arXiv](https://arxiv.org/pdf/1903.00875.pdf)                |                                                              | Arbitrary Magnification       |
| AWSRN       | [arXiv](https://arxiv.org/abs/1904.02358)                    | [PyTorch](https://github.com/ChaofWang/AWSRN)                | Lightweight                   |
| OISR        | CVPR19                                                       | [PyTorch](https://github.com/HolmesShuan/OISR-PyTorch)       | ODE-inspired Network          |
| DPSR        | [CVPR19](https://arxiv.org/pdf/1903.12529.pdf)               | [PyTorch](https://github.com/cszn/DPSR)                      |                               |
| DNI         | [CVPR19](https://arxiv.org/pdf/1811.10515.pdf)               | [PyTorch](https://github.com/xinntao/DNI)                    |                               |
| MAANet      | [arXiv](https://arxiv.org/abs/1904.06252)                    |                                                              | Multi-view Aware Attention    |
| RNAN        | [ICLR19](https://openreview.net/pdf?id=HkeGhoA5FX)           | [PyTorch](https://github.com/yulunzhang/RNAN)                | Residual Non-local Attention  |
| FSTRN        | [CVPR19](https://arxiv.org/pdf/1904.02870.pdf)           | -                | **VideoSR**, fast spatio-temporal residual block  |
| MsDNN | [arXiv](https://arxiv.org/pdf/1904.10698.pdf) | [TensorFlow](https://github.com/shangqigao/gsq-image-SR) | NTIRE19  real SR  21th place |
| SAN | [CVPR19](http://www4.comp.polyu.edu.hk/~cslzhang/paper/CVPR19-SAN.pdf) | [Pytorch](https://github.com/daitao/SAN) | Second-order Attention,cvpr19 oral |
| EDVR        | [CVPR19](https://arxiv.org/pdf/1905.02716.pdf)           |   [Pytorch](https://github.com/xinntao/EDVR)              | **Video**, NTIRE19 video restoration and enhancement champions  |
| Ensemble for VSR        | [CVPR19](https://arxiv.org/pdf/1905.02462.pdf)           |   -              | **VideoSR**, NTIRE19 video SR 2nd place  |
| TENet        | [arXiv](https://arxiv.org/pdf/1905.02538.pdf)           |  -              | a Joint Solution for Demosaicking, Denoising and Super-Resolution |
| MCAN        | [arXiv](https://arxiv.org/pdf/1903.07949.pdf)           |  [Pytorch](https://github.com/macn3388/MCAN) | Matrix-in-matrix CAN, Lightweight |
| IKC&SFTMD        | [CVPR19](https://arxiv.org/pdf/1904.03377.pdf)           |  - | Blind Super-Resolution |

#### Super Resolution survey：

[1] Wenming Yang, Xuechen Zhang, Yapeng Tian, Wei Wang, Jing-Hao Xue. Deep Learning for Single Image Super-Resolution: A Brief Review. arxiv, 2018. [paper](https://arxiv.org/pdf/1808.03344.pdf)

[2]Saeed Anwar, Salman Khan, Nick Barnes. A Deep Journey into Super-resolution: A survey. arxiv, 2019.[paper](https://arxiv.org/pdf/1904.07523.pdf)
