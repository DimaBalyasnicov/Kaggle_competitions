# Kaggle_competitions
Код соревнований с платформы Kaggle, так как сам Kaggle не позваляет мне подвердить аккаунт и показывать свой код там, храню его здесь:

1. House Prices - (housing_price_prediction_using_gradient_boosting.ipynb): Предсказание цены дома на датасете Ames Housing(Iowa).
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
2. Digit Recognizer (digit-recognition-with-cnn.ipynb) - Классическая задача распознования рукописных цифр на датасете MNIST.
https://www.kaggle.com/competitions/digit-recognizer
3. NLP with Disaster Tweets (nlp-disaster-tweets.ipynb) - Распознать в каких твитах говорится о настоящих катастрофах а в каких нет. В данном соревновании я специально не использовал предобученные модели вроде Bert и его вариаций, хотелось вручную проделать процесс NLU - очистка, токенизация и т.д.
https://www.kaggle.com/competitions/nlp-getting-started
4. Contradictory, My Dear Watson - задача NLI (Natural Language Inferencing), где даны данные состояшие из пар предложений - premise и hypothesis на различных языках, необходимо классифицировать так, что 0 - второе предложение логически следует за первым, 1 - предложения нейтральны (независимы), 2 - предложения противоречат друг другу. Модель - Base Bert, но данных для некоторых языков довольно мало. Здесь код c Google Colab, потом переносил обученную модель в Kaggle, так как Kaggle позволял вычислять только на CPU, а в Colab доступны GPU.
https://www.kaggle.com/competitions/contradictory-my-dear-watson/overview
 
Результаты после оценки тестовых данных Kaggle:
- Digit Recognizer - 0.98 Accuracy
- NLP with Disaster Tweets - 0.78 Accuracy, неплохо для модели в 3 скрытых ряда
- House Prices - 0.14 (или 14%) MAPE
- Contradictory, My Dear Watson - 0.61 Accuracy (micro average, по описанию, но не совсем понятно) 

