* * *

# Abstract
The connection between visual input and tactile sensing is critical for object manipulation tasks such as grasping and pushing.
In this work, we introduce the challenging task of estimating a set of tactile physical properties from visual information. We aim to build a model that learns the complex mapping between visual information and tactile physical properties. We construct a first of its kind image-tactile dataset with over 400 multiview image sequences and the corresponding tactile properties. A total of fifteen tactile physical properties across categories including friction, compliance, adhesion, texture, and thermal conductance are measured and then estimated by our models. We develop a cross-modal framework comprised of an adversarial objective and a novel visuo-tactile joint classification loss. Additionally, we introduce a neural architecture search framework capable of  selecting optimal combinations of viewing angles for estimating a given physical property.

* * *

## Video (90 seconds)

[![](http://img.youtube.com/vi/J532toKnly8/0.jpg)](http://www.youtube.com/watch?v=J532toKnly8 "")

* * *

## Paper (ECCV 2020)
<img src="imgs/front-page.png" alt="Front page of research paper" width="184" height="274" class="center">

<a href="https://arxiv.org/pdf/2004.14487.pdf">[arXiv]</a>

If you used or reference our work, please cite our work as follows:
```
@article{purri2020teaching,
  title={Teaching Cameras to Feel: Estimating Tactile Physical Properties of Surfaces From Images},
  author={Purri, Matthew and Dana, Kristin},
  journal={arXiv preprint arXiv:2004.14487},
  year={2020}
}
```

* * *

## Selected Results
<img src="imgs/single_image_results.png" class="center">

<img src="imgs/ablation_study_result.png" class="center">

<img src="imgs/viewpoint_selection_result.png" class="center">


* * *

### Funding & Collaboration
This  research  was  supported  by  NSF  Grant  #1715195.

Tactile measurements were done by SynTouch Inc., with the BioTac Toccare, and purchased by Rutgers.
