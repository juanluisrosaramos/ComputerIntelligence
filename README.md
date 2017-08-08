# ComputerIntelligence

Evaluating ANN to predict Parkinson's disease using the Parkinson's Disease Handwriting Database

Parkinson's disease (PD) is a neurodegenerative disorder which impairs motor skills, speech, and other functions such as behavior, mood, and cognitive processes. One of the most typical clinical hallmarks of PD is handwriting deterioration, usually the first manifestation of PD. 

The Parkinson's Disease Handwriting Database (PaHaW) [1,2] consists of multiple handwriting samples from 37 parkinsonian patients (19 men/18 women) and 38 gender and age matched controls (20 men/18 women). The data is presented as a time sequence and is composed  by the following dynamic features: pencil coordinates, time stamp, pencil on the surface / pencil on the air, pressure, tilt, and elevation. The database is accessible from the Brain Diseases Analysis Laboratory site [3] (Czech Republic) for research purposes.

The most recent study [2] (February 2016) was conducted with this database to discriminate between PD patients and healthy subjects, using three different classifiers: K-nearest neighbors (K-NN), ensemble AdaBoost classifier, and support vector machines (SVM). A previous research [4] was made with the same database using just SVM.  

The aim of this project is to apply different Artificial Neural Networks architectures to the database and compare the accuracy of the classification with the results obtained in [2,4]. Our initial proposal is to use a Feed Forward Neural Network [5] and a Recurrent Neural Network [6], evaluating different parameters in order to obtain the best possible configuration. The selection of the second architecture is because it is recommended for time series data and the selection of Artificial Neural Networks is because we believe that they will perform better with this dataset, given its high grade of expressivity and flexibility.

References:
[1] Peter Drotár, Ji?í Mekyska, Irena Rektorová, Lucia Masarová, Zdenek Smékal, Marcos Faundez-Zanuy, Analysis of in-air movement in handwriting: A novel marker for Parkinson's disease, Computer Methods and Programs in Biomedicine, Volume 117, Issue 3, December 2014, Pages 405-411, ISSN 0169-2607, http://dx.doi.org/10.1016/j.cmpb.2014.08.007.
URL: http://www.sciencedirect.com/science/article/pii/S0169260714003204.


[2] Peter Drotár, Ji?í Mekyska, Irena Rektorová, Lucia Masarová, Zden?k Smékal, Marcos Faundez-Zanuy, Evaluation of handwriting kinematics and pressure for differential diagnosis of Parkinson's disease, Artificial Intelligence in Medicine, Volume 67, February 2016, Pages 39-46, ISSN 0933-3657, http://dx.doi.org/10.1016/j.artmed.2016.01.004. URL:
(http://www.sciencedirect.com/science/article/pii/S0933365716000063)


[3] http://bdalab.utko.feec.vutbr.cz


[4] P. Drotár, J. Mekyska, I. Rektorová, L. Masarová, Z. Smékal and M. Faundez-Zanuy, "Decision Support Framework for Parkinsons Disease Based on Novel Handwriting Markers," in IEEE Transactions on Neural Systems and Rehabilitation Engineering, vol. 23, no. 3, pp. 508-516, May 2015. doi: 10.1109/TNSRE.2014.2359997. URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6910308&isnumber=7104187


[5] https://en.wikipedia.org/wiki/Feedforward_neural_network


[6] https://en.wikipedia.org/wiki/Recurrent_neural_network
