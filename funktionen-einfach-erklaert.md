# Funktionen einfach erklärt – vom Alltag zur mathematischen Definition

## 1. Was ist eine Funktion?

Eine Funktion nimmt etwas entgegen und ordnet diesem Eingang ein Ergebnis zu.

Man kann sich eine Funktion wie eine Maschine vorstellen: Man gibt etwas hinein, die Maschine arbeitet nach einer festen Regel und liefert etwas zurück. Für dieselbe Eingabe liefert sie immer dieselbe Ausgabe.

Funktionen müssen keine mathematischen Formeln sein. Sie können zum Beispiel durch Tabellen, Verarbeitungsschritte oder Programme beschrieben werden.

Beispiele:

- Eine Tabelle ordnet einer Postleitzahl einen Ort zu.
- Ein Wörterbuch ordnet einem englischen Wort eine deutsche Übersetzung zu.
- Eine Suchfunktion erhält einen Suchbegriff und liefert Treffer.
- Ein Getränkeautomat erhält eine Auswahl und liefert ein Getränk.
- Ein Bildfilter erhält ein Bild und liefert ein verändertes Bild.

Entscheidend ist: Für jede erlaubte Eingabe muss eindeutig festgelegt sein, welche Ausgabe dazugehört. Unterschiedliche Eingaben dürfen jedoch zum gleichen Ergebnis führen.

## 2. Andere Begriffe für Funktionen

Für Funktionen werden auch andere Wörter verwendet. Sie beschreiben jeweils einen etwas anderen Blickwinkel:

- **Abbildung:** Betont, dass jedem Eingang ein bestimmter Ausgang zugewiesen wird. Beispiel: Eine Postleitzahl wird auf den dazugehörigen Ort abgebildet.
- **Zuordnung:** Betont die Beziehung zwischen Eingabe und Ausgabe. Beispiel: Jedem Wochentag wird eine Öffnungszeit zugeordnet.
- **Transformation:** Betont, dass eine Eingabe verändert wird. Beispiel: Ein Bildfilter erhält ein Farbfoto und erzeugt daraus ein Schwarz-Weiß-Bild.
- **Operator:** Bezeichnet eine Funktion, die eine bestimmte Operation ausführt. Beispiel: Ein Vergleichsoperator erhält zwei Werte und liefert zurück, ob sie gleich sind.

Diese Begriffe sind nicht immer vollständig austauschbar. In der Mathematik werden vor allem die Begriffe **Funktion** und **Abbildung** verwendet. **Zuordnung** ist ebenfalls ein allgemeiner Begriff und eignet sich besonders gut, um die Grundidee anschaulich zu erklären. **Transformation** und **Operator** beschreiben dagegen eher bestimmte Arten von Funktionen oder besondere Blickwinkel auf sie.

## 3. Der Aufbau einer Funktion

Eine Funktion lässt sich durch drei Bestandteile beschreiben:

- **Name:** Eine Funktion erhält einen Namen, damit wir sie eindeutig benennen und verwenden können. Aus der Schule sind dafür häufig kurze Namen wie **f** oder **g** bekannt. Diese Namen sind frei wählbar. Ein sprechender Name wie „Postleitzahl nachschlagen“ macht dagegen unmittelbar deutlich, was die Funktion tut.
- **Argumente:** Das sind die konkreten Eingaben, die der Funktion übergeben werden. Sie müssen aus dem erlaubten **Definitionsbereich** stammen. Bei der Funktion „Postleitzahl nachschlagen“ ist eine konkrete Postleitzahl das Argument.
- **Ausgabe oder Rückgabewert:** Das ist das Ergebnis, das die Funktion für die übergebenen Argumente liefert. Der Rückgabewert gehört zum **Wertebereich**. Im Beispiel ist der zurückgegebene Ort die Ausgabe.

Eine Funktion kann auch mehrere Argumente entgegennehmen. Eine Funktion zur Suche nach einer Zugverbindung könnte beispielsweise Abfahrtsort, Zielort und Reisetag erhalten und dazu eine passende Verbindung zurückgeben.

Der **Definitionsbereich** beschreibt damit, was in die Funktion hineingegeben werden darf. Der **Wertebereich** beschreibt, welche Ausgaben grundsätzlich möglich sind.

## 4. Eine Funktion als Beziehung zwischen zwei Mengen

Eine Funktion kann als Beziehung zwischen zwei Mengen betrachtet werden:

- Die **erste Menge** enthält alle erlaubten Eingaben.
- Die **zweite Menge** enthält alle grundsätzlich möglichen Ausgaben. Sie wird in diesem Artikel **Wertebereich** genannt.
- Jedem Element der ersten Menge wird **genau ein** Element der zweiten Menge zugeordnet.

„Genau ein“ ist dabei entscheidend: Eine Eingabe darf nicht gleichzeitig zwei verschiedene Ausgaben besitzen. Dann wäre die Beziehung keine Funktion.

