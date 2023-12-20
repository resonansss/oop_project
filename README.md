# oop_project
Для проекта мы выбрали соревнование с сайта kaggle.com ‘Natural Language Processing with Disaster Tweets’. В этом соревновании необходимо было определить, в каких из твитов речь идет о настоящих катастрофах.
• В файле nlp-getting-started.zip находятся тренировочная и тестовая части датасета для обучения.
• В файле kaggleNLP.ipynb находится полный код по обучению модели.
• Также в репозитории есть презентация проекта и файл с лучшими предсказаниями модели для проверки в keggle

МЕТРИКИ ОЦЕНКИ:
-precision;
-recall;
-f1-score;
-матрица ошибок.

ИТОГОВАЯ МОДЕЛЬ:
-классификатор – LogisticRegression;
-токенизатор взят из библиотеки nltk;
-векторайзер - CountVectorizer;
-используем униграммы;
-учитываем стоп-слова и пунктуацию.

Результатом совместной работы является модель с точностью предсказания на уровне 80%. Итоговое место в рейтинге kaggle по соревнованию – 509 из 1184.
