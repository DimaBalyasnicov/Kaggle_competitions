# Kaggle_competitions
Код соревнований с платформы Kaggle:

1. House Prices - Advance Regression Techniques (sale-price-prediction-using-gradient-boosting.ipynb): Предсказание цены дома на датасете Ames Housing(Iowa).
2. Digit Recognizer (digit-recognition-with-cnn.ipynb) - Классическая задача распознования рукописных цифр на датасете MNIST. 
3. NLP with Disaster Tweets (nlp-disaster-tweets.ipynb) - Распознать в каких твитах говорится о настоящих катастрофах а в каких нет. В данном соревновании я специально не использовал готовые, предобученные модели (Transfer learning) вроде Bert и его вариаций, хотелось вручную проделать процесс токенизации и т.д..
 
Rankings:
- Digit Recognizer - 0.98 accuracy, 612 место из 1886.
- NLP with Disaster Tweets - 0.78 Accuracy,  652 место  из 965. Неплохо для простой модели в 2 скрытых ряда. 
- House Prices - 0.14 RMSE между логарифмом предсказанной величины и тестовой(логарифмы нужны чтобы ошибка в дешёвых и дорогих домах влияла одинаково) 2021 место из 4374

