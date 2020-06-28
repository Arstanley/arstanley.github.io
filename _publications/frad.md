---
title: "Early Fraud Detection with Augmented Graph Learning" 
collection: publications
permalink: /publication/frad
date: 2020-06-15
excerpt: 'Can we achieve good results in graph anomaly detection when data is incomplete?'
venue: 'Submitted to the Second International Workshop on Deep Learning on Graphs: Methods and Applications (DLG-KDD’20).'
paperurl: 'arstanley.github.io'
---
_Abstract_- Having an effective fraud detection system can help social media to identify suspicious behaviors or accounts. Early detection is crucial to minimize losses if the fraud is ongoing. Existing detection methods perform effectively when good amounts of observed behavior data are available (which sometimes has been too late); however, at an early stage when the observations are limited, the performance would not be satisfactory. In this work, we propose \method, a novel self-training framework that uses behavior data augmentation for early fraud detection. It has a Seq2Seq-based behavior predictor that predicts (i) whether a user will adopt a new item or an item that has been historically adopted and (ii) which item will be adopted. \method utilizes the prediction results of fraud detection methods to make better prediction of future behavior and uses the augmented graph to help fraud detection methods to achieve higher performance while not requiring any additional data. It explores the mutually beneficial relationship between fraud detection and behavior prediction. Experiments show that \method improves the performance of different kinds of fraud detection methods. With \method augmented methods, the performance of fraud detection at an earlier stage is comparable with and/or better than non-augmented methods on a greater amount of observed data.
