# Eigenschaften von Funktionen – injektiv, surjektiv und bijektiv

Funktionen ordnen jedem Element eines Definitionsbereichs genau ein Element einer Zielmenge zu. Neben dieser grundlegenden Eigenschaft können wir untersuchen, **wie** die Elemente der beiden Mengen miteinander verbunden sind.

Drei besonders wichtige Eigenschaften sind **injektiv**, **surjektiv** und **bijektiv**. Sie lassen sich gut mit einem Kinosaal erklären.

In unserem Beispiel bilden wir zwei Mengen:

- Der **Definitionsbereich** besteht aus den Kinobesuchern.
- Die **Zielmenge** besteht aus den Sitzplätzen im Kinosaal.
- Die Funktion „Sitzplatz“ ordnet jedem Besucher genau einen Platz zu.

## 1. Injektiv: Niemand teilt sich einen Platz

Eine Funktion ist **injektiv**, wenn unterschiedliche Eingaben nicht zur gleichen Ausgabe führen.

Auf das Kino übertragen bedeutet das: Jeder Besucher erhält einen eigenen Sitzplatz. Zwei verschiedene Besucher dürfen nicht demselben Platz zugeordnet sein.

Dabei dürfen Plätze frei bleiben. Für die Injektivität ist nur entscheidend, dass kein Platz doppelt vergeben wird.

Beispiel:

- Anna sitzt auf Platz 12.
- Ben sitzt auf Platz 13.
- Cem sitzt auf Platz 15.
- Platz 14 bleibt frei.

Diese Zuordnung ist injektiv. Alle Besucher haben unterschiedliche Plätze. Dass Platz 14 nicht besetzt ist, spielt dabei keine Rolle.

Nicht injektiv wäre die Zuordnung, wenn Anna und Ben beide Platz 12 erhielten. Zwei unterschiedliche Eingaben würden dann auf dieselbe Ausgabe zeigen.

Ein guter Merksatz lautet:

> **Injektiv bedeutet: Kein Platz aus der Zielmenge wird doppelt vergeben.**

Aus einer Ausgabe kann deshalb eindeutig auf die zugehörige Eingabe zurückgeschlossen werden: Wenn wir wissen, dass Platz 12 besetzt ist, gibt es höchstens einen Besucher, dem dieser Platz zugeordnet wurde.

## 2. Surjektiv: Jeder Platz ist besetzt

Eine Funktion ist **surjektiv**, wenn jedes Element der Zielmenge von mindestens einer Eingabe erreicht wird.

Der Kinobesitzer betrachtet nun nicht die Besucher, sondern seine Plätze. Er möchte, dass jeder Platz besetzt ist. Kein Platz soll leer bleiben.

Für die Surjektivität ist nicht entscheidend, ob ein Platz theoretisch mehreren Besuchern zugeordnet wird. Entscheidend ist zunächst nur, dass **jeder** vorhandene Platz erreicht wird.

Beispiel:

- Platz 12 ist Anna zugeordnet.
- Platz 13 ist Ben zugeordnet.
- Platz 14 ist Cem zugeordnet.

Wenn dies alle Plätze des betrachteten Kinosaals sind, ist die Zuordnung surjektiv: Jeder Platz wurde vergeben.

Bleibt Platz 14 frei, ist die Zuordnung nicht surjektiv. Ein Element der Zielmenge wird dann von keiner Eingabe erreicht.

Ein guter Merksatz lautet:

> **Surjektiv bedeutet: Kein Platz aus der Zielmenge bleibt frei.**

Bei der Surjektivität ist die festgelegte Zielmenge besonders wichtig. Betrachten wir nur die Plätze 12 bis 14, kann die Zuordnung surjektiv sein. Gehört Platz 15 ebenfalls zur Zielmenge und bleibt unbesetzt, ist dieselbe Zuordnung nicht mehr surjektiv.

## 3. Bijektiv: Jeder Besucher hat seinen eigenen Platz und jeder Platz ist besetzt

