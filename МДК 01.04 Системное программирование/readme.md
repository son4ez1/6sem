# ЛК1 15.01.24
[Установка GIT BASH](https://git-scm.com/downloads)

**Git bash** -команды для работы с GIT из терминала

**Прокси сервер** git config --global http.proxy 10.0.50.52:3128

[**Практические задания**](https://smartiqa.ru/courses/git/answer-key)

![image](https://github.com/son4ez1/6sem/assets/113089517/4d056ccd-d13b-4e0f-891e-9e5c2dca4e1c)
---

Создание репозитория на компьютере: инициализация, git init 

![image](https://github.com/son4ez1/6sem/assets/113089517/7f0e8621-0dc2-4562-9960-dbb7eee1bb1e)

cmd //c tree .git - показывает в терминале структуру папки git

--

$ git status - показывает статус репозитория
On branch master - указывает имя ветки

No commits yet - нет сохраненных версий

Untracked files: - не отслеживаемые файлы 
  (use "git add <file>..." to include in what will be committed) - нужна команда добавить, чтобы зафиксировать версию для сохранения
  список файлов для сохранения:
        index.html
        pictures/

nothing added to commit but untracked files present (use "git add" to track) - найдены файлы для добавления

--

**Настраиваем пользователя Git**

Задаем имя и email пользователя для текущего репозитория 23-13 

$ git config  --global user.name PK23-13

$ git config  --global user.email PK23-13@gmail.com

**Отменяют прокси:**

git config --global —unset http.proxy

git config —global —unset https.proxy

git config —global —unset core.gitproxy

добавление файлов - git add * (* - все файлы добавляются)

![image](https://github.com/son4ez1/6sem/assets/113089517/475ef684-8a04-4cd7-9fb0-0b397d76682a)

**Для фиксации версии нужно указать ее название , для этого создается сообщение**

$ git commit -m "G-02: Initial" 

$ git log - выводим информацию о фиксации

![image](https://github.com/son4ez1/6sem/assets/113089517/82a4cc08-700f-4535-927c-eff91d650ac3)

подтверждения git

![image](https://github.com/son4ez1/6sem/assets/113089517/a7bbf279-9f71-42ac-a2b4-64bfcf8a724c)

![image](https://github.com/son4ez1/6sem/assets/113089517/e62a255c-2ebd-4441-802c-e4da3adb20ca)
