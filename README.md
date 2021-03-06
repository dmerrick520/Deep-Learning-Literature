# Deep-Learning-Literature
Collection of Research Papers, Blogs, Articles, Books, etc on Neural Networks that I find interesting and useful... A growing list.

### Spring 2019 - related works
[Image-to-Image Translation with Conditional Adversarial Networks (pixtopix)](http://openaccess.thecvf.com/content_cvpr_2017/papers/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.pdf
)

[Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.pdf)

[Addressing Appearance Change in Outdoor Robotics with Adversarial Domain Adaptatio](https://arxiv.org/pdf/1703.01461.pdf)

### Fundamentals of Neural Networks, an introduction to foundational concepts and whatnot
[FUNDAMENTALS OF NEURAL
NETWORKS - 2001](http://knn.es/Fundamentals_of_Neural_Networks.pdf)

### Activation Function Stuff
[Deep Learning using Rectified Linear Units (ReLU) - March 2018](https://arxiv.org/pdf/1803.08375.pdf)

[Survey of Neural Transfer Functions - 1999](ftp://ftp.icsi.berkeley.edu/pub/ai/jagota/vol2_6.pdf)


### Using Information Theory to Understand and Train Neural Networks

[The Information Bottleneck Method - April 2000](https://arxiv.org/pdf/physics/0004057v1.pdf)

[Deep Learning and the Information Bottleneck Principle - March 2015](https://arxiv.org/pdf/1503.02406.pdf)

[Opening the black box of Deep Neural Networks
via Information - April 2017](https://arxiv.org/pdf/1703.00810.pdf)

[DEEP VARIATIONAL INFORMATION BOTTLENECK - July 2017](https://arxiv.org/pdf/1612.00410.pdf)

[New Theory Cracks Open the Black Box of Deep Learning - Sept 2017](https://www.quantamagazine.org/new-theory-cracks-open-the-black-box-of-deep-learning-20170921/?fbclid=IwAR1c0RKUbQdW83wVIG2l9je7ErEkyL4vJd_yd_4_uNW4ycEn_ssqpW9b8n0?)


### Methods for training Neural Networks 'better'

[Improving neural networks by preventing
co-adaptation of feature detectors, this is Dropout - July 2012](https://arxiv.org/pdf/1207.0580.pdf)

[How Does Batch Normalization Help Optimization? - Oct 2018](https://arxiv.org/pdf/1805.11604.pdf)


### Neural Networks and Semantic Segmentation

[Learning Deconvolution Network for Semantic Segmentation - May 2015](https://arxiv.org/pdf/1505.04366.pdf)

[Learning to Segment Everything - March 2018](https://arxiv.org/pdf/1711.10370.pdf)

[Learning to Segment via Cut-and-Paste - March 2018](https://arxiv.org/pdf/1803.06414.pdf)

[Context Encoding for Semantic Segmentation - March 2018](https://arxiv.org/pdf/1803.08904.pdf
)

### Generative Models

[Tutorial on Variational Autoencoders - August 2016](https://arxiv.org/pdf/1606.05908.pdf)

[Crossing Generative Adversarial Networks for Cross-View Person
Re-identification - January 2018](https://arxiv.org/pdf/1801.01760.pdf)


[Learning to Segment via Cut-and-Paste - March 2018](https://arxiv.org/pdf/1803.06414.pdf)

[Pose-Normalized Image Generation for Person Re-identification - April 2018](https://arxiv.org/pdf/1712.02225.pdf)

[StarGAN: Unified Generative Adversarial Networks
for Multi-Domain Image-to-Image Translation - Sept 2018](https://arxiv.org/pdf/1711.09020.pdf)

### Negative Transfer Stuff
[Asymmetric Multi-task Learning Based on Task Relatedness and Loss - June 2016](http://proceedings.mlr.press/v48/leeb16.pdf)

[Deep Asymmetric Multi-task Feature Learning - June 2018](https://arxiv.org/pdf/1708.00260.pdf)



### Other Cool Stuff

[Learning the Latent “Look”: Unsupervised Discovery of a
Style-Coherent Embedding from Fashion Images - August 2017](https://arxiv.org/pdf/1707.03376.pdf)

[A VARIATIONAL U-NET FOR CONDITIONAL APPEARANCE AND SHAPE GENERATION](https://compvis.github.io/vunet/)

[The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/pdf/1511.07528.pdf)

[Maximal Jacobian-based Saliency Map Attack](https://arxiv.org/pdf/1808.07945.pdf)

[SENSITIVITY AND GENERALIZATION IN NEURAL NETWORKS: AN EMPIRICAL STUDY](https://arxiv.org/pdf/1802.08760.pdf)

[A Generative Model for People in Clothing](https://arxiv.org/pdf/1705.04098.pdf)

[A Photographic Image Synthesis with Cascaded Refinement Networks](https://arxiv.org/pdf/1707.09405.pdf)

[Unsupervised Person Re-identification: Clustering and Fine-tuning](https://arxiv.org/pdf/1705.10444.pdf)

[Deep Asymmetric Multi-task Feature Learning](https://arxiv.org/pdf/1708.00260.pdf)


### A Review of Evaluation Metrics for Object Detection Stability

[Integrated Object Detection and Tracking with Tracklet-Conditioned Detection - Nov, 2018](https://arxiv.org/pdf/1811.11167.pdf)

Evaluation metrics used: "A2. Tracklet Stability Metric
In  [66], the authors first  examined  the  problem  of  detection and tracking stability. Three metrics are proposed
for evaluating stability, namely, fragment error, center po-sition error,  and scale and aspect ratio error.  The metricsare applied on the per-frame detection boxes, produced byvideo object detection algorithms.  For stability evaluation,the detection boxes are assigned to pseudo tracklets, aidedby the oracle ground-truth annotations.   For each ground-truth tracklet, a pseudo tracklet is formed approximately bypicking the detection box with the highest overlap with re-spect to the corresponding ground-truth at each frame2. Thestability errors are averaged over all the pseudo tracklets.It is not specified in [66] how to extend their approach totracklets produced by detection and tracking algorithms.Here, we extend [66] for evaluating the stability of detec-tion and tracking algorithms in a straightforward way. Sim-ilar to the approach in [66], we seek to find a “best-match”tracklet for each ground-truth tracklet.  All the recognizedtracklets are first classified into positive and negative track-lets, according to the box IoU and temporal IoU thresholdsin the mAPtrackmetric.   A positive tracklet is assigned tothe ground-truth tracklet with the highest temporal IoU. Foreach ground-truth tracklet, the tracklet with the highest clas-sification  score  among  all  its  assigned  tracklets  is  pickedas  its  “best-match”.   The  resulting  stability  errors  are  theaveraged errors over all the “best-match” tracklets (gener-ated at various box and temporal IoU thresholds as done formAPtrack)"
