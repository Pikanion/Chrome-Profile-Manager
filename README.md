<!-- ### **[RU](#Tittle_RU) / [EN](#Tittle_EN)** -->
###### Contact me: **[Telegram](https://t.me/pikanion)** - if you have ideas or suggestions

# <a id="Tittle_RU">Chrome-Profile-Manager (RU)</a>
## Описание
Скрипт для работы с гугл профилями для Windows. 

Текущий функционал:
- Просмотр количества профилей в Google Chrome.
- Создание профилей. 
- Запуск профилей:
    - Можно открывать выборочно
    - Можно открывать диапазонами
    - Можно задавать ссылки на сайты, которые будут открыты при запуске профилей

## Запуск скрипта

Если Google Chrome был установлен в не стандартные пути в строках 7 и 8.
``` Batchfile
set "CHROME_PATH="
set "USER_DATA_PATH="
```
> Чтобы изменить строки, нужно открыть .bat файл любым текстовым редактором.

## Roadmap
- [x] Запуск ссылок
- [x] Функция создания новых профилей
- [ ] Закрытие профилей (выборочно или массово)
- [ ] Массовый запуск с определенными: прокси, юзерагентом и отключенным WebRTC
- [ ] Создание шаблонов запуска профилей
- [ ] Скачивание расширений на выбранные профиля (???)
- [ ] Поддержка английского языка
