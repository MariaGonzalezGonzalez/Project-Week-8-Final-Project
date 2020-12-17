<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Breast Cancer Detector

## Content
- [Project Description](#project-description)
- [Project Goals](#project-goals)
- [Dataset](#dataset)
- [Image Recognition](#Image-Recognition)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Breast cancer is the most common cancer in women worldwide and the second most common cancer overall. It is a leading cause of cancer death in less developed countries and the second leading cause of cancer death in American women, exceeded only by lung cancer. There were over 2 million new cases in 2018 and the national incidence rate is around 138 cases per 100,000 inhabitants. As well, that the lifetime risk of developing breast cancer is estimated to be approximately 1 in 8 women. 

This type of cancer is typically detected either during screening, before symptoms have developed, or after a woman notices a lump. Most masses seen on a mammogram and most breast lumps turn out to be benign (not cancerous). When cancer is suspected, tissue for microscopic analysis is usually obtained from a needle biopsy (fine-needle or larger core-needle) and less often from a surgical biopsy. Selection of the type of biopsy is based on multiple factors, including the size and location of the mass, as well as patient factors and preferences and resources.

<a name="project-goals"></a>

## Project Goals
Diagnosis of breast cancer is performed when an abnormal lump is found. When the patient visit the doctor, the doctor take some data regaring the smooth, texture, area of the lump which is going to be needed in order to evaluate if it is a benign or malignant escenario. 


Moreover, it is needed to take a biopsy in order to determine whether it is cancerous and, if so, whether it has spread to other parts of the body.Where image recognition is needed in order to examine the images taken from the microscophy. 

<a name="requirements"></a>

## Workflow
It is crucial to divide this project into two big areas: dataset and image recognition. 

<a name="requirements"></a>

## Dataset 

These are the paramethers that this dataset contain and that is going to guide us in order to determinate if the lump is benign or malignant.
- diagnosis: The diagnosis of breast tissues (1 = malignant, 0 = benign) where malignant denotes that the disease is harmful
- mean_radius: mean of distances from center to points on the perimeter
- mean_texture: standard deviation of gray-scale values
- mean_perimeter: mean size of the core tumor
- mean_area: mean area of the core tumor
- mean_smoothness: mean of local variation in radius lengths
It is crucial to prepare the dataset in order to find the best alogarithm. For this is needed to clean the null data and to check if there is any correlation, whether causal or not, between two variables. Then is been tried differents Machine Learning and Deep Learning models in order to obtain the hightest accurate result. Then we are ready to jump to the next step, image recognition.

<a name="deliverables"></a>

## Image Recognition
As the images obtained from the biopsy are divided into train and test and 0 and 1 (benign or malignant) then they are ready to fit into the deep learning model.


<a name="schedule"></a>


## Links

[Repository](https://github.com/MariaGonzalezGonzalez/Project-Week-8-Final-Project)  
[Slides]( https://drive.google.com/file/d/13a8SHLclN5_5hQ376DIAHQ1K_sYFNXiV/view?usp=sharing)  

<a name="tips-&-tricks"></a>

