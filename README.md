# Sakai-Aufgabe-2
## Uscase 1.03 Alarm bei zu hoher Herzfrequenz
###
Name und Identifikationsnummer: Uc 1.03 Alarm bei zu hoher Herzfrequenz

Beschreibung: Bei zu hoher Herzfrequenz wird automatisch vom System ein Alarm ausgelöst

Status: In Arbeit

Verwendete Anwendungsfälle: UC 1.07 (Abbruch des Leistungstests),UC 1.01 (Probandin anlegen),UC 1.02 (Leistungstest anlegen)

Invarianten: Aufzeichnung der bis zum Abbruch erhobenen Daten. 

Nachbedingung/Ergebnis: 	Ergometer wird in Ruhemodus versetzt (UC 2.01) oder Abruch des Leistungstests

Standardablauf: Alle Leistungsstufen werden nacheinander durchlaufen.Überprüfung, ob Leistungswerte eingehalten.Alarm wenn nötig. Daten werden gespeichert.

Alternative Ablaufschritte: Vorzeitiger Abbruch wenn nörtig

Hinweise: Hardware- Auswahl für EKG-Daten ist aktuell noch zu klären

Änderungsgeschichte: 0.01; 16.03.2024.; Matti Fletschinger 


