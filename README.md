# SLPred: a multi-view subcellular localization prediction tool for human proteins
* SLPred is a multi-view subcellular localization prediction tool for human proteins.
* The tool consists of nine independently developed model for the proteins which have annotation with nine subcellular locations: **Cytoplasm, Nucleus, Cell Membrane, Mitochondrion, Extra cellular, Endoplasmic reticulum, Golgi apparatus, Lysosome and Peroxisome.** 
* SLPred exploits the features of nineteen different protein descriptors from the publicly available tools: POSSUM, iFeature and SPMAP.
* Support Vector Machine (SVM) is used to construct probabilistic prediction models, which produces probabilistic scores indicating the localization probability for a query protein sequence. 
* A weighted score is calculated based on the obtained probabilistic scores from seven feature-based probabilistic prediction models (SVMs) by employing weighted mean voting.
* Binary prediction is given by applying thresholding on the weighted score.

* The following figure shows the proposed method
![alt text](https://github.com/gozsari/SLPred/blob/master/images/model_architecture.png)


