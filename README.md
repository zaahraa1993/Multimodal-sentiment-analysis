# Multimodal-sentiment-analysis
this approach leverages the strengths of different models, allowing the meta_classifier to make more informed predictions based on the combined knowledge from both RNN and BERT models.

1) RNN Model:
   we train an RNN model on the IMDB dataset and save the predictions.
2) BERT Model:
   we train an BERT model on the IMDB dataset and save the predictions.
3) Meta-classifier:
   we combined the predictions from the RNN and BERT Models and train a meta-classifier (logistic regression) to make the final predictions.

 we have ensured both RNN and BERT Models use the same train, validation, and test splits by saving and loading the splits.
