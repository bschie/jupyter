# Selbstlernkurs für die Sprache Python

Die Dateien in diesem Repository bilden einen Selbstlernkurs zur Sprache Python. Er ist entstanden anlässlich einer Reihe von Qualifizierungs-Maßnahmen für Lehrer:innen für das Unterrichtsfach Informatik in der Sekundarstufe 1 im Saarland.

Mehr Information zur Maßnahme finden sich im Flyer zur zweiten Runde:
https://www.lpm.uni-sb.de/typo3/fileadmin/Benutzer/medien/connette/Quali_Informatik_2022-24_V2.pdf

Die Dokumente sind als **Jupyter** - Dateien erstellt. In diesen können sich  Textstücke und Codefragmente abwechseln. Charmant an Jupyter ist, dass man diese Codefragmente ausführen kann ohne in ein anderes Programm zu wechseln. Es ist ebenfalls möglich, dass man die Codefragmente ändern oder ergänzen kann und man sein Werk dann direkt austesten kann.

Ausführliche Informationen zu **Jupyter** finden sich auf der Webseite https://jupyter.org.

Wir nutzen https://mybinder.org als Laufzeitumgebung der Jypiter-Dateien. 

Dieser Selbstlernkurs wird aufgerufen durch https://mybinder.org/v2/gh/bschie/jupyter/main.

Die in dieser Umgebung vorhanden Dateien lassen sich sowohl starten als auch verändern. Diese Veränderungen werden jedoch nicht dauerhaft gespeichert. Wenn man seine Änderungen dennoch sichern möchte, muss man die bearbeiteten oder auch neu erstellten Jupyter - Dateien auf seinen eigenen Rechner downloaden. 

## Alternative Umgebungen

1. Mybinder erstellt eine virtuelle Maschine aus den Dateien des öffentlichen GitLab Repositorys https://github.com/bschie/jupyter. Wenn man die Abhängigkeit von einem externen Anbieter vermeiden möchte, kann man die Jupyter-Software auch auf seinem Rechner lokal installieren und die Jupyter - Dateien dort starten.

2. Google bietet auf der Seite https://colab.research.google.com eine eigene Implementierung der Jupyter - Software an. Das Handling ist sehr ähnlich und die Dateien sind kompatibel. Der Haken: Zwar kann man die Jupyter - Dateien auf diesem Weg veröffentlichen, aber ohne Anmeldung bei einem Google-Konto werden die Codefragmente nur angezeigt und können nicht ausgeführt werden. In Schulen kann das Vorhandensein eines Google-Kontos jedoch weder bei Lehrer:innen noch bei Schüler:innen erwartet werden.

3. Es gibt auch eine Testumgebung für **Jupiter** - Dateien, auf der man hochgeladene Dateien ausführen kann: https://jupyter.org/try-jupyter/lab. Diese Testumgebung kann aber keine Bibliotheken einbinden, die nicht schon vorinstalliert sind. Diese Seite gilt als experimentell.
