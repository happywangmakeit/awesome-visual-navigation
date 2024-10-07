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
*Author(s)* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Website]](link)
```

## <a name="papers"></a> Papers

### <a name="pointgoal"></a> PointGoal Navigation

* **Habitat: A Platform for Embodied AI Research** <br>
*Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)

### <a name="objectgoal"></a> ObjectGoal Navigation

* **Learning to Learn How to Learn: Self-Adaptive Visual Navigation Using Meta-Learning** <br>
*Mitchell Wortsman, Kiana Ehsani, Mohammad Rastegari, Ali Farhadi, Roozbeh Mottaghi* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1812.00971) [[Code]](https://github.com/allenai/savn) [[Website]](https://prior.allenai.org/projects/savn)

### <a name="imagegoal"></a> ImageGoal Navigation

* **Semi-Parametric Topological Memory for Navigation** <br>
*Nikolay Savinov\*, Alexey Dosovitskiy\*, Vladlen Koltun* <br>
ICLR, 2018. [[Paper]](https://arxiv.org/pdf/1803.00653.pdf) [[Code]](https://github.com/nsavinov/SPTM) [[Website]](https://sites.google.com/view/SPTM)

### <a name="vln"></a> Vision-Language Navigation

* **Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments** <br>
*Peter Anderson, Qi Wu, Damien Teney, Jake Bruce, Mark Johnson, Niko Sünderhauf, Ian Reid, Stephen Gould, Anton van den Hengel* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1711.07280) [[Code]](https://github.com/peteanderson80/Matterport3DSimulator) [[Website]](https://bringmeaspoon.org)

### <a name="social"></a> Social

* **Semantic Audio-Visual Navigation** <br>
*Changan Chen, Ziad Al-Halah, Kristen Grauman* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2012.11583.pdf) [[Code]](https://github.com/facebookresearch/sound-spaces/tree/main/ss_baselines/savi) [[Website]](http://vision.cs.utexas.edu/projects/semantic_audio_visual_navigation/)

### <a name="multiagent"></a> Multi-Agent Tasks

* **A Cordial Sync: Going Beyond Marginal Policies For Multi-Agent Embodied Tasks** <br>
*Unnat Jain\*, Luca Weihs\*, Eric Kolve, Ali Farhadi, Svetlana Lazebnik, Aniruddha Kembhavi, Alexander Schwing* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.04979) [[Code]](https://github.com/allenai/cordial-sync) [[Website]](https://unnat.github.io/cordial-sync/)

* **Multi-Object Navigation in real environments using hybrid policies** <br>
*Assem Sadek, Guillaume Bono, Boris Chidlovskii, Atilla Baskurt, Christian Wolf* <br>
ICRA, 2023. [[Paper]](https://arxiv.org/pdf/2401.13800)

### <a name="slam"></a> SLAM

* **Towards Distraction-Robust Active Visual Tracking** <br>
*Fangwei Zhong, Wenhan Luo, Peng Sun, Tingyun Yan, Yizhou Wang* <br>
ICML, 2021. [[Paper]](https://arxiv.org/abs/2106.10110) [[Code]](https://github.com/zfw1226/active_tracking_rl/tree/distractor) [[Website]](https://sites.google.com/view/distraction-robust-avt)

### <a name="lidar"></a> Lidar
* **Embodied Question Answering** <br>
*Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1711.11543) [[Code]](https://github.com/facebookresearch/EmbodiedQA) [[Website]](https://embodiedqa.org/)

## <a name="datasets"></a> Datasets
* **A Dataset for Developing and Benchmarking Active Vision** <br>
*Phil Ammirato, Patrick Poirson, Eunbyung Park, Jana Kosecka, Alexander C. Berg* <br>
ICRA, 2017. [[Paper]](https://www.cs.unc.edu/~ammirato/active_vision_dataset_website/icra-rohit-paper.pdf) [[Code]](https://github.com/ammirato/active_vision_dataset_processing) [[Website]](https://www.cs.unc.edu/~ammirato/active_vision_dataset_website/)

* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **Matterport3D: Learning from RGB-D Data in Indoor Environments** <br>
*Angel Chang, Angela Dai, Thomas Funkhouser, Maciej Halber, Matthias Nießner, Manolis Savva, Shuran Song, Andy Zeng, Yinda Zhang* <br>
3DV, 2017. [[Paper]](https://arxiv.org/pdf/1709.06158.pdf) [[Code]](https://github.com/niessner/Matterport) [[Website]](https://niessner.github.io/Matterport/)

* **Gibson Env: Real-World Perception for Embodied Agents** <br>
*Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)

* **The Replica Dataset: A Digital Replica of Indoor Spaces** <br>
*Julian Straub, Thomas Whelan, Lingni Ma, Yufan Chen, Erik Wijmans, Simon Green, Jakob J. Engel, Raul Mur-Artal, Carl Ren, Shobhit Verma, Anton Clarkson, Mingfei Yan, Brian Budge, Yajie Yan, Xiaqing Pan, June Yon, Yuyang Zou, Kimberly Leon, Nigel Carter, Jesus Briales, Tyler Gillingham, Elias Mueggler, Luis Pesqueira, Manolis Savva, Dhruv Batra, Hauke M. Strasdat, Renzo De Nardi, Michael Goesele, Steven Lovegrove, Richard Newcombe* <br>
arXiV, 2019. [[Paper]](https://arxiv.org/pdf/1906.05797.pdf) [[Code]](https://github.com/facebookresearch/Replica-Dataset)

* **Actionet: An Interactive End-to-End Platform for Task-Based Data Collection and Augmentation in 3D Environments** <br>
*Jiafei Duan, Samson Yu, Hui Li Tan, Cheston Tan* <br>
ICIP, 2020. [[Paper]](https://arxiv.org/pdf/2010.01357.pdf) [[Code]](https://github.com/SamsonYuBaiJian/actionet)

* **Habitat-Matterport 3D Dataset (HM3D): 1000 Large-scale 3D Environments for Embodied AI** <br>
*Santhosh K. Ramakrishnan, Aaron Gokaslan, Erik Wijmans, Oleksandr Maksymets, Alex Clegg, John Turner, Eric Undersander, Wojciech Galuba, Andrew Westbury, Angel X. Chang, Manolis Savva, Yili Zhao, Dhruv Batra* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/pdf/2109.08238.pdf) [[Website]](https://matterport.com/habitat-matterport-3d-research-dataset?fbclid=IwAR0LM7ZsUMOjUtDuDHOWEfY7UuOZ-cl8T5IvuzflDdmy_SCkkordP8yNpd0)

* **🏘️ ProcTHOR-10K: 10K Interactive Household Environments for Embodied AI** <br>
*Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Jordi Salvador, Kiana Ehsani, Winson Han, Eric Kolve, Ali Farhadi, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2206.06994.pdf) [[Website]](https://procthor.allenai.org/)

* **EgoTV 📺: Egocentric Task Verification from Natural Language Task Descriptions** <br>
*Rishi Hazra, Brian Chen, Akshara Rai, Nitin Kamra, Ruta Desai* <br>
ICCV, 2023. [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Hazra_EgoTV_Egocentric_Task_Verification_from_Natural_Language_Task_Descriptions_ICCV_2023_paper.pdf) [[Code]](https://github.com/facebookresearch/EgoTV) [[Website]](https://rishihazra.github.io/EgoTV)

## <a name="simulators"></a> Simulators
* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
*Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)

* **UnrealCV: Virtual Worlds for Computer Vision** <br>
*Weichao Qiu, Fangwei Zhong, Yi Zhang, Siyuan Qiao, Zihao Xiao, Tae Soo Kim, Yizhou Wang, Alan Yuille* <br>
ACM MM Open Source Software Competition, 2017. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3123266.3129396) [[Code]](https://github.com/unrealcv/unrealcv) [[Website]](https://unrealcv.org/)

* **Building Generalizable Agents with a Realistic and Rich 3D Environment (House3D)** <br>
*Yi Wu, Yuxin Wu, Georgia Gkioxari, Yuandong Tian* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1801.02209.pdf) [[Code]](https://github.com/facebookresearch/House3D)

* **CHALET: Cornell House Agent Learning Environment** <br>
*Claudia Yan, Dipendra Misra, Andrew Bennett, Aaron Walsman, Yonatan Bisk and Yoav Artzi* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1801.07357.pdf) [[Code]](https://github.com/facebookresearch/House3D)

* **RoboTHOR: An Open Simulation-to-Real Embodied AI Platform** <br>
*Matt Deitke, Winson Han, Alvaro Herrasti, Aniruddha Kembhavi, Eric Kolve, Roozbeh Mottaghi, Jordi Salvador, Dustin Schwenk, Eli VanderBilt, Matthew Wallingford, Luca Weihs, Mark Yatskar, Ali Farhadi* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/2004.06799) [[Website]](https://github.com/lil-lab/chalet)

* **Gibson Env: Real-World Perception for Embodied Agents** <br>
*Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)

* **Habitat: A Platform for Embodied AI Research** <br>
*Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)

* **VirtualHome: Simulating Household Activities via Programs** <br>
*Xavier Puig\*, Kevin Ra\*, Marko Boben\*, Jiaman Li, Tingwu Wang, Sanja Fidler, Antonio Torralba* <br>
CVPR, 2018. [[Paper]](http://virtual-home.org/paper/virtualhome.pdf) [[Code]](https://github.com/xavierpuigf/virtualhome) [[Website]](http://virtual-home.org/)

* **ThreeDWorld: A Platform for Interactive Multi-Modal Physical Simulation** <br>
*Chuang Gan, Jeremy Schwartz, Seth Alter, Martin Schrimpf, James Traer, Julian De Freitas, Jonas Kubilius, Abhishek Bhandwaldar, Nick Haber, Megumi Sano, Kuno Kim, Elias Wang, Damian Mrowca, Michael Lingelbach, Aidan Curtis, Kevin Feigelis, Daniel M. Bear, Dan Gutfreund, David Cox, James J. DiCarlo, Josh McDermott, Joshua B. Tenenbaum, Daniel L.K. Yamins*<br>
arXiv, 2020. [[Paper]](https://arxiv.org/pdf/2007.04954.pdf) [[Code]](https://github.com/threedworld-mit/tdw) [[Website]](http://www.threedworld.org/)

* **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** <br>
*Mohit Shridhar, Xingdi Yuan, Marc-Alexandre Côté, Yonatan Bisk, Adam Trischler, Matthew Hausknecht*<br>
ICLR, 2021. [[Paper]](https://arxiv.org/abs/2010.03768) [[Code]](https://github.com/alfworld/alfworld) [[Website]](https://alfworld.github.io/)

* **ManipulaTHOR: A Framework for Visual Object Manipulation** <br>
*Kiana Ehsani, Winson Han, Alvaro Herrasti, Eli VanderBilt, Luca Weihs, Eric Kolve, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.11213.pdf) [[Code]](https://github.com/allenai/manipulathor) [[Website]](https://ai2thor.allenai.org/manipulathor/)

* **🏘️ ProcTHOR: Large-Scale Embodied AI Using Procedural Generation** <br>
*Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Jordi Salvador, Kiana Ehsani, Winson Han, Eric Kolve, Ali Farhadi, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2206.06994.pdf) [[Website]](https://procthor.allenai.org/)

* **ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes** <br>
*Ran Gong\*, Jiangyong Huang\*, Yizhou Zhao, Haoran Geng, Xiaofeng Gao, Qingyang Wu, Wensi Ai, Ziheng Zhou, Demetri Terzopoulos, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang* <br>
ICCV, 2023. [[Paper]](https://arxiv.org/abs/2304.04321) [[Website]](https://arnold-benchmark.github.io/)

## <a name="misc"></a> MISC
* **Visual Learning and Embodied Agents in Simulation Environments Workshop** <br>
ECCV, 2018. [[website]](https://eccv18-vlease.github.io/)

* **Embodied-AI Workshop** <br>
CVPR, 2020/2021. [[website]](https://embodied-ai.org/#overview)

* **Gibson Sim2Real Challenge** <br>
CVPR, 2020. [[website]](http://svl.stanford.edu/igibson/challenge.html)

* **Embodied Vision, Actions & Language Workshop** <br>
ECCV, 2020. [[website]](https://askforalfred.com/EVAL/)

* **Closing the Reality Gap in Sim2Real Transfer for Robotics** <br>
RSS, 2020. [[website]](https://sim2real.github.io/?fbclid=IwAR0fyyc_k8AmmYYRHbJJtjqGonAn1TUhUPWEdEpwpMbuwIkTgxmC13TJjG4)

* **On Evaluation of Embodied Navigation Agents** <br>
*Peter Anderson, Angel Chang, Devendra Singh Chaplot, Alexey Dosovitskiy, Saurabh Gupta, Vladlen Koltun, Jana Kosecka, Jitendra Malik, Roozbeh Mottaghi, Manolis Savva, Amir R. Zamir* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/abs/1807.06757)

* **PyRobot: An Open-source Robotics Framework for Research and Benchmarking** <br>
*Adithya Murali\*, Tao Chen\*, Kalyan Vasudev Alwala\*, Dhiraj Gandhi\*, Lerrel Pinto, Saurabh Gupta, Abhinav Gupta* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/abs/1906.08236) [[Code]](https://github.com/facebookresearch/pyrobot) [[Website]](https://www.pyrobot.org/)

* **A Survey of Embodied AI: From Simulators to Research Tasks** <br>
*Jiafei Duan, Samson Yu, Hui Li Tan, Hongyuan Zhu, Cheston Tan* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/abs/2103.04918)

* **AllenAct: A Framework for Embodied AI Research** <br>
*Luca Weihs, Jordi Salvador, Klemen Kotar, Unnat Jain, Kuo-Hao Zeng, Roozbeh Mottaghi, Aniruddha Kembhavi* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2008.12760) [[Website]](https://allenact.org/)

* **CSAIL Embodied Intelligence Seminar** <br>
[[website]](https://ei.csail.mit.edu/seminars.html)
