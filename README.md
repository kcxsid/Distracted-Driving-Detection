# Distracted-Driving-Detection



<!-------------> 


Distracted driving describes the act of driving while engaged in any activity that draws 
drivers’ attention away from the road. Identifying distracted driving is important because they 
are much more likely to be involved in an accident, and they are a threat to other road users. 

This project aims to aid government efforts to curtail preventable road accidents by 
building predictive models to enhance the capabilities of newly implemented driver monitoring 
technology, with novel methodology from the disciplines of computer vision and deep learning.

The dataset to be used has been purpose-built and was published to Kaggle by State 
Farm Insurance. It contains images of drivers seated at the steering wheel of a car, exhibiting 
various behaviors, some of which are negligent and dangerous (State Farm Distracted Driver 
Detection | Kaggle, 201). Images of the dangerous activities are grouped   into a set labelled 
‘distracted’ and subsequently attempted to build a model capable of autonomously identifying 
reckless behavior. The dataset to be used contains over 22,000 labelled colour photos of 81 different 
individuals driving a variety of vehicles, performing 10 distinct tasks.

The task of autonomous detection of distracted drivers by  processing image data with a variety 
of techniques from the discipline of deep learning (i.e. 
Convolutional Neural Networks, Transfer Learning) is performed. A classification model with a 
validation accuracy of 85.71% and a test accuracy of 62.17% is hence obtained. 

## The approach of Deep Learning is performed using CNNs. 

### VGG 16 (CNN):
![image](https://user-images.githubusercontent.com/31934083/182610762-f9e3976c-ef1e-49d8-a9fa-51814882dbe5.png)

### ResNet (CNN): 
![image](https://user-images.githubusercontent.com/31934083/182610892-3ddbe27b-f8bf-428e-8efd-591e69776f4e.png)

### Activation Functions:
![image](https://user-images.githubusercontent.com/31934083/182611001-6460d855-1082-4c6d-aa0a-75a3a750292a.png)

### Model Accuracies: 

<img width="908" alt="image" src="https://user-images.githubusercontent.com/31934083/183368801-65eb0de5-3e43-402a-ac80-569026af87cb.png">

<img width="908" alt="image" src="https://user-images.githubusercontent.com/31934083/183368722-d02bdba0-1e5e-4ae4-8167-29f4615747fa.png">


<img width="908" alt="Screen Shot 2022-08-08 at 5 54 04 pm" src="https://user-images.githubusercontent.com/31934083/183368372-d52d54b7-d523-42f9-8bae-46328344b9b5.png">

The accuracy of ResNet was 73.93% and VGG16 was 99.33% 

