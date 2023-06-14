# Git Tutorial

## 1. Lokal auf dem PC
-----
### Config 

git config --global user.email "meine.mail@icloud.com"

git config --global user.name "username"

----

1. Ordner erstellen mit **mkdir**

2. mit **ls** überprüfen, ob neuer Ordner erstellt wurde

3. mit **cd** in den neuen Ordner rein

4. mit **ls -a** prüfen, ob der Ordner leer ist (Ergebnis: **. ..**)

5. **git status** (-> error fatal, Ordner ist noch kein repo)

6. **git init**, um .git zu erstellen

7. mit **ls -a** prüfen, ob .git vorhanden (Ordner ist nun repo)

8. **git status** muss zeigen:

```
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

9. README.md erstellen mit **touch README.md**

10. **git status** muss zeigen

```
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
```

11. **git add README.md** ODER **git add .** -> zeigt an:

```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
```

12. **git commit -m "README Datei erstellt"** -> zeigt an:

```
[master (root-commit) 10658ad] README Datei erstellt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
```

13. **git status** zeigt an:

```
On branch master
nothing to commit, working tree clean
```

14. Wenn Datei verändert wurde, unbedingt speichern mit **STRG + s**, dann zeigt **git status** in roter Schrift

```
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

15. nach **git add .** zeigt Terminal in grüner Schrift:

```
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

```

16. **git commit -m "README Datei verändert"** ->

```
[master 5944588] README Datei verändert
 1 file changed, 3 insertions(+)
```

17. sollte weitere Datei erstellt werden (z.B. mit **touch math.txt**), muss diese auch mit **git add .** hinzugefügt werden

18. um alle Kommentare im Verlauf zu sehen: **git log** ->

```
commit 594458866e22e211867b052aeb08a96ab4ca10c0
Author: robbdouglas <robert.nimmrich@icloud.com>
Date:   Wed Jun 14 11:18:39 2023 +0200

    README Datei verändert

commit 10658ad19e74cc3171ad804ef9d8b7ced7353ef9
Author: robbdouglas <robert.nimmrich@icloud.com>
Date:   Wed Jun 14 11:05:39 2023 +0200

    README Datei erstellt
```
