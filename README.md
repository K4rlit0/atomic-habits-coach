# Habits Coach

Ein KI-Skill, der Gewohnheiten und Routinen nach einer erprobten Methodik baut. Du sagst, was du aufbauen oder loswerden willst. Er stellt **eine** Runde Fragen zu deinem echten Tag — je nach Umgebung zum Anklicken oder als kurze Liste — und baut daraus einen konkreten, getakteten Plan. Mit einer niederschwelligen 2-Minuten-Startversion.

---

## Installation

Skills gibt es in allen Claude-Plänen — Free, Pro, Max, Team und Enterprise.

| Wo nutzt du Claude? | Nimm |
|---|---|
| **Browser oder Desktop-App** (claude.ai) | **Weg A** — einmal installieren, danach immer da |
| **Cowork** | **Weg B** — die `.skill`-Datei |
| **Handy · Firmen-Account ohne Skills · nur mal ausprobieren** | **Weg C** — Text einfügen, kein Setup |

> ⚠️ **Nicht den grünen `Code`-Button oben rechts benutzen.** Der lädt das komplette Repository als ZIP — dieses ZIP akzeptiert Claude nicht. Nimm die Download-Links unten.

### Weg A — Als Skill in Claude (Browser und Desktop-App)

Einmal einrichten, danach startet er von selbst.

