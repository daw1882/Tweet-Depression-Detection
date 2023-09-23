Authors: Rob Maron, Matthew Peeks, Dade Wood
Data File: depr_detect_data.csv
Code File: FinalProject_MaronPeeksWood.ipynb

=================================

Data:

The data in this project comes in a csv format with each row as a tweet and each column as some aspect of the tweet such as the user it originated from, the text it holds, time posted, depressed or not depressed, etc.


=================================

Project Code:

*** This code is meant to run in the google colab environment since it involves the installation of various packages ***

- DO NOT run any code in the data collection section, this is the code we used to gather data but is not meant to be run more than once to get everything in a csv file of twitter data

- DO NOT run the first cell of Feature Extraction. This cell uses Flair to assign a sentiment to each tweet but since it takes a few hours to process every tweet, these are already stored and saved in the data csv along.

- For all other code, run in sequential order to preprocess, extract features, and regenerate the two models and their evaluation scores.