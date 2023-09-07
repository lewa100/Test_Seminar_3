# Комадны GIT
| Команда | Описание| 
|:----:|:----------|
|`git --version `| ___определить версию git___|
|`git config --global user.name "Lastname Firstname"`|___настройка login для коммитов___|
|`git config --global user.email "email@gmail.com"`|___настройка e-mail для коммитов___|
|`git init`|___инициализация git___|
|`git status `|___отображение файлов с изменениями___|
|`git add file `|___добавление файла в отслеживание изменений___|
|`git commit -m "commit"`|___фиксация изменений в виде коммита___|
|`git log`|___просмотр фиксированных состояний___|
|`git checkout #commit`|___переключение на одно из состояний___|
|`git diff`|___отображение локальных изменений___|
|`git checkout -b branchName`| ___создание новой ветки и переход в нее___|
|`git checkout branchName`| ___переход в указанную ветку___|

## Terminal Alias

| Alias | Описание| 
|:----:|:----------|
|`alias gs='git status'`| ___сокращение команды определения состояния___|
|`alias push='git push'`| ___загрузка изменений на удаленную ветку___|
|`alias pull='git pull'`| ___выгрузка изменений с удаленной ветки___|
|`alias gR='git reset --hard HEAD'`| ___сброс всех локальных изменений___|
|`alias glog='git log --pretty=format:"%h - %an, %ar : %s" --graph'`| ___удобный вывод log___|
|`alias gco='git checkout '`| ___удобный переход в указанную ветку___|
|`alias g='git'`| ___сокращение команды git___|
|`alias gb='git branch '`| ___сокращение команды для вывода веток___|

## REMOTE CMD
| Команда | Описание| 
|:----:|:----------|
|`git remote add origin url`| ___установка внешнего репозитория___|
|`git remote set-url origin url`|___изменение внешнего репозитория___|
|`git pull`|___выгрузка из внешнего репозитория___|
|`git push`|___загрузка на внешний репозиторий___|