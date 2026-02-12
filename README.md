# Анализ лояльности пользователей Яндекс Афиши

## Описание проекта

Исследовательский анализ данных о покупках пользователей Яндекс Афиши с целью выявить закономерности и факторы, влияющие на вероятность повторных заказов.

## Структура проекта

- 'Анализ лояльности пользователей Яндекс Афиши.ipynb` — основной ноутбук с анализом
- `requirements.txt` — зависимости проекта
- `.env` — файл с параметрами подключения к БД (не включён в репозиторий)
- `.gitignore` — список игнорируемых файлов

## Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   https://github.com/platinumrolex777/Yandex.Practicum-Yandex.Afisha.git
   cd yandex-afisha-loyalty-analysis
   ```

2. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

3. Создайте файл `.env` с параметрами подключения к базе данных:
   ```
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_HOST=your_host
   DB_PORT=5432
   DB_NAME=your_database_name
   ```

4. Запустите Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Используемые библиотеки

pandas, sqlalchemy, psycopg2, matplotlib, numpy, python-dotenv, phik, seaborn, scipy
