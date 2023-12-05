# Ход работы:
![log](/IBS_task\log_graph.png)
1. Склонировал репозиторий, используя команду: 
> `git clone https://github.com/CanUFeelMyHeart/IBS.git IBS_task` 

Репозиторий находится в папке `IBS_task` на ПК

2. Добавили изменения в файл Potter.txt, ход работы отображается в файле `README.md`. Добавлено два файла и текст, сохраняем изменения:
> `git add .`  
`git commit -m "text"`

Все дальнейшие манипуляции можно сохранять через команду (новых файлов не будет создано):
> `git commit -am "text"`

3. Создаем и переходим в ветку `feature`, используя команды:
> `git branch feature`  
`git checkout feature`  

**ИЛИ**  
> `git checkout -b feature`


4. Внесли изменения в  каждую из веток. Переходим в ветке `feature`, в которую будем мерджить `master`:
> `git merge master`
При слиянии получаем `merge conflict` и решаем его

