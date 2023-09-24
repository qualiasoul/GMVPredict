**Status**: Pre-Alpha. Under Development.
# GMVPredict: A Pre-Trained Model for Pre-Morbid GMV Estimation
GMVPredict is a pre-trained machine learning model for predicting pre-morbid hippocampal gray matter volumes (GMV) using both voxel-based morphometry (VBM) and demographic data. While the model itself is pending release, here we provide a Jupyter notebook with sample code demonstrating the development process, including data processing, feature engineering, training, hyperparameter optimization, and testing. 

# Background & Aims
Certain neurological disorders result in localized atrophy, such as limbic encephelitis, which is known to result in severe localized hippocampal atrophy (see Loane et al, 2019). Accompanying such atrophy are often cognitive and behavioral impairments. Using the limbic encephelitis example, affected patients will often present with severely impaired episodic memory. Diagnosis itself is often spurred by these cognitive and behavioral impairments such that structural MRI data of the patient is usually only available after onset of the disorder. This issue of 'pre-morbid estimation' presents two problems:
1. In a research context, it is difficult to characterize the mathematical relationship between brain structure and function in these disorders 
2. In a clinical context, early or transitional cases are difficult to diagnose purely on the basis of behavioral deficits which may not have progressed enough to be sufficiently obvious 

In a nutshell: by providing an estimate of what 'healthy' GMV would be in patients with such disorders, GMVPredict provides researchers a tool to characterize the relationship between brain structure and cognitive function, and provides clinicians with a robust method to aid in early stage diagnosis of neurological disorders. 

While the model itself is trained to predict hippocampal GMV, in principle these methods can easily be used to predict GMV of any other ROI as well. 

---
William Yang<sup>1*</sup>, Petar Raykov<sup>1</sup>, Andrea Greve<sup>1</sup>
> <sup>1</sup>MRC Cognition and Brain Sciences Unit, University of Cambridge \
> <sup>*</sup>Correspondence: wy279@cam.ac.uk
