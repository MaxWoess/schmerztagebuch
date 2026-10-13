# Schmerztagebuch

Web-App fürs iPhone (läuft auch auf jedem anderen Gerät): Schmerz täglich pro Körperstelle (0–10) eintragen,
mit Notizen und Schnell-Markierungen, und über Tage, Wochen und Monate auswerten.

- **Kalender:** Monatsansicht, jeder Tag eingefärbt nach dem stärksten Schmerz. Tippen öffnet den Tag.
- **Eintrag:** 31 Körperstellen von Kopf bis Fuß (Arme und Beine links/rechts getrennt), Schieberegler 0–10,
  Markierungen (Schmerzmittel, Sport, Stress, … – eigene hinzufügbar) und ein freies Notizfeld.
  „Wie letzter Eintrag“ übernimmt die Werte des vorigen Tages, „Schmerzfrei“ trägt einen Tag ohne Schmerz ein.
- **Auswertung:** Zeitraum (7 Tage bis alles), Gruppierung nach Tagen/Wochen/Monaten, Ø oder Maximum,
  Verlaufsdiagramm (optional mit einer einzelnen Körperstelle zum Vergleich), Ranking der Körperstellen,
  Vergleich mit dem vorherigen gleich langen Zeitraum, Schmerz an Tagen mit/ohne Markierung, Wochentage.
- **Sicherung:** Export als `.json` (zum Wiederherstellen) und `.csv` (Excel/Numbers), Import mit Zusammenführen
  oder Ersetzen.

Die Daten liegen nur auf dem Gerät (Browser-Speicher) und werden bei jedem Start automatisch geladen.
Nichts wird an einen Server geschickt.


## Sicherung

Trotz lokaler Speicherung regelmäßig unter **Sicherung → Sicherung speichern** eine `.json`-Datei ablegen
(z. B. in iCloud Drive). Die App erinnert daran, wenn die letzte Sicherung älter als 14 Tage ist.
Beim Gerätewechsel die Datei unter **Sicherung laden** wieder einspielen.

## Coded By Claude
