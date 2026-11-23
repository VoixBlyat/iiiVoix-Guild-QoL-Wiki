# Datum und Uhrzeit eingeben

Beim Raid-Formular gibt es zwei Felder:

- **Date or Now** heißt: Datum oder „jetzt“.
- **Start time** heißt: Uhrzeit, zu der es losgeht.

## Der Raid startet jetzt

Wenn der Raid sofort losgehen soll:

- **Date or Now:** `Now`
- **Start time:** leer lassen

Der Bot zeigt den Raid dann als sofort gestartet an.

## Der Raid startet heute später

Beispiel: Es ist gerade Nachmittag und ihr wollt heute um 20:30 Uhr starten.

- **Date or Now:** `Now`
- **Start time:** `20:30`

Die Uhrzeit muss noch in der Zukunft liegen. Eine Uhrzeit, die heute schon vorbei ist, wird abgelehnt.

## Der Raid ist an einem anderen Tag

Schreib das Datum als `TT.MM` oder `TT.MM.JJJJ`. Der Punkt gehört dazu.

Beispiel für den 25. Dezember 2026 um 20:30 Uhr:

- **Date or Now:** `25.12.2026`
- **Start time:** `20:30`

Du kannst das Jahr weglassen. Bei `25.12` nimmt der Bot das nächste passende Datum. Bei einem Datum musst du immer eine Uhrzeit angeben.

## Start- und Endzeit eintragen

Du kannst auch beide Uhrzeiten angeben, zum Beispiel:

- **Start time:** `20:30-21:00`

Das heißt: Der Raid ist von 20:30 bis 21:00 Uhr geplant. Die erste Zeit ist der Start, die zweite das Ende. Es bedeutet **nicht**, dass der Raid irgendwann zwischen 20:30 und 21:00 beginnt.

Die Endzeit muss nach der Startzeit liegen und am selben Tag sein. `21:00-20:30` ist deshalb ungültig.

## Häufige Fehler

- `25/12` funktioniert nicht – nutz Punkte: `25.12`.
- Ein Datum ohne Uhrzeit funktioniert nicht.
- Vergangene Termine funktionieren nicht.
- Nutze das 24-Stunden-Format: `20:30` statt `8:30 PM`.

Die Uhrzeit im fertigen Raid-Post richtet sich nach der Zeitzone, die für den Bot eingestellt ist. Wenn du unsicher bist, frag kurz im Server nach.
