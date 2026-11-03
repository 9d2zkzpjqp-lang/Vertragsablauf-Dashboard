# Vertragsdashboard v1.10 – erster Standardtext

## Standardtext „Protokoll versenden“

In Schritt 5 gibt es nun den aufklappbaren Bereich:

`Standardtext für Protokollversand`

Die globale Standardvorlage lautet:

**Betreff**
`Kooperations- und Planungsgespräch {{Jahr}}: Protokoll`

**Text**
`{{Anrede_Empfänger}},`

`anbei finden Sie das Protokoll unseres Kooperations- und Planungsgesprächs vom {{Gesprächsdatum}}.`

`Viele Grüße`

`Jan-Christof Kölb`

## Empfänger

Beim Erzeugen des Textes werden die Empfänger jeweils neu ausgewählt.

- Mehrfachauswahl ist möglich.
- Zur Auswahl stehen die externen Arbeitskontakte des aktuellen Kooperationspartners.
- Bereits als externe Beteiligte des Kooperationsgesprächs ausgewählte registrierte Kontakte werden bevorzugt vorausgewählt.
- Andernfalls wird der Standardkontakt vorausgewählt.
- Bei nur einem vorhandenen Kontakt wird dieser vorausgewählt.

Die gemeinsame Anrede wird aus den hinterlegten `Briefanrede`-Feldern erzeugt.

Beispiele:

`Liebe Frau Schlaak,`

`Liebe Frau Schlaak, liebe Frau Vogel,`

Wenn für einen ausgewählten Kontakt keine Briefanrede gepflegt ist, erscheint im erzeugten Text sichtbar ein Platzhalter wie:

`{{Briefanrede fehlt: Claudia Schlaak}}`

Es wird keine Anrede aufgrund des Namens geraten.

## Platzhalter

Unterstützt werden zunächst:

- `{{Jahr}}`
- `{{Anrede_Empfänger}}`
- `{{Gesprächsdatum}}`

## Kopieren

Es gibt getrennte Schaltflächen für:

- E-Mail-Adressen kopieren
- Betreff kopieren
- Text kopieren

Der erzeugte Betreff und Text können vor dem Kopieren manuell angepasst werden.

Das Kopieren markiert `Protokoll versendet` **nicht** automatisch als erledigt.

## Vorlage bearbeiten

Die Vorlage kann direkt im selben Bereich bearbeitet und gespeichert werden.

Die Änderung gilt global für alle Kooperationspartner und wird im browserlokalen Arbeitsstand sowie in JSON-Checkpoints mitgeführt.

`Standard wiederherstellen` setzt nur diese Vorlage auf den oben genannten Ausgangstext zurück.
