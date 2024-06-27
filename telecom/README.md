# Выбор лучшей модели (ML) для оператора сотовой связи

[ipynb](https://github.com/satysh/portfolio/blob/main/telecom/project.ipynb)

## Описание проекта

Построил модель для оператора сотовой связи, которая предсказывает разорвёт ли абонент договор в ближайшее время

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **seaborn**
- sklearn.model_selection.**GridSearchCV**
- sklearn.linear_model.**LogisticRegression**
- sklearn.pipeline.**Pipeline**
- sklearn.preprocessing.**StandardScaler**/ **OneHotEncoder**/ **OrdinalEncoder**
- sklearn.compose.**ColumnTransformer**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**

## 

## Общий вывод

Было расмотрено 3 модели машинного обучения, среди них лучшей оказалась модель:
CatBoostClassifier со следующими гиперпараметрами:

* iterations=300
* learning_rate=0.1

Она показала следующий результат на тестовой выборке: **ROC-AUC=0.92**