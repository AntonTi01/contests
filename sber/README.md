# sber_ds_task
Содержит выполненное задание на поиск антифрода SBER


**Основные выводы**

1. Данные были загружены и изучены на этапе EDA
2. Данные были предобработаны: проскалированы, устранены NaN, созданы дамми переменные для категориальных признаков
3. Были обучены три модели:
  - CatBoost на топ 20 важных фичей и на всех
  - RandomForestClassifier на всех фичах
  - Нейронная сеть на всех фичах

Результаты: 
 1. CatBoost на всех фичах: на валидации 0.975, **на тесте 0.9014**
 2. RandomForestClassifier: на валидации 0.95, **на тесте 0.9074**
 3. Нейронка значительно отстает, на тесте 0.88
