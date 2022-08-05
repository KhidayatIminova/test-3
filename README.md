## 8. Работа с удаленным репозиторием 

GitHub.com - сервис для удаленной работы с репозиториями

регистрируемся (Sign Up)

авторизуемся (Sign In)

2. Новый репозиторий на GitHub

Для того, чтобы создать новый репозиторий необходимо нажать кнопку NEW.

Открывается страница Create a New Repository

Заполняем форму:

- Repository name - имя репозитория
- Description - описание репозитория (необязательно)
- Public/Private - соответственно открытый/приватный доступ к репозиторию
- Add a README file - если нужно добавить файл README.md то ставим галочку
- gitignore - ????




3. Push Pull

Создаем новую папку на рабочем столе (например Seminar 3_1)

Открываем ёё в VSCode

выполняем git init

создаем файл README.md
что-нибудь пишем, сохраняем/добавдяем/коммитим 

Переходим на GitHub.com:

Создаем новый репозиторий (кнопка NEW)
В открывшемся окне Create a New Repository заполняем форму:

- Repository name - имя репозитория
- Description - описание репозитория (необязательно)
- Public/Private - соответственно открытый/приватный доступ к репозиторию
- Add a README file - галочку не ставим
- gitignore - ???

Нажимаем кнопку Create

Открывается окно подсказок

![help] help.png

копируем в буфер подсказки из...or push an existing......и вставляем в VSCode:

![paste] paste.png

    git remote add origin https://github.com/KhidayatIminova/test-3.git  

***origin** - обозначение URL-ссылки на репозиторий (например push origin - отправит на удаленный репозиторий)*

    git branch -M main

*главную ветку называем **main** (так принято). Теперь если выполнить git branch, то вместо ветки **master** будет  ветка **main***

    git push -u origin main