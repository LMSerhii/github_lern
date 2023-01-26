# github_lern

---
### Изменения пользователя 
    git config --global user.name "LMSerhii"
    git config --global user.email "leonovserhii89@gmail.com"

---

###### инициализация git репозитория 
    git init
###### добавление в стадию ожидания
    git add . or git add index.html
###### статус
    git status
###### удаление из стадии ожидания 
    git rm --cached index.html or git rm -rf cached .
###### добавление в репозиторий
    git commit -m "text-commit"
###### изменения 
    git log or git log --oneline
###### переход на версию определенного коммита 
    git checkout id_commit 
###### переход на основную ветку 
    git checkout maser 
###### удалить все коммиты до определенного коммита
    git reset id_commit 
###### удаляет все коммиты до определенного коммита и все изменения 
    git reset it_commit --hard 
###### создает новую ветку 
    git branch new_branch
###### переходит на новую ветку 
    git checkout new_branch
###### создает и переходит на новую ветку
    git checkout -b branch_name
###### соединяет текущую ветку с указанной
    git merge example


