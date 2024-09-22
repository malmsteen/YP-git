```bash
# Привязать удалённый репозиторий к локальному
cd ~/dev/first-project
git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git

git push origin local_branch_name:remote_branch_new_name # поменять имя запушеной удаленной ветки
git push origin :remote_branch_old_name # запушить ничего в удаленную ветку
git branch -m new_name # переименование текущей ветки

git pull origin master # origin - имя удаленного репозитория, но загрузится только ветка master, остальные надо с fetch

git fetch origin # приезжают все коммиты и указатели из origin
```
