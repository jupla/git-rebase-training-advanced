Training: Git-Rebase (fortgeschritten)
======================================

Bitte führe dieses Training erst durch, wenn die
"Git-Rebase (grundlegend)" durchgeführt hast!
Die Ausgangssituation und das Zielbild sind
identisch zum Basistraining!

Das Training ist intern und extern verfügbar.
Die externe URL ist: [github:git-rebase-training-advanced](https://github.com/70435-training/git-rebase-training-advanced).

Voraussetzungen
---------------

Seitens der "Infrastruktur" gibt es diese Voraussetzungen:

* Firefox ist installiert (Chrome geht nicht)
* Git-Kommandozeilen-Tools sind installiert
* Meld ist installiert [(Hilfe)](cheat-sheet/cheat-sheet.md#0890)
* Gitg ist installiert [(Hilfe)](cheat-sheet/cheat-sheet.md#0900)
* Fork von diesem Repo ist angelegt, Arbeit erfolgt nur an
  diesem Fork
* Du hast einen lokalen Clone vom Fork [(Hilfe)](cheat-sheet/cheat-sheet.md#0900)
* Dein Arbeitsverzeichnis ist im lokalen Clone
* Diese Anleitung kann in Firefox gesichtet werden: `firefox index.html`

Seitens der Kenntnisse:

* Erfahrung mit der Kommandozeile
* Erfahrung mit Git (clone, branch, pull/push, commit, ...)
* [Training: Git-Rebase (grundlegend)](https://github.com/70435-training/git-rebase-training-basic) ist durchgeführt

Ausgangsituation
----------------

![Ausgangssituation](images/start.png)

Die Ausgangssituation ist quasi identisch zum Basistraining:

- Es gibt einen Master-Branch
- ... und auch den Branch "experiment"
- "experiment" wurde irgendwann in der Vergangenheit erzeugt,
  er zweigt in der Vergangenheit vom Master-Branch ab
- Die Ausgangssituation kannst Du visualisieren mit `gitg origin/master origin/experiment`

Zielbild
--------

![Zielbild](images/final.png)

Das Zielbild ist quasi identisch zum Basistraining:

- Es gibt einen Master-Branch
- ... und auch den Branch "experiment"
- Der Abzweigezeitpunkt von "expriment" ist verschoben
  auf den aktuellen Master-Branch

Ablauf
------

### Vorbereitungen

- Öffne dieses Dokument in Firefox mit `firefox index.html`,
  damit Du direkten Zugriff auf die "cheat sheets" bekommen kannst
  (Chrome geht nicht, Browsen via Github o.ä. geht nicht)
- Stelle sicher, dass alle Änderungen am zentralen Repo bei Dir lokal verfügbar sind [(Hilfe)](cheat-sheet/cheat-sheet.md#1010)
- Visualisiere die Situation [(Hilfe)](cheat-sheet/cheat-sheet.md#1020)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen!
- Kontrolliere, ob "experiment" und "origin/experiment" übereinstimmen!

### Durchführung

- Branch "experiment" auschecken [(Hilfe)](cheat-sheet/cheat-sheet.md#1110)
- Branch "experiment" aktualisieren [(Hilfe)](cheat-sheet/cheat-sheet.md#1120)
- Rebase durchführen [(Hilfe)](cheat-sheet/cheat-sheet.md#1130)
- Sichten [(Hilfe)](cheat-sheet/cheat-sheet.md#1140)
- Ergebnis "veröffentlichen" [(Hilfe)](cheat-sheet/cheat-sheet.md#1150)

Nachkontrolle
-------------

- Visualisiere die Situation [(Hilfe)](cheat-sheet/cheat-sheet.md#1210)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen!
- Kontrolliere, ob "experiment" und "origin/experiment" übereinstimmen!
- Vergleiche Dein Bild strukturell mit [images/final.png](images/final.png)

Abschluß
--------

Nach Abschluß des Trainings bitte die URL zu dem bearbeiteten
Fork per Email schicken an "dp-training@daemons-point.com"!
