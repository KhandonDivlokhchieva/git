# Инструкция по использованию Git

Git - это распределенная система контроля версий, которая помогает в управлении и отслеживании изменений в коде и других файлах.

## Установка Git

1. Скачайте установочный пакет Git с [официального сайта Git](https://git-scm.com/).
2. Запустите установочный файл и следуйте инструкциям мастера установки.

## Начало работы

1. Откройте терминал или командную строку на вашем компьютере.
2. Инициализируйте новый репозиторий в выбранной папке с помощью команды:

git init 

## Добавление файлов в репозиторий

1. Добавьте файлы в индекс Git с помощью команды:

git add <файлы>

Например: 

git add index.html style.css

## Создание коммита

1. Создайте коммит с добавленными файлами, используя команду:

git commit -m "Ваше сообщение коммита"

makefile
Copy code

Например:

git commit -m "Добавлены файлы index.html и style.css"

