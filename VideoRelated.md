# Table of Contents
- [Video Super Resolution](#video-super-resolution)
- [Frame Interpolation](#frame-interpolation)
- [Video Enhancement](#video-enhancement)
- [Video Stabilization](#video-stabilization)
- [Video Denoising](#video-denoising)
- [Video Debluring](#video-debluring)
- [Video Dehazing](#video-dehazing)
- [Video Inpainting](#video-inpainting)
- [Useful Resources](#useful-resources)


# Video Super Resolution
#### BasicVSR++ ★
**[Paper]**  (arXiv 2104) BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment <Br>
**[Author]** [Kelvin C.K. Chan](https://ckkelvinchan.github.io/), [Shangchen Zhou](https://shangchenzhou.com/), [Xintao Wang](https://xinntao.github.io/), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/) <Br>
**[[Pytorch-Code](https://github.com/open-mmlab/mmediting)]** <Br>
在BasicVSR的基础上, 使用反复前向后向传播的结构和flow-guided deformable alignment, 提升了性能
	
#### MIMO-VRN
**[Paper]**  (CVPR 2021) Video Rescaling Networks with Joint Optimization Strategies for Downscaling and Upscaling <Br>
**[Author]**  [Yan-Cheng Huang](https://www.linkedin.com/in/hyancheng96),  [Yi-Hsin Chen](mailto:yhchen12101@gmail.com),  [Cheng-You Lu](https://johnnylu305.github.io), [Hui-Po Wang](https://a514514772.github.io), [Wen-Hsiao Peng](https://sites.google.com/g2.nctu.edu.tw/wpeng/cv), [Ching-Chun Huang](http://acm.cs.nctu.edu.tw/Home.aspx)   <Br>
**[[Project](https://ding3820.github.io/MIMO-VRN/)]** **[[Pytorch-Code](https://github.com/ding3820/MIMO-VRN)]** <Br>

#### BasicVSR ★☆
**[Paper]**  (CVPR 2021) BasicVSR: The Search for Essential Components in Video Super-Resolution and Beyond <Br>
**[Author]** [Kelvin C.K. Chan](https://ckkelvinchan.github.io/), [Xintao Wang](https://xinntao.github.io/), [Ke Yu](https://yuke93.github.io/), [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=zh-CN), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/) <Br>
**[[Project](https://ckkelvinchan.github.io/projects/BasicVSR/)]** **[[Pytorch-Code](https://github.com/ckkelvinchan/BasicVSR-IconVSR)]** <Br>
将视频超分分解为propagation, alignment, aggregation和upsampling四部分. 在此基础上设计了BasicVSR网络, 以及加入了两个新设计模块的IconVSR

#### TMNet
**[Paper]**  (CVPR 2021) Temporal Modulation Network for Controllable Space-Time Video Super-Resolution <Br>
**[Author]** Gang Xu, [Jun Xu](https://csjunxu.github.io/), Zhen Li, Liang Wang, [Xing Sun](https://www.sunxing.org/), [Mingming Cheng](http://mmcheng.net/cmm/) <Br>
**[[Pytorch-Code](https://github.com/CS-GangXu/TMNet)]** <Br>

#### FISR
**[Paper]**  (AAAI 2020) FISR: Deep Joint Frame Interpolation and Super-Resolution with A Multi-scale Temporal Loss <Br>
**[Author]** [Soo Ye Kim](https://sites.google.com/view/sooyekim),[Jihyong Oh](https://sites.google.com/view/ozbro/%ED%99%88), [Munchurl Kim](https://www.viclab.kaist.ac.kr/) <Br>
**[[TF-Code](https://github.com/JihyongOh/FISR)]** <Br>
	
#### STARnet ★★
**[Paper]**  (CVPR 2020) Space-Time-Aware Multi-Resolution Video Enhancement <Br>
**[Author]** [Muhammad Haris](https://alterzero.github.io/), [Greg Shakhnarovich](https://ttic.uchicago.edu/~gregory/), [Norimichi Ukita](https://www.toyota-ti.ac.jp/Lab/Denshi/iim/ukita/)<Br>
**[[Project](https://alterzero.github.io/projects/STAR.html)]** **[[Pytorch-Code](https://github.com/alterzero/STARnet)]** <Br>
时空联合超分
	
#### Zooming-Slow-Mo ★☆
**[Paper]** (CVPR 2020) Fast and Accurate One-Stage Space-Time Video Super-Resolution <Br>
**[Author]**  [Xiaoyu Xiang](https://engineering.purdue.edu/people/xiaoyu.xiang.1), [Yapeng Tian](http://yapengtian.org/), [Yulun Zhang](http://yulunzhang.com/), [Yun Fu](http://www1.ece.neu.edu/~yunfu/), [Jan P. Allebach](https://engineering.purdue.edu/~allebach/), [Chenliang Xu](https://www.cs.rochester.edu/~cxu22/) <Br>
**[[Pytorch-Code](https://github.com/Mukosame/Zooming-Slow-Mo-CVPR-2020)]** <Br>
时空联合超分, 基于deformable卷积和ConvLSTM

#### DeepTemporalSR
**[Paper]** (ECCV 2020) Across Scales & Across Dimensions: Temporal Super-Resolution using Deep Internal Learning <Br>
**[Author]** Liad Pollak Zuckerman, Eyal Naor, George Pisha, [Shai Bagon](https://www.weizmann.ac.il/math/bagon/), Michal Irani <Br>
**[[Project](http://www.wisdom.weizmann.ac.il/~vision/DeepTemporalSR/)]**  **[[Pytorch-Code](https://github.com/eyalnaor/DeepTemporalSR)]** <Br>	

#### MuCAN
**[Paper]** (ECCV 2020) MuCAN: Multi-Correspondence Aggregation Network for Video Super-Resolution <Br>
**[Author]** Wenbo Li, [Xin Tao](http://www.xtao.website/), Taian Guo, [Lu Qi](http://luqi.info/), Jiangbo Lu, [Jiaya Jia](http://jiaya.me/) <Br>

#### RSDN
**[Paper]** (ECCV 2020) Video Super-Resolution with Recurrent Structure-Detail Network <Br>
**[Author]** Takashi Isobe, [Xu Jia](https://stephenjia.github.io/), [Shuhang Gu](https://sites.google.com/site/shuhanggu/), Songjiang Li, Shengjin Wang, Qi Tian<Br>

#### RBPN ★☆
**[Paper]**  (ECCV 2020) Recurrent Back-Projection Network for Video Super-Resolution <Br>
**[Author]** [Muhammad Haris](https://alterzero.github.io/), [Greg Shakhnarovich](https://ttic.uchicago.edu/~gregory/), [Norimichi Ukita](https://www.toyota-ti.ac.jp/Lab/Denshi/iim/ukita/) <Br>
**[[Project](https://alterzero.github.io/projects/RBPN.html)]**  **[[Pytorch-Code](https://github.com/alterzero/RBPN-PyTorch)]** <Br>
视频超分, 使用DBPN中的back-projection结构利用前n帧信息完成对当前帧的空间超分.


	
	
# Frame Interpolation
#### EA-Net ★
**[Paper]**  (arXiv 2105) EA-Net: Edge-Aware Network for Flow-based Video Frame Interpolation <Br>
**[Author]** Bin Zhao, Xuelong Li <Br>
基于光流的插帧, 加入了edge信息
	
#### XVFI ★★
**[Paper]**  (arXiv 2103) XVFI: eXtreme Video Frame Interpolation <Br>
**[Author]** Hyeonjun Sim, [Jihyong Oh](https://sites.google.com/view/ozbro/%ED%99%88), Munchurl Kim <Br>
**[[Pytorch-Code](https://github.com/JihyongOh/XVFI)]** <Br>
1. 提出了一个4K, 1000fps的插帧数据集; 2. 提出一个共享参数的多尺度插帧网络, 通过调整预测的scale级数, 处理不同分辨率和偏移.

#### FLAVR ★★
**[Paper]**  (CVPR 2021) FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation <Br>
**[Author]** [Tarun Kalluri](https://tarun005.github.io/), [Deepak Pathak](https://www.cs.cmu.edu/~dpathak/), [Manmohan Chandraker](http://cseweb.ucsd.edu/~mkchandraker/), [Du Tran](https://dutran.github.io/)    <Br>
**[[Project](https://tarun005.github.io/FLAVR/)]** **[[Pytorch-Code](https://github.com/tarun005/FLAVR)]** <Br>
首次提出用3D卷积做视频插帧, 结构为UNet, 输入为前后四帧, 输出为需要插的k-1帧

#### CDFI ★
**[Paper]**  (CVPR 2021) CDFI: Compression-Driven Network Design for Frame Interpolation <Br>
**[Author]** [Tianyu Ding](https://www.tianyuding.com/), Luming Liang, [Zhihui Zhu](http://mysite.du.edu/~zzhu61/index.html), Ilya Zharkov    <Br>
**[[Pytorch-Code](https://github.com/tding1/CDFI)]** <Br>
通过加入L1正则引入稀疏性, 然后将模型输入层数逐次减小, 得到压缩后的模型. 论文中表示压缩后的结构更合理, from scratch训练该网络就能得到与大模型相近的性能. 之后在小模型上加入了一些改进模块, 进一步提高了精度

#### AnimeInterp ★
**[Paper]**  (CVPR 2021) Deep Animation Video Interpolation in the Wild <Br>
**[Author]** Li Siyao, Shiyu Zhao, Weijiang Yu, Wenxiu Sun, [Dimitris N. Metaxas](https://www.cs.rutgers.edu/~dnm/), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/), [Ziwei Liu](https://liuziwei7.github.io/)    <Br>
**[[Pytorch-Code](https://github.com/lisiyao21/AnimeInterp/)]** <Br>
动画的插帧, 针对动画纹理平滑和位移大的特点, 设计了segment匹配模块和coarse-to-fine的光流匹配模块.

#### RIFE ★★
**[Paper]**  (arXiv 2011) RIFE: Real-Time Intermediate Flow Estimation for Video Frame Interpolation <Br>
**[Author]** [Zhewei Huang](https://github.com/hzwer), [Tianyuan Zhang](http://tianyuanzhang.com/), Wen Heng, [Boxin Shi](http://ci.idm.pku.edu.cn/), [Shuchang Zhou](https://zsc.github.io/) <Br>
**[[Pytorch-Code](https://github.com/hzwer/arXiv2020-RIFE)]** **[[Software](https://github.com/YiWeiHuang-stack/Squirrel-RIFE)]** <Br>
使用一个coarse-to-fine的网络IFNet预测f1,f2到t时刻的光流, 融合部分使用网络预测fusion map和residual. 为更好训练光流, 使用leakage distillation的方法, 先用一训练好的大网络预测中间光流的值.

#### CAIN ★★
**[Paper]**  (AAAI 2020) Channel Attention Is All You Need for Video Frame Interpolation <Br>
**[Author]** [Myungsub Choi](https://myungsub.github.io/), Heewon Kim, [Bohyung Han](https://cv.snu.ac.kr/index.php/~bhhan/), Ning Xu, [Kyoung Mu Lee](https://cv.snu.ac.kr/index.php/~kmlee/) <Br>
**[[Project](https://myungsub.github.io/CAIN/)]** **[[Pytorch-Code](https://github.com/myungsub/CAIN)]** <Br>
(插帧) 设计了一个pixelshuffle + attention residual block的网络, 无需光流估计和warp操作.

#### SoftSplat ★☆
**[Paper]** (CVPR 2020) Softmax Splatting for Video Frame Interpolation <Br>
**[Author]**  [Simon Niklaus](http://sniklaus.com/welcome), [Feng Liu](http://web.cecs.pdx.edu/~fliu/) <Br>
**[[Pytorch-Code](https://github.com/sniklaus/softmax-splatting)]** <Br>
使用前向光流warp的插帧, 大致浏览, 效果不错. 主要创新点为使用I0和I1_warp的亮度一致性作为权重Z, 并用一网络refine Z, 最后在融合时使用exp保证了尺度不变性(此处是从深度图作为Z来论述的).

#### Meta Interpolation
**[Paper]** (CVPR 2020) Scene-Adaptive Video Frame Interpolation via Meta-Learning <Br>
**[Author]**  [Myungsub Choi](https://myungsub.github.io/), Janghoon Choi, [Sungyong Baik](https://baiksung.github.io/), [Tae Hyun Kim](https://sites.google.com/site/lliger9/), [Kyoung Mu Lee](https://cv.snu.ac.kr/index.php/~kmlee/) <Br>
**[[Project](https://myungsub.github.io/meta-interpolation/)]** **[[Pytorch-Code](https://github.com/myungsub/meta-interpolation)]** <Br>

#### BIN
**[Paper]** (CVPR 2020 Oral) Blurry Video Frame Interpolation <Br>
**[Author]** [Wang Shen](https://sites.google.com/view/wangshen94), [Wenbo Bao](https://sites.google.com/view/wenbobao/home), [Guangtao Zhai](https://faculty.sjtu.edu.cn/zhaiguangtao/en/index.htm), Li Chen, [Xiongkuo Min](https://sites.google.com/site/minxiongkuo/home), Zhiyong Gao<Br>
**[[Project](https://alterzero.github.io/projects/STAR.html)]** **[[Pytorch-Code](https://github.com/laomao0/BIN)]** <Br>

#### Deep-SloMo
**[Paper]**  (TPAMI 2020) Deep Slow Motion Video Reconstruction with Hybrid Imaging System <Br>
**[Author]** [Avinash Paliwal](http://people.tamu.edu/~avinashpaliwal/), [Nima Kalantari](https://people.engr.tamu.edu/nimak/index.html) <Br>
**[[Project](https://people.engr.tamu.edu/nimak/Papers/ICCP2020_Slomo/index.html)]** **[[Pytorch-Code](https://github.com/avinashpaliwal/Deep-SloMo)]** <Br>

#### DAIN ★★☆
**[Paper]**  (CVPR 2019) Depth-Aware Video Frame Interpolation <Br>
**[Author]** [Wenbo Bao](https://sites.google.com/view/wenbobao/home), [Wei-Sheng Lai](http://graduatestudents.ucmerced.edu/wlai24/), [Chao Ma](https://vision.sjtu.edu.cn/), Xiaoyun Zhang, Zhiyong Gao, [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/)  <Br>
**[[Project](https://sites.google.com/view/wenbobao/dain)]**  **[[Pytorch-Code](https://github.com/baowenbo/DAIN)]** <Br>
视频插帧, 利用光流和深度信息生成两帧间任意时刻的图像

#### IM-Net ★
**[Paper]**  (CVPR 2019) IM-Net for High Resolution Video Frame Interpolationn <Br>
**[Author]** Tomer Peleg, Pablo Szekely, Doron Sabo, [Omry Sendik](https://omrysendik.github.io/)  <Br>
**[[Project](https://sites.google.com/view/wenbobao/dain)]**  **[[Pytorch-Code](https://github.com/baowenbo/DAIN)]** <Br>
预测motion field vector(光流)和occlusion map做插帧

#### Super SloMo ★☆
**[Paper]**  (CVPR 2018) Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation <Br>
**[Author]** [Huaizu Jiang](http://jianghz.me/), [Deqing Sun](https://deqings.github.io/), [Varun Jampani](https://varunjampani.github.io/), [Ming-Hsuan Yang](https://faculty.ucmerced.edu/mhyang/), [Erik Learned-Miller](https://people.cs.umass.edu/~elm/), [Jan Kautz](https://jankautz.com/)  <Br>
**[[Project](https://github.com/avinashpaliwal/Super-SloMo)]**  **[[Pytorch-Code](http://jianghz.me/projects/superslomo/)]** <Br>
视频插帧. 首先预测双向光流, 接下来在每个要插值的时刻t, 用一个网络refine光流并预测visibility map, 最后根据光流和visibility map插值生成t时刻图像.
	

	
	
# Video Enhancement
#### Temporal Consistency for Low Light Video Enhancement
**[Paper]** (CVPR 2021) Learning Temporal Consistency for Low Light Video Enhancement from Single Images <Br>
**[Author]** Fan Zhang, [Yu Li](https://yu-li.github.io/), [Shaodi You](https://youshaodi.github.io/), Ying Fu <Br>
**[[Code](https://github.com/zkawfanx/StableLLVE)]** 	






# Video Stabilization
##### Deep Online Fused Video Stabilization
**[Paper]** (arXiv 2102) Deep Online Fused Video Stabilization <Br>
**[Author]**  [Zhenmei Shi](http://pages.cs.wisc.edu/~zhmeishi/), [Fuhao Shi](http://fuhaoshi.com/), [Wei-Sheng Lai](http://graduatestudents.ucmerced.edu/wlai24/), [Chia-Kai Liang](http://chiakailiang.org/), [Yingyu Liang](http://pages.cs.wisc.edu/~yliang/) <Br>
**[[Project](https://zhmeishi.github.io/dvs/)]** **[[Pytorch-Code](https://github.com/googleinterns/deep-stabilization)]**  <Br>








# Video Denoising
##### EMVD ★★
**[Paper]** (CVPR 2021) Efficient Multi-Stage Video Denoising with Recurrent Spatio-Temporal Fusion <Br>
**[Author]**  Matteo Maggioni, Yibin Huang, Cheng Li, Shuai Xiao, Zhongqian Fu, Fenglong Song <Br>
轻量级视频去噪, 效果与复杂模型效果相当. 首先用线性变换将raw图像在颜色-亮度和频率上分解; 第二步利用前一帧去噪结果与当前帧融合, 初步去噪; 第三步对初步去噪的图像再次进行去噪; 第四步将两次去噪的结果结合进行refine. 融合和refine是通过预测fusion map完成的.
	
##### FastDVDnet
**[Paper]** (CVPR 2020) FastDVDnet: A Very Fast Deep Video Denoising algorithm <Br>
**[Author]**  Matias Tassano, Julie Delon, Thomas Veit<Br>
**[[Pytorch-Code](https://delon.wp.imt.fr/)]**  <Br>	

##### RViDeNet
**[Paper]** (CVPR 2020) Supervised Raw Video Denoising With a Benchmark Dataset on Dynamic Scenes <Br>
**[Author]**  Huanjing Yue, Cong Cao, Lei Liao, Ronghe Chu, Jingyu Yang<Br>
**[[Pytorch-Code](https://github.com/cao-cong/RViDeNet)]**  <Br>	





# Video Debluring
#### DeFMO ★
**[Paper]** (CVPR 2021) DeFMO: Deblurring and Shape Recovery of Fast Moving Objects <Br>
**[Author]** Denys Rozumnyi, Martin R. Oswald, Vittorio Ferrari, Jiri Matas, Marc Pollefeys<Br>
**[[Pytorch-Code](https://github.com/rozumden/DeFMO)]** <Br>
从单张模糊图像和背景图中恢复t张清晰的图像, 网络结构为一个encoder+t个renderers, 采用了几个loss分别用于处理目标外观, sharpness及空间一致性等.
	
#### ARVo
**[Paper]** (CVPR 2021) ARVo: Learning All-Range Volumetric Correspondence for Video Deblurring <Br>
**[Author]** Dongxu Li, Chenchen Xu, [Kaihao Zhang](https://zhangkaihao.github.io/), [Xin Yu](https://sites.google.com/view/xinyus-homepage/Home), [Yiran Zhong](https://yiranzhong.com/), [Wenqi Ren](https://sites.google.com/site/renwenqi888/home), [Hanna Suominen](https://researchers.anu.edu.au/researchers/suominen-h), Hongdong Li<Br>
**[[Project](https://baihaoran.xyz/projects/cdvd-tsp/index.html)]**  **[[Pytorch-Code](https://github.com/csbhr/CDVD-TSP)]** <Br>

#### Event-Driven Video Deblurring
**[Paper]** (ECCV 2020) Learning Event-Driven Video Deblurring and Interpolation <Br>
**[Author]** Songnan Lin, [Jiawei Zhang](https://sites.google.com/site/zhjw1988), [Jinshan Pan](https://jspan.github.io/), Zhe Jiang, Dongqing Zou, Yongtian Wang, Jing Chen, [Jimmy Ren](http://www.jimmyren.com/) <Br>

#### ESTRNN
**[Paper]** (ECCV 2020 Spotlight) Efficient Spatio-Temporal Recurrent Neural Network for Video Deblurring <Br>
**[Author]** Zhihang Zhong, Ye Gao, Yinqiang Zheng, [Bo Zheng](http://www.bozheng-lab.com/) <Br>
**[[Pytorch-Code](https://github.com/zzh-tech/ESTRNN)]** <Br>
	
#### CDVD-TSP ★☆
**[Paper]** (CVPR 2020) Cascaded Deep Video Deblurring Using Temporal Sharpness Prior <Br>
**[Author]** [Jinshan Pan](https://jspan.github.io/), [Haoran Bai](https://baihaoran.xyz/about), Jinhui Tang<Br>
**[[Project](https://baihaoran.xyz/projects/cdvd-tsp/index.html)]**  **[[Pytorch-Code](https://github.com/csbhr/CDVD-TSP)]** <Br>
使用光流将先后帧warp到当前帧, 和一个新提出的sharpness prior进行concat, 送入网络进行处理. 通过级联(2阶段)的方式提高精度.

#### STFAN
**[Paper]** (ICCV 2019) Spatio-Temporal Filter Adaptive Network for Video Deblurring <Br>
**[Author]** [Shangchen Zhou](https://shangchenzhou.com/), [Jiawei Zhang](https://sites.google.com/site/zhjw1988), [Jinshan Pan](https://jspan.github.io/), [Haozhe Xie](https://haozhexie.com/about), [Wangmeng Zuo](http://homepage.hit.edu.cn/wangmengzuo), [Jimmy Ren](http://www.jimmyren.com/) <Br>
**[[Project](https://www.shangchenzhou.com/projects/stfan/)]**  **[[Pytorch-Code](https://github.com/sczhou/STFAN)]** <Br>





# Video Dehazing
#### Restore Hazy Video
**[Paper]** (CVPR 2021)Learning to Restore Hazy Video: A New Real-World Dataset and A New Method <Br>
**[Author]**  [Xinyi Zhang](https://sites.cs.ucsb.edu/~xyzhang/), Hang Dong, [Jinshan Pan](https://jspan.github.io/), Chao Zhu, [Ying Tai](https://tyshiwo.github.io/), Chengjie Wang, Jilin Li, Feiyue Huang, Fei Wang <Br>





# Video Inpainting
#### Short-Term and Long-Term Context Aggregation Network for Video Inpainting
**[Paper]** (ECCV 2020) Short-Term and Long-Term Context Aggregation Network for Video Inpainting <Br>
**[Author]** [Ang Li](https://angliunimelb.github.io/), [Shanshan Zhao](https://sshan-zhao.github.io/), [Xingjun Ma](http://xingjunma.com/), [Mingming Gong](https://mingming-gong.github.io/), [Jianzhong Qi](https://people.eng.unimelb.edu.au/jianzhongq/), [Rui Zhang](http://www.ruizhang.info/), [Dacheng Tao](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/dacheng-tao.html), [Ramamohanarao Kotagirig](http://www.cloudbus.org/rao/) <Br>

#### STTN
**[Paper]** (ECCV 2020) Learning Joint Spatial-Temporal Transformations for Video Inpainting  <Br>
**[Author]** [Yanhong Zeng](https://sites.google.com/view/1900zyh), [Jianlong Fu](https://jianlong-fu.github.io/), Hongyang Chao <Br>
**[[Pytorch-Code]](https://github.com/researchmm/STTN)]** 

#### DVI
**[Paper]** (ECCV 2020) DVI: Depth Guided Video Inpainting for Autonomous Driving <Br>
**[Author]** Miao Liao, Feixiang Lu, Dingfu Zhou, [Sibo Zhang](https://sites.google.com/view/sibozhang/home), Wei Li, [Ruigang Yang](http://www.vis.uky.edu/~ryang/) <Br>
**[[Project]](https://sites.google.com/view/sibozhang/dvi)]** **[[Code]](https://github.com/sibozhang/Depth-Guided-Inpainting)]** 

#### Depth-Guided-Inpainting
**[Paper]** (ECCV 2020) Learning Joint Spatial-Temporal Transformations for Video Inpainting <Br>
**[Author]** Miao Liao, Feixiang Lu, Dingfu Zhou, [Sibo Zhang](https://sites.google.com/view/sibozhang/home), Wei Li, [Ruigang Yang](http://www.vis.uky.edu/~ryang/) <Br>
**[[Project]](https://sites.google.com/view/sibozhang/dvi)]** **[[Code]](https://github.com/sibozhang/Depth-Guided-Inpainting)]** 






# Useful Resources
**[[SimDeblur]](https://github.com/ljzycmd/SimDeblur)]** 多个deep-learning based图像和视频去模糊Pytorch代码实现

**[[VideoSuperResolution]](https://github.com/LoSealL/VideoSuperResolution)]** A collection of state-of-the-art video or single-image super-resolution architectures, reimplemented in TF

**[[Waifu2x-Extension-GUI]](https://github.com/AaronFeng753/Waifu2x-Extension-GUI)]** Image & GIF & Video Super-Resolution and Video Frame Interpolation using DNNs

