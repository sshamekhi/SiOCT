# SD-OCT
Spectral-domain Optical Coherence Tomography (SD-OCT) is one of the main imaging methods in the diagnosis of retinal diseases such as diabetic macular degeneration (DME) and age-related macular degeneration (AMD). One of the methods that physicians use to diagnose the diseases mentioned above is to check the layers of retinal tissue in SD-OCT images visually. Therefore, for automatic SD-OCT image classification, in this work, an algorithm consisting of four stages of preprocessing, layer border extraction, feature extraction, and image classification was proposed. First, after removing the noise and image artifacts, by presenting a method based on the Frangi vesselness enhancement algorithm the RNFL layer and the IS/OS junction in the retina images were detected. Then, by extracting several linear and nonlinear features from the curves of the layers and corresponding curvatures, an algorithm based on the decision tree ensemble model has been proposed for classifying SD-OCT images of retinas. In this research, the proposed method has been evaluated using images of two well-known databases of Duke University and Kermany. Also, in addition to presenting a MATLAB application (SiOCT), the results of the proposed algorithm have been compared with the results of previous researches that had been performed on similar databases and the results of implementing various classification methods based on machine learning in various criteria. Based on the results, accuracy, sensitivity, specificity, error rate and F1-score of the proposed method in Duke database were equal to 98.4, 98.4, 99, 98.9, 1.6, and 98.4, respectively, and in Kermany Database were 96.8, 96.7, 98.9, 98.4, 3.2 and 96.7 respectively. The results show the superiority of the proposed method compared to other comparative methods as well as previous research.
