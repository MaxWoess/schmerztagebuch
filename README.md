# Schmerztagebuch

Web-App fürs iPhone (läuft auch auf jedem anderen Gerät): Schmerz täglich pro Körperstelle (0–10) eintragen,
mit Notizen und Schnell-Markierungen, und über Tage, Wochen und Monate auswerten.

- **Kalender:** Monatsansicht, jeder Tag eingefärbt nach dem stärksten Schmerz. Tippen öffnet den Tag.
- **Eintrag:**
  - **Befinden:** Tagesverfassung, psychischer Zustand und Ruhe/Unruhe (0–10).
  - **Schmerz & Beschwerden (0–10):** Kopfschmerzen, Migräne, Gesicht/Kiefer, Nacken, trockene Augen, trockener Mund,
    Schulter und Hand/Finger (L/R), oberer und unterer Rücken, Magen- und Bauchschmerzen, Gesäß, Blähungen,
    Hüfte, Oberschenkel, Knie, Unterschenkel/Wade und Fuß (L/R).
  - **Stuhlgang:** Anzahl und Konsistenz nach Bristol-Skala (Typ 1–7).
  - **Haut & Nägel:** Ausprägung 0–10 und ein Feld, wo/was.
  - **Schlaf:** Qualität per Symbol-Regler, Dauer in Stunden. **Wetter:** Symbol-Regler.
  - **Ernährung:** Frühstück, Mittag, Abend. **Notizen** und **Medikamente** als Textfelder, dazu Markierungen.
  - „Wie letzter Eintrag“ übernimmt die Schmerzwerte des vorigen Tages, „Schmerzfrei“ trägt einen Tag ohne Schmerz ein.
- **Auswertung:** Zeitraum (7 Tage bis alles), Gruppierung nach Tagen/Wochen/Monaten, Ø oder Maximum,
  Schmerzverlauf je Bereich (Kopf, Schultern & Hände, Rumpf & Verdauung, Hüfte & Beine; Linien per Legende ein-/ausblendbar,
  optional mit einer Vergleichsreihe), Befinden-Verlauf, Schlaf (Dauer und Qualität), Ranking der Körperstellen,
  Vergleich mit dem vorherigen Zeitraum und Schmerz an Tagen mit/ohne Markierung. Beschwerden wie trockene Augen oder
  Blähungen zählen nicht in den Schmerz-Durchschnitt.
- **Sicherung:** Export als `.json` (zum Wiederherstellen) und `.csv` (Excel/Numbers), Import mit Zusammenführen
  oder Ersetzen.

Die Daten liegen nur auf dem Gerät (Browser-Speicher) und werden bei jedem Start automatisch geladen.
Nichts wird an einen Server geschickt.


## Sicherung

Trotz lokaler Speicherung regelmäßig unter **Sicherung → Sicherung speichern** eine `.json`-Datei ablegen
(z. B. in iCloud Drive). Die App erinnert daran, wenn die letzte Sicherung älter als 14 Tage ist.
Beim Gerätewechsel die Datei unter **Sicherung laden** wieder einspielen.

## Coded By Claude
