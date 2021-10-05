# Rugby-vs-Soccer-Image-Classification
GOAL: The project aims to classify the sports between rugby and soccer.

## Introduction      
Convolutional Neural Networks come under the subdomain of Machine Learning which is Deep Learning. Algorithms under Deep Learning process information the same way the human brain does, but obviously on a very small scale, since our brain is too complex (our brain has around 86 billion neurons).          
Image classification involves the extraction of features from the image to observe some patterns in the dataset.           
There are multiple convolutional layers extracting features from the image and finally the output layer.       

![image](https://user-images.githubusercontent.com/66559579/136025976-a86c64c7-b4e8-4a28-953a-cf94e1fb435e.png)

## Libraries Need
  Pandas      
  Numpy         
  Matplotlib            
  Seaborn
  os      
  cv2      
  sklearn     
  keras      
  
## What I had Done
Firstly,I have import the data and distinguish the image & assign the respective labels of the sports for training purpose.            
Then i convert the image into array and normalize the array and reshape so that every image should have the same size.

Data augmentation techniques used to increase the amount of data by adding slightly modified copies of already existing data.        
It acts as a regularizer and helps reduce overfitting when training a machine learning model.         
After augmentation,applied simple CNN  archetiture to the train data & acheived 67% accuracy on test data.

Applied Transfer Learning in search of higher accuracy,so create a base model from the MobileNetV2 model. by using a pre-trained model on similar images we can easily achieve high performance. 
Since our problem statement is a good fit for transfer learning,implementing a pre-trained model and hooray we significantly acheive a better accuracy.

## Conclusion
Implemented Simple CNN on the data but didn't acheive higher accuracy.So,get a help from Transfer Learning to acheive Higher accuracy.
