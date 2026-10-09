# So arbeiten wir

## Scrum im Überblick

- **Sprintlänge:** 2 Wochen _(mit dem Team bestätigen)_
- **Sprint Planning:** Stories aus dem Product Backlog ins Sprint Backlog ziehen und per Planning Poker schätzen
- **Daily Scrum:** 2–3× pro Woche, kurz in den Discussions oder im Chat: Was habe ich gemacht? Was mache ich als Nächstes? Was blockiert mich?
- **Sprint Review:** Ergebnis zeigen, PO nimmt Stories ab
- **Retrospektive:** Was lief gut, was verbessern wir? Ergebnis als Discussion festhalten

## Definition of Done

Eine User Story ist **fertig**, wenn:

1. alle Akzeptanzkriterien umgesetzt sind,
2. der Code dem Coding-Style entspricht und der Linter fehlerfrei durchläuft,
3. Unit-Tests vorhanden sind und die CI-Pipeline grün ist,
4. die MVC-Struktur und unsere Architekturentscheidungen eingehalten wurden,
5. die Funktion im Browser getestet wurde (mind. Chrome und Firefox),
6. mindestens ein anderes Teammitglied den Code reviewt hat,
7. die Dokumentation in `docs/` aktuell ist,
8. der Product Owner die Story abgenommen hat.

## Branches

- `main` ist immer lauffähig, niemand pusht direkt darauf
- Für jedes Issue ein eigener Branch: `feature/12-kreisel-zusammenstellen`, `bug/31-absturz-in-arena`, `docs/5-srs`
- Änderungen kommen nur per Pull Request mit Review nach `main`

## Commits

Kurze, aussagekräftige Nachrichten mit Issue-Nummer, z. B.:

```
#12 Auswahl der Kreiselteile im Editor hinzugefügt
```

## Issues

- Neue Funktionen als **User Story** anlegen (Template „User Story“)
- Größere Stories (≥ 13 Punkte) in kleinere aufteilen
- Technische Teilaufgaben als **Aufgabe** anlegen und mit der Story verknüpfen

## Stunden

Arbeitszeit bitte laufend in [`docs/stunden/stunden.csv`](docs/stunden/stunden.csv) eintragen – der Dozent gewichtet die Teamnote nach Eigenbeitrag.
