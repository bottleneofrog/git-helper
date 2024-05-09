# git-helper
### что такое Git
Git или SCM (**S**ource **C**ontrol **M**anagement) - консольный инструмент для работы с репозиториями и хранением истории изменений

### что такое GitHub
Платформа для совместной работы над проектами, которая предоставляет инструменты для создания удаленных репозиториев

### что такое SSH
**S**ecure **Sh**ell Protocol - обеспечивает безопасный обмен данными в сети

### базовые консольные команды:
``` pwd ```- **p**rint **w**orking **d**irectory - вывод текущей директории

``` cd ``` - **c**hange **d**irectory - смена директории
* ``` cd ~ ``` -  для смены директории на домашнюю
  

``` ls ``` - **l**i**s**t directory contents - вывод файлов в текущей директории

* ``` ls -a ``` - вывод скрытых файлов

``` .. ``` - родительскаяа директория

``` . ``` - текущая директория

``` touch ``` - создание файла

``` mkdir ``` - **m**a**k**e **dir**rectory - создание директории (папки)

``` cp ``` - **c**o**p**y - копирование

``` mv ``` - **m**o**v**e - перемещение

``` cat ``` - con**cat**enate and print - вывод содержимого текстового файла

``` rm ``` - **r**e**m**ove - удаление файла
* ```rm -r ``` для удаления папок вместе с их содержимым
* ```rm -f``` для форсированного удаления

``` rmdir ``` - **r**e**m**ove **dir**ectory - удаление директории

```clip``` - копирование содержимого в буфер обмена


* использовать ```&&``` для объединения команд в одну строку
* использовать ```tab``` для автодополнения
* использовать стрелки ```↑``` ```↓``` для перемещения в истории команд


### команды для работы с Git
```git version``` - проверка версии git

```git config``` - настройка конфигурации git

* ```user.name```- имя или ник пользователя
* ```user.email``` - электронная почта пользователя
##### флаги:
* ```--global``` для срабатывания команды во всех директориях

* ```--list``` для вывода содержимого файла конфигурации

  
```git init``` - инициализация репозиторием (сделать папку репозиторием)

```rm -rf .git``` - "разгитить папку" (--recursive, --force)

```git status``` - проверка состояния репозитория

```git add .``` - подготовить все файлы текущей папки к сохранению

```git commit -m``` - выполнить коммит (--message для добавления комментария)

```git log``` - вывести историю коммитов

```git remote -v``` - проверить, что репозитории связаны (--verbose для подробного вывода)

```git remote add``` - связывает удаленный репозиторий с локальным

```git push``` - отправить изменения на удаленный репозиторий


### команды для SSH
```ssh-keygen``` - генерация ssh-пары

```ls -la .ssh``` - вывод списка созданных ключей
