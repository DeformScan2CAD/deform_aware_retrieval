# Deformation-Aware 3D Shape Embedding and Retrieval
[Mikaela Angelina Uy](https://mikacuy.github.io), [Jingwei Huang](http://cs.stanford.edu/~jingweih/), [Minhyuk Sung](https://mhsung.github.io), [Tolga Birdal](http://tbirdal.me/), [Leonidas Guibas](https://geometry.stanford.edu/member/guibas/)

[Stanford University](http://www.stanford.edu) & [Adobe Research](https://research.adobe.com)

European Conference on Computer Vision (ECCV) 2020

<img src="assets/intro_image.png" width="800" alt="centered image">

## Abstract
We introduce a new problem of **_retrieving_** 3D models that are **_deformable_** to a given query shape and present a novel deep **_deformation-aware_** embedding to solve this retrieval task. 3D model retrieval is a fundamental operation for recovering a clean and complete 3D model from a noisy and partial 3D scan. However, given a finite collection of 3D shapes, even the closest model to a query may not be satisfactory. This motivates us to apply 3D model deformation techniques to adapt the retrieved model so as to better fit the query. Yet, certain restrictions are enforced in most 3D deformation techniques to preserve important features of the original model that prevent a perfect fitting of the deformed model to the query. This gap between the deformed model and the query induces asymmetric relationships among the models, which cannot be handled by typical metric learning techniques. Thus, to retrieve the best models for fitting, we propose a novel deep embedding approach that learns the **_asymmetric_** relationships by leveraging location-dependent egocentric distance fields. We also propose two strategies for training the embedding network. We demonstrate that both of these approaches outperform other baselines in our experiments with both synthetic and real data.

