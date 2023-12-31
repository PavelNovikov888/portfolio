# Определение влияния рекламы чая на продажи  
---------
# Оглавление  
----------  
[1.Описание проекта](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9#1%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)  
[2.Общий вывод](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9#2%D0%BE%D0%B1%D1%89%D0%B8%D0%B9-%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4)  
[3.Датасет](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9#3%D0%B4%D0%B0%D1%82%D0%B0%D1%81%D0%B5%D1%82)   

# 1.Описание проекта  
Оценим, есть ли влияние от рекламы чая «Ахмад» в передаче «Что? Где? Когда?» на его продажи.  
Произвем парсинг данных о датах проведения передачи «Что? Где? Когда?».  
Построим boxplot, определим наличие аномалии роста продаж после передачи.  
Построим модель, предсказывающая значение временного ряда продаж.  
Определим есть ли статистически значимая разница между предсказанием и реальными продажами.  
  Осуществим кластеризацию точек продаж (по всем трём вендорам) и определим аномалии.    
# 2.Общий вывод  
Статистические тесты показывают наличие разницы в продажах.
Прогнозы вполне совпадают с фактической продажей, что не говорит в пользу наличия роста уровня продаж выше стандартного отклонения.  
Выявление аномалий с точки зрения кластеризации субъективно и может трактоваться по разному, хотя аномалий вызванных рекламой явно нет.   
Так что существующая разность средних вызвана скорее иными, чем реклама в популярной передаче.  
# 3.Датасет
tea_demand.zip  
Размер: 2КБ
 
:arrow_up: [к оглавлению](https://github.com/PavelNovikov888/portfolio/tree/master/%D0%94%D0%B5%D1%82%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B0%D0%BD%D0%BE%D0%BC%D0%B0%D0%BB%D0%B8%D0%B9#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)
