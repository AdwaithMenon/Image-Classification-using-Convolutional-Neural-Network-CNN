# _**Image Classification Using Convolutional Neural Network (CNN)**_

## **Project Description**

* The goal of this project is to  to develop a Convolutional Neural Network (CNN) model that can accurately classify an insect as either a Honey Bee or a Wasp. 

* Insect stings can vary in intensity depending on the insect, and this is largely due to the varying compounds present in their venoms.Scientists have determined that these two insects have different venom chemical compositions, necessitating different antidotes. 

* Additionally, individuals can be allergic to different types of venom, further highlighting the importance of accurately identifying the insect before administering treatment.

* Since Honey Bees and Wasps can look very similar to the naked eye, our CNN model would provide a valuable tool for correctly identifying the insect and selecting the appropriate antidote.

## **Methodology**

a) **Data Collection:** Data for the model was collected using the Bing Image Downloader. Specifically, 200 images of Honey Bees and 200 images of Wasps were downloaded. These images were then resized to 1./255.

b) **Data Preparation:** The data was divided into three sets: a training set, a validation set, and a test set. The training set was used to train the CNN, while the validation set was used to improve the performance of the model. Labels were also created for each image, specifying whether it is a Honey Bee or a Wasp.

c) **Model Building:** A CNN model was built using Keras, which is a high-level neural networks API. The model was built using MaxPooling, Dense, and Flatten layers. Binary cross-entropy was used as the loss function and Adam was used as the optimizer. Accuracy was specified as the metric to evaluate the performance of the model.

d) **Model Training:** The training set was used to train the model. The number of epochs was set to 10 and the batch size was set to 20 . The model's performance was evaluated after each epoch using the validation set.

e) **Model Evaluation:** The performance of the model was evaluated using the test set. The accuracy, loss, confusion matrix, support, precision, recall, and F1-score were calculated to determine the model's performance.


## **Model Architecture**

<img width="308" alt="image" src="https://user-images.githubusercontent.com/70052374/226969153-61b900fb-9158-43bf-b3c3-2408d1bd2503.png">


## **Model Evaluation**



## **Analysis**

* To improve the model's accuracy, new data can be artificially generated from existing data through the process of data augmentation.

* Prior to data augmentation, the overall accuracy of the model on the validation set was **0.642.** 

* However, following the implementation of data augmentation, the model's accuracy improved to **0.724** on the validation set.
