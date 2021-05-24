# simpsons_facial_recognition
Using a convolutional neural network to develop a facial recognition algorithm on characters from the Simpsons.

In this project, I am aiming to build a facial recognition model that will be able to look at a certain frame from the Simpsons and identify which character is prominently featured. While this may be a bit more simplistic version of facial recognition, it is a valuable stepping stone in more intricate models which would take in real world faces and images.
	
In terms of my data source, I would be pulling around 20,000 frames from various episodes of The Simpsons, organized into folders for 20 of the most prominent characters, separated into training and testing data. (Accessed here). I then would have to access those images from google colab to resize them to be the same shape, convert them all into arrays which I could work with and save them to a npy file which I could work with later on. I also needed to build out the target data for both training and testing sets. After downloading all of the images, I reformatted them and processed them in this notebook. (I have already done a fair amount of work on this).

After all this preprocessing, I hope to build out a convolutional neural network to recognize the characters contained within the images. This will require some external research, but I will build off of the skills I have developed in my supervised learning and deep learning modules. This work is also sharpening my python and research skills, as I have already learned a lot in the processing of these images.

I think that during this project, building the neural network will require a lot of trial and error. Model optimization is a huge part of data science, and figuring out how best to train my neural network to identify these characters will be a challenge I look forward to tackling.
