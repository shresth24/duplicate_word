# duplicate_word
#ABOUT THE DATASET:
the samples dataset have been taken form kaggle from a online contest organised by quora
The goal of this competition was to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.

Please note: as an anti-cheating measure, Kaggle has supplemented the test set with computer-generated question pairs. Those rows do not come from Quora, and are not counted in the scoring. All of the questions in the training set are genuine examples from Quora.

Data fields
id - the id of a training set question pair
qid1, qid2 - unique ids of each question (only available in train.csv)
question1, question2 - the full text of each question
is_duplicate - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.
 TEXT PREPROCESSING:
 Firstly random forest classifier was used to oredict the accuraccy on the naive data 
 then Text preprocessing ws applied by adding 22 more features
 which were classifies as:
 1->length based features
 2->Token Features
 3->Fuzzy Features
 finally the accuracy of 79%(approx) was achieved
 there are more scope in increasing the accuracy of the project by running the code in cloud platform,increasing the dataset,increasing the features count etc.
