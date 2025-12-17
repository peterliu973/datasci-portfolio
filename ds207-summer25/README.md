# Abstract: Google Merch Store Churn: Predicting Sale Conversion Using Machine Learning

This project investigates whether a user session on the Google Merchandise Store will result in a purchase, framing the conversion prediction as a binary classification task to help businesses reduce unnecessary marketing spend on broad strategies and instead focus resources on high-potential sessions. The input data is session-level information, including traffic source, user behavior metrics (like pageviews and timeOnSite), and technical details (like device\_category), with the target variable being `session_convert` (1 if a transaction occurred, 0 otherwise),. The primary challenge was the extreme class imbalance, where converting sessions represented only 2.5% of the data, which was addressed by upsampling the minority class to 15% and tuning model hyperparameters,. Among the models evaluated, including logistic regression, k-nearest neighbors, neural networks, and random forests, the hyperparameter-tuned random forest model emerged as the best performer, achieving the highest precision (0.76), recall (0.996), and an F1 score (0.86) on the positive class,. This demonstrates that well-tuned classical ensemble models can outperform more complex architectures like Convolutional Neural Networks (CNNs) with embeddings on structured tabular data, providing a strong predictive baseline for identifying high-value sessions and optimizing marketing efforts,.


[Check out this report](Final____DS207_Project_Final_Report.pdf) and [this notebook](peter_models.ipynb)

<p align="center">
  <img src="banner_ds207.jpg" width="600">
</p>