Beispiel: Die erste Menge enthält Personen, die zweite Menge enthält Geburtsjahre. Jeder Person wird genau ein Geburtsjahr zugeordnet. Mehrere Personen dürfen dasselbe Geburtsjahr haben. Es ist auch nicht erforderlich, dass jedes mögliche Geburtsjahr tatsächlich einer Person zugeordnet wird.

Daraus ergeben sich drei wichtige Regeln:

1. Jedes Element der ersten Menge muss eine Zuordnung besitzen.
2. Jedes Element der ersten Menge darf nur einem Element der zweiten Menge zugeordnet sein.
3. Mehrere Elemente der ersten Menge dürfen demselben Element der zweiten Menge zugeordnet sein.

Die erste Menge wird **Definitionsmenge** oder **Definitionsbereich** genannt. Die zweite Menge heißt **Wertemenge** oder **Wertebereich**. Vereinfacht gesagt enthält der Definitionsbereich die erlaubten Eingaben und der Wertebereich die möglichen Ausgaben.

In genaueren mathematischen Darstellungen wird die zweite Menge häufig auch **Zielmenge** genannt. Die tatsächlich erreichten Werte heißen dann **Bildmenge**. Für die grundlegende Erklärung verwenden wir im Folgenden den leichter verständlichen Begriff **Wertebereich**.

## 5. Linkstotal und rechtseindeutig

Damit eine Zuordnung als Funktion gilt, muss sie **linkstotal** und **rechtseindeutig** sein. Hinter diesen Fachbegriffen stehen die beiden ersten Regeln aus dem vorherigen Abschnitt.

### 5.1 Linkstotal: Keine Eingabe bleibt ohne Ergebnis

**Linkstotal** bedeutet: Jedes Element des Definitionsbereichs muss einem Element des Wertebereichs zugeordnet sein.

Beispiel: Eine Tabelle ordnet jedem Wochentag die Öffnungszeit eines Geschäfts zu. Wenn für alle sieben Wochentage eine Angabe vorhanden ist, ist die Zuordnung linkstotal. Auch „geschlossen“ ist dabei ein gültiges Ergebnis.

Fehlt dagegen der Eintrag für Sonntag vollständig, ist die Zuordnung nicht linkstotal. Eine erlaubte Eingabe hätte dann kein Ergebnis und die Tabelle würde keine vollständige Funktion beschreiben.

### 5.2 Rechtseindeutig: Eine Eingabe hat nur ein Ergebnis

**Rechtseindeutig** bedeutet: Einem Element des Definitionsbereichs darf nicht gleichzeitig mehr als ein Element des Wertebereichs zugeordnet sein.

Beispiel: Jedem Menschen wird sein Geburtsjahr zugeordnet. Eine Person besitzt genau ein Geburtsjahr. Die Zuordnung ist daher rechtseindeutig.

Würde dieselbe Person gleichzeitig den Geburtsjahren 1978 und 1979 zugeordnet, wäre die Zuordnung nicht rechtseindeutig und damit keine Funktion.

Mehrere Eingaben dürfen jedoch dasselbe Ergebnis haben: Verschiedene Menschen können im selben Jahr geboren worden sein. Das widerspricht der Rechtseindeutigkeit nicht, denn jede einzelne Person besitzt weiterhin nur ein zugeordnetes Geburtsjahr.

### 5.3 Beides muss gleichzeitig gelten

Eine Zuordnung ist nur dann eine Funktion, wenn sie beide Bedingungen erfüllt:

- **linkstotal:** Jede erlaubte Eingabe hat ein Ergebnis.
- **rechtseindeutig:** Jede erlaubte Eingabe hat höchstens ein Ergebnis.

Gemeinsam bedeuten beide Eigenschaften: **Jede erlaubte Eingabe hat genau ein Ergebnis.**

## 6. Funktionen in der echten Welt finden

Wer in der echten Welt nach Funktionen sucht, kann in drei Schritten vorgehen:

1. **Definitionsmenge festlegen:** Welche Dinge dürfen als Eingabe verwendet werden?
2. **Wertebereich festlegen:** Welche Ergebnisse können diesen Eingaben zugeordnet werden?
3. **Funktion benennen:** Ein kurzer Buchstabe wie **f** ist möglich. Ein sprechender Name macht jedoch leichter verständlich, was zugeordnet wird.

Sind Definitionsmenge und Wertebereich festgelegt, kann die Funktion kurz so beschrieben werden:

> **f: D → W**

Dabei steht **f** für den frei gewählten Namen der Funktion, **D** für die Definitionsmenge und **W** für den Wertebereich. Der Pfeil bedeutet: Die Funktion ordnet jedem Element aus D genau ein Element aus W zu. Diese Schreibweise ist keine Rechenformel, sondern eine kompakte Beschreibung der Zuordnung.

### 6.1 Beispiel: Trainingsplan

- **Definitionsmenge D:** die sieben Wochentage
- **Wertebereich W:** Ruhetag, lockerer Lauf, Intervalltraining, Krafttraining und langer Lauf
- **Name der Funktion:** Training

