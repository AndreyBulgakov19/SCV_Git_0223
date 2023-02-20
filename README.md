![Logo](IMG_0648.PNG)

# Работа с Git и GitHub

## 1. Проверка наличия устанновленного Git
в терминале выполнить команду `git version`
если установлен - инфа об установленной версии, иначе ошибка.

## 2. Установка Git
Загружаем последнюю версию с сайта https://git-scm/dowmload.
Устанавливаем с настройками по умолчанию.

## 3. Настройка Git
первым делом необходимо указать имя пользователя и адрес электронной почты _это очень важно_. 
Для настройки используй команду git config --global user.name "John D"
и git config --global user.email johnd@example.com. 
Проверить настройку можно командой __git config --list__.

## 4. Инициализация репозитория
Для отслеживания существующего проекта надо перейти в папку проекта и ввести команду __git init__.
Для копирования есть команда __git clone__.

## 5. Запись изменений в репозиорий
__git status__ определяет состояние файлов. 

__git add__ записывает файл и начинает слежение за ним

__git commit -m__ индексирует файл

## 6. Просмотр изменений
Для этого есть команда ***git diff***.

## 7. Просмотр истории веток
Для просмотра истории веток используй командк ***git log***.

## 8. Игнорирование файлов
для исключения из отслеживания в репозитории определенные файлы и папки необходимо создать там файл ***.gitignore***, и записать туда их названия, или шаблона.

## 9. Создание веток в Git
Ветка в Git - это простой перемещаемый указатель на один из комитов, для работы используем команды :

__git branch__ для просмотра веток

__git branch branch_name__ для созданию новой ветки

__git checkout branch_name__ для создания и перхода на новую ветку, или перемещения по веткам


## 10. Слияние веток и разрешение конфликтов
Для слияния выбранной ветки с текущей нужно выполнить команду:

__git merge <name_branch>__ 

Если была изменена одна и таже тогда конфликт который требует участия пользоателя. В программе VScode выбрать одно из предложенных действий.

## 11. Работа с удаленным репозиторием

