# California Housing Price Prediction

Проект по предсказанию цен на жилье в Калифорнии с использованием классических алгоритмов машинного обучения

## Цель
Построить модель регрессии для предсказания цен на жилье на основе датасета California Housing

## Результаты
- R²: 0.77
- MSE: 0.21
- RMSE: 0.46
- MAE: 0.31

## Модели
- Использован алгоритм: Random Forest
- Алгоритм обучен с использвоанием кросс-валидации
- Использован grid search для подбора параметров

## Структура
- houses.ipynb: Проект выполнен целиком в одном ноутбуке.

## Применяем библиотеки
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- sklearn
- statsmodels
- Стандартные библиотеки python

## Датасет
- Использован датасет California Housing.
- Датасет доступен в sklearn.datasets: https://inria.github.io/scikit-learn-mooc/python_scripts/datasets_california_housing.html
- Можно скачать с помощью 'from sklearn.datasets import fetch_california_housing' и 'california_housing = fetch_california_housing(as_frame=True)'
