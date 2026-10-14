# Hack This Site
 
## Überblick
Dieses Repository dient als umfassende Dokumentation meines Lernprozesses auf der Plattform ![Hack This Site](https://www.hackthissite.org/).
Das Ziel ist das aktive Ausnutzen von Web-Schwachstellen, um zu verstehen, wie man Systeme und Anwendungen effektiv absichert – sowohl für eigene Projekte als auch im Berufsalltag.

Zudem lerne ich, IT-Sicherheit aus der Perspektive eines Angreifers zu betrachten. Es geht immer darum, typische Schwachstellen zu identifizieren, den Weg des geringsten Widerstands zu finden und die Denkmuster hinter Exploits zu verstehen.

## Was ich in diesem Repo behandle
Neben dem reinen Lösen der Level lege ich in diesem Repo Wert auf die Kernprinzipien der Web-Sicherheit:

- **Client vs. Server Trust:** Die Erkenntnis, dass man niemals Daten vertrauen darf, die vom Client (Browser) kommen. Alles, was im Frontend passiert, kann manipuliert werden. Validierung muss immer serverseitig stattfinden.
- **Security by Obscurity ist keine Sicherheit:** Das bloße Verstecken von Informationen (wie Passwörter im HTML-Quelltext oder in unauffälligen Verzeichnissen) schützt nicht vor Angriffen. Ein Angreifer findet immer den Weg, wenn die Architektur selbst Schwachstellen aufweist.
- **Vom Exploit zur Mitigation:** Es reicht nicht, eine Lücke nur zu finden und das Level zu bestehen. Das Verständnis dafür, wie der zugrundeliegende Code funktioniert und wie man die Schwachstelle als Entwickler effektiv schließt, steht hier im Vordergrund.

## Struktur des Repositories
Um meinen Lernprozess sauber zu dokumentieren, ist dieses Repo wie folgt aufgebaut:

- **Konzepte & Writeups:** Meine Schritt-für-Schritt-Notizen zu den Grundlagen und Lösungswegen der einzelnen Level (z. B. Basic und Realistic Missions).
- **Lessons Learned:** Meine wichtigsten Takeaways aus jeder Mission und wie man die Lücke technisch beheben würde.