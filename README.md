# Awesome-Physcial-Adversarial-Examples-on-Computer-Vision

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of Awesome Computer-Vision (Image Classification, Object Detection and Image Segmentation) Real-world Adversarial Examples (Aka Physcial Adversarial Examples, PAE) academic and R&D resources. 

## Table of Contents
 - [Survey](#survey)
 - [Attack](#attack)
 - [Defense](#defense)
 - [Tutorial](#tutorial)
 - [ToolBox](#toolbox)


## Survey

- [A survey of practical adversarial example attacks](https://doi.org/10.1186/s42400-018-0012-9), Sun et al., Cybersecurity 1, 9(2018).

## Attack
**Image Classification**

- [Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533), Kurakin et al., ICLR Workshop 2017. [[demo](https://www.youtube.com/watch?v=zQ_uMenoBCk)]
    - The first work study Physical Adversarial Examples by experiment which direct transfer Digital Adversarial Examples.

- [Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition](https://doi.org/10.1145/2976749.2978392), Sharif et al., CCS 2016. [[code](https://github.com/mahmoods01/accessorize-to-a-crime), [talk](https://www.youtube.com/watch?v=6Xh1vuwnVhU)]
    - The first public paper contribute embryo of Patch Attack classic face recognition system.

- [Adversarial Patch](https://arxiv.org/abs/1712.09665), Brown et al., NIPS 2017. [[demo](https://www.youtube.com/watch?v=i1sp4X57TL4), [code](https://github.com/cleverhans-lab/cleverhans/tree/master/cleverhans_v3.1.0/examples/adversarial_patch)]
    - The first work contribute Patch Attack.

- [Synthesizing Robust Adversarial Examples](https://arxiv.org/abs/1707.07397), Athalye et al., ICML 2018. [[OpenReview](https://openreview.net/forum?id=BJDH5M-AW), [code](https://github.com/prabhant/synthesizing-robust-adversarial-examples)]
    - The first work study 3D Attack.

- [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945), Eykholt et al., CVPR 2018. [[homepage](https://iotsecurity.engin.umich.edu/robust-physical-world-attacks-on-deep-learning-visual-classification/), [blog](https://bair.berkeley.edu/blog/2017/12/30/yolo-attack/), [demo](https://www.youtube.com/watch?v=1mJMPqi2bSQ), [code](https://github.com/evtimovi/robust_physical_perturbations), [talk](https://www.youtube.com/watch?v=5CmVbqBSM48)]

**Object Detection**

- [Adversarial Examples that Fool Detectors](https://arxiv.org/abs/1712.02494), Lu et al., arXiv preprint 2017. 
    - The first experiment Physical Adversarial Examples in Detectors.

- [ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector](https://link.springer.com/content/pdf/10.1007%2F978-3-030-10925-7_4.pdf), Chen et al., ECML-PKDD 2018. [[code](https://github.com/shangtse/robust-physical-attack)]
    - Faster R-CNN

- [Physical Adversarial Examples for Object Detectors](https://www.usenix.org/system/files/conference/woot18/woot18-paper-eykholt.pdf), Eykholt et al., WOOT 2018.

- [Fooling automated surveillance cameras: adversarial patches to attack person detection](https://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Thys_Fooling_Automated_Surveillance_Cameras_Adversarial_Patches_to_Attack_Person_Detection_CVPRW_2019_paper.pdf), S. Thys, W. V. Ranst et al., CVPR workshop 2019. [[video](https://www.youtube.com/watch?v=MIbFvK2S9g8)]

- [DPATCH: An Adversarial Patch Attack on Object Detectors](https://arxiv.org/pdf/1806.02299.pdf), X Liu et al., AAAI workshop 2019.

- [On Physical Adversarial Patches for Object Detection](https://arxiv.org/pdf/1906.11897.pdf), Lee. M et al., ICML workshop 2019. [[video](https://www.youtube.com/watch?v=WXnQjbZ1e7Y)]

- [CAMOU: Learning Physical Vehicle Camouflages to Adversarially Attack Detectors in the Wild](https://openreview.net/pdf?id=SJgEl3A5tm), Y. Zhang et al., ICLR 2019.

- [Making an Invisibility Cloak: Real World Adversarial Attacks on Object Detectors](https://arxiv.org/pdf/1910.14667.pdf), Z. Wu et al, arXiv 2019. [[blog](https://www.cs.umd.edu/~tomg/projects/invisible/)]
- [Adversarial T-shirt! Evading Person Detectors in A Physical World](https://arxiv.org/pdf/1910.11099.pdf), K. Xu et al, arXiv 2019. [[blog](https://medium.com/@ODSC/evading-real-time-person-detectors-by-adversarial-t-shirt-8e0149e97e5a)]

- [Design and Interpretation of Universal Adversarial Patches in Face Detection](https://arxiv.org/pdf/1912.05021.pdf), X. Yang, F. Wei, H. Zhang et al., arXiv 2019.



- [FCA: Learning a 3D Full-coverage Vehicle Camouflage for Multi-view Physical Adversarial Attack](https://arxiv.org/abs/2109.07193), Wang. D et al., AAAI 2022. [[homepage](https://idrl-lab.github.io/Full-coverage-camouflage-adversarial-attack/), [blog](https://mp.weixin.qq.com/s/Bgjj0fyxAKWX31_X2IjdEg), [code](https://github.com/idrl-lab/Full-coverage-camouflage-adversarial-attack/tree/gh-pages/src)]
- [DTA: Physical Camouflage Attacks using Differentiable Transformation Network](https://arxiv.org/abs/2203.09831), Suryanto. N et al., CVPR 2022. [[homepage](https://islab-ai.github.io/dta-cvpr2022/)]

**Image Segmentation**

**3D Attacks**
- [MeshAdv: Adversarial Meshes for Visual Recognition](), 


## Defense
**Image Classification**


**Object Detection**

- [NO Need to Worry about Adversarial Examples in Object Detection in Autonomous Vehicles](), Lu et al., CVPR 2017.
    - The first paper think Physical Adversarial Examples in Detectors not very serious.

- [Role of Spatial Context in Adversarial Robustness for Object Detection](https://arxiv.org/abs/1910.00068), Saha et al., CVPR Workshop 2020. [[code](https://github.com/UMBCvision/Contextual-Adversarial-Patches)]

- [Information Distribution Based Defense Against Physical Attacks on Object Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9105983), G. Zhou et al., IEEE ICMEW 2020.

**Image Segmentation**

## Tutorial
- [CS 404/504 Adversarial Machine Learning](https://www.webpages.uidaho.edu/vakanski/CS_504.html), Alex Vakanski, University of Idaho, Fall 2021.
- [CS 562 Advanced Topics in Security, Privacy and Machine Learning](https://aisecure.github.io/TEACHING/CS562/CS562.html), Bo Li, University of Illinois at Urbana-Champaign, Fall 2021.
- [CY 7790 Machine Learning Security and Privacy](https://www.ccs.neu.edu/home/alina/classes/Fall2021/), Alina Oprea, Northeastern University, Fall 2021.
- [Security and Privacy of Machine Learning](), Shang-Tse Chen, NTU, Fall 2021.
- [Adversarial Machine Learning in Computer Vision](https://advmlincv.github.io/cvpr21-tutorial/), CVPR 2021 Tutorial, June 2021.
- [CS 498 Special Topics on Trustworthy Machine Learning
](https://courses.grainger.illinois.edu/cs498lb1/sp2021/), Bo Li, University of Illinois at Urbana-Champaign, Spring 2021.
- [CS 6231 Adversarial Machine Learning](https://www.comp.nus.edu.sg/~reza/courses/cs6231/), Reza Shokri, National University of Singapore, Fall 2019.

## Toolbox
- [Foolbox](https://github.com/bethgelab/foolbox)
- [CleverHans](https://github.com/tensorflow/cleverhans)
- [AdverTorch](https://github.com/BorealisAI/advertorch)
- [AdvBox](https://github.com/advboxes/AdvBox)
- [Adversarial Robustness Toolbox](https://github.com/IBM/adversarial-robustness-toolbox)
- [Adversarial-Face-Attack](https://github.com/ppwwyyxx/Adversarial-Face-Attack)

## License
[![img](https://camo.githubusercontent.com/d81c1a80f6c3d68d5f1a80b016db6802aa480411/68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792d6e632d73612f342e302f38307831352e706e67)](https://camo.githubusercontent.com/d81c1a80f6c3d68d5f1a80b016db6802aa480411/68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792d6e632d73612f342e302f38307831352e706e67) 

[(Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)

To the extent possible under law, Jing Li <lixeon.lij@gmail.com> has waived all copyright and related or neighboring rights to this work.
