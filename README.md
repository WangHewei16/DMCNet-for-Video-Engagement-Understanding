# Understanding Engagement from Video Screengrabs


### Executive summary
Engagement is a key indicator of the quality-of-learning experience (QoLE) and plays a major role in developing intelligent educational interfaces. The number of people learning through Massively Open Online Courses (MOOCs) and other online resources has been increasing rapidly because they provide you the flexibility to learn from anywhere at any time, so to provide a good learning experience such interface requires the ability to recognize the level of engagement in order to respond appropriately. We presents a variety of models that have been trained on a given data set and explain in detail how each model was prepared and trained. To show how each model performs we have used a variety of metrics like the Gini Index, AGF (Adjusted F-Measure), AUC, etc, To understand how data is distributed we use various dimensionality reduction techniques like PCA and t-SNE with their plots for our data set.


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
