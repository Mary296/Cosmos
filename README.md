
# Загрузка изображений космоса
## Описание
Проект создан для загрузки изображений космоса, запуска космических кораблей и планеты "Земля". Программа создает отдельные директории для каждого набора изображений автомастически, без участи пользователя. 


## Установка
Скачайте необходимые файлы, затем используйте `pip` (или `pip3`, если есть конфликт с Python2) для установки зависимостей и установить зависимости. Зависимости можно установить командой, представленной ниже.
Создайте бота у отца ботов. Создайте новый канал в Telegram.

Установите зависимости командой:
```python
  pip install -r requirements.txt
```

## Пример запуска скрипта
Для запуска скрипта у вас уже должен быть установлен Python3.

Для получения необходимых изображений необходимо написать:

```python
  python main.py
```

## Переменные окружения
Часть настроек проекта берётся из переменных окружения. 
Переменные окружения - это переменные, значения которых присваиваются программе Python извне.
Чтобы их определить, создайте файл `.env` рядом с `main.py` и запишите туда данные в таком формате: ПЕРЕМЕННАЯ=значение.

Пример содержания файла `.env`:

```python

API_KEY = "nasa-token"
TG_TOKEN = "bot-token"
CHAT_ID = "@chat_id"

FOLDER_SPACEX = "SpaceX"
FOLDER_NASA = "Nasa"
FOLDER_EPIC = "Epic"

```

Получить токен `API_KEY` можно на сайте [NASA](https://api.nasa.gov/). 
Получить токен `TELEGRAM_BOT_TOKEN` можно у отца ботов.
В описании канала получите название и положите в переменную `TG_CHAT_ID`. 

## Цель проекта
Код написан в образовательных целях на онлайн-курсе для веб-разработчиков dvmn.org.