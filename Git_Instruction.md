# Работа с Git
## 1. Проверка наличия установленного Git
В терминале выполнить команду `git version`.
```C#
while(n > 0)
{
    n++;
}
```
Если Git установлен, появится информация с версией программы. Иначе будет сообщение об ошибке.


## 2. Установка Git
Загружаем полседнюю версию Git с сайта https://git-scm.com/book/en/v2/Getting-Started-Installing-Git .
Устанавливаем с настройками по умолчанию.

## 3. Настройка Git

При первом использовании Git необходимо представиться. Для этого нужно ввести в терминале две команды:
```
git config --global user.email "ВАШ email"
git config --global user.name "ВАШЕ Имя"
```

## 4. Инициализация репазитория Git init

Далее в терменале необходимо ввести.
```
git init
```
После этой команды Git начнёт отслеживать изменения файлов проекта.
Также данная команда отобразит нам в какой ветке мы находимся.

## 5. Получение информации о папке

Для того, чтобы получить от Git информацию о его текущем состоянии, в терменале необходимо ввести команду:
```
git status
```
После того как мы ввели данную команду, мы видем что у нас появляется ошибка и Git подсказывает что нам необходимо сделать.
```
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Git_Instruction.md

no changes added to commit (use "git add" and/or "git commit -a")
```

