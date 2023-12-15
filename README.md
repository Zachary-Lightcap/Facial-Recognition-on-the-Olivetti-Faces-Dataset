

# Facial-Recognition-on-the-Olivetti-Faces-Dataset

Finding the best learning technique for classifying the Olivetti Faces Dataset

Note that this ipython notebook was made with Google Colab, so libraries used were not needed to be installed. If run outside of Colab, user needs the appropriate libraries (seaborn, sklearn, etc.)

## The Olivetti Faces Dataset
The dataset came from a 2 year period of April 1992 and April 1994 from AT&T Laboratories Cambridge. During this period, they archived 400 images (10 for each particpant) that were originally taken as 92x112 size.  

We use the `sklearn.datasets.fetch_olivetti_faces` function to get the data which has been compressed to 64 x 64 images. Our `target`for this dataset is an integer 0 to 39 indicating which person was pictured.

## Tasks Covered

 - Applying various supervised and unsupervised learning techniques and determine which is best for the data
 - Determine optimal number of components to keep 90% vairiance
 - Apply PCA to the data and determine if it benefits the model
 
 **Final Result**: Found that Linear SVM and Ridge Regression (no-GD) worked best with the data. Using PCA on the data did not change outcome of thse two techniques.
 
## Future Tasks
 - [ ] Change from classification problem to a semi-supervised learning problem
 - [ ] Tune Hyperparameters for Linear SVM

> Written with [StackEdit](https://stackedit.io/).
