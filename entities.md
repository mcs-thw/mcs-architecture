# Entities

Zuordnungen erfolgen transitiv. D. h. eine Person wird z. B. einer Gruppe zugeordnet, die Gruppe wird dem Bereitstellungsraum zugeordnet, damit ist die Person automatisch im BR mit erfasst.

### Person
* Ist eine einzelne Person
* Kann zugeordnet sein zu
	* Führungsstruktur (nur eine Auswahl möglich)
		* Bereitstellungsraum
		* Einsatzabschnitt
		* Einsatzstelle
		* Trupp
		* Gruppe
		* (Zug)
	* Informativ (zusätzliche Zuordnung möglich, auch mehrere)
		* Fahrzeug
* Eigenschaften
	* Name
	* Vorname
	* Ortsverband
	* berufene Funktion
		* Helfer
		* Truppführer
		* Gruppenführer
		* Zugführer
		* Sachgebietsleiter
	* Zusatzfunktion im laufenden Einsatz
		* Fachberater
		* Leiter FüSt
		* ...
	* Fähigkeiten/Qualifikationen
		* Kraftfahrer B/BE/C/CE
		* Maschnist
		* ...

### Trupp
* Menge von Personen
* Kann zugeordnet sein zu
	* Bereitstellungsraum
	* Einsatzabschnitt
	* Einsatzstelle
	* Gruppe
	* Zug
* Eigenschaften
	* Name
	* Ortsverband

### Gruppe
* Menge von Personen + Trupps
* Kann zugeordnet sein zu
	* Bereitstellungsraum
	* Einsatzabschnitt
	* Einsatzstelle
	* Zug
* Eigenschaften
	* Name
	* Ortsverband

### Zug
* Menge von Trupps + Gruppen (+ Personen)
* Kann zugeordnet sein zu
	* Bereitstellungsraum
	* Einsatzabschnitt
	* Einsatzstelle
* Eigenschaften
	* Name
	* Ortsverband

### Fahrzeug
* Ist ein Kraftfahrzeug, ein Anhänger, ein Boot
* Kann zugeordnet sein zu
	* Bereitstellungsraum
	* Einsatzabschnitt
	* Einsatzstelle
	* Trupp
	* Gruppe
	* (Zug)

### Bereitstellungsraum
* Menge von Personen + Trupps + Gruppen + Züge + Fahrzeuge
* Eigenschaften
	* Name
	* Ort/Adresse
	* Leiter BR (Auswahl aus zugeordneten Personen)

### Einsatzabschnitt
* Menge von Personen + Trupps + Gruppen + Züge + Fahrzeuge
* Eigenschaften
	* Name
	* Ort/Adresse
	* Leiter Einsatzabschnitt (Auswahl aus zugeordneten Personen)

### Untereinsatzabschnitt
* Menge von Personen + Trupps + Gruppen + Züge + Fahrzeuge
* Kann zugeordnet sein zu
	* Einsatzabschnitt
* Eigenschaften
	* Name
	* Ort/Adresse
	* Leiter Untereinsatzabschnitt (Auswahl aus zugeordneten Personen)

### Einsatzstelle
* Menge von Personen + Trupps + Gruppen + Züge + Fahrzeuge
* Kann zugeordnet sein zu
	* Einsatzabschnitt
	* Untereinsatzabschnitt
* Eigenschaften
	* Name
	* Ort/Adresse
