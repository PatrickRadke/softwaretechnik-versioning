# softwaretechnik-versioning


## Aufgaben

1. [x]  Erstellen Sie sich ein Repository in Github oder GitLab.
2. [x] Pushen Sie ein eigenes Projekt von Ihnen hoch (z. B. das CCD-Projekt) oder erstellen Sie ein neues Projekt!
3. [x] Wenden Sie alle in der Lerneinheit genannten relevanten Methoden beweisbar an: (das Github Repo ist Beweis) 
        [x] push, 
        [x] pull, 
        [x] add, 
        [x] commit, 
        [x] diff, 
        [x] status, 
        [x] rm/mv, etc.
4. [ ] Experimentieren Sie mit Zeitreisen!
5. [ ] Erstellen Sie zwei unterschiedliche aber ähnliche Branches, wechseln Sie hin und her und mergen sie diese Branches dann wieder!
6. [ ] Erstellen Sie in GitHub einen Pull-Request bezugnehmend auf https://github.com/edlich/education! (was kleines, nützliches, witziges, etc., aber nicht via Shell, sondern via GitHub click!)




## 1. 
 
- repo softwaretechnik-versioning erstellt
- https://github.com/PatrickRadke/softwaretechnik-versioning



## 2.  

- neues Projekt erstellt


## 3.  

### add
- "hello world.txt" file im Projekt zugefügt -> anfangs untracked (U)

![screenshot.png](pics/untracked.png)

- nutze Befehl: 'git add *'
- file nun im Status "index added":

![screenshot.png](pics/add.png)



### diff

- nutze Befehl: 'git diff'
- Ergebnis:

![screenshot.png](pics/diff.png)


### pull

- nutze Befehl: 'git pull'
- Ergebnis:

![screenshot.png](pics/pull.png)


### commit

- nutze Befehl: 'git commit -m "hello world und pics zugefügt"'
- Ergebnis Projekt:

![screenshot.png](pics/commit-local.png)


### status

- nutze Befehl: 'git status'
- Ergebnis:
![screenshot.png](pics/status.png)



### rm

- lege Datei an, die gelöscht werden soll: fileToDelete.txt
- adde und committe die Datei
- nutze Befehl: 'git rm fileToDelete.txt'
- Ergebnis:

![screenshot.png](pics/rm.png)


### mv

- lege Datei an, die verschoben oder umbenannt werden soll: fileToMoveOrRename.txt
- adde und comitte die Datei
- nutze Befehl: 'git mv fileToMoveOrRename.txt file1.txt'
- Ergebnis:

![screenshot.png](pics/mv.png)
(der Befehl gab keine weitere Bestätigung aber die Datei war danach umbenannt)


### push

- commite letzten aktuellen Stand
- nutze Befehl: 'git push'
- Ergebnis lokal:

![screenshot.png](pics/pushLokal.png)

- Ergebnis repo:

![screenshot.png](pics/push.png)