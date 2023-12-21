# Классификация сообщений(спам/неспам)
-------
# Оглавление  
[1.Описание проекта](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#1%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)  
[2.Особенности и функциональность](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#2%D0%BE%D1%81%D0%BE%D0%B1%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%B8-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D1%8C)  
[3.Установка](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#3%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0)  
[4.Использование](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#4%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)  
[5.Датасет](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#5%D0%B4%D0%B0%D1%82%D0%B0%D1%81%D0%B5%D1%82)  
--------

# 1.Описание проекта
Есть размеченые данные о sms-сообщениях, необходимо создать модель классификации текстов наилучшим способом определяющиюю спам и неспам.
# 2.Особенности и функциональность
Для создания модели используем векторизацию текста CountVectorizer() и байесовские алгоритмы классификации ComplementNB и MultinomialNB
# 3.Установка
Зависимости находятся в файлах requirements.txt и environment.yml
# 4.Использование
Принцип построения модели классификации можно применить на любых текстовых данных.  
# 5.Датасет
 Данные находятся по [ссылке](https://drive.google.com/file/d/1MZYZV-5B2lTJR-tLcxtEg5Vs0DlXVi2_/view?usp=sharing)  
 Название файла: spam_or_not_spam.zip  
 Размер: 1,1 МБ
  
:arrow_up: [к оглавлению](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%91%D0%B0%D0%B9%D0%B5%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%D0%BF%D0%B0%D0%BC%D0%B0#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)
