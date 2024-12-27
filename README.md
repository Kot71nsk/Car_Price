# Car_Price

# Описание кода


Код представляет собой полную реализацию процесса машинного обучения для предсказания цены автомобиля на основе его характеристик. Код включает в себя следующие этапы:

1. **Обработка данных**
Загрузка данных из файла CSV с помощью функции pd.read_csv.
Удаление строк с пропущенными значениями с помощью функции dropna.
Преобразование типов данных для столбцов "price", "year" и "odometer" с помощью функций astype.
Закодирование категориальных переменных с помощью функции get_dummies.
Нормализация данных с помощью функции apply.

2. **Разделение на тестовые и тренировочные данные**
Разделение данных на тестовые и тренировочные данные с помощью функции train_test_split.

3. **Обучение моделей**
Обучение модели XGBoost с помощью функции XGBRegressor.
Обучение модели линейной регрессии с помощью функции LinearRegression.
Обучение модели деревьев решений с помощью функции DecisionTreeRegressor.
Обучение модели Gradient Boosting Regressor с помощью функции GradientBoostingRegressor.

4. **Оценка моделей**
Оценка точности моделей по метрикам MAE и MSE с помощью функций mean_absolute_error и mean_squared_error.

5. **Визуализация данных**
Строение графика зависимости цены от года выпуска и марки с помощью функции lineplot.
Преобразование данных в длинный формат с помощью функции melt.
Фильтрация данных только для строк, где марка равна 1.

6. **Строение графика**
Строение графика зависимости цены от года выпуска и марки с помощью функции lineplot.

# Цель кода

Цель кода - предсказать цену автомобиля на основе его характеристик.

# Требования

1.   Python 3.x.
2.   Библиотека pandas.
3.   Библиотека scikit-learn.
4.   Библиотека matplotlib.
5.   Библиотека seaborn.


# Car_Price

# Code description


The code is a complete implementation of a machine learning process for predicting the price of a car based on its characteristics. The code includes the following steps:

1. **Data processing**
Loading data from a CSV file using the pd.read_csv function.
Deleting rows with missing values using the dropna function.
Converting data types for the "price", "year", and "odometer" columns using the astype functions.
Encoding categorical variables using the get_dummies function.
Normalization of data using the apply function.

2. **Separation into test and training data**
Splitting the data into test and training data using the train_test_split function.

3. **Model training**
Training the XGBoost model using the XGBRegressor function.
Training a linear regression model using the LinearRegression function.
Training a decision tree model using the DecisionTreeRegressor function.
Training the Gradient Boosting Regressor model using the GradientBoostingRegressor function.

4. **Evaluation of models**
Estimation of model accuracy using the MAE and MSE metrics using the mean_absolute_error and mean_squared_error functions.

5. **Data visualization**
Plotting the price dependence on the year of manufacture and brand using the lineplot function.
Convert data to a long format using the melt function.
Filtering data only for rows where the mark is 1.

6. **The structure of the graph**
Plotting the price dependence on the year of manufacture and brand using the lineplot function.

# The purpose of the code

The purpose of the code is to predict the price of a car based on its characteristics.

# Requirements

1. Python 3.x.
2. The pandas library.
3. Scikit-learn library.
4. matplotlib library.
5. Seaborn Library.
