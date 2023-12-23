# Название:
### Тип:
---------
## Оглавление
[1.Описание](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%AF%D0%B4%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%20%D0%B2%D1%8B%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%BD%D0%B0%20%D0%A2%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D0%BA%D0%B5#1%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)   
[2.Справочная информация](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%AF%D0%B4%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%20%D0%B2%D1%8B%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%BD%D0%B0%20%D0%A2%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D0%BA%D0%B5#2%D1%81%D0%BF%D1%80%D0%B0%D0%B2%D0%BE%D1%87%D0%BD%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F)   
[3.Резюме](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%AF%D0%B4%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%20%D0%B2%D1%8B%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%BD%D0%B0%20%D0%A2%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D0%BA%D0%B5#%D1%80%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5)

## 1.Описание
В целях повышения качество предсказания количества выживших пассажиров 
построить и сравнить модели:
- Наивный байесовский классификатор
- Логистическая регрессия
- Дерево решений
- K Ближайших соседей
- Случайный лес
- SVM с RBF
- Xgboost
Данные:   
Survived: результат выживания (0 = нет; 1 = да)  
Pclass: социально-экономический класс (1 = высший класс; 2 = средний класс; 3 = низший класс)  
Name: Имя пассажира  
Sex: Пол пассажира  
Age: возраст пассажира (некоторые записи содержат NaN).  
SibSp: количество братьев и сестер и супругов пассажира на борту  
Parch: количество родителей и детей пассажира на борту  
Ticket: номер билета пассажира.  
Fare: тариф оплачивается пассажиром.  
Cabin: Номер кабины пассажира (некоторые записи содержат NaN)  
Embarked: Порт посадки пассажира (C = Шербур; Q = Квинстаун; S = Саутгемптон)    

## 2.Справочная информация
|Характеристика| Описание |
|-|-|
| Тип задачи |Задача классификации|
| Библиотеки | sklearn |
|<!-- -->|<!-- -->|
| Данные |titanic.csv |
| Подготовка данных | Feature Engineering, Data Preprocessing, get_dummies, StandardScaler |
| Тип валидации | cross_val_score|
|<!-- -->|<!-- -->|
| Модели ML | GaussianNB, LogisticRegression, KNeighborsClassifier, RandomForestClassifier, SVC|
| Метрика | accuracy |

## Резюме
Model	Score  
Naive Bayes	72.6%  
Logistic Regression	82.1%  
Decision Tree	77.6%  
K Nearest Neighbor	80.5%  
Random Forest	80.6%  
Support Vector Classifier	83.2%  
Xtreme Gradient Boosting	81.8%  
По результатам сравнения различных классификаторов наилучшие результаы показывает Support Vector Classifier	

:arrow_up: [к оглавлению](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%AF%D0%B4%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%20%D0%B2%D1%8B%D0%B6%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%BD%D0%B0%20%D0%A2%D0%B8%D1%82%D0%B0%D0%BD%D0%B8%D0%BA%D0%B5#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)
