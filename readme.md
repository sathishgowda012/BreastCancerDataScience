Breast Cancer Detection with Reduced Feature Set
Problem Statement
Breast cancer is one the leading causes of death among all women. Early detection and diagnosis of cancer are essential for the treatment of the disease.
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors and their visual inspec-
tions.
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors and their visual inspec-
tions.
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors and their visual inspec-
tions.
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors and their visual inspec-
tions.
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors
How-
ever, the traditional approach to cancer diagnosis depends
highly on the experience of doctors
an recognize patterns easily. How-
ever, they fail when probabilities have to be assigned to obser-
vations []. Although several tests are applied, exact diagnosis
may be dicult even for an expert. 
How-ever, the traditional approach to cancer diagnosis depends highly on the experience of doctors and their visual inspections. Naturally, human beings can make mistakes due to their limitations. Humans can recognize patterns easily. How-ever, they fail when probabilities have to be assigned to observations. How-ever, they fail when probabilities have to be assigned to observations. Although several tests are applied, exact diagnosis may be difficult even for an expert. That is why automatic diagnosis of breast cancer is investigated by many researchers. correct diagnosis is achieved with the help of machine learning. Tumors are classified as benign and malignant. Benign tumors are not cancerous or life threatening. However, these can increase the risk of getting breast cancer. Malignant tumors are cancerous and more alarming than benign tumors. In order to improve accuracy of breast mass classification as benign and malignant, the performance of back-propagation artificial neural network (ANN) was evaluated
Support vector machine (SVM) is an effective statistical learning method for classification. SVM is based on Finding optimal hyperplane to separate different classes mapping input data into higher-dimensional feature space. SVM has advantage of fast training technique, even with large number	 of input data. therefore, it has been used for many recognition problems such as object recognition and face detection.
Principal component analysis (PCA) is a technique to reduce dimensionality using second order statistical information. Independent component analysis (ICA) is a recently developed method in pattern recognition and signal processing fields. It involves higher order statistics to extract independent components that involve richer information than PCA. ICA can be used to reduce dimensionality before training. Consequently, the complexity of classifiers can be reduced; convergence velocity and performance can be increased

Proposed System:
The objective of the proposed study is to analyse the effect of feature reduction using ICA on classification of the tumors as benign or malignant. Thus, the dimension of WDBC dataset is reduced into only one feature using ICA. The reduced data is subdivided into test and training data using fold cross-validation and partitioning to evaluate the performance of k-NN, SVM.









Dataset Information
WBDC dataset includes 569 instances with class distribution of 357 benign and 212 malignant. Each sample consists of ID number, diagnosis (B=benign=malignant), and 30 features. Features have been computed from a digitized image of a fine needle aspirate (FNA)of a breast
Methodology
The features of WDBC data and reduced one feature using ICA are deployed to evaluate the classifiers performance on breast cancer decision. Thus, the proposed Model applied to WDBC data that have the 30 features and 569 instances (patients) were used to train and test the models. First, the dimensionality of the data is reduced using CA and partitioned into subsamples using 5/20-CV and 20%partitioning to evaluate the classifiers. The subsamples have been used sequentially to train and test SVM and K-NN. The outputs of the classifiers have been evaluated to find out performance measures. IC can successfully identify the thirty features with the retained 98.2% of nonzero eigenvalues. The data are divided into subsets using 5/10-CV and 20% partitioning to test and train classifiers. After training process, the test data are used to evaluate diagnostic performances of the classifiers in terms of sensitivity, specificity, accuracy.
For training processes, k-NN classifier, one-dimensional Euclidean distance, Formal is used between test and training samples.

Description:
Predicting If the cancer diagnosis is benign or malignant based on several observations features 30 features are used, for Examples
-radius (Mean of distances from centre to points on perimeter)
-texture (Standard deviation of gray-Scale values)
-perimeter
-area
-smoothness (local variation in radius lengths)
-compactness(perimeter^2/area-1.0)
-concavity (severity of concave portions of the contour)
-concave points (number of concave portions of the contour)
-symmetry
-fractal dimension
-Datasets are linearly separable using  all 30 input features
-Number of instances:569
-Class Distribution:212 Malignant,357 Benign
-Target class:
*Malignant
*Benign

Conclusion:
Machine Learning techniques(SVM) can be used to classify tumors into Malignant/Benign with 98% accuracy.
The technique can rapidly evaluate breast masses and classify them in automated fashion
 Early breast cancer can save live in developing world
The technique can be further improved by combining Computer vision/ML techniques to directly classify cancer tissue using images

