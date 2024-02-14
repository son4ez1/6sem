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

![image](https://github.com/son4ez1/6sem/assets/113089517/e07433f9-6abc-4c79-8b8c-61bd5261b0c1)

**Основные ошибки:**
1. **remote** - подключение к удаленному репозиторию (показывает на какой репозиторий мы хотим сохранить данные). может быть ошибка , что неправильно указали ссылку, чтобы изменить, добавить set-URL/
2. **авторизация** - гитхабу нужно передать данные пользователя (логин, пароль или токен).
3. **прокси сервер** - проверять включен или нет


# ЛК2 22.01.24
1. Если есть папка **.git**, то команду **git init** выполнять не нужно
2. Команды **config** настраиваются на ПК один раз
3. git remote указывается один раз

   ![image](https://github.com/son4ez1/6sem/assets/113089517/3292bb86-0f7b-4c63-92e6-5dad9ea413cd)

# ЛК 05.02.24 Работа с файлами

1.Создание

2.Перенесение

3.Редактирование

4.Удаление

![image](https://github.com/son4ez1/6sem/assets/113089517/adafd637-ea10-4c34-b8fb-10a2f07cda96)

![image](https://github.com/son4ez1/6sem/assets/113089517/e3059ff8-e6b7-44fd-912b-eae8932143e6)

![image](https://github.com/son4ez1/6sem/assets/113089517/fcf1bb31-15e7-4a4e-b858-e8d5c511cbb3)


**Обычный или regular файл**

1)прикоснуться kstr.txt

2)nano kstr.txt/home/stud/'Рабочий стол'

3)mv kstr.txt/home/stud/'Рабочий стол'

4)rm /home/stud/'Рабочий стол'/kstr.txt

5)cat /home/stud/'Рабочий стол'/kstr.txt

**mv** - перемешение

**rm** - удалить(каталог можно удалить только с -r, тк там внутри файлы)

**ls** - просмотреть

**-r** - рекурсия

**cat** - чтение

**mkdir** - создает директорию

![image](https://github.com/son4ez1/6sem/assets/113089517/5c0711ed-6f1c-4ebd-a03a-4ca0ca13ea58)
![image](https://github.com/son4ez1/6sem/assets/113089517/e7947672-3ba0-46ea-b2e3-5070b9254bd1)
![image](https://github.com/son4ez1/6sem/assets/113089517/b898a1fb-001b-4ec2-a1da-84a4a81c977c)
![image](https://github.com/son4ez1/6sem/assets/113089517/40f0b39c-4311-4b0e-8f6a-256efecc9367)


**Папка (directory)**

1)mkdir /главная страница/ шпилька/ kss

2)mkdir /главная страница/stud/kss главная страница/stud/ksss

3)коснитесь home/stud/ksss/mayy

4) коснитесь "Домой"/stud/ksss

5)rm -r home/шпилька/ksss

![image](https://github.com/son4ez1/6sem/assets/113089517/69df0e96-06a3-458f-8f27-89fc98f39ff9)

---

**Устройства:**
1. символьные (мышка, клавиатура)
   
   ![image](https://github.com/son4ez1/6sem/assets/113089517/2aa30af1-f7c7-4824-ba20-f770c5cf35c5)
![image](https://github.com/son4ez1/6sem/assets/113089517/28a1d7a2-e4f4-4d12-9785-0a186c1933ce)

**c** - cимвольные

3. блочные (флешки) 

![image](https://github.com/son4ez1/6sem/assets/113089517/211fd3b6-2d4e-4e67-9ad8-5308819d6c37)

![image](https://github.com/son4ez1/6sem/assets/113089517/ed4e1061-0272-4adb-b560-05fe10249bf5)

![image](https://github.com/son4ez1/6sem/assets/113089517/db22f090-db52-498e-a5c8-058e19f9326a)

**b**  - блок

Пытались создать флешку

--- 

Файлам присваиваются уникальные номера - **inod**, посмотреть команды - **ls-i1**

![image](https://github.com/son4ez1/6sem/assets/113089517/bdcfd048-83a6-46f7-ab1f-c2167c60861c)

Жесткие ссылки имеют тот же номер что и файл и это можно использовать, чтобы найти все жесткие ссылки


![image](https://github.com/son4ez1/6sem/assets/113089517/8a945bc0-710e-4adb-8983-2ee3569dc6db)

![image](https://github.com/son4ez1/6sem/assets/113089517/e2b40f74-2926-4ba4-ad24-f2728172bef7)

![image](https://github.com/son4ez1/6sem/assets/113089517/45491995-f405-4669-b636-acb7670eae75)

![image](https://github.com/son4ez1/6sem/assets/113089517/c017b611-5439-49da-aa48-f7c6549914c0)

![image](https://github.com/son4ez1/6sem/assets/113089517/89b6f859-9b07-4ebf-acca-66ba760a8c93)
![image](https://github.com/son4ez1/6sem/assets/113089517/f3f0ae26-a031-4da8-b99a-c81d8f45fbd7)

