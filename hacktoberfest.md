autoscale: true

![](img/bg_akademie.png)
#  Starting soon
## at 10:00 am

---

![](img/HF2020Events1920x1080Centered.png)

^ Willkommen

---

## Niclas Kahlmeier
Full Stack Developer @ Webmasters Akademie

@niclaskahlmeier

^ Wer bin ich?

---
## Was ist das Hacktoberfest

---
## Time Schedule ⏱

- 10.10 Uhr | Vorstellung der Webmasters Akademie
- 10.20 Uhr | Was ist Open Source und wieso sollte man Open Source unterstützen?
- 10.30 Uhr | Networking
- 11.00 Uhr | Workshop - Wie funktioniert Open Source?
    - Einführung Git & Github
    - Der Weg zur ersten Pull Request
- 11.30 Uhr | Wie finde ich passende Projekte?
- 12.00 Uhr | Hacken, Coden & Contributen
- 16.00 Uhr | Fazit

---
## Vorstellung der Webmasters Akademie

---
## Was ist Open Source?


^ Was ist Open Source? Warum veranstalten wir den ganzen Spaß hier ?
^ Open Source Software kann für jeden Zweck verwendet, inspiziert, modifiziert und weiterverbreitet werden.
^ kostenfrei
^ Das bedeutet, dass du schlichtweg mit Open Source machen kannst was du willst.
^ -> Microsoft Office = Lizens & Kosten & keine Modifikation
^ Jeder kann nach Fehlern suchen und diese beheben.

- Zusammenarbeit mit anderen
- Das Projekt kann angepasst und weiterverwendet werden
- Transparenz
- Demokratisch
- Flexibel

^ Übrigens ist der Punkt kostenfrei nur ein kleiner Teil des Gesamtwerts, den man von Open Source Software erhält.
^ Das wichtigste ist, dass du den Code modifizieren und republishen darfst. Mach das mal bei Powerpoint

___

![inline](img/jail.gif)

---

## Warum Open Source?

^ Ok also wir haben da den Vorteil für den Nutzer. Warum sollte ich aber als Maintainer meinen Code öffnen und jedermann kostenfrei zur Verfügung stellen?
^ Ein Maintainer versucht meist mit seinem Projekt ein eigenes Problem zu lösen. Viele andere Programierer haben oft das gleiche Problem.
^ profitieren von der gruppe
^ Open Source ist innovativ #latest technologies
^ Unternehmen verwenden extrem viel Open Source und geben auch viel zurück
^ ohne Open Source würde die heutige Software Welt nicht mehr funktionieren
^ - Laravel
^ - Node
^ - React

In der Gruppe sind wir stark!

Open Source = Innovation

^ Taylor Otwell wollte Problem beheben und hat Laravel für sich entwickelt.
^ Php war alte Sprache und wurde von vielen nicht gemocht. Mittlerweile ist PHP wieder mega hip und hat sich ernorm weiterentwickelt. Maßgeblich durch Laravel


---
## Was ist Open Source nicht?

^ Es wird nicht alles gemerged
^ Der Maintainer hat viel Arbeit damit
^ Meist ein Contributer den einen PR den er braucht und danach sieht man ihn nie wieder
^ => Lösung: Fork und ein eigenes Projekt mit du machen kannst was du willst

- nicht alles wird gemerged
- Mehrwert für die Community

---
## Kritik am Hacktoberfest

^ SHitstorm
^ Viel Spam
^ Tshirt
^ bitte spammt nicht

Many people try to be **smart** and send low-effort, borderline-spam PRs, essentially ruining a maintainer's day.

^ nun Beispiel warum Shitstorm

---

![inline](img/tweet/CleanShot 2020-10-15 at 7.50.44@2x.png)

---

![inline](img/tweet/CleanShot 2020-10-15 at 7.51.42@2x.png)

---

![inline](img/tweet/CleanShot 2020-10-15 at 7.51.57@2x.png)

---

![inline](img/tweet/CleanShot 2020-10-15 at 7.52.12@2x.png)

---

## Antwort auf die Kritik der Community

- Opt in
- PR Label hacktoberfest-accepted
- Repo Topic hacktoberfest


