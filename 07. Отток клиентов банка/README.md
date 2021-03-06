# Отток клиентов банка

## Цель проекта
На основании анализа исторических данных о поведении клиентов банка построить модель, прогнозирующую, уйдет клиент в ближайшее время или нет.

## Вывод
Проанализировали данные, исследовали баланс классов (только 20% клиентов расторгают контракт с банком).

Обучили разные модели без учёта дисбаланса. Выбрали лучшую, затем повысили ее качество, разными способами решая проблему дисбаланса. В итоге выбрали лучшую модель (случайный лес), полученную при обучении со сбалансироваными весами классов (F1=0.61, AUC-ROC=0.85).

Проверили и подтвердили качество модели на тестовой выборке, получив F1=0.59 (что соответствует задаче проекта - довести метрику до 0.59). Дополнительно замерили AUC-ROC для теста: 0.85. Проверили и подтвердили адекватность модели.

## Используемые библиотеки
- Pandas
- Matplotlib
- NumPy
- Scikit-learn

## Статус
- [x] Завершен
