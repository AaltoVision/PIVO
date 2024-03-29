## Abstract

This paper presents a novel method for visual-inertial odometry. The method is based on an information fusion framework employing low-cost IMU sensors and the monocular camera in a standard smartphone. We formulate a sequential inference scheme, where the IMU drives the dynamical model and the camera frames are used in coupling trailing sequences of augmented poses. The novelty in the model is in taking into account all the cross-terms in the updates, thus propagating the inter-connected uncertainties throughout the model. Stronger coupling between the inertial and visual data sources leads to robustness against occlusion and feature-poor environments. We demonstrate results on data collected with an iPhone and provide comparisons against the Tango device and using the EuRoC data set.

## Paper

[arXiv pre-print](https://arxiv.org/abs/1708.00894)

## Poster

![WACV poster]({{ site.baseurl }}/assets/WACV-poster.jpg)

[WACV poster]({{ site.baseurl }}/assets/WACV-poster.pdf)

## Video 1

<iframe width="560" height="315" src="https://www.youtube.com/embed/suTx4FPcwbA" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>

## Video 2

<iframe width="560" height="315" src="https://www.youtube.com/embed/CK8RuoSEw0o" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>

## Code

If you are looking for a reference implementation of PIVO, please see [HybVIO](https://github.com/SpectacularAI/HybVIO) which extends and improves the PIVO approach.

## Referencing

{% raw  %}
```
@inproceedings{Solin+Cortes+Rahtu+Kannala:2018,
      title = {{PIVO}: {P}robabilistic inertial-visual odometry for 
               occlusion-robust navigation},
     author = {Solin, Arno and Cortes, Santiago and Rahtu, Esa 
               and Kannala, Juho},
       year = {2018},
  booktitle = {Proceedings of the IEEE Winter Conference on 
               Applications of Computer Vision (WACV)}
}
```
{% endraw  %}
