## Problem Statement - Rice Leaf Disease Detection (CNN)

* The problem of rice leaf disease detection involves developing a model that can accurately identify and classify diseases affecting rice plants based on images of their leaves. 

* The goal of this project is to provide an efficient model for detecting diseases in rice crops, which can help farmers and agricultural experts in timely disease management and treatment.

* The objective is to train a deep learning model to recognize patterns and characteristics associated with different types of diseases, such as bacterial leaf blight, brown spot, or Leaf smut. The model should be capable of accurately classifying new, unseen images into their respective disease categories.

* This can contribute to better crop management, improved yield, and ultimately, the overall sustainability and productivity of rice farming.

* The images are grouped into 3 classes based on the type of disease. There are 40 images in each class. The format of all images are jpg.

### Classes are as below:

1) Bacterial leaf blight
   
2) Brown spot
   
3) Leaf smut

### Project Summary

* Challenges : "Limited Dataset Size"

During the data collection and preprocessing phase, One of the main challenge was the limited size of the available dataset.

The dataset consisted of a relatively small number of images for each rice leaf disease category, making it difficult to train a robust and accurate model. 

This limited dataset size could lead to overfitting and reduced generalization capability of the model.

* Techniques Used : " Data Augmentation"

To address the limited dataset size and class imbalance challenges, data augmentation techniques were employed. 

Data augmentation involves generating new training samples by applying various transformations such as rotation, scaling, and flipping to the existing images. 

This technique helps increase the dataset size and introduce more variability, enabling the model to learn diverse patterns and improve its generalization ability.

### Conclusion

* we have successfully developed a CNN model for rice leaf disease detection.
  
* The model showed promising results with an accuracy of 90% on the test set, indicating its effectiveness in accurately classifying rice leaf diseases.
  
* The use of data augmentation technique helped improve the model's performance and generalization ability.
  
* The model can be a valuable tool for farmers and agricultural experts in timely disease detection and management, ultimately leading to higher crop yields and healthier rice plants.
  
* Further improvements can be made by expanding the dataset and exploring other advanced CNN architectures.
