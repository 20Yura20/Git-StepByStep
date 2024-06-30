# GIT от простого к сложному
   
***GIT*** - это система управления исходным кодом ( SCM ), система 
контроля версий (VCM)
</br>
* Созадаем директорию в которой будем храниться проэкт _git_ c помощью команды `mkdir`.
* Переходим в эту директорию ( `cd назавание директории` ) и создаём гит репозиторий `git init`.

## Подключение к удааленному репозиторию
==
+ Переходим на сайт [github](https://www.hithub.com 'гитхаб').
- Авторизируемся 
+ Создаём удалённый репозиторий
+ Связываем удалённый репозиторий с локальным ропозиторием `git remote add (назавание удаоенного репозитория)origin  main(локальный)`

## Создание, созхранение и отправка изменений на удаленный репозиторий
=
> Создадим файл `touch имя_файла`
> Сохраним измененеия в локальном репозитории `git add имя_файла && git commit -m 'описание комита'`
> Отправим в удаленный репощзиторий первый раз `git push -u origin main` последуйщие `git push`
> Проверим состояние `git status`
