# Basic 1 - The Idiot Test

## Konzepte & Writeup

![Basic 1 Übersicht](./img/1basic1lvl.png)

Mit Basic 1 beginnt die erste Mission der Serie. Der Hinweis deutet direkt darauf hin, dass hier grundlegende HTML-Kenntnisse gefragt sind. Das Level trägt den Namen "The Idiot Test" – anfangs war nicht sofort ersichtlich, warum. 

![Level Beschreibung](./img/2lvlbeschreibung.png)

Da HTML (Hypertext Markup Language) das Grundgerüst ist, mit dem Webseiten im Browser strukturiert werden, ist der logische erste Schritt eine Prüfung des Frontends. Das zentrale Konzept hierbei: Alles, was der Server an den Client ausliefert, ist im Klartext einsehbar.
    
Also mache ich einen Rechtsklick auf die Seite, öffne die Entwicklertools und untersuche den HTML-Quellcode, um speziell das Passwort-Eingabefeld und die umliegende Struktur zu analysieren.

![HTML Code untersuchen](./img/3htmluntersuchen.png)

Dabei springt mir im Quelltext sofort ein grüner HTML-Kommentar ins Auge. Dieser liefert das gesuchte Passwort direkt im Klartext.

![Passwort im HTML Kommentar](./img/4lösungimcode.png)

Damit klärt sich auch, wieso das Level "Idiotentest" genannt wird. Ich kopiere das gefundene Passwort, füge es in das Formular ein und bestätige die Eingabe. Daraufhin wird das Level als erfolgreich bestanden gewertet.

![Level erfolgreich bestanden](./img/5bestanden.png)

## Lessons Learned

Auch wenn dieses Level technisch extrem simpel ist, demonstriert es einen klassischen Architekturfehler im Web-Bereich: Sensible Daten wie Passwörter oder interne Logiken haben in HTML-Kommentaren oder generell im Frontend absolut nichts zu suchen.
    
Das grundlegende Takeaway, auch für den echten Berufsalltag: Wenn unklar ist, was einen erwartet, beginnt man immer mit der elementaren Aufklärung (Reconnaissance) der Client-Seite. Oft sind kritische Informationen durch eine mangelhafte Trennung von Client- und Server-Trust direkt im Quelltext hardcoded.