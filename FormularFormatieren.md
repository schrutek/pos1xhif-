# Formular formatieren

Excel eignet sich als Tabellenprogramm natürlich auch gut dazu Worksheets in Form von Formularen zu gestalten. Heute werden wir einFormular gestalten.

Folgendes Formular soll erstellt werden:

![Formatierungsblock](Formular21.PNG)

Das ganze ist eine kleine spielerei. Aber ich möchte einige Tips geben, wie man an die Sache herangehen kann:

Jedes Feld, bzw. dazugehöriger Feldname ist eine Zelle. Wir müssen also die Breiten der Zellen so verändern, dass sie der Vorgabe entsprechen.

## Schritt 1

Jenen Bereich im Formular ermittel, der die meisten Spalten benötigt.

Vorname, Max, Nachname, Muster = 4 Spalten

X, Dokumenatarfilm, X, Lehr-Schulungsfilm, X, All Media, X, Intranet = 8 Splaten

usw.

Das ist also eindeutig die Zeile (Bereich) unterhalb "Bitte angeben", mit den X-Feldern

Also die ersten 8 Spalten im Worksheet auf die entsprechende Breite ändern: (Ändern der Splatenbreite durch rechtsklick auf den Splatenzwischenraum in der Splatenüberschrift (graue Zeile ganz oben) siehe letzte Übung) 

1, 3, 18, 3, 18, 3, 18, 3, 18, 1

(Die erste und letzte Splate dient nur als Abstandshalter zum Rand und erhält die Breite 1)

Die Splatenbreite eienr Zelle kann man übrigens exakt festelegen, indem man bei der entsprechenden Spalte mit der rechten Maustaste auf die Splatenüberschrift klickt und dann "Splatenbreite" auswählt.

![Formatierungsblock](ColumnWidth.png)

Das Ergebnis sieht dann also so aus:

![Formatierungsblock](Formular01.PNG)

Die Zellen, die Checkboxen darstellen sollen, können dann gleich umrahmt werden:

![Formatierungsblock](Formular02.PNG)

Und die Bezeichnungen können eingefügt werden:

![Formatierungsblock](Formular03.PNG)

**Erinnerung zu Rahemnformatierungen**

![Formatierungsblock](Rahmen.PNG)


## Schritt 2

Setzten wir mit dem Block darunter fort. Man kann sehen, dass die Bezeichnungen in der Splate E über die Zellen hinausragen.

![Formatierungsblock](Formular04.PNG)

Nun gibt es mehrere Möglichkeiten das zu formatieren. Wir machen das mal folgendermaßen:

Spalte E wird breiter gemacht, dann  müssen wir natürlich eine andere Spalte um den gleichen Wert schmäler machen. Hier: Spalte G (die eignet sich auf Grund des Inhaltes am besten)

![Formatierungsblock](Formular05.PNG)

## Schritt 3

Den Block "Sonstige Kopien" müssen wir irgendwie unterbringen. Das geht sich mit den vorhandenen Spalten nicht aus:

![Formatierungsblock](Formular06.PNG)

Hier ist es erstmals notwendig, Zellen zu verbinden um ein sauberes Formularfeld zu erstellen. Wir benötigen nach Spalte F eine weitere Splate gleicher Breite, die den Abstand zwischen den Feldern in Spalte G und dem Feld "Sonstige Kopien" darestellen wird.

![Formatierungsblock](Formular07.PNG)

Also: Rechte Maustaste auf Spalte F und auf Einfügen klicken. Gegebenenfalls die Spaltenbreite verändern. Die Splate J muss dann entsprechend verringert werden.

Jetzt kann die entsprechende Range für das Formularfeld umrahmt werden:

![Formatierungsblock](Formular08.PNG)

## Schritt 4

Als nächstes erstellen wir die Zeilen für die Playlist darunter. Dabei schreiben wir mal die Spaltenüberschriften in jene Zellen, in die es am besten passt. Das passt wie man sieht eigentlich ganz gut. Das Feld Titel darf etwas breiter sein, das Feld Länge enthält die Länge eines Songs in Sekunden, das wird wohl nur ein 3-stelliger Wert sein (z.B.: 240 Sek). Wenn wir Glück haben geht sich das weiterhin schön aus. (Ich sags gleich, das wird es nicht)

![Formatierungsblock](Formular09.PNG)

## Schritt 5

Eine kleine Hürde ist noch der oberste Block mit "Vorname" und "Nachname". Die Felder sollen so platziert werden, dass sie etwa gleich groß sind und das Formular etwa in der Mitte teilen. Wieder müssen wir Zellen verbinden.

