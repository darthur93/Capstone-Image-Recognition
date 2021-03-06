# Capstone-Image-Recognition
## Introduction
Technological pursuit has been fundamental to human prospering  since the beginning.
From Prometheus bringing fire, to Loki crafting the first net, we have mythologised the technological progress
However we are feeble creatures and our pursuits are imperfect
With technology, 
We are as new lovers 
All eager innocence and elbows
Our attempts to connect through social networks, have created more alienation
Our cure of hunger has created an epidemic of obesity.
Indeed, even Prometheus ended chained to a rock, and Loki ensnared the the very net he invented

We are no longer what we were, we were born in the changing tide of advancement.
Now is the time for a mature stance on progress.
We must make things fit us, not make us, fit the things we make.

This leads me to introduce Nature’s Eye
It is an educational app that will allow users to interact with what they see.
The general idea is that users will be able to take a picture, initially of an animal. 
And a model will identify the animal, then link useful educational information related to what was identified.

## Data Understanding

![antelope1](https://user-images.githubusercontent.com/92397941/151287811-5db0bad2-53f2-445d-9bd0-a7aa8cb1c6e1.jpg)\
![bear2](https://user-images.githubusercontent.com/92397941/151287842-ff6ca184-3ffe-41c8-9836-8f3599a53bf3.jpg)\
![caterpillar1](https://user-images.githubusercontent.com/92397941/151287860-c617fcb2-544f-4e33-8231-04350f1b6411.jpg)\
I chose a data set with 5000 images of 90 different animals, from Kaggle There is a lack of data with only 60 instances of each class. This is the primary limit of the data. I will need to collect more photos to compensate for this. This data is useful because it has already been labeled with the class of animal and will reduce preprossing time. Since the data is just an image and is associated class, all the data will be included.\
Links to access the data are in the notebook.
## Modeling
To get a general understanding on how nerual network 'learn' to identify pictures. First the model has an imput of all the pixels of the image, then it subdivides the image into smaller units. It then finds patterns of these smaller units to make predictions about the classification of an image. For more infomation this a link to a useful source. https://stackabuse.com/image-recognition-in-python-with-tensorflow-and-keras/
![image](https://user-images.githubusercontent.com/92397941/150362319-7029fa69-1e60-4362-992b-ec8ac30a84ae.png)
![image](https://user-images.githubusercontent.com/92397941/150362354-53cf5ee7-0a36-4c1e-b0d8-2651c806a9fa.png)\
I will be using the accuracy metric, because of the low cost of false positives. My final Model is the Dense Net, which had an accuracy score of 13% on training data The model had an accuracy of 11% on testing data This Model is not good enough for it to be deployed. It first needs to be improved


## Summary
My model only has an accuracy of 13% so it needs improvement.
First, I going to get more data, this is clearly a huge reason that my model is less accurate than i would like
Next, I would like to radically expand the domain of the model, to incorporate more animals as well as plants, stars, even famous artwork and architecture
Finally, when the model is performing at a non comedic level, I will create an app, so that people will have acces

├── README.md                               <- The top-level README for reviewers of this project\
├── Notebook.ipynb                          <- Concise summary of the project with all data science steps\
├── Slides.pdf                              <- PDF version of project presentation\
├── Archive                                 <- Both sourced externally and generated from code, includes exploratory notebooks\
└── Images                                  <- Both sourced externally and generated from code\
