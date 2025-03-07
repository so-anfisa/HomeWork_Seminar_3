# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
---
**Git** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
---
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
---
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Просмотр состояния репозитория
---
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
---
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
---
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
---
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки
---
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток
---
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
---
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Добавление картинок
Для добавления *картинки* из интернета нужно написать следующее:  ![Картинка](https://bipbap.ru/wp-content/uploads/2021/11/1619541010_52-oir_mobi-p-nyashnie-kotiki-zhivotnie-krasivo-foto-57-730x856.jpg)

## Добавление ссылок:
Для того, чтобы добавить *ссылку* надо совершить следующее: [Работа_с_markdown](https://help.vivaldi.com/ru/services-ru/forum-ru/markdown-formatting/#:~:text=Markdown%20%E2%80%94%20%D1%8D%D1%82%D0%BE%20%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%B9%20%D1%8F%D0%B7%D1%8B%D0%BA%20%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%82%D0%BA%D0%B8,%D0%B8%20%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%BD%D1%8B%D0%B5%20%D0%BD%D0%B0%20%D0%B2%D1%81%D0%B5%D1%85%20%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D0%B0%D1%82%D1%83%D1%80%D0%B0%D1%85.)

---
Для того чтобы добавить **картинку**, надо:
![картинка](https://vsegda-pomnim.com/uploads/posts/2022-04/1649816359_47-vsegda-pomnim-com-p-tsveti-pioni-foto-48.jpg)

## Добавление ссылок
---
Для того, чтобы добавить ***ссылку***, надо:
[ссылка](https://funart.pro/21732-samye-krasivye-piony-62-foto.html)
## Добавление списков и цитат
---
* Ненумерованные списки задаются тремя фигурами:
* Первый
+ Второй
- Третий
---
Чтобы добавить *цитату* используем знак ">"
>Пионы — дикой розы нежность, прелестных бабочек альянс, любви прекрасной неизбежность, зари предутренней пасьянс.
>>Пион кричащий, но элегантный, это яркая Арката, которая бросает свои ароматы в воздух, переполнение красоты.


>Пион– олицетворение красоты, жизни, силы и любви.
