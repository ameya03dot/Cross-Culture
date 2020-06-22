# Project Name - Cross-Culture Emotion Recognition
Define a way using CNN to examine emotions from different cultures and compare to see how different or same they are from each other.

The 3 datasets that were choosen for this project are Radvess Dataset(North American), Canadian French Dataset, and the EMOVO(Italian Dataset). Each dataset can be easily found on the internet and are free of charge. Since each dataset had to be combined to make one dataset, we had to make certain changes. Certain Pre-processing was done for this. The CNN Model was trained on the English dataset and and then tested on the North American and the Italian dataset. The machine obtained and accuracy of 71.10% for Canadian French,71.90% for Italian and 73.89% for English Dataset. This goes to show that it does not matter what the speaker is saying,rather how exactly he is saying which determines the emotion at hand.

The documentation for each dataset is contained in thier respective files and have clear information abou them.

The code itself was obtained from another source and is not ours to begin with. We simple modified the code to our specifications and used it.

There are 6 traditional emotions that include Anger,Sad,Disgust,Calm,Happy,Surprise and a 7th emotion as Neutral. For our Project we chose to focus on Anger,Sad,Calm and Happy as they are very distinct emotions. Due to less number of samples for training and testing,we used Data Augmentation which effectively increased the number of samples thrice.
