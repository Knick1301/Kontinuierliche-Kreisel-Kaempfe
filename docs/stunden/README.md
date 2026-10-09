# Stundenaufzeichnung

Jede Person trägt ihre Arbeitszeit in [`stunden.csv`](stunden.csv) ein – am besten direkt nach der Arbeit, nicht erst am Ende der Woche.

## Spalten

| Spalte | Bedeutung | Beispiel |
|--------|-----------|----------|
| `datum` | Tag der Arbeit (JJJJ-MM-TT) | `2026-10-09` |
| `person` | GitHub-Name | `Knick1301` |
| `issue` | Zugehöriges Issue (leer, falls keins) | `#12` |
| `phase` | Konzeption, Entwurf, Konstruktion, Überprüfung, Übergang | `Konzeption` |
| `disziplin` | siehe Liste unten | `Projektmanagement` |
| `stunden` | Dezimalzahl mit Punkt | `1.5` |
| `beschreibung` | Was wurde gemacht? | `Sprint Planning` |

## Disziplinen (aus Folie 13)

- Anforderungen
- Analyse & Entwurf
- Implementierung
- Test
- Auslieferung
- Konfigurations- & Änderungsmanagement
- Projektmanagement
- Infrastruktur

**Faustregeln:** Scrum-Meetings, Blogbeiträge und Planung → *Projektmanagement*. Repo, Board und CI/CD einrichten → *Infrastruktur*. User Stories und SRS schreiben → *Anforderungen*. UML und Architektur → *Analyse & Entwurf*.

Aus dieser Datei lässt sich die Phasen×Disziplinen-Tabelle für den Dozenten per Pivot-Tabelle (Excel/LibreOffice) zusammenzählen.
