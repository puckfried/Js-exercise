# Js-exercise

### Vorbereitung

- Erstellt eine **index.html**, **style.css** und **script.js** Datei
- erstellt die HTML-Grundstruktur
- verlinkt die Style- und Script-Datei im HTML
- im der Html sollte es 2 Boxen (`<div>`) geben (die 3. Box ist ein Bonus, kann am Anfang weggelassen werden)
- In der ersten Box befinden sich 3 Buttons (`<button>`) mit folgender Bezeichnung geben: **Farbe**, **Drehen**, **Ausblenden**  
- In der zweiten Box befindet sich ein `<input>` Feld und ein Button (**Text laden**) (*verwendet hier kein form Element sondern nur ein input*)
- Die dritte Box ist Bonus (siehe unten): Eine Box mit einem Button (**Erstelle**) und einer leeren `div` (nicht sichtbar, da kein Inhalt)

***Hier eine mögliche Darstellung, aber es kommt nicht darauf an, das Design zu treffen, so können eure Buttons auch nebeneinander sein:***
<br>

![Vorschau der Seite](mockup.png)

### Aufgabe
- jeder `button` soll eine Funktionalität bekommen
- `Farbe` --> die erste Box soll eingefärbe werden 
- `Drehen` --> der erste Kasten soll sich um 360 Grad drehen, benutzt `transition` um den Effekt zu sehen 
- `Ausblenden` --> beim Klicken soll der Kasten verschwinden
- `Text laden` --> der Text aus dem Eingabefeld soll dadrunter ausgegeben werden
<br>

**Bonus** *hattten wir nicht in der Präsentation, versucht es zu googlen, oder fragt mich :-)*
- `Erstelle` --> bei jedem Klick sollen 5 neue kleine Boxen in der Box entstehen
- versucht beim `button` Farbe eine zufällige Farbe mit jedem Klick zu vergeben, das geht nicht mit Klassen im CSS, nur mit element.style.backgroundColor)
