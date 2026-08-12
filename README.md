# Habits Coach

Ein KI-Skill, der Gewohnheiten und Routinen nach einer erprobten Methodik baut. Du sagst, was du aufbauen oder loswerden willst. Er stellt ein paar Fragen zu deinem echten Tag — meist zum Anklicken statt zum Tippen — und baut daraus einen konkreten, getakteten Plan. Mit einer 2-Minuten-Startversion für die Tage, an denen nichts läuft.

---

## Installation

Skills gibt es in allen Claude-Plänen. Voraussetzung ist, dass **Code-Ausführung** in den Einstellungen aktiviert ist — ohne die taucht der Skill nicht auf.

### Weg 1 — Als Skill in Claude (Browser und App)

**Empfohlen.** Einmal einrichten, danach ist er immer da.

1. [`habits-coach.zip`](habits-coach.zip) herunterladen: auf die Datei klicken, dann rechts auf **Download**. **Nicht entpacken.**
2. In Claude: **Einstellungen → Skills** (englische Oberfläche: *Customize → Skills*), dort das ZIP hochladen.
3. Den Skill einschalten.

Ab jetzt startet er von selbst, sobald du über Gewohnheiten oder Routinen sprichst.

### Weg 2 — Ohne Installation, funktioniert überall

Für einmal ausprobieren, oder wenn du am Handy bist.

1. [`habits-coach/SKILL.md`](habits-coach/SKILL.md) öffnen.
2. Den **kompletten** Text kopieren, auch die Zeilen zwischen den `---` ganz oben.
3. In Claude einfügen und darunter schreiben, welche Gewohnheit oder Routine du bauen willst.

Kein Setup. Gilt nur für diesen einen Chat.

### Weg 3 — Cowork / Claude Desktop

Die Datei [`habits-coach.skill`](habits-coach.skill) herunterladen und in Cowork installieren.

---

## Was er kann

- **Einzelne Gewohnheit** auf- oder abbauen — Plan nach den vier Gesetzen.
- **Routine** takten — rückwärts gerechnet von einem festen Anker (wann du aus dem Haus musst, wann du einschlafen willst). Läuft dein Tag nicht nach der Uhr — Schicht, kleine Kinder, wechselnde Termine — hängt er die Gewohnheiten stattdessen an Ereignisse.
- **Ganzes System** über Tag und Woche — Schicht für Schicht eingeführt statt alles auf einmal.
- **Reparieren**, wenn es nicht gehalten hat — er findet, welches der vier Gesetze gebrochen ist, und ändert genau das.

Weißt du noch nicht, wo du anfangen sollst, geht er vorher mit dir deinen Tag durch. Und wenn nicht Disziplin der Engpass ist, sondern Erinnern und Anfangen selbst, baut er den Plan anders: externe Auslöser, kürzere Ketten, keine Streak-Zählerei.

---

## So sieht das aus

> **Du:** Ich nehme mir seit Monaten vor, morgens laufen zu gehen. Passiert nie. Ich muss um 8:00 aus dem Haus.

**Der Coach fragt einmal nach — zum Anklicken:**

| Frage | Auswahl |
|---|---|
| Läuft dein Morgen nach festen Zeiten? | **Weitgehend fest** · Wechselt ständig |
| Was hat dich bisher gebremst? | Im Alltag untergegangen · **Zu groß, keine Zeit** · Keine Lust · Nichts gespürt |
| An welchen Tagen soll es gelten? | **Mo–Fr, Wochenende frei** · Jeden Tag · Bestimmte Tage |

*(Fett = angeklickt. Eigene Antwort geht immer auch.)*

**Dann kommt der Plan:**

