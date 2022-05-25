# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2022

+ Group 2
+ Team members
	+ team member 1: Clement, Micol (mc5104)
	+ team member 2: Agarwal, Rishav (ra3141)
	+ team member 3: Fang, Wenhui (wf2282)
	+ team member 4: Liao, Jingwei (jl5983)
	+ team member 5: Wang, Xubo (xw2808)

+ Project summary: In this project, we created a Weakly Supervised Learning model to classify the CIFAR-10 dataset where the labels were disturbed by noise. Multiple model that had good perfomance on the clean CIFAR-10 dataset were tested : VCG model, Compact Convolutional Transformers, ResNet20 and ResNet44 adapted for the CIFAR dataset. Those model were first trained on the noisy data set. The trained convolutional embbeding of each of the tested models is then used for the label cleaning network that takes a noisy label and its corresponding image and return the clean label. Once this label cleaning network was used, we clean our label and retrained our CNN models on the new cleaned dataset. This lead to an improvement of 7% in accuracy on the test set.
	
**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
