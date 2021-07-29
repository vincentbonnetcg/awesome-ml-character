# Awesome ML Character 

> A collection of papers about characters generation with machine learning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

## Contents

- [Parametric Model](#parametric-model)
- [Rigging](#rigging)
- [Deformation](#deformation)
- [Body Simulation](#body-simulation)
- [Cloth Simulation](#cloth-simulation)
- [Motion Controller](#motion-controller)
- [Motion Generation](#motion-generation)
- [Motion Inbetweening](#motion-inbetweening)
- [Motion Retargeting](#motion-retargeting)
- [Contribute](#contribute)

## Parametric Model

**SMPL: A skinned multi-person linear model.**<br>
*Loper, Matthew, Naureen Mahmood, Javier Romero, Gerard Pons-Moll, and Michael J. Black.*<br>
SIGGRAPH 2015. [[PDF](https://files.is.tue.mpg.de/black/papers/SMPL2015.pdf)][[Course](https://smpl-made-simple.is.tue.mpg.de/index.html)]

**Parametric modeling of 3D human body shape—A survey.**<br>
*Cheng, Zhi-Quan, Yin Chen, Ralph R. Martin, Tong Wu, and Zhan Song.*<br>
2015. [[Website](https://www.sciencedirect.com/science/article/abs/pii/S0097849317301929)]

**SCAPE: Shape Completion and Animation of People.**<br>
*Anguelov, Dragomir, Praveen Srinivasan, Daphne Koller, Sebastian Thrun, Jim Rodgers, and James Davis.*<br>
SIGGRAPH 2005. [[PDF](https://ai.stanford.edu/~drago/Papers/shapecomp.pdf)]

## Rigging

**Learning Skeletal Articulations with Neural Blend Shapes.**<br>
*Li, Peizhuo, Kfir Aberman, Rana Hanocka, Libin Liu, Olga Sorkine-Hornung, and Baoquan Chen.*<br>
SIGGRAPH 2021. [[PDF](https://arxiv.org/pdf/2105.02451)]

**HeterSkinNet: A Heterogeneous Network for Skin Weights Prediction.**<br>
*Pan, Xiaoyu, Jiancong Huang, Jiaming Mai, He Wang, Honglin Li, Tongkui Su, Wenjun Wang, and Xiaogang Jin.*<br>
I3D 2021. [[PDF](https://arxiv.org/pdf/2103.10602)]

**Rignet: Neural rigging for articulated characters.**<br>
*Xu, Zhan, Yang Zhou, Evangelos Kalogerakis, Chris Landreth, and Karan Singh.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/pdf/2005.00559)]

**NiLBS: Neural Inverse Linear Blend Skinning.**<br>
*Jeruzalski, Timothy, David IW Levin, Alec Jacobson, Paul Lalonde, Mohammad Norouzi, and Andrea Tagliasacchi.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/pdf/2004.05980)]

## Deformation

**PBNS: Physically Based Neural Simulator for Unsupervised Garment Pose Space Deformation.**<br>
*Bertiche, Hugo, Meysam Madadi, and Sergio Escalera.*<br>
2020.[[PDF](https://arxiv.org/pdf/2012.11310)]

**Fast and deep deformation approximations.**<br>
*Bailey, Stephen W., Dave Otte, Paul Dilorenzo, and James F. O'Brien.*<br>
2018.[[PDF](https://research.dreamworks.com/wp-content/uploads/2018/08/Rig_Approximation-Edited.pdf)]

## Body Simulation

**SoftSMPL: Data-driven Modeling of Nonlinear Soft-tissue Dynamics for Parametric Humans.**<br>
*Santesteban, Igor, Elena Garces, Miguel A. Otaduy, and Dan Casas.*<br>
Eurographics 2020.[[PDF](https://arxiv.org/pdf/2004.00326)]


## Cloth Simulation

**Swish: Neural Network Cloth Simulation on Madden NFL 21.**<br>
*Lewin, Chris, James Power, and James Cobb.*<br>
2021.[[PDF](https://media.contentapi.ea.com/content/dam/ea/seed/presentations/seed-swish-cloth-simulation-madden-nfl.pdf)]

**Learning Mesh-Based Simulation with Graph Networks.**<br>
*Pfaff, Tobias, Meire Fortunato, Alvaro Sanchez-Gonzalez, and Peter W. Battaglia.*<br>
2020.[[PDF](https://arxiv.org/pdf/2010.03409)]

**Subspace neural physics: Fast data-driven interactive simulation.**<br>
*Holden, Daniel, Bang Chi Duong, Sayantan Datta, and Derek Nowrouzezahrai..*<br>
2020.[[PDF](http://cim.mcgill.ca/~derek/files/Deep-Cloth-paper.pdf)]

## Motion Controller

### Data-Driven Controller

**AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control.**<br>
*Peng, Xue Bin, Ze Ma, Pieter Abbeel, Sergey Levine, and Angjoo Kanazawa.*<br>
2021.[[PDF](https://arxiv.org/pdf/2104.02180)]

**A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control.**<br>
*Xu, Pei, and Ioannis Karamouzas.*<br>
2021. [[PDF](https://arxiv.org/pdf/2105.10066)]

**Learned motion matching.**<br>
*Xu, Pei, and Ioannis Karamouzas.*<br>
2020. [[PDF](http://theorangeduck.com/media/uploads/other_stuff/Learned_Motion_Matching.pdf)]

**Local motion phases for learning multi-contact character movements.**<br>
*Starke, Sebastian, Yiwei Zhao, Taku Komura, and Kazi Zaman.*<br>
2020. [[PDF](https://www.pure.ed.ac.uk/ws/portalfiles/portal/157671564/Local_Motion_Phases_STARKE_DOA27042020_AFV.pdf)]

**Neural state machine for character-scene interactions.**<br>
*Starke, Sebastian, He Zhang, Taku Komura, and Jun Saito.*<br>
SIGGRAPH Asia 2019. [[PDF](https://www.pure.ed.ac.uk/ws/files/112627363/papers_168s4_file2.pdf)]

**Mode-adaptive neural networks for quadruped motion control .**<br>
*Zhang, He, Sebastian Starke, Taku Komura, and Jun Saito.*<br>
2018. [[PDF](https://www.pure.ed.ac.uk/ws/files/60838109/dog2.pdf)]

**Phase-functioned neural networks for character control.**<br>
*Holden, Daniel, Taku Komura, and Jun Saito.*<br>
2017. [[PDF](http://theorangeduck.com/media/uploads/other_stuff/phasefunction.pdf)]

### Physics-Based Controller

**CARL: Controllable Agent with Reinforcement Learning for Quadruped Locomotion.**<br>
*Luo, Ying-Sheng, Jonathan Hans Soeseno, Trista Pei-Chun Chen, and Wei-Chao Chen.*<br>
2020. [[PDF](https://arxiv.org/pdf/2005.03288)]

## Motion Generation

**Deeploco: Dynamic locomotion skills using hierarchical deep reinforcement learning.**<br>
*Peng, Xue Bin, Glen Berseth, KangKang Yin, and Michiel Van De Panne.*<br>
2017.[[PDF](https://www.cs.ubc.ca/~van/papers/2017-TOG-deepLoco/2017-TOG-deepLoco.pdf)]

**Emergence of locomotion behaviours in rich environments.**<br>
*Heess, Nicolas, Dhruva TB, Srinivasan Sriram, Jay Lemmon, Josh Merel, Greg Wayne, Yuval Tassa et al..*<br>
2017.[[PDF](https://arxiv.org/pdf/1707.02286)]

## Motion Inbetweening

**Recurrent transition networks for character locomotion.**<br>
*Harvey, Félix G., and Christopher Pal*<br>
SIGGRAPH Asia 2018.[[PDF](https://arxiv.org/pdf/1810.02363)]

**Robust motion in-betweening.**<br>
*Harvey, Félix G., Mike Yurick, Derek Nowrouzezahrai, and Christopher Pal*<br>
SIGGRAPH 2020.[[PDF](https://arxiv.org/pdf/2102.04942)]

## Motion Retargeting

**Skeleton-Aware Networks for Deep Motion Retargeting.**<br>
*Aberman, Kfir, Peizhuo Li, Dani Lischinski, Olga Sorkine-Hornung, Daniel Cohen-Or, and Baoquan Chen*<br>
SIGGRAPH 2020.[[PDF](https://arxiv.org/pdf/2005.05732)]

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.