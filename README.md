## IMAGE CLASSIFICATION

  Image classification is a supervised learning problem: define a set of target classes (objects to identify in images), and train a model to recognize them using labeled example photos.
		
Classification is a technique where we categorize data into a given number of classes. The main goal of a classification problem is to identify the category/class to which a new data will fall under. Classifier is an algorithm that maps the input data to a specific category.
	 	 
## WHY DO WE CLASSIFY IMAGES
	
The objective of image classification is to identify and portray, as a unique gray level (or color), the features occurring in an image in terms of the object or type of land cover these features actually represent on the ground. Image classification is perhaps the most important part of digital image analysis.

## SPORTS IMAGE CLASSIFICATION
		
		
This is a standard image classification challenge, where you need to build a classifier that can correctly decide which kind of sport appears on a given image.
		
we selected only 9 sport categories: badminton, basketball, baseball, icehockey, boxing, chess, fencing, football and hockey.
	  
## STRUCTURE OF DATA

	data/

		badminton/
	
			00000000.jpg
			
			00000001.jpg
			
			...
		...
		
## MODEL

	  	resnet-50
      
## REQUISITES
      
      	fastai
      	ImageDataBunch
      	cnn_learner
     
## BASE PAPER

https://www.researchgate.net/publication/330527726_Analysis_of_sports_image_detection_technology_based_on_machine_learning
