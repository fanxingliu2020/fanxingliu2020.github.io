---
title: "Feature Encoding With Autoencoders for Weakly Supervised Anomaly Detection"
collection: publications
category: manuscripts
permalink: /publication/Feature_Encoding_With_Autoencoders_for_Weakly_Supervised_Anomaly_Detection
excerpt: 'Participated in this work during my undergraduate studies.'
date: 2021-6-25
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: 'https://arxiv.org/abs/2105.10500'
citation: 'Yingjie Zhou, Xucheng Song, Yanru Zhang, Fanxing Liu, Ce Zhu and Lingqiao Liu. Feature Encoding with AutoEncoders for Weakly-supervised Anomaly Detection, IEEE Transactions on Neural Networks and Learning Systems, 2022, 33(6): 2454 - 2465.'
---

Weakly supervised anomaly detection aims at learning an anomaly detector from a limited amount of labeled data and abundant unlabeled data. Recent works build deep neural networks for anomaly detection by discriminatively mapping the normal samples and abnormal samples to different regions in the feature space or fitting different distributions. However, due to the limited number of annotated anomaly samples, directly training networks with the discriminative loss may not be sufficient. To overcome this issue, this article proposes a novel strategy to transform the input data into a more meaningful representation that could be used for anomaly detection. Specifically, we leverage an autoencoder to encode the input data and utilize three factors, hidden representation, reconstruction residual vector, and reconstruction error, as the new representation for the input data. This representation amounts to encode a test sample with its projection on the training data manifold, its direction to its projection, and its distance to its projection. In addition to this encoding, we also propose a novel network architecture to seamlessly incorporate those three factors. From our extensive experiments, the benefits of the proposed strategy are clearly demonstrated by its superior performance over the competitive methods. Code is available at: https://github.com/yj-zhou/Feature_Encoding_with_AutoEncoders_for_Weakly-supervised_Anomaly_Detection.