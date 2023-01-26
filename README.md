# Sentiment-Analysis-on-Twitter-Hate-Speech
Hate speech dataset - SemEval 2019 (Hateval)
https://competitions.codalab.org/competitions/19935#learn_the_details-overview

All data for the competition are collected from Twitter.

According to the need of the task and related subtasks, for each tweet each dataset will include:

    a numeric ID that uniquely identifies the tweet within the dataset
    the text of the tweet
    a binary value (1/0) indicating if hate speech is occurring against one of the given targets (women or immigrants)

An annotated tweet is a tab-separated line with the following pattern:

    id[tab]text[tab]HS

where 'id' is a progressive number denoting the tweet, 'text' is the given text of the tweet
while the other parts of the pattern (given in dev and training data and to be predicted in testing data) is whether Hate Speech (HS) is present (1) or not (0).

    42648663[tab]USER_NAME Stupid ugly cunt who needs to die[tab]1

More information about the Hateval dataset in the following paper:

@inproceedings{basile2019semeval,
  title={Semeval-2019 task 5: Multilingual detection of hate speech against immigrants and women in twitter},
  author={Basile, Valerio and Bosco, Cristina and Fersini, Elisabetta and Nozza, Debora and Patti, Viviana and Pardo, Francisco Manuel Rangel and Rosso, Paolo and Sanguinetti, Manuela},
  booktitle={Proceedings of the 13th International Workshop on Semantic Evaluation},
  pages={54--63},
  year={2019}
}
