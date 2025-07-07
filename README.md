# JavaScript Exercise

## Deutsch

### Vorbereitung

- Erstelle eine **index.html**, **style.css** und **script.js** Datei
- Erstelle die HTML-Grundstruktur
- Verlinke die Style- und Script-Datei in der HTML
- In der HTML sollten 2 Boxen (`<div>`) vorhanden sein (die 3. Box ist ein Bonus und kann am Anfang weggelassen werden)
- In der ersten Box befinden sich 3 Buttons (`<button>`) mit folgenden Bezeichnungen: **Farbe**, **Drehen**, **Ausblenden**  
- In der zweiten Box befindet sich ein `<input>`-Feld und ein Button (**Text laden**) (*verwende hier kein form-Element, sondern nur ein input*)
- Die dritte Box ist ein Bonus (siehe unten): Eine Box mit einem Button (**Erstelle**) und einer leeren `div` (nicht sichtbar, da kein Inhalt)

***Hier ist eine mögliche Darstellung, aber es kommt nicht darauf an, das Design genau zu treffen - eure Buttons können auch nebeneinander angeordnet sein:***

![Vorschau der Seite](mockup.png)

### Aufgabe
- Jeder `button` soll eine Funktionalität bekommen:
  - `Farbe` → die erste Box soll eingefärbt werden 
  - `Drehen` → der erste Kasten soll sich um 360 Grad drehen (benutze `transition`, um den Effekt zu sehen)
  - `Ausblenden` → beim Klicken soll der Kasten verschwinden
  - `Text laden` → der Text aus dem Eingabefeld soll darunter ausgegeben werden

**Bonus** *(hatten wir nicht in der Präsentation, versucht es zu googeln oder fragt mich :-)*
- `Erstelle` → bei jedem Klick sollen 5 neue kleine Boxen in der Box entstehen
- Versucht beim `button` "Farbe" eine zufällige Farbe mit jedem Klick zu vergeben (das geht nicht mit Klassen im CSS, nur mit `element.style.backgroundColor`)

---

## English

### Preparation

- Create an **index.html**, **style.css**, and **script.js** file
- Create the basic HTML structure
- Link the style and script files in the HTML
- The HTML should contain 2 boxes (`<div>`) (the 3rd box is a bonus and can be omitted initially)
- The first box contains 3 buttons (`<button>`) with the following labels: **Color**, **Rotate**, **Hide**
- The second box contains an `<input>` field and a button (**Load Text**) (*don't use a form element here, just an input*)
- The third box is a bonus (see below): A box with a button (**Create**) and an empty `div` (not visible since it has no content)

***Here's a possible layout, but it doesn't matter if you match the design exactly - your buttons can also be arranged side by side:***

![Page Preview](mockup.png)

### Task
- Each `button` should get functionality:
  - `Color` → the first box should be colored
  - `Rotate` → the first box should rotate 360 degrees (use `transition` to see the effect)
  - `Hide` → clicking should make the box disappear
  - `Load Text` → the text from the input field should be displayed below

**Bonus** *(we didn't cover this in the presentation, try to google it or ask me :-)*
- `Create` → with each click, 5 new small boxes should be created in the box
- Try to assign a random color to the "Color" button with each click (this doesn't work with CSS classes, only with `element.style.backgroundColor`)
