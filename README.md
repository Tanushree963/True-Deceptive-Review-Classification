# True-Deceptive-Review-Classification
In this project we have classified true and deceptive hotel reviews with the help of **Random Forest Classifier**.The dataset used to train this model 
is the Deceptive Opinion Spam Dataset

## Understanding the Deceptive Opinion Spam Dataset
The Deceptive opinion spam dataset is a corpus consisting of truthful and deceptive hotel reviews of 20 Chicago hotels. 
The corpus contains:
```
400 truthful, positive reviews from TripAdvisor
400 deceptive positive reviews from Mechanical Turk
400 truthful, negative reviews from Expedia, Hotels.com, Orbitz, Priceline, TripAdvisor, and Yelp
400 deceptive negative reviews from Mechanical Turk
```
In total we have 1600 reviews, the task is to classify review either as truthful or deceptive hotel reviews.

N.B: There is a strong distributional difference between informative and imaginative word, 
the former typically consists of more nouns, adjectives, prepositions, determiners, and coordinating conjunctions,
while the latter includes more verbs, adverbs, pronouns, and pre-determiners. Deceptive opinions contain more superlatives since deceptive writing often contains exaggerated language.
