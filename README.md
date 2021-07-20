This is website text classification. There are 14 categories to be classified;
Travel, Education, Sports, Health and Fitness, Business/Corporate, E-Commerce, Games, Photography, Food, News, Computer and Technology, Law and Government, Steaming Services and Social Networking and Messaging

5 ML model was explored.
Multinomial Naive Bayes, Guassian Naive Bayes, LinearSVC, SVM and Random Forest Classifier.
LinearSVC gave the best performance with 94%.

SpaCy was used for the lemmatization process.
A combination of min_df=2, mid_df=3 with unigram, bigram and trigram was explored.

LinearSVC perform best for min_df=2 with trigrams. 
Multinomial peform best for min_df=3 with bigram. 
SVM perform best for min_df=3 with unigram.

Multinomial perform better using CountVecotrizer(), whereas LinearSVC and SVM perform better with TfidfVectorizer()
