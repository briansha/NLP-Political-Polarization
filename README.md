# NLP-Political-Polarization

## Analyzing Political Polarization in News Media with Natural Language Processing

Thesis work.

Classification_Pandas.ipynb notebooks: Training of machine learning models. There are six of these due to training time (can run four at once in parallel). Otherwise, training of models could have been comprised in one notebook.

Load_Picklefile.ipynb: Displays results and accuracy of each model against the overall dataset.

Top_Features_TFIDF.ipynb: Displays top TFIDF identifying features of differing political poles.

Top_Features_Frequency: Generates a Word Cloud regarding the frequency of key identifying features of differing political poles.

bag_of_features.xlsx: Top 40 TFIDF values of differing political poles trained on data where proper nouns were not considered as features for 18 models. Positive values correlate to words seen more frequently used by right-wing sources. Negative values correlate to words seen more frequently used by left-wing sources.

top40_18models_frequency_final.xlsx: Frequency of key identifying features of differing political poles. Some features had ratios scaled down so as to not overshadow other features when generating the Word Cloud in Top_Features_Frequency. (Original frequencys: chop - 23:1, wuhan virus: 22.91:1, right wing: 74:1). Positive values correlate to words seen more frequently used by right-wing sources. Negative values correlate to words seen more frequently used by left-wing sources.

Copyright &copy; 2020 Brian Sharber
All rights reserved