---
## Code of Conduct

✅ Kein Rassismums
✅ kein Mobbing
✅ keine Diskriminierung
✅ keine sexuellen Anspielungen
✅ keine anzüglichen Texte und Bilder
✅ **KEIN SPAM**

[CoC](https://docs.google.com/document/d/1gFKOhyUqMZzrZcbq8A_TpO5x9J9HK6agv70awCH8pyI/edit)

___

![inline](img/tweet/CleanShot 2020-10-15 at 7.50.23@2x.png)

---


## Vorstellungsrunde

- Wer bist du?
- Welche Vorerfahrung hast du?
- Welche Programmiersprachen benutzt / bevorzugst du?
- Welche Themen / Projekte interessieren dich?
- Möchtest du ein eigenes Projekt oder eine Projektidee kurz vorstellen?


---

## Einführung in Git & Github

^ Einführung in Git und Github

---
## Was ist Git?

-  Datenbank

^ Which Changes were made
^ Who made changes
^ When were the changes made
^ Why were changes needed

^ wenn kein Git sondern Dateien manuell von a nach b via FTP
^ -> mehrere Leute = katastrohe

^ um die lokale git datenbank zu erstellen
^ git init oder clone exisiting project


---
## Was ist Github?

- Online Git Provider

^ Build software together
^ share version tracked projects online
^ Share Code from local machine

---
## Git Flow

---

![inline](img/firstpr/Git_Layout.png)

---

git init

^ erstelle lokale git datenbank

---

git add .

^ sage git, dass die Änderungen im nächsten Commit aufgenommen werden sollen | Man spricht von Staging

---

git status

^ zeige Änderungen an

---

git commit -m "Nachricht"

^ Snapshot der aktuellen Änderung aus der Staging Umgebung
^ -> Meilensteine in Zeitleiste des Projekts

^ letzten commit zurück
^ git commit --amend

___

git push

^ exportiere Änderungen

---

git fetch

^ importiere Änderungern

---
git pull

^ fetch + merge
^ hole Änderungen und führe zusammen

---

## Git Begrifflichkeiten

---
## Was ist ein Fork?

^ you cannot push code to repos you dont own or have insufficient permissions.
^ because of that you need to make your own copy of the repo
^ Do whatever you want its yours
^ when you have done all changes you want in your fork / repo you can pull request
^ how?
^ click on fork
^ then clone
^ ssh or https or gh cli

## Was ist ein Issue?

- Bug Reports
- Feature Requests
- Fragen stellen

---
## Was ist ein gutes Issue?

^ - opening a good issue helps very much
^ - describe well and clear
^ - describe why
^ - comunicate whit maintainer => warum wie was

Communication is key

---

## Was ist ein Branch?

---

![](img/zach-reiner-H7LxvEmVZnE-unsplash.jpg)


---

![](img/yancy-min-842ofHC6MaI-unsplash.jpg)

---

^ - Save Place to experiment and develop without make difficulties in production
^ branch = unabhängig
^ branch verweist auf commit
^ machst du etwas in deiner Branch kaputt stört es nicht das ganze Projekt

Unabhängige Spielwiese

^ every feature and bugfix in own branch
^ prefix feature and bugfix
^ keep master clean

^ current branch
^ create branch with name

`git branch`
`git checkout -b feature/ `
`git checkout master`

---
## Was ist ein Pull Request?

^ jemand schaut über die Änderungen bevor etwas damit passiert

- Lass andere deine Änderungen sehen
- Diskutiere

---
## Was kann man pull requesten?

- feature
- bugfix
- docs

---

## Der Weg zur ersten Pull Request

---

1. fork
1. clone
2. Fork aktuell halten
3. outbranch
4. Änderungen vornehmen
5. Pull Request

---

^ you have to keep up to date with the upstream repositroy we forked from
^ they keep working while we work.
^ add repo we forked from as remote repo we can pull from
^ use their ssh url
^ git remote add upstream url

git remote -v
git remote add upstream url

---

^ get the newest changes

git fetch upstream

---

^ their master ist pointed to their master
^ our master is pointed to our master (origin)
^ we want to point our master to their master (upstream)
^ so whenever we pull we get their latest changes

git branch --set-upstream-to=upstream/master master

---

^ create branch

![inline](img/firstpr/CleanShot 2020-10-15 at 9.05.25@2x.png)

git checkout -b feature/completed-readme

---

^ make changes

![inline](img/firstpr/CleanShot 2020-10-15 at 9.05.50@2x.png)

---

^ add subject + comment
^ checks of ci have to pass!!!

![inline](img/firstpr/CleanShot 2020-10-15 at 9.06.01@2x.png)


---

^ look for comments in code
^ and for comments in main pr
^ make the requested changes to your pr

![inline](img/firstpr/CleanShot 2020-10-15 at 9.06.11@2x.png)

---

Merge Conflict

^ but what happens when they work and we work and our project isnt up to date with the upstream ?
^ then we get a merge conflict
^ we have to manage the merge conflict
^ we have to rebase it
^ then get a fresh copy of upstram master and then put our changes on top


git fetch upstream
git merge upstream/master


---

^ it is reviewed

![inline](img/firstpr/CleanShot 2020-10-15 at 9.06.21@2x.png)

---

🎉

___

### Wie sieht ein guter Commit aus?

![inline](https://imgs.xkcd.com/comics/git_commit_2x.png)
#### Quelle: https://imgs.xkcd.com/comics/git_commit_2x.png
^ würdet ihr die sagen, dass sind gut nachrichten?
^ wisst ihr, was in dem Commit geändert wurde?

---
^keine Nachricht wip
^write for every commit what you did

**Was und Warum**

^z.B. Refactor X to Y
^try your commits to do one thing
^each commit should be meaningful

^Limit first line to 50 chars
^explain why and what in body

---

### Gute Commit Nachricht:

Fix PHPUnit bool server consts result in null

After updating to Laravel 8 I suddenly had my test suite failing because telescope would not be disabled properly by `phpunit.xml` anymore.
This changes fixed my test suite.
I've also created a clean Laravel 8 project and added some tests to demonstrate the issue:

---

### Wie sieht ein guter Pull Request aus?

- Schau nach offenen Issues
- Schau ob es zu dem Thema schon einen offenen PR gibt
- Contributing.md
- Draft PR
- passe dich an
- Sei höflich, nett und freundlich

^ Wenn du eine Feature Idee hast, erst Issue und darüber sprechen
^ => spare deine Zeit und die der Maintainer

^ => Style Guide, you submit to another codebase foloew the style they have
^ -most repos linter als gh actions

^ Make a draft with minimal implememntation => proof of concept
^ => it visualise what you want to change
^ => wenn nicht weiterkommst oder etwas nicht verstehst, frag nach

^ write clean understandable code
^ - proper var names
^ - doc blocks
^ - describe what you did in the code and what it should do

^ fix one at the time
^ when doing multiple features make one pr per feature

^ use feature branches => dont push to main

---

---
## Wie finde ich passende Projekte?

https://github.com/search

- label:hacktoberfest is:open type:issue laravel
- label:hacktoberfest is:open type:issue language:JavaScript
- label:hacktoberfest is:open type:issue  language:Javascript Node
- label:hacktoberfest is:open type:issue language:HTML
- label:hacktoberfest is:open type:issue language:CSS
- label:hacktoberfest is:open type:issue  language:PHP

---
## Battleship

---
## Calculator

---
## CSS Art

---
## CSS Art

![inline](img/jslogo.png)![inline](img/christmas_tree.png)![inline](img/mario_pip.png)

---
## Stock Tracker CLI

---
## Resources

[Slack Channel](https://join.slack.com/t/hacktoberfest-lxf1464/shared_invite/zt-ihg5tyr4-rItlsR2usYHQZr3n8mOREw)


---
## Happy Hacking


---

---
## Austauschrunde

^ Was haben wir bis jetzt geschafft?
^ Erfahrungsaustausch


---
## Vielen Dank

---

## Schönes Wochenende

---

<!--
provide the oldest parent of commit of the rebase
-i = interactive
git rebase -i paste commit hash
or HEAD~ amount to go back
from top to bottom and you can take a command ever line
if you remove one commit it gets skipped
squash the second into the first
git push -f -->
