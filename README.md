# Mein Git Lernjournal

## Grundlagen

**Frage1:**     Ein Commit speichert drei Dinge. Was sind sie?

**Antwort:**    Ein Commit speichert:
                1. Was wurde geändert.
                2. Wer hat es geändert.
                3. Warum wurde es geändert.

**Frage2:**     Was ist der "Stamm" (trunk) des Baumes in der Terminologie der Versionskontrolle?

**Antwort:**    Der Stamm (trunc) ist die Hauptentwicklungslinie , die Hauptversion von der alle branches Äste abgehen.


## Architektur

**Frage1:**     Was ist in einem zentralisierten System der "Single point of failure"?

**Antwort:**    Der zentrale Server ist der Single point of failure, wenn diesere ausfällt , kann niemand mehr arbeiten, comitten, backups 
                machen.

**Frage2:**     Wo wird in einem verteiltem System (wie Git) die vollständige Projekthistorie gespeichert?

**Antwort:**    Auf einem verteiltem System wird an zwei Orten gespeichert , lokal und auf einem Server, sodass jeder Entwickler eine         
                vollständige Kopie besitzt.


## Der Workflow

**Frage:**      Was entspricht in der "Supermarkt-Analogie" dem Einkaufswagen?

**Antwort:**    Die Staging Area, in der man sozusagen Dateien markiert - in den Einkaufswagen legt um sie später an der Kasse mit nach Hause 
                zu nehmen.

**Frage:**      Welcher Befehl wird verwendet, um einen Schnappschuss des Einkaufswagens zu machen?

**Antwort:**    Der Commit Befehl ist ein permanenter Schappschuss des Projekts, in der Supermarkt-Analogie" ein SChnappschuss des          
                Einkaufswagens zu einem bestimmten Zeitpunkt bevor es weiter zur Kasse geht und bezahlt wird.