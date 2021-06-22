
Decamouflage: A Framework to Detect Image-Scaling Attacks on CNN
------------------------------------------------------------------------------------------------------------------------------


Introduction
------------------------------------------------------------------------------------------------------------------------------

Image-scaling is a typical operation that processes the input image before feeding it into convolutional neural network models. However, it is vulnerable to the newly revealed image-scaling attack. This work presents an image-scaling attack detection framework, Decamouflage, consisting of three independent detection methods: scaling, filtering, and steganalysis, to detect the attack through examining distinct image characteristics. Decamouflage has a pre-determined detection threshold that is generic. More precisely, as we have validated, the threshold determined from one dataset is also applicable to other different datasets. Extensive experiments show that Decamouflage achieves detection accuracy of 99.9% and 98.5% in the white-box and the black-box settings, respectively. We also measured its running time overhead on a PC with an Intel i5 CPU and 8GB RAM. The experimental results show that image-scaling attacks can be detected in milliseconds. Moreover, Decamouflage is highly
robust against adaptive image-scaling attacks (e.g., attack image size variances)

Summary of code
------------------------------------------------------------------------------------------------------------------------------

We uploaded the code for Decamouflage.
Which included the proposed method: scaling, filtering, and steganalysis. 
We used the NeurIPS 2017 Adversarial Attacks and Defences Competition Track image dataset and to find the optimal thresholds for Decamouflage 
and used the Caltech 256 image dataset for testing. You can see more detail for datasets and Scaling attack open-source in Reference.

Reference
------------------------------------------------------------------------------------------------------------------------------

[1] Qixue Xiao*, Yufei Chen*, Chao Shen, Yu Chen, and Kang Li. Seeing is Not Believing: Camouflage Attacks on Image Scaling Algorithms, USENIX Security 2019.
[2] Yufei Chen, Chao Shen, Cong Wang, Qixue Xiao, Kang Li, and Yu Chen. Scaling Camouflage: Content Disguising Attack Against Computer Vision Applications, IEEE TDSC 2020.
    (open source-https://github.com/yfchen1994/scaling_camouflage)
[3] NeurIPS 2017 Adversarial Attacks and Defences Competition Track image dataset: https://www.kaggle.com/c/nips-2017-defense-against-adversarial-attack
[4] Caltech 256 image dataset: https://www.kaggle.com/jessicali9530/caltech256
