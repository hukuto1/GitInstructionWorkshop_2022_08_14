# Инструкция по работе с git

## Что это и для чего нужна система контроля версий?

### Что такое система контроля версий?
Программное обеспечение контроля версий отслеживает все вносимые в код изменения в специальной базе данных.
### Для чего нужна система контроля версий
Программное обеспечение контроля версий отслеживает все вносимые в код изменения в специальной базе данных. При обнаружении ошибки разработчики могут вернуться назад и выполнить сравнение с более ранними версиями кода для исправления ошибок, сводя к минимуму проблемы для всех участников команды
## Установка git и VSCode на ваш ПК.

### Установка VSCode на ваш ПК.
Скачиваем с сайта https://code.visualstudio.com/, запускаем установщик, через интерфейс устанавливаем русский язык.
### Установка git на ваш ПК
Скачиваем с сайта https://git-scm.com/, запускаем установщик, указываем связку с VS Code, устанавливаем, запускаем терминал в VS Code.
#### Первая настройка git

____________________
**Начало работы:**
1. На компьютере **установлены** программы Git и Visual Studio Code

*(Скачать их можно здесь: https://git-scm.com/download/win
 и здесь https://code.visualstudio.com/docs/?dv=win 
)* 

** *! Обратите внимание: сначала лучше установить Git, затем Visual Studio Code* **

2. В корневом каталоге **создаем рабочую папку** проекта

3. **Заходим** в Visual Studio Code и нажимаем:
*File -> Open Folder..* **Выбираем** нашу папку.

4. **Создаем новый маркдаун-файл** для нашего проекта:
*File -> New File..* Создаем файл нашего проекта.

*(например, наш файл называется: instruction_hw1.md)*

5. **Запускаем термнал** для отслеживания и фиксации изменений: *Terminal -> New Terminal..* В нижней части экрана появляется окно терминала. **Убеждаемся**, что в терминале указано название папки нашего проекта.

6. Для отображения редактируемого файла в режиме просмотра следует также нажать на значок открытой книжки с небольшим кружочком - он расположен на уровне кнопок *Get Started* и названия рабочего файла в верхней части окна, чуть ниже команд *File, Edit, .. Terminal, Help*  

**Итог**: программа Visual Studio Code готова к работе с Git. **Можно приступать к работе**

** *! Обратите внимание:* **при первом запуске Git** *и Visual Studio Code, система попросит представиться - указать имя и email. необходимые команды и их формат будут указаны в терминале* **

__________________________


## Создание и базовая работа с локальным репозиторием.

### Что такое репозиторий и инструкция по созданию локальных репозиториев.
Репозиторий или хранилище — это каталог, в котором хранятся файлы вашего проекта. Он может быть расположен в хранилище GitHub или в локальном хранилище на вашем компьютере. Вы можете хранить файлы кодов, изображения, аудио или всё, что связано с проектом, в хранилище.
### Базовая работа с локальным репозиторием
git init
git branch
git checkout
git commit -m "comment"
git merge
git clone
git log
## Ветки. Локальная работа с ветками в git.

### Что такое ветки и для чего они нужны при работе с системой контроля версий.
Ветки позволяют работать над кодом так, чтобы на время разработки, основная версия проекта оставалась без изменений. Представьте, что у вас есть код, который работает. В какой-то момент вы решили добавить в него изменения.
### Базовая работа с ветками в git.
git branch
git checkout
## Работа с удаленными репозиториями.

### Что такое удаленный репозиторий и для чего он нужен
Удалённые репозитории — это модификации проекта, которые хранятся в интернете или ещё где-то в сети. Их может быть несколько, каждый из которых как правило доступен для вас либо только на чтение, либо на чтение и запись.
### Базовая работа с удаленными репозиториями GitHub
git clon
git pull
git push
## Совместная работа над проектом (fork, pull request)

### Как строится и для чего нужна совместная работа в системах контроля версий
Система управления версиями (также используется определение «система контроля версий[1]», от англ. Version Control System, VCS или Revision Control System) — программное обеспечение для облегчения работы с изменяющейся информацией. Система управления версиями позволяет хранить несколько версий одного и того же документа, при необходимости возвращаться к более ранним версиям, определять, кто и когда сделал то или иное изменение, и многое другое.

Такие системы наиболее широко используются при разработке программного обеспечения для хранения исходных кодов разрабатываемой программы. Однако они могут с успехом применяться и в других областях, в которых ведётся работа с большим количеством непрерывно изменяющихся электронных документов. В частности, системы управления версиями применяются в САПР, обычно в составе систем управления данными об изделии (PDM). Управление версиями используется в инструментах конфигурационного управления (Software Configuration Management Tools).
### Инструкция по созданию pull request
Сохраняете изменения в файла, комитите, и делаете git pull request
## Книги и полезные ссылки по изучению git.
https://learngitbranching.js.org/?locale=ru_RU
## Альтернативные системы контроля версий.
GitLab, Gogs