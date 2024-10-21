# Beispiel 2 (Auch aus dem Unterricht, aber leicht erweitert)

### Der Arbeitsauftrag besteht aus der aufgabe ein programm mit pseudo code zu erstellen dass das Alter einer Person abfrägt und je nach Alter ausgibt ob man den Führerschein machen darf oder nicht.

> So wie immer schreibt man zuerst seinen Namen hin und importiert dann die benötigten Klassen

> Danach deklariert und initialisert man die benötigten variablen mit ihren jeweiligen "Pseudocode namen"

> Dann führt man die benötigten Aktionen aus, in diesem fall die Abfrage des Alters, die überprüfung und ausgabe je nach Eingabe

> Zuletzt deaktiviert man den Scanner und beendet das Programm

```
// Nachname, Vorname
// Import benötiger klassen (import java.util.Scanner)
// Benötigte Variablen deklarieren und initialisieren

alter(GZ) = 0

// Scanner objekt erzeugen (new Scanner(System.in))
// Aufforderung zur eingabe des Alters

Ausgabe: "Bitte geben sie ihr Alter ein: "
Eingabe: alter

// Verarbeitung und ausgabe je nach Alter

WENN alter >= 16
  Ausgabe: "Gluekwunsch! Sie duerfen den Fuehrerschein A1 machen!"
SONST
  Ausgabe: "Schade! Sie duerfen noch keinen Fuehrerschein machen."
ENDE WENN

// Scanner deaktivieren
// Programm beenden

Ausgabe: "Das Programm wird nun beendet. Auf Wiedersehen!"
```
