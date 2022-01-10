# AMLS_21-22_SN18100145

## Overview of the Project

In this project, a binary and multiclass classifier has been built for identifying MRI scannings with no tumor and MRI scannings with tumor as well as identifying the brain tumor types of meningioma, glioma, pituitary tumors, and no tumor with the aid of the machine learning techniques. This application was separated to Task A, in which a binary classifier is developed to distinguish between tumorless brain and brain with tumor, and Task B, in which a multiclass classsifier is developed to distinguish between brain with meningioma, glioma, pituitary or no tumor. For the binary classifier, accuracies of 94.50% and 96.00% have been obtained by employing the SVM and CNN algorithms, respectively. For the multiclass classifier, an accuracy of 86.00% has been obtained with the aid of the CNN algorithm.

# Description and Role of Files

* In Task A, a binary classifier with the aid of the SVM algorithm has been built. The code for the SVM algorithm can be found in the 'Task A SVM' file. A second binary classifier has also been built with the aid of the CNN. The code for the classifier utilizing the CNN can be found in the 'Task A CNN' file.

* In Task B, a multiclass classifier with the aid of CNN has been built. The code for the classifier utilizing CNN can be found in the 'Task B CNN' file.

* Additionally, the test and data sets employed in the tasks have been provided inside the folders 'dataset' and 'test'. Download them alongside the code files to  run the code without incurring file pathing issues.

# Necessary Packages to Install

* numpy
* sklearn
* os
* seaborn
* matplotlib
* tensorflow
* keras

# Running the Code

For running the code, download all the code files as well as the aforementioned data containing folders. Open Anaconda.Navigator and install all the libraries given above into an environment. Install and run Jupyter Notebook through Anaconda.Navigator. Locate the folder containing the code and the data folders. Open the tasks one by one and run the cells.

