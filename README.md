# Awesome Visual Navigation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list of visual navigation resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing and [awesome-enbodied-vision](https://github.com/ChanganVR/awesome-embodied-vision).

By [POSS](http://www.poss.pku.edu.cn/), PKU Omni Smart Sensing, the major collector and contributor is [Haotian Zhou](zhouhaotian19@pku.edu.cn), [Jianghuan Xu](xjhcgdk@stu.pku.edu.cn) and [Xiaole Wang](w2576827927@stu.pku.edu.cn). If you see papers missing from the list, please send me an email or a pull request (format see [below](#contributing)).

## Table of Content

* [Papers](#papers)
	* [PointGoal Navigation](#pointgoal)
	* [ObjectGoal Navigation](#objectgoal)
	* [ImageGoal Navigation](#imagegoal)
	* [Vision-Language Navigation](#vln)
	* [Social ](#social)
	* [Multi-Agent Tasks](#multiagent)
	* [SLAM](#slam)
	* [Lidar](#lidar)
* [Datasets](#datasets)
* [Simulators](#simulators)
* [MISC](#misc)

## <a name="contributing"></a> Contributing
When sending PRs, please put the new paper at the correct chronological position as the following format: <br>

```
* **Paper Title** <br>
*Author(s), Organization* <br>
*Simulator, Data* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Project]](link)
```

## <a name="papers"></a> Papers

### <a name="pointgoal"></a> PointGoal Navigation

* **Learning to Explore Using Active Neural SLAM** *cited: 500*<br> *Chaplot et al., Carnegie Mellon University* <br> *Habitat, Gibson&MP3D* <br> ICLR, 2020. [[Code]](https://github.com/devendrachaplot/Neural-SLAM) [[Project]](https://devendrachaplot.github.io/projects/Neural-SLAM)

* **Safe-Nav: learning to prevent PointGoal navigation failure in unknown environments** *cited: 7*<br> *Jin et al., Tianjin University* <br> *nan, nan* <br> Complex & Intelligent Systems, 2022. [[Code]](nan) [[Project]](nan)

* **Is Mapping Necessary for Realistic PointGoal Navigation?** *cited: 31*<br> *Partsey et al., Ukrainian Catholic University* <br> *nan, nan* <br> CVPR, 2023. [[Code]](https://github.com/rpartsey/pointgoal-navigation) [[Project]](https://rpartsey.github.io/pointgoalnav/)   

* **TTA-Nav: Test-time Adaptive Reconstruction for Point-Goal Navigation under Visual Corruptions** *cited: 1*<br> *nan, nan* <br> *nan, nan* <br> Arxiv, 2024. [[Code]](nan) [[Project]](nan)

* **Is Mapping Necessary for Realistic PointGoal Navigation?** *cited: 35*<br> *Partsey et al., Ukrainian Catholic University* <br> *nan, nan* <br> CVPR, 2022. [[Code]](nan) [[Project]](nan)

### <a name="objectgoal"></a> ObjectGoal Navigation

* **Object Goal Navigation using Goal-Oriented Semantic Exploration** *cited: 425*<br> *Chaplot et al., Carnegie Mellon University* <br> *Habitat, Gibson&MP3D* <br> NIPS, 2020. [[Code]](https://github.com/devendrachaplot/Object-Goal-Navigation) [[Project]](https://devendrachaplot.github.io/projects/semantic-exploration)

* **PONI: Potential Functions for ObjectGoal Navigation with Interaction-free Learning** *cited: 114*<br> *Ramakrishnan et al., Meta* <br> *Habitat, Gibson&MP3D* <br> CVPR, 2022. [[Code]](https://github.com/srama2512/PONI) [[Project]](https://vision.cs.utexas.edu/projects/poni/)

* **Learning Embodied Object-Search Strategies from Human Demonstrations** *cited: 77*<br> *Ramrakhya et al., Georgia Institute of Technology* <br> *Habitat, nan* <br> CVPR, 2022. [[Code]](https://github.com/Ram81/habitat-web) [[Project]](https://ram81.github.io/projects/habitat-web)

* **Pirlnav: Pretraining with imitation and rl finetuning for objectnav** *cited: 38*<br> *Ramrakhya et al., Georgia Institute of Technology* <br> *nan, nan* <br> CVPR, 2023. [[Code]](https://github.com/Ram81/pirlnav) [[Project]](https://ram81.github.io/projects/pirlnav)      

* **SPOC: Imitating Shortest Paths in Simulation Enables Effective Navigation and Manipulation in the Real World** *cited: 1*<br> *Ehsani et al., Allen Institute for AI* <br> *AI2-THOR, SPOC* <br> CVPR, 2024. [[Code]](https://github.com/allenai/spoc-robot-training) [[Project]](https://spoc-robot.github.io/)

* **TDANet: Target-Directed Attention Network For Object-Goal Visual Navigation With Zero-Shot Ability** *cited: 0*<br> *Lian et al., PKU* <br> *AI2THOR, v1.0.1* <br> RAL, 2024. [[Code]](no) [[Project]](no)

* **Exploitation-Guided Exploration for Semantic Embodied Navigation SLAM** *cited: 0*<br> *Wasserman et al., University of Illinois, Meta* <br> *Habitat, HM3D* <br> Arxiv, 2023. [[Code]](https://github.com/Jbwasse2/XGX) [[Project]](https://xgxvisnav.github.io/)

* **RoboHop: Segment-based Topological Map Representation for Open-World Visual Navigation** *cited: 4*<br> *Garg et al., nan* <br> *Habitat, GibsonEnv&PanoContext&GPCampus* <br> ICRA, 2024. [[Code]](No) [[Project]](https://oravus.github.io/RoboHop/)

* **Offline Visual Representation Learning for Embodied Navigation** *cited: 55*<br> *Yadav et al., Meta* <br> *nan, nan* <br> ICLR, 2023. [[Code]](Coming soon?) [[Project]](https://www.karmeshyadav.com/publication/ovrl/)

* **Combining Optimal Control and Learning for Visual Navigation in Novel Environments** *cited: 182*<br> *Bansal et al., nan* <br> *nan, 2D-3D-S* <br> CoRL, 2020. [[Code]](https://github.com/smlbansal/Visual-Navigation-Release) [[Project]](https://smlbansal.github.io/LB-WayPtNav/)

* **Vision-Only Robot Navigation in a Neural Radiance World** *cited: 182*<br> *Adamkiewicz et al., nan* <br> *nan, nan* <br> RAL, 2022. [[Code]](https://github.com/mikh3x4/nerf-navigation) [[Project]](https://mikh3x4.github.io/nerf-navigation/)

* **Fast Traversability Estimation for Wild Visual Navigation** *cited: 32*<br> *Frey et al., nan* <br> *nan, nan* <br> RSS, 2023. [[Code]](No) [[Project]](https://sites.google.com/leggedrobotics.com/wild-visual-navigation)

* **Scene Memory Transformer for Embodied Agents in Long-Horizon Tasks** *cited: 188*<br> *Fang et al., Stanford* <br> *nan, SUNCG* <br> CVPR, 2019. [[Code]](no official) [[Project]](https://sites.google.com/view/scene-memory-transformer)

* **Target-driven Visual Navigation in Indoor Scenes using Deep Reinforcement Learning** *cited: 1845*<br> *Zhu et al., Stanford* <br> *nan, nan* <br> ICRA, 2017. [[Code]](https://github.com/caomw/icra2017-visual-navigation-1) [[Video]](https://www.youtube.com/watch?v=SmBxMDiOrvs&ab_channel=AllenInstituteforAI)

* **Visual Object Search by Learning Spatial Context** *cited: 73*<br> *Druon et al., Paul Sabatier University* <br> *nan, AI2-THOR* <br> RAL, 2020. [[Code]](nan) [[Project]](nan)     

* **Exploiting scene-specific features for object goal navigation** *cited: 24*<br> *Campari et al., University of Padova* <br> *nan, nan* <br> ECCV, 2020. [[Code]](nan) [[Project]](nan)

* **VME-Transformer: Enhancing Visual Memory Encoding for Navigation in Interactive Environments** *cited: nan*<br> *Jiwei Shen, 华东师大* <br> *nan, iGibson* <br> RAL, 2024. [[Code]](no) [[Project]](nan)

* **Low-Level Active Visual Navigation: Increasing Robustness of Vision-Based Localization Using Potential Fields** *cited: nan*<br> *Rˆ omulo T. Rodrigues, University of Lisboa* <br> *nan, nan* <br> RAL, 2018. [[Code]](nan) [[Project]](nan)

* **Learning Composable Behavior Embeddings for Long-Horizon Visual Navigation** *cited: nan*<br> *Xiangyun Meng, University of Washington* <br> *nan, Gibson* <br> RAL, 2021. [[Code]](nan) [[Project]](nan)

* **Stubborn: A Strong Baseline for Indoor Object Navigation** *cited: 26*<br> *Luo et al., MIT* <br> *nan, nan* <br> IROS, 2022. [[Code]](https://github.com/Improbable-AI/Stubborn) [[Project]](nan)

* **Navigating to objects in unseen environments by distance prediction** *cited: 20*<br> *Zhu et al., ByteDance* <br> *nan, nan* <br> IROS, 2022. [[Code]](no) [[Project]](nan)        

* **Auxiliary Tasks and Exploration Enable ObjectGoal Navigation** *cited: 46*<br> *Ye et al., Georgia Institute of Technology* <br> *nan, nan* <br> ICCV, 2021. [[Code]](https://github.com/joel99/objectnav) [[Project]](https://joel99.github.io/objectnav/)

* **Learning exploration policies for navigation.** *cited: 238*<br> *Chen et al., Carnegie Mellon University* <br> *nan, nan* <br> ICLR, 2019. [[Code]](https://github.com/taochenshh/exp4nav) [[Project]](https://sites.google.com/view/exploration-for-nav/)

* **A Novel Neural Multi-Store Memory Network for Autonomous Visual Navigation in Unknown Environment** *cited: 22*<br> *Sang et al., Tongji University* <br> *Habitat, MP3D* <br> RAL, 2022. [[Code]](nan) [[Project]](nan)

* **Commonsense-Aware Object Value Graph for Object Goal Navigation** *cited: 0*<br> *Yoo et al., Seoul National University* <br> *nan, nan* <br> RAL, 2024. [[Code]](nan) [[Project]](nan)

* **THDA: Treasure Hunt Data Augmentation for Semantic Navigation** *cited: 70*<br> *Maksymets et al., Facebook AI* <br> *nan, nan* <br> ICCV, 2021. [[Code]](nan) [[Project]](nan)     

* **Bridging Zero-shot Object Navigation and Foundation Models through Pixel-Guided Navigation Skill** *cited: 10*<br> *Cai et al., PKU* <br> *Habitat, HM3D* <br> ICRA, 2024. [[Code]](https://github.com/wzcai99/Pixel-Navigator) [[Project]](nan)

* **Esc: Exploration with soft commonsense constraints for zeroshot object navigation** *cited: 53*<br> *Zhou et al., University of California* <br> *nan, MP3D&HM3D&RoboTHOR* <br> ICML, 2023. [[Code]](no!) [[Project]](https://sites.google.com/ucsc.edu/escnav/home)

* **HM3D-OVON: A Dataset and Benchmark for Open-Vocabulary Object Goal Navigation** *cited: not released, 从homepage上找的*<br> *Yokoyama et al., Georgia Institute of Technology* <br> *nan, nan* <br> IROS, 2024. [[Code]](https://github.com/naokiyokoyama/ovon) [[Project]](nan) 

* **Vlfm: Vision-language frontier maps for zero-shot semantic navigation** *cited: 15*<br> *Yokoyama et al., Boston Dynamics + Georgia Institute of Technology* <br> *Habitat, HM3D & Gibson & MP3D* <br> ICRA, 2024. [[Code]](https://github.com/bdaiinstitute/vlfm) [[Project]](https://naoki.io/portfolio/vlfm.html)

* **MOPA: Modular Object Navigation with PointGoal Agents** *cited: 4*<br> *Raychaudhuri et al., Simon Fraser University* <br> *Habitat+MultiON, nan* <br> WACV, 2024. [[Code]](https://github.com/3dlg-hcvc/mopa) [[Project]](nan)

* **Learning hierarchical relationships for object-goal navigation** *cited: 36*<br> *Qiu et al., UCSD* <br> *AI2THOR, nan* <br> CoRL, 2020. [[Code]](https://github.com/cassieqiuyd/MJOLNIR) [[Project]](https://www.youtube.com/watch?v=eCxWwohbOd8)

* **Zero-shot object goal visual navigation** *cited: 26*<br> *Zhao et al., Chinese Academy of Sciences* <br> *AI2THOR, nan* <br> ICRA, 2023. [[Code]](https://github.com/pioneer-innovation/Zero-Shot-Object-Navigation) [[Project]](no)

* **Learning to Learn How to Learn: Self-Adaptive Visual Navigation Using Meta-Learning** *cited: 243*<br> *Wortsman et al., Allen Institute for AI* <br> *AI2THOR, nan* <br> CVPR (Oral), 2019. [[Code]](https://github.com/allenai/savn) [[Project]](no)

* **GOAT: Go to anything** *cited: 29*<br> *Chang et al., UIUC Carnegie Georgia …* <br> *nan, 不太需要训练data，自采真实数据测试* <br> Arxiv, 2023. [[Code]](https://github.com/facebookresearch/home-robot) [[Project]](https://theophilegervet.github.io/projects/goat/)

* **OpenFMNav: Towards Open-Set Zero-Shot Object Navigation via Vision-Language Foundation Models** *cited: nan*<br> *Kuang et al., PKU* <br> *nan, nan* <br> nan, 2024. [[Code]](https://github.com/yxKryptonite/OpenFMNav) [[Project]](nan)

### <a name="imagegoal"></a> ImageGoal Navigation

* **No RL, No Simulation: Learning to Navigate without Navigating** *cited: 64*<br> *Hahn et al., Georgia Institute of Technology* <br> *Habitat, NRNS本身* <br> NIPS, 2021. [[Code]](https://github.com//meera1hahn/NRNS) [[Project]](https://meerahahn.github.io/nrns/)

* **Last-Mile Embodied Visual Navigation** *cited: 24*<br> *Wasserman et al., University of Illinois, Meta* <br> *Habitat, NRNS* <br> CoRL, 2022. [[Code]](https://github.com/Jbwasse2/SLING) [[Project]](https://jbwasse2.github.io/portfolio/SLING/)

* **Neural Topological SLAM for Visual Navigation** *cited: 261*<br> *Chaplot et al., Carnegie Mellon University* <br> *Habitat, Gibson* <br> CVPR, 2020. [[Code]](No) [[Project]](https://devendrachaplot.github.io/projects/Neural-Topological-SLAM)

* **Topological Semantic Graph Memory for Image-Goal Navigation** *cited: 26*<br> *Kim et al., Seoul National University* <br> *nan, nan* <br> CoRL (Oral), 2022. [[Code]](https://github.com/rllab-snu/TopologicalSemanticGraphMemory?tab=readme-ov-file) [[Project]](https://bareblackfoot.github.io/TopologicalSemanticGraphMemory/)

* **GaussNav: Gaussian Splatting for Visual Navigation** *cited: 0*<br> *Lei et al., nan* <br> *Habitat, HM3D* <br> Arxiv, 2024. [[Code]](https://github.com/XiaohanLei/GaussNav) [[Project]](https://xiaohanlei.github.io/projects/GaussNav/)

* **Renderable Neural Radiance Map for Visual Navigation** *cited: 31*<br> *Kwon et al., Seoul National University* <br> *Habitat, NRNS* <br> CVPR (Highlight), 2023. [[Code]](No) [[Project]](https://rllab-snu.github.io/projects/RNR-Map/)

* **Towards Target-Driven Visual Navigation in Indoor Scenes via Generative Imitation Learning** *cited: 37*<br> *Wu et al., Nanjing University.* <br> *nan, nan* <br> RAL, 2021. [[Code]](https://github.com/wqynew/Enhanced-NeoNav) [[Project]](nan)

* **Visual Graph Memory with Unsupervised Representation for Visual Navigation** *cited: 48*<br> *Obin Kwon, Seoul National University* <br> *Habitat, Gibson* <br> ICCV, 2021. [[Code]](rllab-snu/Visual-Graph-Memory: Official GitHub Repository for paper "Visual Graph Memory with Unsupervised Representation for Visual Navigation", ICCV 2021) [[Project]](https://sites.google.com/view/iccv2021vgm)

* **Lifelong Topological Visual Navigation** *cited: 11*<br> *nan, nan* <br> *nan, nan* <br> RAL, 2022. [[Code]](nan) [[Project]](nan)

### <a name="vln"></a> Vision-Language Navigation

* **Discuss Before Moving: Visual Language Navigation via Multi-expert Discussions** *cited: 7*<br> *Long et al., Peking（董豪）* <br> *nan, R2R* <br> ICRA, 2024. [[Code]](nan) [[Project]](github: https://github.com/LYX0501/DiscussNav)

* **NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation** *cited: 0*<br> *Zhang et al., Peking（王鹤）* <br> *nan, R2R RxR* <br> RSS, 2024. [[Code]](nan) [[Project]](https://pku-epic.github.io/NaVid/)

* **NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models** *cited: 65*<br> *Zhou et al., University of Adelaide* <br> *nan, R2R* <br> AAAI, 2024. [[Code]](https://github.com/GengzeZhou/NavGPT) [[Project]](nan)

* **Structured Scene Memory for Vision-Language Navigation** *cited: 106*<br> *Wang et al., Beijing Institute of Technology* <br> *nan, nan* <br> CVPR, 2021. [[Code]](nan) [[Project]](nan)

* **REVE-CE: Remote Embodied Visual Referring Expression in Continuous Environment** *cited: 12*<br> *nan, nan* <br> *nan, nan* <br> nan, nan. [[Code]](nan) [[Project]](nan)


### <a name="social"></a> Social

* **SACSoN: Scalable Autonomous Control for Social Navigation** *cited: nan*<br> *Hirose et al., University of California* <br> *nan, nan* <br> RAL, 2024. [[Code]](https://github.com/NHirose/SACSoN) [[Project]](https://sites.google.com/view/SACSoN-review)

### <a name="multiagent"></a> Multi-Agent Tasks

* **Multi-Agent Embodied Visual Semantic Navigation With Scene Prior Knowledge** *cited: 23*<br> *Liu et al., Tsinghua University* <br> *nan, nan* <br> RAL, 2022. [[Code]](nan) [[Project]](nan)

* **Multi-Object Navigation in real environments using hybrid policies** <br>
*Assem Sadek, Guillaume Bono, Boris Chidlovskii, Atilla Baskurt, Christian Wolf* <br>
ICRA, 2023. [[Paper]](https://arxiv.org/pdf/2401.13800)

* **One Map to Find Them All: Real-time Open-Vocabulary Mapping for Zero-shot Multi-Object Navigation** <br>
*Finn Lukas Busch, Timon Homberger, Jes'us Ortega-Peimbert, Quantao Yang, Olov Andersson* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.11764) [[Website]](https://www.finnbusch.com/OneMap/)


### <a name="slam"></a> SLAM

* **Unconstrained Scene Generation with Locally Conditioned Radiance Fields** *cited: 132*<br> *DeVries et al., Apple* <br> *nan, Vizdoom & Replica* <br> ICCV, 2021. [[Code]](https://github.com/apple/ml-gsn) [[Project]](https://apple.github.io/ml-gsn/)

* **NICE-SLAM: Neural Implicit Scalable Encoding for SLAM** *cited: 482*<br> *Zhu et al., Zhejiang University* <br> *nan, nan* <br> CVPR, 2022. [[Code]](nan) [[Project]](nan)

* **GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting** *cited: 57*<br> *Yan et al., Shanghai AI Lab* <br> *nan, nan* <br> CVPR, 2024. [[Code]](nan) [[Project]](nan)

### <a name="lidar"></a> Lidar
* **Robust Lifelong Indoor LiDAR Localization using the Area Graph** *cited: 2*<br> *nan, nan* <br> *nan, nan* <br> RAL, 2023. [[Code]](nan) [[Project]](nan)

## <a name="datasets"></a> Datasets

* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **Habitat-Matterport 3D Dataset (HM3D): 1000 Large-scale 3D Environments for Embodied AI** <br>
*Santhosh K. Ramakrishnan, Aaron Gokaslan, Erik Wijmans, Oleksandr Maksymets, Alex Clegg, John Turner, Eric Undersander, Wojciech Galuba, Andrew Westbury, Angel X. Chang, Manolis Savva, Yili Zhao, Dhruv Batra* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/pdf/2109.08238.pdf) [[Website]](https://matterport.com/habitat-matterport-3d-research-dataset?fbclid=IwAR0LM7ZsUMOjUtDuDHOWEfY7UuOZ-cl8T5IvuzflDdmy_SCkkordP8yNpd0)

* **🏘️ ProcTHOR-10K: 10K Interactive Household Environments for Embodied AI** <br>
*Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Jordi Salvador, Kiana Ehsani, Winson Han, Eric Kolve, Ali Farhadi, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2206.06994.pdf) [[Website]](https://procthor.allenai.org/)

## <a name="simulators"></a> Simulators
* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **RoboTHOR: An Open Simulation-to-Real Embodied AI Platform** <br>
*Matt Deitke, Winson Han, Alvaro Herrasti, Aniruddha Kembhavi, Eric Kolve, Roozbeh Mottaghi, Jordi Salvador, Dustin Schwenk, Eli VanderBilt, Matthew Wallingford, Luca Weihs, Mark Yatskar, Ali Farhadi* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/2004.06799) [[Website]](https://github.com/lil-lab/chalet)

* **Habitat: A Platform for Embodied AI Research** <br>
*Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)

## <a name="misc"></a> MISC

* **Awesome Enbodied Vision** <br>
[[Project]](https://github.com/ChanganVR/awesome-embodied-vision)

* **Awesome LLM EN** <br>
[[Project]](https://github.com/Rongtao-Xu/Awesome-LLM-EN)

* **Awesome Robot Social Navigation** <br>
[[Project]](https://github.com/Shuijing725/awesome-robot-social-navigation)

* **Awesome Vision and Language Navigation** <br>
[[Project]](https://github.com/iminolee/Awesome-Vision-and-Language-Navigation)


