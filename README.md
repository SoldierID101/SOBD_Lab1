# Лабораторная работа №1 — Exploratory Data Analysis (Spark)

Этот репозиторий содержит первую лабораторную работу по дисциплине **Системы обработки больших данных (СОБД)**.

## Содержание

- **1_Data_cleansing.ipynb** — очистка и подготовка данных Yellow Taxi Dataset  
- **2_Exploratory_analysis.ipynb** — исследовательский анализ данных (EDA):  
  - базовые статистики  
  - распределения числовых признаков  
  - анализ по времени  
  - выбросы  
  - корреляция признаков

## Используемые технологии

- Apache Spark (PySpark)
- Python (pandas, matplotlib)
- Jupyter Notebook

## Данные

Используется набор **Yellow Taxi Trip Data (NYC)** — данные о поездках такси за 2018 год.
https://www.kaggle.com/datasets/geetmukherjee/taxi-trip-data?utm_source=chatgpt.com  
Файлы CSV и Parquet не хранятся в репозитории из-за большого объёма (>9 ГБ).  
Путь к данным указывается локально в ноутбуках.