1. **[`habits-coach.zip` herunterladen](habits-coach.zip?raw=1)** — der Link lädt direkt los. **Nicht entpacken.**
2. In Claude die **Einstellungen → Capabilities** öffnen und **Code-Ausführung und Dateierstellung** einschalten. Skills funktionieren ohne das nicht.
3. **[claude.ai/customize/skills](https://claude.ai/customize/skills)** öffnen (im Menü: **Customize → Skills**, je nach Spracheinstellung „Anpassen → Skills"), auf **„+"** und dann **„Create skill"** klicken, das ZIP hochladen und den Skill einschalten.

Ab jetzt läuft er von allein an, sobald du über Gewohnheiten oder Routinen sprichst. **Test:** Schreib „Ich will morgens zehn Minuten lesen." Kommt eine kurze Fragerunde statt eines allgemeinen Ratgebertextes, läuft er.

**Firmen- oder Uni-Account (Team/Enterprise)?** Dort entscheidet die Organisation, ob Skills erlaubt sind. Wenn du das Menü nicht findest, ist es zentral abgeschaltet — dann nimm **Weg C**, der funktioniert immer.

**Am Handy?** Hochladen geht nur im Browser oder in der Desktop-App, nicht in der Handy-App. Einmal am Rechner installieren, danach ist er auch am Handy da. Oder direkt **Weg C**.

### Weg B — Cowork

**[`habits-coach.skill` herunterladen](habits-coach.skill?raw=1)** und in Cowork installieren.

*Inhaltlich identisch zu `habits-coach.zip` — nur die Endung unterscheidet sich, weil Cowork und claude.ai verschiedene Formate erwarten. Du brauchst immer nur eine der beiden Dateien.*

### Weg C — Ohne Installation, funktioniert überall

Für einmal ausprobieren, am Handy, oder wenn dein Account keine Skills zulässt.

1. **[`PROMPT.md` öffnen](PROMPT.md?plain=1)** — der Link öffnet die Textansicht.
2. Oben rechts auf das **Kopier-Symbol** klicken, das die ganze Datei kopiert. *(Nicht aus der normal dargestellten Ansicht kopieren — dabei gehen Tabellen und Formatierung verloren.)*
3. In Claude einfügen und darunter in einem Satz schreiben, welche Gewohnheit oder Routine du bauen willst.

Kein Setup, kein Account-Zwang, funktioniert auch in anderen KI-Chats. Gilt allerdings nur für diesen einen Chat.

---

## Vier Prompts zum Ausprobieren

„Hilf mir, produktiver zu werden" ist zu unscharf — der Coach kann daraus keinen Anker bauen. Diese vier zeigen, was er wirklich kann. Kopier einen und pass ihn an:

```text
Ich möchte an Werktagen nach dem ersten Kaffee zehn Minuten lesen.
Bisher vergesse ich es oder greife stattdessen zum Handy.
```

```text
Ich arbeite in wechselnden Schichten und will Sport, Essen vorbereiten
und Lernen als festes System aufbauen. Plane ereignisbasiert, nicht nach Uhrzeit.
```

```text
Meine Abendroutine ist nach einer stressigen Woche komplett gerissen.
Reparier bitte die eine Stelle, die nicht gehalten hat, statt alles neu zu planen.
```

```text
Ich will abends weniger snacken. Es passiert bei Stress,
vor dem Fernseher und direkt nach dem Abendessen.
```

Je konkreter du deinen echten Tag beschreibst, desto weniger muss er fragen und desto brauchbarer wird der Plan.

---

## Wo er wie funktioniert

Der Skill passt sich der Umgebung an. Was du bekommst, hängt davon ab, wo du ihn nutzt:

| Umgebung | Fragen | Plan zum Mitnehmen |
|---|---|---|
| **Cowork** | Auswahl-Buttons | Datei im gewählten Ordner |
| **claude.ai Browser/Desktop** (Weg A) | kurze nummerierte Liste | Datei zum Download |
| **Claude Code / Terminal** | je nach Setup | Datei — aber nur in einen Ordner, den du selbst nennst |
| **Handy-App** | kurze nummerierte Liste | kopierbarer Markdown-Block |
| **Weg C** (Text eingefügt, auch andere KI-Chats) | kurze nummerierte Liste | kopierbarer Markdown-Block |

Der kopierbare Block ist der Standard und funktioniert überall — eine Datei kommt nur dazu, wenn klar ist, wohin sie gehört. Nach einem Speicherort fragt er dich nie. Wenn etwas davon bei dir anders läuft, mach bitte ein Issue auf.

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

**Der Coach fragt einmal nach — hier in einer Umgebung mit Auswahl-Buttons:**

| Frage | Auswahl |
|---|---|
| Läuft dein Morgen nach festen Zeiten? | **Weitgehend fest** · Wechselt ständig |
| Was hat dich bisher gebremst? | Im Alltag untergegangen · **Zu groß, keine Zeit** · Keine Lust · Nichts gespürt |
| An welchen Tagen soll es gelten? | **Mo–Fr, Wochenende frei** · Jeden Tag · Bestimmte Tage |

*(Fett = gewählt. Eigene Antwort geht immer auch.)*

Ob die Fragen als Buttons kommen, hängt an deinem Claude — nicht jede Oberfläche bietet Auswahl-Buttons an. Wo es sie nicht gibt, stellt der Coach dieselben Fragen als kurze nummerierte Liste. Auch dann bleibt es bei **einer** Runde: Du antwortest kurz, danach kommt der Plan. Und wenn du gar nicht antworten willst, baut er ihn mit sichtbar markierten Annahmen.

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
> Ich nehme an, du stehst bisher gegen 7:15 auf — dann sind das 30 Minuten früher. Stimmt das nicht, sag Bescheid. Wenn dir das zu viel ist, kürzen wir das Laufen auf 12 Minuten, dann reicht 6:53. Lieber kurz und jeden Tag als lang und dreimal.
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

Der Skill deckt Alltagsgewohnheiten ab — Sport, Lesen, Lernen, Handyzeit, Ordnung, Ernährung und Gewicht inklusive. Auch Rauchstopp, alkoholfreie Tage, ein trockener Monat, weniger Koffein oder „die Tabletten endlich regelmäßig nehmen" sind normale Fälle und werden normal geplant.

Wo er bewusst keinen Plan baut, sondern auf fachliche Begleitung verweist: Entzug, der körperlich gefährlich werden kann, das Absetzen verschriebener Medikamente, Schlafverkürzung, Selbstverletzung und Zwänge. Die Grenze ist das medizinische Risiko beim Absetzen, nicht das Stichwort — deshalb ist Rauchstopp drin und täglicher Alkoholkonsum nicht. Das ist so gewollt: ein getakteter Gewohnheitsplan ist dort das falsche Werkzeug.

Er ersetzt keine ärztliche, therapeutische oder psychologische Beratung.

Für Terminplanung, Kalender, To-do-Listen, Projektplanung oder Morgen-Briefings ist er ebenfalls nicht gedacht — dafür gibt es bessere Werkzeuge.

## Deine Daten

Der Skill ist reiner Text ohne Code, ohne Netzwerkzugriff und ohne Tracking. Was du im Gespräch über deinen Tag erzählst, bleibt in deinem Claude-Konto und läuft weder über mich noch über Dritte. Wie Claude selbst mit Chatinhalten umgeht, steht in Anthropics Datenschutzerklärung.

---

## Lizenz und Herkunft

**Version 1.6** — `habits-coach.zip`, `habits-coach.skill` und `PROMPT.md` enthalten immer denselben Stand wie [`habits-coach/SKILL.md`](habits-coach/SKILL.md).

Der Skill steht unter der [MIT-Lizenz](LICENSE) — nutzen, ändern, weitergeben ist ausdrücklich erwünscht, Namensnennung genügt.

### Quelle: das Buch

Die Methodik stammt aus **[*Atomic Habits* von James Clear](https://jamesclear.com/atomic-habits)** (Avery / Penguin Random House, 2018). Auf Deutsch erschienen als **[*Die 1%-Methode*](https://www.randomhouse.de/Paperback/Die-1Prozent-Methode-Minimale-Veraenderung-maximale-Wirkung/James-Clear/Goldmann/e552511.rhd)** bei Goldmann.

Wenn dir der Skill etwas bringt, kauf das Buch. Es steht deutlich mehr drin, als ein Werkzeug wie dieses abbilden kann.

### Disclaimer

Dieser Skill ist ein **unabhängiges, inoffizielles** Werkzeug. Er ist **nicht mit James Clear, James Clear Holdings LLC oder Penguin Random House verbunden**, wird von diesen weder unterstützt noch geprüft, und es besteht keine Lizenzbeziehung. Der Buchtitel wird ausschließlich genannt, um auf die zugrunde liegende Quelle zu verweisen — nicht als Produktname.

Der Skill gibt die Prinzipien in eigenen Worten wieder und **enthält keine Auszüge, Zitate oder Zusammenfassungen von Buchtext**. Er ist **kein Ersatz für das Buch**, sondern ein Werkzeug, um dessen Ideen im Alltag umzusetzen — und ebenso kein Ersatz für ärztliche, therapeutische oder psychologische Beratung.

*This is an independent, unofficial tool. It is not affiliated with, endorsed by, or licensed by James Clear, James Clear Holdings LLC, or Penguin Random House. The book title is cited only to credit the underlying source, not as a product name. The skill applies the principles in the author's own words, contains no excerpts or quotations from the book, and is not a substitute for reading it — nor for medical, therapeutic, or psychological advice. Please [buy the book](https://jamesclear.com/atomic-habits).*
