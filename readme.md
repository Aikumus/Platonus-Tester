# Platonus Tester
Замечательно, что Вы зашли в репозиторий этого проекта!
Ну или Вас "забросило" сюда, потому что Вы нажали "О программе". Anyway ....

| Вопрос | Ответ |
|--------|-------|
| Что это? | Программа для тестирования в домашних условиях |
| Для кого? | Для студентов Казахстана, у которых сессия проводится в системе Platonus |
| Какие требования к ОС? | Минимальная ОС: Windows 7, установленный пакет .Net Framework версии 4.5.2 минимум. Установить можно со [страницы](https://www.microsoft.com/ru-ru/download/details.aspx?id=48130). Или просто забить в гугл ".Net Framework" |
| Кто автор? | Мой профиль в православном [Вконтакте](https://vk.com/maximgorbatyuk) |
| А зачем мне ссылки? | Чтобы прислать мне багрепорт со скриншотом или сообщить свои предложения и пожелания |
| Сколько стоит? | Распространяется свободно. Юзай, зубри, высший балл получай |
| Как использовать? | В программе есть инструкция, но в целом - ничего сложного |
| Как скачать?| [Прямая ссылка](https://github.com/maximgorbatyuk/Platonus-Tester/releases/tag/1.0.0) на zip-архив, в котором запакованы все файлы. Скачать, распаковать и не забыть быть классным |

## Возможности программы
 * Возможность прохождения тестирования по системе Platonus
 * Автоматическая обработка данных
 * Работа с файлами Word (*.docx и *.doc)
 * Обработка и отображение изображений в вопросах
 * Обработка и отображение таблиц в вопросах
 * Загрузка новых комментариев к результату тестирования
 * Комментарии Вы можете предлагать сами через Pull request в этом репозитории (Если не знаете как, но горите желанием, ссылки на профили разработчика оставлены не просто так)


## Планы проекта
* [ ] Создать инсталлятор проекта
* [ ] Создать утилиту обновления в атоматическом режиме
* [x] Рефакторинг для оптимизации работы. Например, переработка архитектуры проекта в соответствии (хотя бы приблизительно) с объектно-ориентированными паттернами.
* [x] Рефакторинг интерфейса программы. Перевод на WPF, возможно. Приведение к минималистическому дизайну(_СДЕЛАНО. Информация ниже_)
* [x] Организовать две версии программы: x64 и х32, чтобы была возможность открыть на всех операционных системах(_нет необходимости. Сделал только x32_)
* [x] _Основное!_ Разработать поддержку доковских файлов и картинок соответственно, чтобы было *идеально* (ну как сказать)
* [ ] Найти единомышленников, которые помогли бы с интерфейсом и некоторыми доработками. Ну и тренировка пул-реквестов что-ле.
* [x] Сделать вывод версий файла. Чтобы была возможность скачать различные версии программы из репозитория (_Нет необходимости_)
* [ ] Сделать проверку на ТАМОСовские артефакты ([q]3:1: Question [a][+] variant)

## Описание программы
Этот репозиторий - эволюция предыдущего [проекта](https://github.com/maximgorbatyuk/Test-Unit-Project/), построенного на базе WinForms. WinForms ограничивал в создании responsive UI, а замена на WPF в рамках одного проекта не представлялась возможным. Было решено (03.06.2016) создать новый проект и перенести функционал (читай классы) сюда. За один вечер и одно утро было сделано, что сподвигло на рефакторинг, изменение структуры некоторых классов, способствовало открытию нового функционала C# (BackgroundWorker). Есть и минусы, но о них потом. Ниже описание из старого проекта.

Программа выводит короткий комментарий, исходя из результата тестирования. Комментарий может быть "спокойным" и "ругательным". Вывод ругательств настраивается и по умолчанию выключен. В случае, если в вопросе только 4 варианта ответа, то пятый вариант ответа будет выглядеть следующим образом: "Ошибка: вопрос содержит только 4 варианта ответа". При возникновении проблемы при обработке вопроса будет выдано сообщение об ошибке и текст вопроса.

## Лицензия
Программа разработана исключительно в целях подготовки разработчика и его одногруппников к сессии, посему распространяется свободно и не несет в себе цели на коммерческую прибыль. Но в случае, если юзер использует программу в коммерческих целях, желательно сообщить об этом разработчику и разделить деньги поровну.

Обычно подобное ПО лицензируется по [Apache License](https://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F_Apache).
 Чем я хуже? Посему объявляю данное ПО лицензируемым [Apache](https://github.com/maximgorbatyuk/Platonus-Tester/blob/master/license.md). 
 Можно менять, распространять, но нельзя изменять имя. А если Вы используете программу в коммерческих целях, но перестаньте это делать, пожалуйста. Это нехорошо и неправильно.


