# Tweet-Geolocation-Classifier
Built a geolocation classifier for Tweets. That is, given a tweet, the system will produce a prediction of where the tweeter is located. For this project, the set of relevant
locations (target classes) is limited to the following three states that are well–represented in the dataset: New York, California, and Georgia.

Data Sets:
1. **RAW Tweets datasets** with the format:
          Tweet_id, User_id, tweet text, location (new line)
2. **ARFF format datasets**: In these files, each instance corresponds to a single tweet, and we have calculated the frequency of some marginally useful terms as attribute values, determined using the following procedure:  
• Pre-processed the training tweets to remove non-alphabetical characters  
• Recorded the term frequency for the top 10, 20, 50, 200 terms according to document frequency  
• Used the method of Mutual Information to determine the best 10, 20, 50, and 200 terms for each of 3 classes (removing the duplicate terms)

Algorithms implemented for classification:
1. Naive Bayes
2. Random forest

Software used: **Weka**
