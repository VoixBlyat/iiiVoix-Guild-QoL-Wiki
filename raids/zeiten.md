# Datum und Uhrzeit eingeben

Beim Raid-Formular gibt es zwei Felder:

- **Date or Now:** Wann soll der Raid stattfinden?
- **Start time:** Um wie viel Uhr geht es los?

## Der Raid startet jetzt

- **Date or Now:** `Now`
- **Start time:** leer lassen

Dann zeigt der Bot den Raid als sofort gestartet an.

## Der Raid startet heute später

Beispiel: Es ist gerade Nachmittag und der Raid soll heute um 20:30 Uhr losgehen.

- **Date or Now:** `Now`
- **Start time:** `20:30`

Die Uhrzeit muss noch in der Zukunft liegen. Eine Uhrzeit, die heute schon vorbei ist, wird abgelehnt.

## Der Raid ist an einem anderen Tag

Schreib das Datum als `TT.MM` oder `TT.MM.JJJJ`. Der Punkt gehört dazu.

Beispiele:

- **Date or Now:** `25.12.2026`
- **Start time:** `20:30`

Das heißt: 25. Dezember 2026 um 20:30 Uhr.

Du kannst das Jahr weglassen:

- **Date or Now:** `25.12`
- **Start time:** `20:30`

Dann nimmt der Bot das nächste passende Datum. Bei einem Datum muss immer eine Startzeit eingetragen sein.

## Einen Zeitraum angeben

Wenn der Start nicht auf eine feste Minute festgelegt ist, kannst du ein Zeitfenster schreiben:

- **Start time:** `20:30-21:00`

Das bedeutet: Start zwischen 20:30 und 21:00 Uhr. Die Endzeit muss später sein als die Startzeit und am selben Tag liegen. Zum Beispiel ist `21:00-20:30` ungültig.

## Häufige Fehler

- `25/12` funktioniert nicht – nutz Punkte: `25.12`.
- Ein Datum ohne Startzeit funktioniert nicht.
- Vergangene Termine funktionieren nicht.
- Schreib die Uhrzeit im 24-Stunden-Format, zum Beispiel `20:30` statt `8:30 PM`.

Die Uhrzeit im fertigen Raid-Post richtet sich nach der Zeitzone, die für den Bot eingestellt ist. Wenn du unsicher bist, frag kurz im Server nach.
