# Object-Localization-and-Classification
 Using deep learning techniques we can create a model that can accomplish both classification and Locating the traffic sign in a street view(Localization)  at once with multi output methods.
### Data Preparation:
Using the real life images with street views or backgrounds in order to better simulate actual views self-driving cars may encounter for classification, in order to get the bounding box information (coordinates), each image is annotated manually using Microsoft VoTT Open source image captioning tool.
Generated python script to extract the annotated XML files and create a csv of images with their labels.
Current dataset includes Stop Sign images, Speed limit 35 and no sign at all.
### Data Augmentation:
Applied random effects to original images using Imgaug Library and increased data by 3x and made sure spatial information isn’t lost after data augmentation
### Model architecture:
![Blank diagram (3)](https://user-images.githubusercontent.com/38468068/207135368-db710c8d-2b1a-45f6-910e-006ef806a3fd.jpg)