> ### 🎯 Morgens laufen — Mo bis Fr
>
> **Identität:** Du bist jemand, der den Tag beginnt, bevor der Tag mit dir beginnt.
>
> **Dein Morgen, rückwärts vom Anker gerechnet:**
>
> | Zeit | Block | Dauer |
> |------|-------|-------|
> | 6:45 | Aufstehen, Laufsachen an | 10 min |
> | 6:55 | **Laufen** | 20 min |
> | 7:15 | Duschen, fertig machen | 15 min |
> | 7:30 | Frühstück | 20 min |
> | 7:50 | Anziehen, packen | 10 min |
> | 8:00 | **Aus dem Haus** *(Anker, fix)* | — |
>
> Das sind 30 Minuten früher als deine bisherigen 7:15. Wenn dir das zu viel ist, kürzen wir das Laufen auf 12 Minuten — dann reichen 6:55. Lieber kurz und jeden Tag als lang und dreimal.
>
> **Warum es bisher nicht lief:** Du hast „zu groß, keine Zeit" angeklickt. Das ist Gesetz 3 — *Einfach*. Nicht deine Disziplin war das Problem, die Dosis war es. Deshalb steht hier keine Stunde Sport.
>
> **1. Offensichtlich** — Laufsachen liegen abends neben dem Bett, Schuhe an der Tür. Wecker ans andere Ende des Zimmers.
> **2. Attraktiv** — Der Podcast, den du sonst im Auto hörst, läuft ab jetzt nur beim Laufen.
> **3. Einfach** — 20 Minuten sind das Ziel, nicht der Einstieg. Der Einstieg ist: Schuhe an, vor die Tür.
> **4. Befriedigend** — Kaffee gibt es nach dem Laufen, nicht davor. Und ein Haken im Kalender, sichtbar.
>
> **Wenn's hakt:** Schuhe an und einmal um den Block. Zählt als erledigt. Nie zwei Tage hintereinander aussetzen.
>
> **Erster Schritt — heute Abend:** Laufsachen rauslegen. Nicht morgen früh suchen.

Denselben Plan bekommst du als Markdown zum Abspeichern.

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

## Lizenz und Herkunft

Der Skill steht unter der [MIT-Lizenz](LICENSE) — nutzen, ändern, weitergeben ist ausdrücklich erwünscht, Namensnennung genügt.

### Quelle: das Buch

Die Methodik stammt aus **[*Atomic Habits* von James Clear](https://jamesclear.com/atomic-habits)** (Avery / Penguin Random House, 2018). Auf Deutsch erschienen als **[*Die 1%-Methode*](https://www.randomhouse.de/Paperback/Die-1Prozent-Methode-Minimale-Veraenderung-maximale-Wirkung/James-Clear/Goldmann/e552511.rhd)** bei Goldmann.

Wenn dir der Skill etwas bringt, kauf das Buch. Es steht deutlich mehr drin, als ein Werkzeug wie dieses abbilden kann.

### Disclaimer

Dieser Skill ist ein **unabhängiges, inoffizielles** Werkzeug. Er ist **nicht mit James Clear, James Clear Holdings LLC oder Penguin Random House verbunden**, wird von diesen weder unterstützt noch geprüft, und es besteht keine Lizenzbeziehung. Der Buchtitel wird ausschließlich genannt, um auf die zugrunde liegende Quelle zu verweisen — nicht als Produktname.

Der Skill gibt die Prinzipien in eigenen Worten wieder und **enthält keine Auszüge, Zitate oder Zusammenfassungen von Buchtext**. Er ist **kein Ersatz für das Buch**, sondern ein Werkzeug, um dessen Ideen im Alltag umzusetzen — und ebenso kein Ersatz für ärztliche, therapeutische oder psychologische Beratung.

*This is an independent, unofficial tool. It is not affiliated with, endorsed by, or licensed by James Clear, James Clear Holdings LLC, or Penguin Random House. The book title is cited only to credit the underlying source, not as a product name. The skill applies the principles in the author's own words, contains no excerpts or quotations from the book, and is not a substitute for reading it — nor for medical, therapeutic, or psychological advice. Please [buy the book](https://jamesclear.com/atomic-habits).*
