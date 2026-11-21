<p align="center"><img src="social-preview.png" alt="Aether Hive – Drei Systeme für verlässliche Entscheidungen. Eine Methode." width="100%"></p>

# Aether Hive

**Drei Systeme für verlässliche Entscheidungen, eine Methode.** VERAX MERIDIAN prüft jeden Launch, bevor Geld fließt. ANTERA sichert Entscheidungen im Tagesgeschäft ab, von der Kampagne bis zum Deal. PARALLAX prüft, ob das Geschäftsmodell die nächste Marktverschiebung übersteht.

> **Status:** VERAX MERIDIAN ist ein installierbares Open-Source-Werkzeug (Apache-2.0, [Repository](https://github.com/darealone/VERAX)). ANTERA und PARALLAX sind Konzepte in Entwicklung; ihre Demos zeigen den geplanten Ablauf mit fiktiven bzw. synthetischen Daten, ohne Anbindung an echte Systeme.

**Live:** https://darealone.github.io/aether-hive/

---

## In short (English)

Three systems for reliable decisions from the studio Aether Hive. **VERAX MERIDIAN** is an installable, open-source launch readiness gate: deterministic checks, named approvals and an audit trail decide GO, BLOCKED or NEEDS REVIEW before a launch. **ANTERA** protects marketing and sales decisions before launch, after each campaign run and inside live enterprise deals. **PARALLAX** detects structural business-model risks before they show up in the numbers. In both, the agent observes, investigates and prepares; deciding, starting and sending stay with humans. ANTERA and PARALLAX are concepts in development with demo data. The pages are in German.

## Die Systeme

| | Worum es geht | Ansehen | Details |
|---|---|---|---|
| **VERAX MERIDIAN** | Open-Source-Werkzeug, das vor jedem Launch die Kette vom Klick bis zum CRM prüft und nur mit namentlicher Freigabe GO gibt. Selbst gehostet. | [Produktseite](https://darealone.github.io/aether-hive/verax/) | [Repository](https://github.com/darealone/VERAX) |
| **ANTERA** | Agentisches System, das Entscheidungen in Marketing und Vertrieb absichert: Verhindern, Verstehen, Tragbar machen. „Darf stoppen. Nie starten.“ | [Konzeptseite](https://darealone.github.io/aether-hive/antera/) | [README](antera/README.md) |
| **PARALLAX** | Konzept und Offline-Prototyp, der strukturelle Risiken im Geschäftsmodell erkennt: Wirkpfade, Frühindikatoren, Widerlegungsbedingungen, Experimente. | [Prototyp](https://darealone.github.io/aether-hive/parallax/) | [README](parallax/README.md) |

## Die gemeinsame Methode

1. **Beobachten.** Was wurde tatsächlich gemessen?
2. **Ableiten.** Was folgt daraus, und wie sicher ist das?
3. **Widerlegen.** Was würde die Annahme kippen? Gegenbelege stehen gleichberechtigt daneben.
4. **Handeln.** Jede Erkenntnis mündet in eine Entscheidung oder ein Experiment mit Verantwortung.
5. **Lernen.** Ergebnisse kalibrieren die Regeln, durch Menschen.

Der Agent liest, untersucht und entwirft. Entscheiden, starten und senden bleibt beim Menschen.

## Struktur

```
index.html          Übersichtsseite
verax/              VERAX MERIDIAN: Produktseite (Simulation), Code im eigenen Repository
antera/             ANTERA: Konzeptseite, README, Vorschaubild
parallax/           PARALLAX: Prototyp, README, Vorschaubild
social-preview.png  Vorschaubild für geteilte Links (1280 × 640)
```

Jede Seite ist eine einzelne HTML-Datei ohne Abhängigkeiten und ohne Build. **Lokal ansehen:** `index.html` im Browser öffnen. Es werden keine externen Skripte geladen, nichts getrackt und nichts an Server gesendet. PARALLAX speichert Eingaben nur im eigenen Browser (localStorage).

---

Ein Projekt von **Aether Hive**, *Intelligence, by Design.*
