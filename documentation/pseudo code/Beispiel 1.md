# Beispiel aus dem Unterricht

### Der Arbeitsauftrag besteht aus der aufgabe ein programm mit pseudo code zu erstellen welches einen dazu auffordert seinen Namen und Alter einzugeben. Das Programm soll anschliesend den Benutzer mit seinen Namen begrüßen und das Alter in Tagen ausgeben.

> Man fängt damit an seinen Namen hinzuschreiben und die benötigten Klassen zu importieren

> Danach deklariert und Initialisiert man die benötigten Variablen **mit ihren "Pseudocode namen" in Klammern**

> Als nächstes führt man die benötigten aktionen aus um den Arbeitsauftrag zu erfüllen. Dabei ist wichtig das bei einer Eingabe oder Ausgabe jeweils **Eingabe** oder **Ausgabe** auch verwendet wird.

> Wenn das Programm fertig ist deaktiviert man am besten den Scanner **wenn man einen benutzt hat**, und dann beendet man die Anwendung *(optimals mit einer kleinen Naricht als auf wiedersehen)*

```
// Nachname, Vorname
// Import benötiger Klassen (import java.util.*)
// Benötigte variablen deklarieren und initialisieren

alter(GZ) = 0
name(Text) = ""

// Scanner Objekt erzeugen (new)
// Ausgabe auf der Konsole und Eingabe des Namens und Alters

Ausgabe: "Bitte geben sie ihren Namen ein:"
Eingabe:name

Ausgabe: "Bitte geben sie ihr Alter ein:"
Eingabe:alter

// Verarbeitung
alter = alter * 365

// Ausgabe

Ausgabe: "Ihr name lautet: " + name
Ausgabe: "Ihr Alter in Tagen ist: " + alter + " Tage"

// Scanner deaktivieren
// Anwendung beenden

Ausgabe: "Programm wird beendet. Auf Wiedersehen." 
```


