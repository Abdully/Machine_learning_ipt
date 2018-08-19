# Week Three Report
On this week on train of Parrotai2018 I learned the various concept about the transfer learning,
Recommendation system and last is how to solve the machine learning problem. In older to to archive 
this the various tools used. Transfer learning this is machine learning method when developed for task 
is reused as the starting point to for a model on a second task. This method is very import due to help
develop the deep learning project due to deep network are expensive to train, this model is available 
online in older to use this first download this is more applicable due it helps to used when you have 
few datasets for example you have dataset of image of contain 120 pictures of image the transfer learning
solves this problem. In older to do this must use the transfer learning strategies there are
 * Feature extractor on this freeze all layer expect the final one. This model has many classifications 
 more than 1000 but the final layer change according to your problem for example your problem is binary classification
 it means that the output layer has two output.
* Data augmentation this is process which used to exiting image like adjust the colors, flipping it horizontal or
vertical, scaling, cropping and other methods you do this in older to make model easy in train in image 224 size is
used in cropping for train quickly.
* Fine-turning it consists of using the pretrained network on the base dataset and train all layers in the target 
dataset. On this your dataset is trained according to the model which already trained.



Recommendation engines this is more applicable on amazon, utube, Facebook and other it recommended according to user
or items. It helps to avoid the wastage of time, it filters the data using the different algorithm and recommend the 
most relevant items to users. How it works it recommended items to abuser which are most popular among all the users,
it dived the user into multiple segment based on user feature. The recommendation system dived i
nto three names
	Popular base recommends on this it recommend items views/purchased by most people recommendation. It bases on context, user 
feature, items feature, purchase history
*	Classification model it used feature of both products as well as user in older to predict whether a user will like
a product or not for example user feature are age, gender and example of product feature are cost, quality.
 * Nearest neighbor collaborative filtering dived into two part 
    * user-based collaborative filtering finds users who have a similar taste of products as the current user.
    Similarity is based upon similarity in user’ purchasing behavior.
    * Items-based Collaborative Filtering on this recommend items that are similar to the items the user bought.
    Similar is based upon co-occurrence of purchase.
* Model based Collaborative Filtering (matrix Factorization) in this identify latent (hidden) feature from input user x
items Rating matrix to represent users and items as vector in N dimensional space.


Last I learned about problem solution on machine learning. In machine learning before coding first understand the problem and
data. The dataset available will choose which algorithm will used. But on this week end discussed how to solve the machine learning
from start to end with practical on practical learned that some problem on dataset is not balance on target value most occur on 
classification problem in older to solver this in balance techniques is applicable. And also, confusion matrix is import in check
the result during validation and test.