Eine Funktion ist **bijektiv**, wenn sie gleichzeitig injektiv und surjektiv ist.

Im Kino müssen dafür beide Bedingungen erfüllt sein:

- Kein Platz wird doppelt vergeben.
- Kein Platz bleibt frei.

Damit gehört zu jedem Besucher genau ein eigener Platz und zu jedem Platz genau ein Besucher.

Beispiel:

- Anna sitzt auf Platz 12.
- Ben sitzt auf Platz 13.
- Cem sitzt auf Platz 14.

Wenn Anna, Ben und Cem alle Besucher und die Plätze 12 bis 14 alle verfügbaren Plätze sind, ist die Zuordnung bijektiv.

Ein guter Merksatz lautet:

> **Bijektiv bedeutet: Jeder Besucher hat seinen eigenen Platz und jeder Platz ist besetzt.**

Eine bijektive Zuordnung kann eindeutig umgekehrt werden. Wir können nicht nur vom Besucher auf seinen Platz schließen, sondern auch von jedem Platz auf genau einen Besucher.

## 4. Die drei Eigenschaften im Vergleich

| Eigenschaft | Frage an die Zuordnung | Kinobeispiel |
|---|---|---|
| **Injektiv** | Teilen sich unterschiedliche Eingaben eine Ausgabe? | Kein Platz ist doppelt vergeben; Plätze dürfen frei bleiben. |
| **Surjektiv** | Wird jede mögliche Ausgabe erreicht? | Jeder Platz ist besetzt. |
| **Bijektiv** | Ist die Funktion injektiv und surjektiv? | Jeder Platz ist genau einem Besucher zugeordnet. |

## 5. Ein zweites Bild: Jäger und Füchse

Auch der Satz „Jeder Jäger hat seinen Fuchs“ kann als Zuordnung verstanden werden. Damit die Eigenschaften eindeutig beurteilt werden können, müssen wir aber genauer fragen:

- **Injektiv:** Jeder Jäger hat einen anderen Fuchs. Kein Fuchs ist zwei Jägern zugeordnet.
- **Surjektiv:** Jeder Fuchs aus der betrachteten Gruppe ist mindestens einem Jäger zugeordnet.
- **Bijektiv:** Jeder Jäger hat genau seinen eigenen Fuchs und jeder Fuchs gehört genau zu einem Jäger.

Der Satz „Jeder Jäger hat einen Fuchs“ allein reicht noch nicht aus, um Injektivität oder Surjektivität festzustellen. Er sagt nur, dass jeder Jäger überhaupt eine Zuordnung besitzt.

## 6. Zusammenfassung

Die drei Eigenschaften betrachten eine Funktion aus unterschiedlichen Blickwinkeln:

- **Injektiv** schaut darauf, ob eine Ausgabe mehrfach getroffen wird.
- **Surjektiv** schaut darauf, ob alle Elemente der Zielmenge getroffen werden.
- **Bijektiv** verbindet beide Anforderungen.

Kurz auf das Kino bezogen:

> **Injektiv:** kein Platz doppelt.  
> **Surjektiv:** kein Platz frei.  
> **Bijektiv:** jeder Platz genau einmal vergeben.

## 7. Die formale Beschreibung

Nachdem wir die drei Eigenschaften anschaulich betrachtet haben, können wir sie nun in mathematischer Sprache beschreiben.

Wir gehen von einer Funktion aus, die Elemente aus dem Definitionsbereich **D** Elementen aus der Zielmenge **W** zuordnet:

$$
f: D \rightarrow W
$$

Dabei ist **x** eine Eingabe aus D und **f(x)** die zugehörige Ausgabe in W.

### 7.1 Verwendete Zeichen und Quantoren

In den formalen Definitionen werden **Quantoren** verwendet. Quantoren geben an, ob eine Aussage für alle Elemente oder nur für mindestens ein Element einer Menge gelten soll.

Die wichtigsten Zeichen sind:

