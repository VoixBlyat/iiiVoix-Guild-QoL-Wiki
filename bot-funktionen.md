# Unser QoL-Bot: Was du damit machen kannst

Willkommen 👋 Hier steht, welche Funktionen du als Member direkt benutzen kannst. Admin-Einstellungen und Admin-Befehle lassen wir hier bewusst weg.

## Raids finden und planen

### Kommende Raids ansehen

Mit `/raid list` bekommst du eine private Übersicht der kommenden Raids. Dort findest du Titel, Termin, freie Plätze und den Kanal, in dem der Raid-Post steht.

[Raids finden – Schritt für Schritt](./raids/finden.md)

### Selbst einen Raid starten

Mit `/raid create` öffnet sich ein Formular. Du wählst den Raid-Titel, den Termin, die Gruppengröße und kannst eine kurze Nachricht für die Gruppe dazuschreiben. Der Bot erstellt den Raid-Post und trägt dich direkt als erste Person ein.

Bei Rosso/Berthe CM kannst du zum Beispiel **8 Plätze** auswählen. Dann bist du selbst schon auf Platz 1 und sieben weitere Leute können mitmachen.

[So erstellst du einen Raid](./raids/erstellen.md)

### „Now“ richtig benutzen

- Soll es sofort losgehen? Schreib bei **Date or Now** `Now` und lass **Start time** leer.
- Soll es heute später losgehen? Schreib `Now` und bei **Start time** zum Beispiel `20:30`.
- Für einen anderen Tag gib ein Datum ein. Bei einem Datum ist eine Uhrzeit nötig.

Du kannst auch ein Zeitfenster wie `20:30-21:00` eintragen. Das bedeutet: Start um 20:30 Uhr, geplantes Ende um 21:00 Uhr.

[Mehr Beispiele für Datum und Uhrzeit](./raids/zeiten.md)

## An einem Raid teilnehmen

Im Raid-Post siehst du, wann es losgeht, wie viele Plätze belegt sind und wer schon mitkommt.

- **Join raid:** Melde dich an. Danach wählst du dein Charakter-Emote.
- **Change character:** Ändere dein Emote, ohne dich abzumelden.
- **Leave raid:** Melde dich ab. Dein Platz wird wieder frei.
- **Options:** Öffnet ein privates Menü mit Feedback. Als Ersteller findest du dort außerdem die Funktionen für deinen eigenen Raid.

[Den Raid-Post und seine Buttons verstehen](./raids/raid-post.md) · [An- und abmelden](./raids/anmelden.md) · [Emote ändern](./raids/emote-aendern.md)

## Deinen eigenen Raid verwalten

Wenn du einen Raid erstellt hast, kannst du ihn über **Options** bearbeiten. Dort kannst du zum Beispiel Termin, Gruppengröße oder Nachricht ändern, einen Platz reservieren, jemanden aus deinem Raid entfernen oder den Post löschen.

Wenn der Raid vorbei ist, kannst du einen 30-Minuten-Timer starten. Danach wird der Raid-Post automatisch entfernt. Der Timer startet nicht von allein.

## Feedback und Bug Reports

Du hast eine Idee oder etwas funktioniert nicht? Öffne im Raid-Post **Options** und wähl **Send feedback**. Schreib kurz dazu, was passiert ist und was du erwartet hast.

Ein Screenshot ist freiwillig, hilft bei Fehlern aber oft weiter. Wenn du Feedback abschickst, bekomme ich deine Nachricht privat per DM. Damit ich nicht zugespammt werde, gibt es einen Cooldown von fünf Minuten pro Person.

[Feedback mit oder ohne Screenshot senden](./raids/raid-post.md#einen-fehler-mit-screenshot-melden)

## CoboDex-Neuigkeiten

Wenn neue CoboDex-Babel-Updates kommen, kann der Bot sie automatisch im dafür vorgesehenen Server-Kanal posten. Du musst dafür nichts einstellen.

## Server-Logs und Privatsphäre

Wenn Logging auf dem Server eingerichtet ist, kann der Bot je nach Auswahl zum Beispiel Voice-Kanalwechsel, Nachrichtenänderungen oder -löschungen, Mitglieder-, Kanal- und Rollenänderungen sowie Moderationsaktionen protokollieren. Bestimmte Rollen können von nutzerbezogenen Logs ausgeschlossen sein.

Bei einigen Verwaltungsaktionen kann der Bot zusätzlich in Discords Audit-Logs nachsehen, wer die Aktion ausgelöst hat. Das klappt nicht bei jedem Ereignis. Ereignisse, die passieren, während der Bot offline ist, werden nicht allgemein nachträglich eingetragen.

## Wenn etwas nicht klappt

Schau zuerst in die [häufigen Fragen](./faq.md). Wenn du dort keine Antwort findest, schick mir über **Send feedback** eine kurze Beschreibung. Bei einem Problem mit einem bestimmten Raid hilft auch der Link zum Raid-Post.

Hast du einen GitHub-Account? Dann kannst du Bugs, Fragen oder fehlende Anleitungen auch ganz easy als [Issue eintragen](https://github.com/VoixBlyat/iiiVoix-Guild-QoL-Wiki/issues/new) :D
