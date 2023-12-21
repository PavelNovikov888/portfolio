# Кейсы выполненые с использованием Tableau

[1.Описание задачи](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8)

[2.Какой кейс решаем?](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BA%D0%B5%D0%B9%D1%81-%D1%80%D0%B5%D1%88%D0%B0%D0%B5%D0%BC)

[3.Краткая информация о данных](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)

[4.Этапы работы над проектом](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D0%BD%D0%B0%D0%B4-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%BC) 

[5.Результат](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82)


### Описание задачи

Изучаем данные о продажах в супермаркетах Северной, Центральной и Южной Европы

### Какой кейс решаем?

Построим 3 дашборда для знакомства с основными и расширенными возможностями Tableau.

*Что практикуем*

Учимся работать с данными, в частности строить дашборды с использованием инструментов визуализации Tableau.   

Учимся подключатся к PostgreSQL c целью выгрузки нужных данных.  

Учимся преобразовывать данные, писать меры с помощью инструментов Tableau и с помощью языка DAX.  

Учимся создавать шлюзы для выгрузки данных и настройку обновлений.  

Учимся публиковать дашборды в Tableu Public

### Краткая информация о данных

Данные находятся в базе данных PostgreSQL.  

Database: skillfactory  

Файл EU Sample Superstore

### Этапы работы над проектом

1. Начнём с подключения к источникам данных.  
2. Изучим, как создавать визуализации и использовать расчётные формулы.  
3. В конце модуля мы объединим созданные визуализации в интерактивный дашборд.  

### Результат  

[Анализ клиентов](https://public.tableau.com/views/Customer_analysis_Novikov_Pavel/sheet5?:language=en-US&:display_count=n&:origin=viz_share_link)

В данном дашборде отражена следующая информация:
1. Основные показатели:
- Объём продаж (sales)  
- Прибыль (profit)  
- Прибыльность в %  
2. Динамика продаж (sales) по годам и кварталам
3. Объем продаж по подкатегориям (sub category)
4. Диаграмма прибыли и объема продаж по клиентам

[Анализ продаж](https://public.tableau.com/views/Analisys_sales_Novokov_Pavel/sheet24?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

В данном дашборде отражена следующая информация:
1. Динамика продаж и прогноз  
2. Карта продаж  
3. Продажи по продукту
4. Продажи по подкатегориям  

[Анализ показателей](https://public.tableau.com/views/analysis_of_indicators_Novikov_Pavel/sheet6?:language=en-US&:display_count=n&:origin=viz_share_link)

1. Прогноз по категориям   
2. Продажи по категориям накопительным итогом  
3. Динамика продаж и прибыли  
4. Зависимость прибыли от скидки  
5. Когортный анализ по товарам  
6. Прибыль в сегментах по странам  


:arrow_up: [к оглавлению](https://github.com/PavelNovikov888/practical_work/tree/master/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%20%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/Tableau#%D0%BA%D0%B5%D0%B9%D1%81%D1%8B-%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D1%8B%D0%B5-%D1%81-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%D0%BC-tableau)
