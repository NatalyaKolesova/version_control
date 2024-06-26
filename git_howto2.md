# Инструкция по командам Git
## 1. Сделать папку репозиторием
```sh
git init
```
## 2. Проверить статус файла
```sh
git status
```
## 3. Добавить файл в репозиторий
```sh
git add
```
## 4. Сохранить изменения файла
```sh
git commit -m"text"
```
## 5. Проверить журнал изменений
```sh
git log
```
## 6. Сделать лог более удобным для просмотра (одной строкой)
```sh
git log --oneline
```
## 7. Посмотреть, есть ли изменения в записанных файлах
```sh
git diff
```
## 8. Перейти к одному из коммитов
```sh
git checkout[id коммита]
```
## 9. Вернуться к текущему состоянию ветки
```sh
git checkout master
```
## 10. Добавить картинку
```sh
git add [my picture] (my_picture.jpg)
```
## 11. Влить ветку в текущую
```sh
git merge [имя ветки]
```
## 12. Отображение всех веток
```
git branch
```
## 13. Перемещение по веткам
```sh
git checkout <имя ветки>
```
## 14. Создание новой ветки
```sh
git branch <branch_name>
```
## 15. Удаление ненужной ветки
```sh
git branch -d <branch_name>
```
## 16. Графический просмотр веток в логе
```sh
git log --graph
```
## 17. Игнорирование файла
Создать файл .gitignore, написать в правой поле редактора его имя, добавить и закоммитить его.

## 18. Работа с удаленным репозиторием на GitHub
* Зарегистрироваться на GitHub, найти нужный репозиторий, сделать fork, чужой репозиторий копируется в наш аккаунт.
* Чтобы перендести его к себе локально, создаем папку, заходим в нее в редакторе и командой 
```sh
git clone
```
копируем в свой репозиторий.

* Чтобы внести изменения, создаем для них новую ветку.
* Чтобы отправить изменения в свой удаленный репозиторий, команда
```sh
git push
```
* Чтобы не было конфликта, необходимо перед тем, как вносить изменения, скачивать себе последнюю версию командой
```sh
git pull
```
* Чтобы отправить запрос владельцу репозитория на ваши изменения, необходимо сделать pull request через соответствующую кнопку на GitHub.
Чтобы пофиксить ошибку, ввести 
```sh
git pull --rebase origin
```
Полная инструкция
git diff