# Git
### Git - это система контроляверсий, помогающая разработчикам управлять состоянием исходного кода на протяжение всей разработки, т.е. система, которая записывает ваши изменения в файл и позже позволяет откатиться к более ранней версии проекта.

# Основные команды

## Навигация.

**pwd** - выводит путь к текущей директории.

**ls** - выводит список файлов и папок в текущей директории.

**ls -a** - выводит в том числе и скрытые файлы.

**cd <имя>** - перейти из текущей директории в директорию <имя>. 

**cd ~ ** - путь к домашней директории.

**cd ..** - вернуться в родительскую директорию.

## Работа с файлами и папками.

### Создание.

**touch <имя.расширение> <имя.расширение>** - создать файл. Можно одновременно несколько файлов или только один.

**mkdir <имя директории>** - создать директорию.

### Копирование и перемещение.
**mv <что переместить> <куда переместить>** - перемещение файлов и директорий.

**cp <что скопировать> <куда скопировать>** - копирование файлов и директорий.

### Чтение.

**cat <имя файла>** - вывести содержимое текстового файла.

### Удаление.

**rm <имя файла>** - удалить файл.

**rmdir <имя директории>** - удалить пустую директорию.

**rm -r <имя директории>** - удалить директорию со всеми вложенными файлами.

## Репозитории.

### Инициализация и удаление репозитория.

**git init** - создать папку с репозиторием.

**rm -rf .git** - разгитить папку если что-то пошло не так.

### Просмотр состояния файлов.

**git status** - показать текущее состояние репозитория.

### Подготовка файла или папки к коммиту.

**git add <имя файла> или --all** - подготовить файлы к сохранению.

**git add .** - подготовить к коммиту текущую папку и все файлы в ней.

### Создание коммита.

**git commit -m "сообщение"** - выполнить коммит.

### Просмотр информации о коммитах.

**git log** - посмотреть историю изменений.

### Клонирование репозитория.

**git clone <SSH-key>** - копирование пепозитория на локальный компьютер.

**git remote -v** - убедиться, что репозитории связаны.

### Отправка изменений на удаленный репозиторий.

**git push** - загрузить содержимое на GitHub.

**git push -u origin main** - для первого раза.
