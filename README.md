# Лаба по СКВ Соколов Артём И-21
```
PS C: \Users\User\Documents\SokolovI-21> git add readme.md
PS C:\Users\User\Documents\SokolovI-21> git status readme.md
On branch master
No commits yet
Changes to be committed:
(use "git rm --cached <file>…" to unstage)
new file: readme. md
PS C: Users\User\Documents\SokolovI-21>
```
---

```
PS C:\Users\User\Documents\SokolovI-21> git add readme.md
PS C:\Users\User\Documents\SokolovI-21> git status readme.md
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md
```
---
```
Changes to be committed:
new file:
readme.
Untracked files:
mydirster]: created 463dc4f: "мой первый коммит"
2 files changed, 3 insertions(+), 0 deletions(-)
create mode 100644
C:/Users/User/Documents
SokolovI-21/
```
---
```
git commit  
```
```
Обнаружен своп-файл с именем "C:/Users/User/Documents/SokolovI-21/.git/.COMMIT_EDITMSG.swp"
          владелец: User    дата: 06 фев 2021 Сб 10:14:52
         имя файла: ~User/SokolovI-21/.git/COMMIT_EDITMSG
           изменён: ДА
      пользователь: User  компьютер: DESKTOP-T6GNTP0
           процесс: 1559 (ВЫПОЛНЯЕТСЯ)
при открытии файла: "C:/Users/User/Documents/SokolovI-21/.git/COMMIT_EDITMSG"
              дата: 06 фев 2021 Сб 10:35:15
                    Более СВЕЖИЙ, чем своп-файл!
(1) Возможно, редактирование этого же файла выполняется в другой программе.
    Если это так, то будьте внимательны при внесении изменений, чтобы
    у вас не появилось два разных варианта одного и того же файла.
    Выйдите или продолжайте с осторожностью.
(2) Сеанс редактирования этого файла завершён аварийно.
    В этом случае, используйте команду ":recover" или "vim -r C:/Users/User/Documents/SokolovI-21/.git/COMMIT_EDITMSG"
    для восстановления изменений (см. ":help recovery").
    Если вы уже выполняли эту операцию, удалите своп-файл "C:/Users/User/Documents/SokolovI-21/.git/.COMMIT_EDITMSG.swp"
    чтобы избежать появления этого сообщения в будущем.

Своп-файл "C:/Users/User/Documents/SokolovI-21/.git/.COMMIT_EDITMSG.swp" уже существует!
[O] Открыть для чтения, (E) Редактировать, (R) Восстановить, (Q) Выход, (A) Прервать: 
```
---
```
git commit -m "мой первый коммит"
>> 
[master (root-commit) 6e33b27] мой первый коммит
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
```
---
```
git remote
pb
```
---
```
git remote
pb
```
---
```
git checkout
M       readme.md
```
----
```
git checkout readme.md
Updated 1 path from the index
```
---
```
git stash 
No local changes to save
```
---
```
git stash pop
No stash entries found.
```
---
```
git branch юху
git checkout юху
Switched to branch 'юху'
```
---
```
PS C:\Users\User\Documents\SokolovI-21> git checkout master
Switched to branch 'master'
PS C:\Users\User\Documents\SokolovI-21> git merge юху
Already up to date.
```
---