| Zeichen | Gesprochen | Bedeutung |
|---|---|---|
| **∀** | „für alle“ oder „für jedes“ | Die folgende Aussage muss für jedes betrachtete Element gelten. |
| **∃** | „es existiert“ oder „es gibt mindestens ein“ | Mindestens ein passendes Element muss vorhanden sein. Es dürfen auch mehrere sein. |
| **∃!** | „es existiert genau ein“ | Es muss ein passendes Element geben und es darf kein zweites geben. |
| **∈** | „ist Element von“ oder „gehört zu“ | Das genannte Element gehört zu einer bestimmten Menge. |
| **:** | „sodass gilt“ | Danach folgt die Bedingung, die erfüllt sein muss. |
| **f(x)** | „f von x“ | Der Wert, den die Funktion f für die Eingabe x liefert. |

Betrachten wir damit die formale Beschreibung einer bijektiven Funktion:

$$
\forall y \in W\; \exists! x \in D: f(x)=y
$$

Wir lesen sie von links nach rechts:

1. **∀ y ∈ W:** Für jedes Element y aus der Zielmenge W
2. **∃! x ∈ D:** existiert genau ein Element x aus dem Definitionsbereich D,
3. **f(x) = y:** sodass die Funktion dieses x auf y abbildet.

Als vollständiger Satz lautet die Aussage:

> Für jedes Element der Zielmenge existiert genau eine Eingabe aus dem Definitionsbereich, die auf dieses Element abgebildet wird.

Auf das Kino übertragen bedeutet das: Für jeden Sitzplatz aus der Zielmenge gibt es genau einen Besucher aus dem Definitionsbereich, dem dieser Platz zugeordnet ist.

Die Reihenfolge der Quantoren ist wichtig: Zuerst wird ein beliebiger Platz betrachtet. Danach wird gefragt, ob es genau einen dazugehörigen Besucher gibt.

### 7.2 Injektiv

Eine Funktion ist injektiv, wenn aus gleichen Ausgaben auf gleiche Eingaben geschlossen werden kann:

$$
\forall x_1,x_2 \in D: f(x_1)=f(x_2) \Rightarrow x_1=x_2
$$

Das bedeutet: Wenn zwei Eingaben denselben Funktionswert besitzen, müssen sie dieselbe Eingabe sein. Zwei tatsächlich unterschiedliche Eingaben können daher nicht auf dieselbe Ausgabe abgebildet werden.

Auf das Kino übertragen: Wenn zwei Zuordnungen auf denselben Platz zeigen, müssen sie zum selben Besucher gehören. Verschiedene Besucher können nicht denselben Platz erhalten.

### 7.3 Surjektiv

Eine Funktion ist surjektiv, wenn jedes Element der Zielmenge W von mindestens einer Eingabe aus D erreicht wird:

$$
\forall y \in W\; \exists x \in D: f(x)=y
$$

Die Zeichen bedeuten:

- **Für jedes y aus W**
- **existiert mindestens ein x aus D,**
- **dessen Funktionswert y ist.**

Auf das Kino übertragen: Für jeden Platz aus der Zielmenge gibt es mindestens einen Besucher, dem dieser Platz zugeordnet wurde. Kein Platz bleibt frei.

### 7.4 Bijektiv

Eine Funktion ist bijektiv, wenn sie gleichzeitig injektiv und surjektiv ist. Jeder Wert aus der Zielmenge wird dann von genau einer Eingabe erreicht:

$$
\forall y \in W\; \exists! x \in D: f(x)=y
$$

Das Ausrufezeichen hinter dem Existenzzeichen bedeutet **„es existiert genau ein“**.

Auf das Kino übertragen: Für jeden Platz gibt es genau einen Besucher. Kein Platz bleibt frei und kein Platz wird doppelt vergeben.

Eine bijektive Funktion stellt damit eine eindeutige Eins-zu-eins-Zuordnung zwischen Definitionsbereich und Zielmenge her.
