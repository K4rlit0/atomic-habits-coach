# Habits Coach

Ein KI-Skill, der Gewohnheiten und Routinen nach einer erprobten Methodik baut. Du sagst, welche Gewohnheit oder Routine du aufbauen oder loswerden willst. Er stellt ein paar Fragen zu deinem echten Tag und baut daraus einen konkreten, getakteten Plan — mit einer 2-Minuten-Startversion für die Tage, an denen nichts läuft.

Er kann vier Dinge:

- **Einzelne Gewohnheit** auf- oder abbauen — Plan nach den vier Gesetzen.
- **Routine** takten — rückwärts gerechnet von einem festen Anker (wann du aus dem Haus musst, wann du einschlafen willst). Läuft dein Tag nicht nach der Uhr — Schicht, kleine Kinder, wechselnde Termine — hängt er die Gewohnheiten stattdessen an Ereignisse.
- **Ganzes System** über Tag und Woche — Schicht für Schicht eingeführt statt alles auf einmal.
- **Reparieren**, wenn es nicht gehalten hat — er findet, welches der vier Gesetze gebrochen ist, und ändert genau das.

Weißt du noch nicht, wo du anfangen sollst, geht er vorher mit dir deinen Tag durch. Und wenn nicht Disziplin der Engpass ist, sondern Erinnern und Anfangen selbst, baut er den Plan anders: externe Auslöser, kürzere Ketten, keine Streak-Zählerei.

---

## So sieht das aus

> **Du:** Ich will abends nicht mehr eine Stunde am Handy hängen, bevor ich schlafe.

> **Coach:** Bevor ich plane, vier Fragen:
> 1. Was soll stattdessen passieren — oder erstmal nur weniger Handy?
> 2. Was passiert direkt davor, wenn du zum Handy greifst?
> 3. Wann willst du einschlafen?
> 4. Liegt das Handy nachts im Schlafzimmer?

*(Du antwortest in zwei Zeilen.)*

> **Coach:** 🚫 Ablegen: Handy im Bett
> **Identität:** Du bist jemand, der seinen Abend selbst beendet.
> **Schleife:** Auslöser *ins Bett legen* → Verlangen *runterkommen* → Scrollen → Belohnung *Ablenkung*
> **1. Unsichtbar** — Ladekabel ab heute in die Küche. Das ist der ganze Hebel.
> **2. Unattraktiv** — Bildschirmzeit-Report Sonntag anschauen, eine Minute.
> **3. Schwer** — Wecker kaufen, damit "ich brauch's als Wecker" wegfällt.
> **4. Unbefriedigend** — Strich im Kalender an jedem Abend ohne Handy im Bett.
> **Ersatz:** Buch auf dem Nachttisch, zwei Seiten reichen.
> **Wenn's hakt:** Handy ins Bad statt in die Küche.
> **Erster Schritt heute:** Ladekabel umstecken. Jetzt, nicht heute Abend.

Dazu bekommst du denselben Plan als Markdown zum Abspeichern.

---

## Installation

Skills gibt es in allen Claude-Plänen. Voraussetzung ist, dass **Code-Ausführung** in den Einstellungen aktiviert ist — ohne die taucht der Skill nicht auf.

### Weg 1 — Ohne Installation, funktioniert überall

1. [`habits-coach/SKILL.md`](habits-coach/SKILL.md) öffnen.
2. Den **kompletten** Text kopieren, auch die Zeilen zwischen den `---` ganz oben.
3. In Claude einfügen und darunter schreiben, welche Gewohnheit oder Routine du bauen willst.

Kein Setup, funktioniert auch am Handy. Gilt nur für den einen Chat.

### Weg 2 — Als Skill in Claude (Browser und App)

1. [`habits-coach.zip`](habits-coach.zip) herunterladen (auf die Datei klicken, dann rechts auf **Download**). Nicht entpacken.
2. In Claude: **Einstellungen → Skills** (englische Oberfläche: *Customize → Skills*), dort das ZIP hochladen.
3. Den Skill einschalten.

Ab jetzt startet er von selbst, sobald du über Gewohnheiten oder Routinen sprichst.

### Weg 3 — Claude Code

Die `habits-coach.zip` enthält den Skill bereits im richtigen Ordner, also reicht Entpacken am richtigen Ort:

```bash
mkdir -p ~/.claude/skills
unzip habits-coach.zip -d ~/.claude/skills/
```

Ergebnis: `~/.claude/skills/habits-coach/SKILL.md`. Für ein Projekt statt global dasselbe nach `.claude/skills/` im Projektordner.

### Weg 4 — Cowork / Claude Desktop

Die Datei [`habits-coach.skill`](habits-coach.skill) herunterladen und in Cowork installieren.

---

