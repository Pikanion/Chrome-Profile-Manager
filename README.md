<!-- ### **[RU](#Tittle_RU) / [EN](#Tittle_EN)** -->
###### Contact me: **[Telegram](https://t.me/pikanion)** - if you have ideas or suggestions

# <a id="Tittle_RU">Chrome-Profile-Manager (RU)</a>
## Описание
Скрипт для работы с гугл профилями для Windows. 

Текущий функционал:
- Просмотр количества профилей в Google Chrome.
- Массовый запуск профилей.
   - Выборочный запуск (К примеру - 1, 2, 3, 5).
   - Запуск диапазона(-ов) профилей (К примеру, 1-20 или 1-5, 10-15, 20-30).
- Запуск профиля с новыми вкладками (ссылки задаются пользователем).   

## Запуск скрипта
### Настройка

Перед запуском скрипта нужно будет поменять две переменные в нем:
1. Проверить путь до .exe файла Google Chrome в строке 8:
``` Batchfile
set chrome_exe="C:\Program Files\Google\Chrome\Application\chrome.exe"
```
2. Заменить путь до папки, в которой хранятся профиля от Google Chrome в строке 10: 
```Batchfile
set user_data="C:\Users\$username$\AppData\Local\Google\Chrome\User Data"
```
### Запуск

Запускается двойным щелчком мыши.

## Запланировано
- [x] Запуск ссылок
- [x] Функция создания новых профилей
- [ ] Массовый запуск с определенными: прокси, юзерагентом и отключенным WebRTC
- [ ] Просмотр списков прокси и юзерагентов внутри скрипта
- [ ] Создание шаблонов запуска профилей
- [ ] Скачивание расширений на выбранные профиля (???)
- [ ] Поддержка английского языка
