# STAGE AND SNAPSHOTS

Working with snapshots and the Git staging area  

Работа со снапшотами и промежуточной областью Git  

```bash
git status
```
show modified files in working directory, staged for your next commit  

показывать измененные файлы в рабочем каталоге, подготовленные для вашего следующего коммита

```bash
git add [file]
```
add a file as it looks now to your next commit(stage)  

добавить файл, как он выглядит сейчас, в ваш следующий коммит(этап)

```bash
git reset [file]
```
unstage a file as it looks now to your next commit(stage)  

отключить файл, как он выглядит сейчас, в вашем следующем коммите(этапе)  
```bash
git diff
```
diff of what is changed but not staged  

разница того что изменено, но не добавлено в stage  
```bash
git diff --staged
```
diff of what is staged but not yet committed  

разница того что добавлено в stage, но ещё не зафиксировано  
```bash
git commit -m "[descriptive message]"
```
commit your staged content as a new commit snapshot  

зафиксировать подготовленный контент как новый снимок фиксации  
