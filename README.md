# Репозиторий для **pull request**
* В своём аккаунте на GitHub создать копию репозитория **"AndreyBulgakov19
/SCV_Git_0107"** с помощью кнопки **"Fork"**.
---
* Клонировать копию репозитория на локальный компьютер.
---
* Создать новую ветку.
---
* Добавить файл с инструкцией в новую ветку.
---
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
---
* Зафиксировать изменения (коммиты).
---
* Отправить изменения на GitHub.
---
* На сайте GitHub выполнить **Pull request**.
---
# Инструкция по работе с GIT
## 1. Проверка установленного git
* откройте терминал 
* введите к строке терминала `git version`
## 2. Создание репозитория 
* проверьте, явдяется ли открытая папка репозиторием введя в строке терминала команду `git status`
* если открытая папка не является репозиторием, создайте репозиотрий. Для этого введите в строке терминала команду `git init`
> скорее всего в терминале появится сообщение о том, что был создан пустой репозиторий
## 3. Создание файла
* создайте файл через основное меню или нажав на иконку "создать файл"
* введите в строке терминала команду `git add "имя файла.расширение"`, для того, чтобы git отследивал файл
* проверьте, что файл добавлен и отслеживается git, введя в терминале команду `git status`
## 4. Сохранение изменений 
* добавьте содержимое рабочего каталога в индех для последующего комита. Для этого в строке терминала введите команду `git add "имя_файла.расширение"`
> используйте **TAB** для автоматического заполнения
* зафиксируйте (сохраните) изменеия. Для этого в строке терминала введите команду `git commit -m "комментарий"` 
* проверьте, что все сохранилось корректно. Для этого в строке терминала введите команду `git status` 
## 5. Основные команды GIT 
* текущее состояние git 
```
git status
```
> Чтобы вызвать ранее введённую команду, пользуйте стрелки на клавиатуре. Перебирайте недавно введённые команды нажатием стрелки «вверх».
* добавление содержимое рабочего каталога в индекс  для последующего коммита
``` 
git add "имя_файла.расширение" 
```
* зафиксировать (сохранить) изменения 
```
git commit -m "комментарий" 
```
* журнал изменений 
```
git log
```
* переключение между версиями 
```
git checkout 
```
* возвращение в основную верку
```
git checkout master
````
> Нажатие клавиши ‘q’ возвращает в исходное окно терминала
* разница между текущим файлом и сохранённым
```
git diff
```

**продолжение следут...** 

## 6. Создание веток
* Для того, чтобы создать новую ветку введите в терминале команду:
```
git branch имя_ветки
```
* для того чтобы удалить ветку введите в терминале команду: 
```
git branch -d имя_ветки
```
* для того, чтобы слить ветки введите в терминале команду:
```
git merge имя_ветки_которая_вольется
```
* для того, чтобы перейти на ветку, введите в терминале команду:
```
git checkout имя_ветки
```

## 7. Добавление фотографий 
* добавьте фото в репозиторий 
* создайте файл .gitignore, где пропишите имя и расширение фотографии (для того, чтобы скрыть файл от системы контроля версий)
> в файле .gitignore можно задать фаблон файлов следующим образом: `*.расширение`
* вставтьте фото в текст, прописав в файле следующую команду: 
> восклицательный знак [текст](путь до фото)

![милый котик](kotik.jpg)
> где  [в квадратных скобках прописывается текст, который будет отображаться, если фото не загрузиться], а (в круглых скопках прорисывается путь до фото, в нашем случае это имя.расширение, т.к. фото хранится в основной папке)

**перенесли проект в github**
**перенесла проет на рабочий копьютер.**
> для того, чтобы начать редактирование проекта, обязательно поменять директорию с помощью команды `cd имя_папки`
## 8. Работа с удаленными репозиториями 
1. Создайте аккаунт на GitHub
2. Создайте на своем аккаунте репозиторий 
3. Подружите ваш локальный репозиторий и удаленный. Во вкледке `Code` на аккаунке в GitHub есть все необходимые инструкции
4. С помошью команды `push`  вы можете отправить свою версию репозитория во внешний репозиотрий
5. С помощью команды `pull` вы можете выкачать актуальную информацию из удаленного репозитория 
6. С помощью команды `git clone hpps//ссылка` вы можете клонировать удаленный репозиторий на локальный. Ссылку можно взять во вкладке `code`
## 9. Pull request
1. Сделайте `fork` (ответвление) стороннего репозитория на свой аккаутн GitHub
2. Сделайте `git clone` с удаленного репозиотрия на локальный
3. Создайте новую ветку и внесите все необходимые изменнеия
4. Зафиксируйте изменения (`add, commit -m`)
5. Отправьте измненеия на свой удаленный репозиторий
6. На сайте GitHub нажмите кнопку `pull request`
