1) Скачиваем для начала данные

#!/bin/bash
curl -L -o ~/Downloads/kinopoisktop250russiandataset.zip\
  https://www.kaggle.com/api/v1/datasets/download/alexandertesemnikov/kinopoisktop250russiandataset

2) Создаем окружение 

python3 -m venv ./

3) Активируем окружение в bin

source activate

4) Устанавливаем jupyter-notebook

pip install jupyter

5) Запускаем jupyter-notebook
 jupyter-notebook

6) В запустившемся окне вставляем токен и задаем пароль

7) Установили pandas

pip install pandas

8) Установили wordcloud

pip install. wordcloud

9) Установили matplotlib

pip install matploylib

Цель — научиться чистить данные, строить простую аналитику и визуализации.

Анализ фильмов с IMDb или Кинопоиска

Найти датасет с рейтингами фильмов

Ответить на вопросы:
1) жанры с наибольшим рейтингом
2) какие актеры чаще всего снимаются в топ-10
3) как изменялись тренды по годам

Сделать графики (seaborn / matplotlib / plotly)