![Formatierungsblock](Formular10.PNG)

Man kann sehen, dass sich das für den Vornamen gut ausgeht, für den Nachnamen aber gar nicht.

![Formatierungsblock](Formular11.PNG)

Das gleiche Spiel nochmal. Wider eine neue Splate nach der splate E einfügen. Diese nun auf die Breite 1 reduzieren.

![Formatierungsblock](Formular12.PNG)

Die Bezeichnung Nachname ist nun immer noch zu lang. Daher eine weitere Spalte nach H einfügen. (Also auf "H" rechts klicken und auf "Splate einfügen")

![Formatierungsblock](Formular13.PNG)

Jetzt geht sich das schün aus. Allerdings muss nun die Breite von einer anderen Splaten wieder reduziert werden, damit die Gesamtbreite gleich bleibt. Nehmen wir die Splate L, und reduzieren sie um 4.

![Formatierungsblock](Formular14.PNG)

## Schritt 6

Jetzt gehts an den Endspurt, an das Zellen verbinden. Einfach den Bereich (Range) der Zellen auswählen die man verbinden möchte und auf das Icon im Ribbon klicken:

![Formatierungsblock](MergeZells.PNG)

Das machen wir nun für alle Felder, die sich über mehrere Zellen erstrecken:

![Formatierungsblock](Formular15.PNG)

Jetzt noch der Bereich der Play List. Hier werden ebenfalls alle Zellen verbunden, damit die entsprechende Range eine Zelle einzige wird.

Achtung! Das bitte immer Zeilenweise tun, sonst wird die Range zu einer einzigen Zelle. Das soll nicht sein.

![Formatierungsblock](Formular16.PNG)

Anschließend kann man auch diesen Bereich mit einem Rahmen versehen.

![Formatierungsblock](Formular17.PNG)

## Schritt 7

Im oberen Block möchte ich jetzt noch eine weitere Zeile einfügen, die sich mit der ersten Zeile in etwa decken soll:

![Formatierungsblock](Formular18.PNG)

Man kann sehen, das Wort Bild/Tonträger ist mal wieder zu lange für den Bereich. Also wieder daselbe Spiel. Wieder eine neue Splate einfügen, dafür eine andere Spalte schmäler machen.

![Formatierungsblock](Formular19.PNG)

Nun passt das Ergebnis. Die verbundenen Zellen bei Komponist in der Play List muss nochmal nachgearbeitet werden. Dazu kann man die Verbindung wider auflösen (Icon "Zellen verbinden" klicken um die Verbindung zu deaktivieren) und dann neu setzten (Icon "Zellen verbinden" klicken um die verbindung zu aktivieren).

![Formatierungsblock](Formular20.PNG)

Nun wird das Formular noch etwas formatiert. Dabei sind der Kreativität /keine Grenzen gesetzt. Tobt euch hier ruhig aus.

## Schritt 8: Eine Drop Down Liste im Formularfeld

Im Feld "Produktion" und "Bild/Tonträger" möchte ich ein Auswahl mittels Drop-Down-Feld erstellen. Das ist für die Eingabe von Daten durch den späteren Benutzer sehr praktisch.

![Formatierungsblock](DropDown.PNG)

**Wie geht das?**

Es ist ganz einfach. Wir benötigen ein 2. Worksheet mit den Daten die in den beiden Drop-Down-Feldern angezeigt werden sollen:

![Formatierungsblock](DropDownData.png)

Also auf das Plus ganz unten klicken, es erscheint ein neues Arbeitsblatt, dann dafür einen Namen eingeben, z.B. "Data". Anschließend die anzuzeigende Liste in irgend eine Splate eingeben. Ganz egal welche.

Als nächstes wählt man jene Splate im Formular aus, in der man die Drop Down Liste haben möchte un klickt im Ribbon auf "Daten", anschließend auf "Daten Validierungen".

![Formatierungsblock](DataValidation.png)

Es öffnet sich ein Dialogfeld in dem man nun die Kriterien der Daten auswählen kann. In der obersten Drop-Down-Box "Liste" wählen, und anschließend den Bereich, in dem die Daten für die Liste gefunden werden können. Auf das Icon klicken und den Bereich auf dem Worksheet "Data" auswählen. Bitte für die beiden Drwop-Down-Boxen im Formular die beiden Bereiche separat auswählen.

![Formatierungsblock](DataValidation02.png)

Das für beide Felder im Formular durchführen, und die Übung ist erledigt.

Hier habe ich noch ein kurzes Video gefunden, welches die Drop-Down-Box in Formularen nochmal erklärt:

https://www.youtube.com/watch?v=FZPyAFo2qKM