Kurz geschrieben:

> **Training: Wochentage → Trainingseinheiten**

Die Funktion ordnet jedem Wochentag genau eine Trainingseinheit zu. Auch „Ruhetag“ ist ein gültiger Rückgabewert. Würde der Sonntag im Plan fehlen, wäre die Zuordnung nicht linkstotal. Würden dem Montag gleichzeitig ein lockerer Lauf und ein Krafttraining zugeordnet, wäre sie nicht rechtseindeutig. Sollen an einem Tag mehrere Einheiten möglich sein, muss eine vollständige Tagesliste als ein gemeinsamer Rückgabewert betrachtet werden.

### 6.2 Beispiel: Geburtsjahr

- **Definitionsmenge D:** eine festgelegte Gruppe von Personen
- **Wertebereich W:** mögliche Geburtsjahre
- **Name der Funktion:** Geburtsjahr

Kurz geschrieben:

> **Geburtsjahr: Personen → Jahre**

Jeder Person wird genau ein Geburtsjahr zugeordnet. Mehrere Personen dürfen dasselbe Geburtsjahr haben.

### 6.3 Beispiel: Bundesland einer Gemeinde

- **Definitionsmenge D:** alle Gemeinden Deutschlands
- **Wertebereich W:** die 16 deutschen Bundesländer
- **Name der Funktion:** Bundesland

Kurz geschrieben:

> **Bundesland: Gemeinden → Bundesländer**

Jede Gemeinde liegt in genau einem Bundesland. Mehrere Gemeinden werden demselben Bundesland zugeordnet.

### 6.4 Beispiel: Zeichenlänge eines Wortes

- **Definitionsmenge D:** alle Wörter in einem festgelegten Wörterbuch
- **Wertebereich W:** mögliche Anzahlen von Zeichen
- **Name der Funktion:** Zeichenlänge

Kurz geschrieben:

> **Zeichenlänge: Wörter → Anzahlen**

Jedem Wort wird genau eine Zeichenanzahl zugeordnet. Verschiedene Wörter können dieselbe Länge besitzen.

## 7. Die formale Definition einer Funktion

Nachdem wir Funktionen zunächst ohne Formeln betrachtet haben, können wir die mathematische Schreibweise nun aus den bekannten Bestandteilen ableiten.

### 7.1 Name, Definitionsbereich und Wertebereich

Eine Funktion besitzt einen Namen, einen Definitionsbereich und einen Wertebereich. Das wird kurz so geschrieben:

\[
f\colon D \to W
\]

Die Zeichen bedeuten:

- **f** ist der frei gewählte Name der Funktion.
- **D** ist der Definitionsbereich mit allen erlaubten Eingaben.
- **W** ist der Wertebereich mit allen möglichen Ausgaben.
- Der Pfeil zeigt, dass die Funktion Elemente aus D Elementen aus W zuordnet.

### 7.2 Beispiele mathematischer Funktionen

#### 7.2.1 Eine Zahl quadrieren

Die Funktion erhält eine Zahl und gibt deren Quadrat zurück:

\[
f(x)=x^2
\]

Dabei ist **x** das Argument und **f(x)** der Rückgabewert.

Beispiele:

- Für die Eingabe 2 ist die Ausgabe 4.
- Für die Eingabe −3 ist die Ausgabe 9.
- Für die Eingabe 0 ist die Ausgabe 0.

Die Funktion zeigt auch, dass unterschiedliche Eingaben denselben Rückgabewert haben dürfen: Sowohl 3 als auch −3 werden der Zahl 9 zugeordnet.

#### 7.2.2 Den Umfang eines Kreises berechnen

Diese Funktion erhält den Radius eines Kreises und gibt dessen Umfang zurück:

\[
U(r)=2\pi r
\]

Dabei steht:

- **U** für den Namen der Funktion,
- **r** für den Radius und damit für das Argument,
- **U(r)** für den berechneten Umfang.

Als Radius sind nur Zahlen größer oder gleich null sinnvoll. Der Definitionsbereich muss daher passend zur Bedeutung der Funktion gewählt werden.

#### 7.2.3 Eine Zahl verdoppeln

Die Funktion erhält eine Zahl und gibt das Doppelte dieser Zahl zurück:

\[
d(x)=2x
\]

Beispiele:

- Aus 3 wird 6.
- Aus 10 wird 20.
- Aus −2 wird −4.

#### 7.2.4 Den absoluten Wert bestimmen

Der absolute Wert beschreibt den Abstand einer Zahl von null. Das Ergebnis ist daher niemals negativ:

\[
a(x)=|x|
\]

Beispiele:

- Aus 5 wird 5.
- Aus −5 wird ebenfalls 5.
- Aus 0 wird 0.

Diese Beispiele zeigen: Eine mathematische Funktion erhält ein oder mehrere Argumente aus ihrem Definitionsbereich und erzeugt nach einer festgelegten Vorschrift einen Rückgabewert aus ihrem Wertebereich.
