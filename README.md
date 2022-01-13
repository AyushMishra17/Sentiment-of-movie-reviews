# Sentiment-of-movie-reviews
I label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive. Obstacles like sentence negation, sarcasm, terseness, language ambiguity, and many others make this task very challenging.

This project uses datasets available on kaggle for training and testing.




![image](https://user-images.githubusercontent.com/97682962/149369236-02b3e795-325e-4be0-be50-e23a095107b9.png)
Transformers brings all these models together and makes it very easy to use each with only a few lines of code. In fact they even provide us with cool tools like pipelines or live demo that we can classify our text without any training or long periods of coding. But as you can geuss these simple and ready to use models have their weaknesses. For example, you can't classify the text with them with the number of labels you want because they've been pretrained on a text with specific labels. Also not all models used by them are as strong and accurate as we want them to be(for example the default model for sentiment analysis is uncased distillbert which is not the best model we can find out there). With all these in mind, we want to train .Transformers models on our own data with the models that we prefer.
