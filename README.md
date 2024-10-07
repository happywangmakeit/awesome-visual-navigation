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

* **One Map to Find Them All: Real-time Open-Vocabulary Mapping for Zero-shot Multi-Object Navigation** <br>
*Finn Lukas Busch, Timon Homberger, Jes'us Ortega-Peimbert, Quantao Yang, Olov Andersson* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.11764) [[Website]](https://www.finnbusch.com/OneMap/)

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

* **Gibson Sim2Real Challenge** <br>
CVPR, 2020. [[website]](http://svl.stanford.edu/igibson/challenge.html)

