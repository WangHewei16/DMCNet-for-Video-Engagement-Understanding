# Understanding Engagement from Video Screengrabs


### Executive summary
Engagement is an essential indicator of the Quality-of-Learning Experience (QoLE) and plays a major role in developing intelligent educational interfaces. The number of people learning through Massively Open Online Courses (MOOCs) and other online resources has been increasing rapidly because they provide you with the flexibility to learn from anywhere at any time, so to provide a good learning experience such interface requires the ability to recognize the level of engagement to respond appropriately; however, there is very little existing data to learn from, and new data is expensive and difficult to acquire. This paper proposes a variety of models that have been trained on a given data set, non-deep learning models based on the combination of some algorithm such as Convolutional Neural Network (CNN), Histogram of Oriented Gradient (HOG), Support Vector Machine (SVM), Scale Invariant Feature Transform (SIFT) and Speeded Up Robust Features (SURF). Deep learning methods include Densely Connected Convolutional Networks (DenseNet-121), Residual Network (ResNet-18) and MobileNetV1. We also explain in detail how each model was prepared and trained. To show the performance of each model, we use a variety of metrics such as the Gini Index, Adjusted F-Measure (AGF), Area Under ROC Curve (AUC), etc, and to understand how data is distributed, we use various dimensionality reduction techniques such as Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) with their plots for our data set.


### Code Organization
All code are written in Python3


### Dependencies

The following libraries should be installed before the execution of the codes.

	•Pillow                        6.2.1

	•pycm                          2.8

	•pandas                        0.25.3

	•matplotlib                    3.1.2

	•numpy                         1.15.4

	•opencv-python                 4.2.0.34

	•torch                         1.2.0

	•torchvision                   0.4.0

	•tqdm                          4.41.1

	•scikit-learn                  0.22.1

### Data
The data source in this work is https://github.com/e-drishti/wacv2016.

### File Descriptions

	•box_plot.ipynb - Contains the code for the box plot.

	•PCA_WACV_DATASET.ipynb - Contains the code for the PCA plot.

	•TSNE_plots.ipynb - Contains the code for the TSNE plot.

	•CNN_based_Engagement_Analysis.ipynb - Contains the code for the CNN based implementation technique.

	•hog+CNN_based_classification.ipynb - Contains the code for the HOG+CNN based implementation technique.

	•hog_sift_based_engagement_analysis.ipynb - Contains the code for the HOG+SIFT+SVM based implementation technique.

	•hog_svm_based_classification.ipynb - Contains the code for the HOG+SVM based implementation technique.

	•surf_based_engagement_analysis.ipynb - Contains the code for the SURF+SVM based implementation technique.

	•DenseNet-121_based_classification.ipynb - Contains the code for the DenseNet-121 based implementation technique.
	
	•ResNet-18_based_classification.ipynb - Contains the code for the ResNet-18 based implementation technique.
	
	•MobileNetV1_based_classification.ipynb - Contains the code for the MobileNetV1 based implementation technique.
