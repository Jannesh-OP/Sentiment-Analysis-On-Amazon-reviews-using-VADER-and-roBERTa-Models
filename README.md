# Sentiment-Analysis-On-Amazon-reviews-using-VADER-and-roBERTa-Models

1) First I have imported the "Amazon Food review Dataset"[ UNLABELED ]
2) The dataset consist of around 5lakh samples and was highly imbalanced.("with respect to star ratings")
3) So I have performed Undersampling and balanced the data.
4) Then I have done a crisp EDA on the dataset.
5) Then I have classified[[(i.e) sentiment analysis] the reviews using VADER[Valence Aware Dictionary and sEntiment Reasoner], and merged the outcomes to the dataset.
6) Then I have classified the reviews using roBERTa[Robustly optimized BERT approach], and again merged the outcomes to the dataset.
7) Also I have performed an analysis of the performance of both Models, by manually collecting samples(using core python techniques) that have been classified differently by the models.
