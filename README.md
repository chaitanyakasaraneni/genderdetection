# Gender Detection on CelebA Dataset

This project is done as a part of CMPE 258 course.

Dataset was taken from Kaggle: https://www.kaggle.com/jessicali9530/celeba-dataset/ <br>
Image recognition is one of the many applications of Machine Learning, it can solve problems for security purposes, object detection, face detection, healthcare, entertainment, among others. This application has an enormous potential to help our society, so it is important to find new uses for this tool, improve the current methods and get more accurate and useful insights from it.

## Model Used

### Inception-V3

Used pretrained Inception-V3 model with imagenet weights. This is the structure of the Inception-V3 model, developed over the imagenet dataset.

![alt text](https://github.com/chaitanyakasaraneni/genderdetection/blob/master/images/inceptionv3_structure.png "Structure of Inception-V3")

##### New Top layers
Layers to be trained with the new model.
![alt text](https://github.com/chaitanyakasaraneni/genderdetection/blob/master/images/modified_top_layer.png "Layers to be trained on")
