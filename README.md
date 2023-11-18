# Avandy News Analysis
![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)
![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)

Десктопная программа, которая анализирует частоту употребления слов в новостных заголовках для понимания "картины дня" за выбранный период, а также рассчитывает общий эмоциональный фон по заранее установленным правилам. Имеется возможность оффлайн работы благодаря встроенной СУБД SQLite.

Программа включена в [Реестр российского программного](https://reestr.digital.gov.ru/reestr/1483979/) обеспечения.

![QIP Shot - Screen 1168](https://github.com/mrprogre/avandy-news/assets/45883640/81e94755-32bb-4054-9420-d46028ec0eeb)

![b4087d22886c05f621a0eac1f606d7ae](https://github.com/mrprogre/avandy-news/assets/45883640/51c3ba9b-3750-4903-85e5-bcf7baa5f7f0)

----
**Возможности программы:**
- многопользовательское приложение с персонализированными настройками интерфейса и фильтрацией новостей
- поиск новостей по одному слову или по нескольким ключевым словам за период без фильтрации заголовков
- поиск всех новостей с применением фильтрации
- возможность добавления/удаления/деактивации источников новостей (более 20 источников RSS по умолчанию)
- анализ частоты употребления слов в новостных заголовках - "Топ-10" с применением метода схожести строк Джаро-Винклера
- отображение заголовков по двойному клику на слове из "Топ-10" за период
- возможность исключать слова из "Топ-10" и возвращать их обратно
- ручная установка ощущений от прочтения новости (позитив/негатив) и её значимости (вес)
- автоматическая установка ощущений по заранее установленным правилам (добавление/удаление/деактивация правил определения позитив/негатив)
- встроенная СУБД SQLite
- сохранение заголовков в избранные
- ручное добавление новостей в архив
- уведомление о заранее добавленных событиях
- быстрый переход на часто используемые сайты
- экспорт результатов в Excel и CSV
- двойной щелчок по заголовку открывает веб-страницу с новостью
- быстрое переключение между пользователями (можо завести несколько пользователей с разными настройками и фильтрами)
- для синхронизации между компьютерами можно поменять путь к файлу базы данных в настройках приложения
- сохранение состояния интерфейса
- разнообразные темы интерфейса
- настройка прозрачности окна
- журнал работы программы
- режим чтения

----

Путь к файлам программы:

**Windows**: C:\Users\username\News

**Linux**: home/username/News

