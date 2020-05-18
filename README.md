# dlnd_tv_script_generation
Generate Seinfeld TV script using PyTorch LSTM 


This project takes existing script data from the TV series, Seinfeld, and applies word2Vec LSTM approaches to generate a new script. This is a Udacity project in the Deep Neural Networks course.

 Data is loaded and prepped such that the target is the next predicted word in a sequence of words. Sequence length and batch sizes are variable, as are the hyperparameters. 
