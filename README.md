# COMP5318
Sentiment140 dataset with 1.6 million tweets

Dataset from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140).

In this case, only using a subset which contains [**300k** tweets](https://drive.google.com/file/d/1w9vysV8MIl_6LF26XFZlfCbyG2MbDj--/view)(lacking of GPU time). Evaluating the performance by 60,000(20%) tweets and training the model on 240,000(80%) tweets and finally achieving **81%** accuracy.

The final model is constructed by 2 layers of **Bi-LSTM**, followed by **CNN**. And the output is logist.

![network architecture](network_architecture.png)


