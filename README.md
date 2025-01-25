<h2>Телеграм бот с функцией валидации JSON</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
Помочь тестировщику быстрее проверить JSON на нарушение синтаксиса

Этот бот при получении JSON:
* Проверяет на ошибки синтаксиса
* Возвращает JSON в удобочитаемом формате

## 🖼 Скриншоты

Стартовое меню:

![photo_2025-01-25_22-34-21](https://github.com/user-attachments/assets/4a7a7b92-3374-4e66-a986-ee4eee13dbbd)

После отправки JSON c ошибкой:

![photo_2025-01-25_22-37-15](https://github.com/user-attachments/assets/9aa9922f-f4e9-4fbb-8295-94ffaa1b6df1)


Пример работы бьютифаера:

![photo_2025-01-25_22-36-33](https://github.com/user-attachments/assets/99db34aa-996c-48f7-8307-15f49d4ff811)



## 💻 Технологии

* Python
* Библиотека `telebot`

## ⏬ Установка на локальном компьютере

1. Скачать проект
   
2. Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

3. Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
4. Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```


5. Запускаем
``` markdown
python3 json_bot.py
```


