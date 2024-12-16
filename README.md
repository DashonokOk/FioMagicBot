 # FioMagicBot

Этот репозиторий содержит Telegram-бота, который выполняет транслитерацию ФИО с кириллицы на латиницу в соответствии с Приказом МИД России № 2113 от 12.02.2020.

## Описание

Бот принимает ФИО на кириллице через сообщения в Telegram и возвращает транслитерацию ФИО на латиницу по официальным правилам. Бот также логирует все взаимодействия и ошибки в файл.

## Установка и запуск

### Предварительные требования

- Docker

### Шаги для запуска

1. Клонируйте репозиторий:
   ```sh
   git clone <ссылка>
   cd FioMagicBot
   
   docker build -t telegram-translit-bot .
   docker run -d -e TOKEN=<ВАШ_ТОКЕН> --name telegram-translit-bot telegram-translit-bot

## Использование
После запуска бота отправьте ему ФИО на кириллице, и он вернет транслитерацию на латиницу.



