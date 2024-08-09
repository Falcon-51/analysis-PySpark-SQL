# analysis-PySpark-SQL
Анализ данных с использованием временных таблиц и SQL
# 1) Загрузка данных
Загрузим данные из CSV файлов в Spark DataFrame.

- movies.csv\
![image](https://github.com/user-attachments/assets/d41d8a63-15ce-4f74-90b0-dee9455ff67b)

- movie_actors.csv\
![image](https://github.com/user-attachments/assets/80776351-6ed2-41e7-bbb5-ba9f9e5f8419)

- actors.csv\
![image](https://github.com/user-attachments/assets/07b0340b-9031-4698-95bf-1cf7839f2f32)


# 2) Создание временных таблиц
Создадим временные таблицы для данных о фильмах, актерах и связях между ними.
# 3) SQL запросы
- Найдём топ-5 жанров по количеству фильмов.
- Найдём актера с наибольшим количеством фильмов.
- Подсчитаем средний бюджет фильмов по жанрам.
- Найдём фильмы, в которых снялось более одного актера из одной страны.
