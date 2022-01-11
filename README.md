# NLP-disaster-tweet

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). But, it’s not always clear whether a person’s words are actually announcing a disaster.

We will build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t using a dataset of 10,000 tweets that were hand classified.

The text preprocessing is made up of six main steps which are: Lowercasing, Entities, URL Links and Punctuation Removal, Spelling Correction, Filling Missing Data, Lemmatization and Stop Words Removal. In the model section, transfer learning is used to create word embeddings.
