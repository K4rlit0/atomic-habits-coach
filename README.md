# Atomic Habits Coach

Ein KI-Skill, der die Methode aus James Clears *Atomic Habits* anwendet. Du sagst, welche Gewohnheit oder Routine du aufbauen oder loswerden willst. Er stellt ein paar Fragen zu deinem echten Tag und baut daraus einen konkreten, getakteten Plan — mit einer 2-Minuten-Startversion für die Tage, an denen nichts läuft.

Er kann vier Dinge:

- **Einzelne Gewohnheit** auf- oder abbauen — Plan nach den vier Gesetzen.
- **Routine** takten — rückwärts gerechnet von einem festen Anker (wann du aus dem Haus musst, wann du einschlafen willst).
- **Ganzes System** über Tag und Woche — Schicht für Schicht eingeführt statt alles auf einmal.
- **Reparieren**, wenn es nicht gehalten hat — er findet, welches der vier Gesetze gebrochen ist, und ändert genau das.

Weißt du noch nicht, wo du anfangen sollst, geht er vorher mit dir deinen Tag durch.

---

## Installation

### Weg 1 — Ohne Installation, funktioniert überall

1. [`atomic-habits-coach/SKILL.md`](atomic-habits-coach/SKILL.md) öffnen.
2. Den **kompletten** Text kopieren, auch die Zeilen zwischen den `---` ganz oben.
3. In Claude einfügen und darunter schreiben, welche Gewohnheit oder Routine du bauen willst.

Kein Setup, funktioniert auch am Handy. Gilt nur für den einen Chat.

### Weg 2 — Als Skill in Claude (Browser und App)

1. [`atomic-habits-coach.zip`](atomic-habits-coach.zip) herunterladen (auf die Datei klicken, dann rechts auf **Download**). Nicht entpacken.
2. In Claude: **Einstellungen → Skills** (englische Oberfläche: *Customize → Skills*), dort das ZIP hochladen.
3. Den Skill einschalten.

Ab jetzt startet er von selbst, sobald du über Gewohnheiten oder Routinen sprichst.

### Weg 3 — Claude Code

```bash
git clone https://github.com/K4rlit0/atomic-habits-coach.git
mkdir -p ~/.claude/skills
cp -r atomic-habits-coach/atomic-habits-coach ~/.claude/skills/
```

### Weg 4 — Cowork / Claude Desktop

Die Datei `atomic-habits-coach.skill` herunterladen und in Cowork installieren.

---

## So holst du am meisten raus

- **Sei ehrlich über deinen echten Tag.** Der Plan ist nur so gut wie die Anker, die er kennt. Ein Anker, den es in deinem Alltag nicht wirklich gibt, trägt keine Gewohnheit.
- **Fang lächerlich klein an.** Die 2-Minuten-Version ist kein Gimmick, sondern der Grund, warum es überhaupt anspringt. Zwei Seiten lesen schlägt ein Kapitel, das du dir dreimal vornimmst.
- **Bei einem ganzen System: Schicht für Schicht.** Alles gleichzeitig zu starten ist der zuverlässigste Weg, in zwei Wochen wieder bei null zu sein.
- **Wenn es gerissen ist, komm zurück und sag es.** Er baut dann keinen neuen Plan, sondern repariert die eine Stelle, die nicht gehalten hat.

## Wofür er nicht gedacht ist

Der Skill deckt Alltagsgewohnheiten ab. Bei Themen wie eingeschränktem Essverhalten, Substanzentzug, Schlafverkürzung, Selbstverletzung oder Zwängen baut er bewusst keinen Plan, sondern verweist auf fachliche Begleitung. Das ist so gewollt: Ein Gewohnheitsplan ist dort das falsche Werkzeug.

Er ersetzt keine ärztliche, therapeutische oder psychologische Beratung.

---

## Lizenz und Herkunft

Der Skill steht unter der [MIT-Lizenz](LICENSE) — nutzen, ändern, weitergeben ist ausdrücklich erwünscht, Namensnennung genügt.

Er basiert auf den Prinzipien aus *Atomic Habits* von James Clear, in eigenen Worten angewandt, und enthält keine Auszüge aus dem Buch. Er ist kein Ersatz für die Lektüre, sondern ein Werkzeug, um die Ideen daraus umzusetzen. Keine Verbindung zu James Clear oder seinem Verlag.

*This skill applies principles from James Clear's "Atomic Habits" in the author's own words. It contains no excerpts from the book and is not affiliated with or endorsed by James Clear. It is not a substitute for medical, therapeutic, or psychological advice.*
