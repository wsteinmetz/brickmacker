# brickmacker
Maßgeschneiderte Klemmbausteine aus dem Browser
ie Faszination für Klemmbausteine ist generationsübergreifend. Doch was passiert, wenn der benötigte Stein für ein eigenes Projekt einfach nicht existiert? Eine maßgeschneiderte Grundplatte für den Roboter-Bausatz? Ein runder 8x8 Stein als Gehäuseabdeckung? Genau hier setzt der neue **parametrische BrickMaker** an.

Die kostenlose Web-Applikation erlaubt es, individuelle Bausteine direkt im Browser zu konfigurieren und als fertige 3D-Druck-Datei herunterzuladen – komplett ohne Software-Installation. Das Tool richtet sich dabei nicht nur an leidenschaftliche 3D-Druck-Hobbyisten, sondern entpuppt sich als geniales Werkzeug für den MINT-Unterricht (Mathematik, Informatik, Naturwissenschaft, Technik) in der Mittelstufe.

## Für Hobby-Makers: FDM-optimiert und Support-frei

Wer schon einmal versucht hat, Klemmbausteine auf einem handelsüblichen FDM-3D-Drucker (wie einem Prusa, Bambu Lab oder Creality) zu drucken, kennt das Problem: Entweder brechen die Noppen ab, der Stein passt nicht auf originale Teile, oder die hohle Unterseite erfordert mühsam zu entfernende Stützstrukturen (Support).

Der BrickMaker löst diese Probleme durch intelligentes Design direkt im Code:

* **Support-freies Drucken (Bridging):** Die inneren Röhren und Decken der Steine sind so konstruiert, dass sie vom Slicer als saubere "Brücken" (Bridges) erkannt werden. Der Drucker spannt das flüssige Plastik einfach in der Luft, ganz ohne Stützmaterial.

* **Perfekte Passform:** Über einen Slider lässt sich die *Toleranz* in 0.05-mm-Schritten anpassen. So kann der "Friction Fit" (die Klemmkraft) perfekt auf das eigene Filament (PLA, PETG) kalibriert werden.

* **Integrierte Grundplatten:** Das Programm generiert nicht nur Steine (von 1x1 bis 12x2), sondern auch extrem flache Grundplatten (bis 200x200 mm) mit einem gewichtssparenden "Waffle-Grid" auf der Unterseite, das ein Durchbiegen beim Druck verhindert.

* **Direkter STL-Export:** Mit einem Klick landet die fertige `.stl`-Datei auf dem Rechner und kann sofort in den Slicer gezogen werden.

## Für Lehrer und Schüler: Geometrie und Programmieren "begreifen"

Für den Einsatz in der Mittelstufe (Sekundarstufe I) bietet die App einen unschätzbaren pädagogischen Mehrwert. Das Konzept von räumlichem Denken und Geometrie ist für viele Schüler abstrakt. Der BrickMaker macht Mathematik sprichwörtlich begreifbar.

### 1. Niederschwelliger Einstieg ins 3D-Design

Da die App rein webbasiert ist, entfällt für Schulen das Problem von fehlenden Admin-Rechten, veralteten Computern oder komplexen Installationen. Schüler öffnen einfach die Webseite und können sofort in einer intuitiven, modernen 3D-Umgebung arbeiten.

### 2. Code-Sichtbarkeit (OpenSCAD)

Der größte Clou für den Informatik-Unterricht versteckt sich in der unteren rechten Ecke des Bildschirms: Ein Code-Fenster zeigt in Echtzeit das zugrundeliegende **OpenSCAD-Skript** an.
Wenn ein Schüler den Stein von 4x2 auf 6x2 Noppen vergrößert, sieht er direkt, wie sich die Variablen im Quelltext ändern und wie eine *For-Schleife* im Code die zusätzlichen Noppen berechnet. Das Verständnis für Variablen, Schleifen (`for x = [0 : cols - 1]`) und boolesche Operationen (`difference`, `union`) wird hier spielerisch und visuell vermittelt.

### 3. Problemlösungsorientiertes Lernen

Lehrer können praxisnahe Aufgaben stellen: *"Konstruiert eine Halterung für unsere Schul-Mikrocontroller. Welche Grundplatte benötigen wir, und welche Toleranz müssen wir für unseren Schul-Drucker einstellen?"*
Die Schüler entwerfen das Teil digital, drucken es aus und testen es in der physischen Welt. Ein perfekter Kreislauf aus Iteration und praktischem Lernen.

## Fazit

Egal ob es darum geht, ein fehlendes Teil für die heimische Klemmbaustein-Eisenbahn zu drucken, oder einer 8. Klasse die Grundlagen der parametrischen 3D-Konstruktion beizubringen: Der BrickMaker schlägt eine elegante Brücke zwischen digitalem Code und physischem Objekt. Ein kleines Stück Software, das zeigt, wie zugänglich und mächtig moderne Maker-Tools heute sein können.
