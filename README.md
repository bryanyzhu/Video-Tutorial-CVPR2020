## A Comprehensive Tutorial on Video Modeling (CVPR 2020)

Abstract
--------

In this tutorial, we will present a comprehensive tutorial on video understanding with hands-on sessions. We provide coverage for 9 different types of video models (two-stream, TSN, TSM, C3D, I3D, Non-Local, SlowFast, R2+1D and SCSampler) on 6 widely adopted video datasets (UCF101, HMDB51, Kinetics, Something-Something-V2, ActivityNet and HACS). We will walk through the technical details of the state-of-the-art algorithms for video understanding, using human action recognition task as an illustrating example. We will provide step-by-step tutorials on how to reproduce SOTA video models, how to fine-tune a network on your own dataset, how to perform distributed training, how to extract spatiotemporal features from pre-trained deep video models, how to search the best network architecture for your use case, how to deploy your trained model to edge devices, etc.

Highlights
----------

* We provide a general video dataloader (can handle both frame format and raw video). You can do training, fine-tuning, prediction and feature extraction without writing complicate code. Just prepare a text file containing the video information is enough.
* We have more pre-trained models in our model zoo.
* We provide training commands and logs to help you reproduce SOTA video models.
* We support distributed training.
* We support AutoML, in terms of both hyperparameter optimization and neural architecture seach.
* We support easy deployment (by TVM) and model quantization (by Intel).

Agenda
------

| Topic                                                     | Slides   | Notebook |
|-----------------------------------------------------------|----------|----------|
| Opening and tutorial setup                                |          |[link][01]|
| A walk through on SOTA video methods                      |[link][10]|[link][11]|
| Bag of tricks for training deep video models              |          |[link][21], [link][22], [link][23], [link][24]|
| Decord: a fast video loader                               |          |[link][31]|
| Neural architecture search in video                       |          |          |
| Painless from research to deployment                      |          |[link][51], [link][52], [link][53]|
| Q&A and Closing                                           |          |          |


[01]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/00_setup/use_aws.ipynb
[10]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/02_sota/video_understanding.pptx
[11]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/02_sota/VideoActionRecognition.ipynb
[21]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/03_train/finetune_custom.ipynb
[22]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/03_train/feat_custom.ipynb
[23]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/03_train/distributed_slowfast.ipynb
[24]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/03_train/demo_custom.ipynb
[31]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/04_decord/decord_loader.ipynb
[51]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/06_deploy/TVMInference.ipynb
[52]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/06_deploy/cpp_inference.ipynb
[53]: https://github.com/bryanyzhu/Video-Tutorial/blob/master/06_deploy/TVMInference.ipynb