## So holst du am meisten raus

- **Sei ehrlich über deinen echten Tag.** Der Plan ist nur so gut wie die Anker, die er kennt. Ein Anker, den es in deinem Alltag nicht wirklich gibt, trägt keine Gewohnheit.
- **Fang lächerlich klein an.** Die 2-Minuten-Version ist kein Gimmick, sondern der Grund, warum es überhaupt anspringt. Zwei Seiten lesen schlägt ein Kapitel, das du dir dreimal vornimmst.
- **Bei einem ganzen System: Schicht für Schicht.** Alles gleichzeitig zu starten ist der zuverlässigste Weg, in zwei Wochen wieder bei null zu sein.
- **Wenn es gerissen ist, komm zurück und sag es.** Er baut dann keinen neuen Plan, sondern repariert die eine Stelle, die nicht gehalten hat.

## Wofür er nicht gedacht ist

Der Skill deckt Alltagsgewohnheiten ab — Sport, Lesen, Lernen, Handyzeit, Ordnung, Ernährung und Gewicht inklusive. Bei Substanzentzug, Schlafverkürzung, Selbstverletzung oder Zwängen baut er bewusst keinen Plan, sondern verweist auf fachliche Begleitung. Das ist so gewollt: Ein getakteter Gewohnheitsplan ist dort das falsche Werkzeug.

Er ersetzt keine ärztliche, therapeutische oder psychologische Beratung.

Für Terminplanung, Kalender, To-do-Listen, Projektplanung oder Morgen-Briefings ist er ebenfalls nicht gedacht — dafür gibt es bessere Werkzeuge.

## Deine Daten

Der Skill ist reiner Text ohne Code, ohne Netzwerkzugriff und ohne Tracking. Was du im Gespräch über deinen Tag erzählst, bleibt in deinem Claude-Konto und läuft weder über mich noch über Dritte. Wie Claude selbst mit Chatinhalten umgeht, steht in Anthropics Datenschutzerklärung.

---

## Version

**1.2** — umbenannt zu `habits-coach`, Ernährung und Gewicht als normale Alltagsziele freigegeben, Anpassungen für den Fall, dass Erinnern und Anfangen der Engpass sind (externe Cues, kürzere Ketten, keine Streaks), Tracker entschärft, sauberer Umgang mit Dateipfaden, funktioniert auch in Läufen ohne Gegenüber.

**1.1** — Sicherheitsgrenzen, Reparatur-Modus für gerissene Gewohnheiten, Bestandsaufnahme für "ich weiß nicht, wo ich anfangen soll", ereignisbasierte Anker für unregelmäßige Tage, funktioniert auch ohne Dateizugriff im Browser-Chat.

## Lizenz und Herkunft

Der Skill steht unter der [MIT-Lizenz](LICENSE) — nutzen, ändern, weitergeben ist ausdrücklich erwünscht, Namensnennung genügt.

### Quelle: das Buch

Die Methodik stammt aus **[*Atomic Habits* von James Clear](https://jamesclear.com/atomic-habits)** (Avery / Penguin Random House, 2018). Auf Deutsch erschienen als **[*Die 1%-Methode*](https://www.randomhouse.de/Paperback/Die-1Prozent-Methode-Minimale-Veraenderung-maximale-Wirkung/James-Clear/Goldmann/e552511.rhd)** bei Goldmann.

Wenn dir der Skill etwas bringt, kauf das Buch. Es steht deutlich mehr drin, als ein Werkzeug wie dieses abbilden kann.

### Disclaimer

Dieser Skill ist ein **unabhängiges, inoffizielles** Werkzeug. Er ist **nicht mit James Clear, James Clear Holdings LLC oder Penguin Random House verbunden**, wird von diesen weder unterstützt noch geprüft, und es besteht keine Lizenzbeziehung. Der Buchtitel wird ausschließlich genannt, um auf die zugrunde liegende Quelle zu verweisen — nicht als Produktname.

Der Skill gibt die Prinzipien in eigenen Worten wieder und **enthält keine Auszüge, Zitate oder Zusammenfassungen von Buchtext**. Er ist **kein Ersatz für das Buch**, sondern ein Werkzeug, um dessen Ideen im Alltag umzusetzen — und ebenso kein Ersatz für ärztliche, therapeutische oder psychologische Beratung.

*This is an independent, unofficial tool. It is not affiliated with, endorsed by, or licensed by James Clear, James Clear Holdings LLC, or Penguin Random House. The book title is cited only to credit the underlying source, not as a product name. The skill applies the principles in the author's own words, contains no excerpts or quotations from the book, and is not a substitute for reading it — nor for medical, therapeutic, or psychological advice. Please [buy the book](https://jamesclear.com/atomic-habits).*
