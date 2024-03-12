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
![image](https://github.com/son4ez1/6sem/assets/113089517/50dd59ee-3bc3-4d40-afca-b9acc83c09e6)
![image](https://github.com/son4ez1/6sem/assets/113089517/741c2c36-d286-48c0-a266-8a3e57d8fea4)

![image](https://github.com/son4ez1/6sem/assets/113089517/a6e15a71-427f-49a7-8406-f396a89b0acd)
![image](https://github.com/son4ez1/6sem/assets/113089517/e5a85f8e-72b2-4559-8292-c02506914c9b)
![image](https://github.com/son4ez1/6sem/assets/113089517/328b5e3c-8881-4819-be8d-97273713c349)

![image](https://github.com/son4ez1/6sem/assets/113089517/991af1e9-82ae-4a58-a8c5-8fb35e5c09a2)


# 19.02.2024 Скрипт на создание и удаление пользователя

**stud:x:1000:1000:Student,,,:/home/stud:/bin/bash**

имя пользователя:
1. x - место под пароль
2. 1000 - номер пользователя
3. 1000 - номер группы пользователя
4. Student - название группы
5. /home/stud: - домашняя директория пользователя
6. /bin/bash - терминал пользователя

создали пользователя:

![image](https://github.com/son4ez1/6sem/assets/113089517/07c96432-d785-45ef-8483-69d23670f0a5)

![image](https://github.com/son4ez1/6sem/assets/113089517/a30b52b0-797d-4286-aa4a-837b338c7c22)

создали пароль для sonya
![image](https://github.com/son4ez1/6sem/assets/113089517/29715272-0475-421e-9265-462a2b07f50b)

зашли в дебиан под новым пользователем
![image](https://github.com/son4ez1/6sem/assets/113089517/cd494749-83aa-4d5a-8a86-876f81f8b072)

![image](https://github.com/son4ez1/6sem/assets/113089517/29eb6c2f-1d04-48f8-9cbb-0bf1703d4242)
![image](https://github.com/son4ez1/6sem/assets/113089517/0e47ba78-8273-4f37-9a9a-8ec6ef50eb79)

![310381967-5eccff94-37df-4d46-93d5-85d0516f21db](https://github.com/son4ez1/6sem/assets/113089517/f8e6eba5-c59d-4d11-9366-a98b5550f433)

![310382045-0db71c7b-6898-436f-9e3b-e9a76b06de1e](https://github.com/son4ez1/6sem/assets/113089517/3b42bcb7-1ce7-4b3a-81ac-f044ae9daee4)

![310382205-c7baa1f1-c565-4a0c-8ebd-19c40dbbca18](https://github.com/son4ez1/6sem/assets/113089517/1b263652-0190-432d-9543-578c442e9f98)

![310382285-b6414a5c-e5fc-4aeb-9ce6-3006eecf98c2](https://github.com/son4ez1/6sem/assets/113089517/dd2c6b1f-c5a8-4155-a717-e194cd4db0bb)

![310382337-45714afb-bd26-43e9-8258-9353002b4fe9](https://github.com/son4ez1/6sem/assets/113089517/c53c1fd4-4e01-4c6a-ad3a-f4867559d1e8)

![310380717-861e9a25-1bb5-4d5f-8625-e3f700e9649d](https://github.com/son4ez1/6sem/assets/113089517/e2bb43e0-5f51-4095-83bd-d135e4d5ba18)

![310380787-8b35d716-c84f-41fa-93f4-a6fb654df710](https://github.com/son4ez1/6sem/assets/113089517/e2bf5fd4-1122-4b2c-85d9-54537ed19096)

![310380885-4a87bb05-ac7f-42af-9781-c9c960fd84df](https://github.com/son4ez1/6sem/assets/113089517/7f23a283-68ac-4463-825a-d258674d7d06)

![310381260-9d795aa5-49a5-45ac-8e41-93934fe7d832](https://github.com/son4ez1/6sem/assets/113089517/3178b985-9e8f-4b81-80c8-eaef0a4e9985)

![310381451-e9e07fee-bfcf-4ef0-876a-a43798d016c2](https://github.com/son4ez1/6sem/assets/113089517/bc45c699-8fd8-4127-8a44-02b84429a2c4)

![310383858-f6e092f9-0c95-4150-9977-665963df7337](https://github.com/son4ez1/6sem/assets/113089517/f59f80b6-24c3-4636-bd26-13d6a4cf2646)

![310383945-b163db35-a0e5-4634-af8d-038872ef5e4d](https://github.com/son4ez1/6sem/assets/113089517/023741a9-3111-43fa-a5e0-8f321b6b4c85)


# ЛК4 04.03.24 Структура памяти процесса

![309723313-aec0d04a-b2b9-427e-9c95-3aaa6b4e44b3](https://github.com/son4ez1/6sem/assets/113089517/f13a4cde-4d79-4fbe-86c8-cc1bb10504d0)

![309725210-96e1a93f-619a-4cbe-9165-1b536f677ac6](https://github.com/son4ez1/6sem/assets/113089517/728dcb50-58c6-4437-b538-4626c6fbbab1)

![309731370-3d72fb07-40fe-4e8c-9a1a-dc6941bdc39f](https://github.com/son4ez1/6sem/assets/113089517/5de2cd99-6470-48c7-8144-063eed9e026f)

![309731432-83fa1a6e-158b-4b61-99b6-a40c601a9361](https://github.com/son4ez1/6sem/assets/113089517/b3225ea2-d47e-4068-aec0-d2593f228828)

![309732444-8195be3b-28b1-40e5-82d6-74b5cab05dcc](https://github.com/son4ez1/6sem/assets/113089517/e7f8f1c1-e5c7-4d74-8b92-355d0b8db382)

![309732444-8195be3b-28b1-40e5-82d6-74b5cab05dcc-2](https://github.com/son4ez1/6sem/assets/113089517/b893fd9e-c55a-493e-970b-20afeae1e249)

**PID** - номера поцесса (на винде в диспетчере задач смотрим)

![309734470-a98b6c71-f6e3-49a9-a88f-eff1070a8ab1](https://github.com/son4ez1/6sem/assets/113089517/c6167453-1826-488e-a67e-4478074caf5e)

![309734910-31f6269f-0329-4084-af26-75ad2d1f2919](https://github.com/son4ez1/6sem/assets/113089517/aff30091-5a01-4e22-8958-491a68e0cdc7)

![309735194-de6ff1c7-40f9-44b6-8501-7daace1c8be8](https://github.com/son4ez1/6sem/assets/113089517/5ec49d24-0457-44ab-8647-dc0c1de5bb04)

Память запоняется в определенные ячейки(разные)

![309739580-77589065-f271-45c2-80c9-b8910c4c9bdb](https://github.com/son4ez1/6sem/assets/113089517/b2974fc4-0ef6-4cd2-949f-e4340ffe8819)

**Библиотеки:**

![309741013-d7c43635-31bb-42a3-ad8f-5b207be28f54](https://github.com/son4ez1/6sem/assets/113089517/d4e614fd-6fd0-428b-a4a0-40cb62443a60)

Область данных и текст(код):

![309741193-671f9271-4922-4e5b-bf3b-8dc128da2fb1](https://github.com/son4ez1/6sem/assets/113089517/1768b093-3d75-48ce-b46f-9adfedd61833)

![309742585-e306985d-2954-4fdf-b994-f1946d369af3](https://github.com/son4ez1/6sem/assets/113089517/9d199b8c-7e81-4b1a-bb87-9d848ff3f2d3)

![309743702-11877113-51d8-42d3-9d61-af83a04bb345](https://github.com/son4ez1/6sem/assets/113089517/4e539444-9e98-48ea-8949-4800d9482382)

![309743955-3a0573ff-f1df-473f-b76d-3c9910715277](https://github.com/son4ez1/6sem/assets/113089517/7a3099ac-4c9c-4fd3-977a-a4e47930e2dd)

![310398372-5dfad536-aac3-48f9-83d8-7ec9cd48b3cb](https://github.com/son4ez1/6sem/assets/113089517/98288bdc-1eab-4129-98d1-a892d75e2445)

![310405908-bb3ce670-1313-4614-9a99-fd8fda8a88bd](https://github.com/son4ez1/6sem/assets/113089517/6b77173f-c07e-4eae-8ace-c130169b12cb)

![310406136-8ea8d718-5952-484d-9ccd-63b8be08fdc8](https://github.com/son4ez1/6sem/assets/113089517/0c519a85-0812-4ba7-925b-0f6b5b6847c3)

![310406062-28587c19-1c89-468b-bcac-743190dad1f6](https://github.com/son4ez1/6sem/assets/113089517/fb2c9d8f-6efe-4653-ad91-769c1e0f2244)

![310406501-048b9bfa-6c7b-4ddd-ac0a-0ff3129a0a6f](https://github.com/son4ez1/6sem/assets/113089517/f4e5c7e3-3e78-4dce-862b-31fe6a85d854)

# ЛК5 11.03.24. Потоки в БД

**Атрибуты процесса:**

1. PID - уникальный идентификатор
2. Адресация областей памяти процесса
3. fd - открытые файловые дескрипторы (терминал или файлы которые используют процессы)
4. Обработчики сигналов процесса (введение запроса пользователя)
5. Код выхода (Ctr+C, Ctr+Z, exit, Программа все выполнила)
6. Рабочий каталог (Папка рабочего процесса - proc)
7. Переменные окружения (Комментарии)
8. Состояние процесса
9. Аппаратный контекст (То что определяься компьютером)

![311677518-e815d141-22b8-4194-8846-42907d916483](https://github.com/son4ez1/6sem/assets/113089517/05cdcdf1-46ac-4039-bdb6-65f17bc39e3b)

Состяние процесса

![311677658-cd5cfc1d-92a2-4d4c-adda-6682f0b6ca21](https://github.com/son4ez1/6sem/assets/113089517/81dd661f-d159-4c41-badf-e8d9d088ed05)

Первый процесс init

![311678846-b4c88025-e5b0-40ad-a4b1-5cb31145a0e2](https://github.com/son4ez1/6sem/assets/113089517/9288412c-9bbe-461f-8459-a2e4ec8a60c3)

**Соcтояние процессса:** Ready

![311681794-a6bc2b96-59c6-4d75-9f24-6de5f4d4096c](https://github.com/son4ez1/6sem/assets/113089517/b031fcb0-0bda-4bc7-a6f3-d13e7e460854)

**Соcтояние процессса:** Running

![311681747-1b1ec900-73c3-4f8d-bd09-b78aafa0e492](https://github.com/son4ez1/6sem/assets/113089517/0dd347d8-504e-441b-baa6-d51bbdc645f8)

**Соcтояние процессса:** Sleeping

![311686819-4a0d4a9b-e92e-4ab4-ae4c-96ed0ee0206e](https://github.com/son4ez1/6sem/assets/113089517/00684af3-c10e-4a9f-8d77-f6e9875e5f92)

**Соcтояние процессса:** Zombie

![311686851-bad08e57-3053-4899-9b6d-647ba97e5947](https://github.com/son4ez1/6sem/assets/113089517/2ffe77c1-8a73-4816-8abf-cd384f2dc58e)

**Смерть процесса**

1. exit() или kill() - останавливает поцесс

2. После завершения род.процессса, дочерний переходит либо в состояние зомби, либо к другому род.процссу

![311686330-7bae567d-c610-4bb2-a5aa-5cfecf5dd6e0](https://github.com/son4ez1/6sem/assets/113089517/2def446f-98d9-4044-8228-64aebc67f804)

**Сигналы**

![311687151-642f829f-25bc-4247-b937-39563f9f4031](https://github.com/son4ez1/6sem/assets/113089517/703d3a55-aebc-440f-8527-a779c4042c81)









