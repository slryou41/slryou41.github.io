---
layout: project
---

# Anchor Loss: Modulating loss scale based on prediction difficulty, <font size="4">ICCV19 Oral</font>

<p class="aligncenter">
  <img src="https://github.com/slryou41/slryou41.github.io/blob/master/images/overview.png?raw=true" style="width:500px">
</p>

We propose a novel loss function that dynamically rescales the cross entropy based on prediction difficulty regarding a sample. Deep neural network architectures in image classification tasks struggle to disambiguate visually similar objects. Likewise, in human pose estimation symmetric body parts often confuse the network with assigning indiscriminative scores to them. This is due to the output prediction, to which only the highest confidence label is selected without taking into consideration a measure of uncertainty. In this work, we define the prediction difficulty as a relative property coming from the confidence score gap between positive and negative labels. More precisely, the proposed loss function penalizes the network to avoid the score of a false prediction being significant. To demonstrate the efficacy of our loss function, we evaluate it on two different domains: image classification and human pose estimation. We find improvements in both applications by achieving higher accuracy compared to the baseline methods.

[code](https://github.com/slryou41/AnchorLoss), [arxiv](https://arxiv.org/abs/1909.11155)

## Presentation

[slides](https://drive.google.com/file/d/1G2e6EY9VVcf6Ft0iQu4vWT1t3QFHvck4/view?usp=sharing), [poster]


<div class="iframeVideo">
  <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/c7InF0ifjuY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Cite:
```

```


[back](./)
