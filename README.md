# Forum for Information Retrieval Evaluation - Conference

## Information Retrieval from Microblogs during Disasters (IRMiDis) 2022

#### Task 1: The dataset provided contained 4392 tweets for training and 717 tweets for testing. Every tweet in the dataset was labelled as one of 3 stance reflected towards COVID-19 vaccines, as explained below: <br>
`AntiVax` - The tweet expresses reluctance on the part of the user who tweeted it to utilise vaccines. <br>
`ProVax` - The tweet endorsing or promoting the use of vaccinations. <br>
`Neutral` - The tweet does not clearly reflect any opinion about vaccines or has nothing to do with vaccines. <br>

#### Task 2: The dataset provided contained 1574 tweets for training and 400 tweets for testing. Every tweet in the dataset was labelled as one of 4 classes, that report someone experiencing COVID-19 symptoms, as explained below: <br>
`Primary Reporting` - The tweet's submitter is outlining personal symptoms. <br>
`Secondary Reporting` - The user is outlining the signs of a friend, family member, neighbour, or recent acquaintance. <br>
`Third-party Reporting` - A third party or famous person's symptoms are being referenced by the user. <br>
`Non-Reporting` - The user is not claiming that anyone is displaying COVID-19 symptoms and is instead utilising symptom-words in a different context. This collection of tweets only offers general information on COVID-19 symptoms; no specific people who may be experiencing these symptoms are mentioned. <br>


### Methodolgy
After preprocessing, we used tweets to train specialised algorithms such as Word2vec and BERT to efficiently handle sentence classification. The process of a deep learning-based transformers technique was applied. It helped in getting correct perceptions of the text and quickly establish them with the associated labels in the data. 

### Results :

##### Task 1 (Rank 4)
Accuracy: 0.529 <br>
Macro F1 Score:  0.503 <br>

##### Task 2 (Rank 2)
Accuracy:  0.790 <br>
Macro F1 Score:  0.740
