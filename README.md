# AI-security
A classification model trained on CIFAR 10
Introduction:
This is a simple CNN model that is trained on CIFAR 10 dataset, which is to make classification between 10 different kinds of objects.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
And I download the whole dataset and use it locally
Network Architecture is shown below:
 ![image](https://user-images.githubusercontent.com/50764328/136697968-3f051634-addd-4a42-8e87-3fd58ff10750.png)

To evaluate the model, I use the predicting accuracy and test accuracy. At the same time, I draw the confusion matrix and plot the accuracy versus epoch. Because all of them looks similar and have no obvious difference, I do not add it to the comparation for the change of the hyperparameter.
	For the change of the hyperparameter, I choose the learning rate. The learning rates I choose are 0.0001, 0.00007 and 0.0003, that might influence the training speed and the final accuracy. As all of them are quite small, I choose the epoch to be 100 so that the model is fully trained.
For 0.0001:
 ![image](https://user-images.githubusercontent.com/50764328/136697978-e2de73de-f9bb-49b0-9b76-b6d8b773b985.png)

For 0.00007:
![image](https://user-images.githubusercontent.com/50764328/136697988-b385f0d3-1faa-4173-9909-7c7cd006af3e.png)
![image](https://user-images.githubusercontent.com/50764328/136697993-8171de2a-4e13-4e97-bb6e-5cfd01c3b09a.png)

 			
 	  
		 
 	 	
For 0.0003:
 ![image](https://user-images.githubusercontent.com/50764328/136697999-eef30cd6-0bdb-48db-ab31-6dc9954d23e0.png)
![image](https://user-images.githubusercontent.com/50764328/136698002-92e30794-8ef4-4a03-bf32-bc0008b4918d.png)

It is clear that when the learning rate is high, it is more likely that the model is trained more quickly while its final accuracy is a little lower and go to overfit earlier.
But when the learning rate is really low, it means that you should train the model for more epoches, which means much longer time and caculations. An appropriate learning rate is needed
			
			
 			 
 			
 			
		
