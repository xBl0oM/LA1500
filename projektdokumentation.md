# Projekt-Dokumentation



Hydrangea
Sivickas, Karrer, Özden, Frey

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|09.03 | 0.0.1|Heute haben wir alle an unseren Level gearbeitet und haben dabei zusammen einen Charakter erstellt.|
|16.03|0.1.0|Heute haben wir weiter an unseren Level gearbeitet, dabei haben wir das Menu fertiggestellt, weiter am Fighter gearbeitet, den Platformer fast fertiggestellt und das Auto des Racing Game zum Laufen gebracht.|
|23.03|0.1.1|Heute haben wir wieder an unseren Level gearbeitet und jeder ist schon fast am Ende. Wenn jeder seine Level fertig hat, werden wir sie alle zusammenfügen und die Präsentation machen. |
|30.03|1.0.0|Wir haben bis Heute alle Levels zusammengefügt und auch die Präsentation fertig gestellt. Neben dem Präsentieren müssen wir jetzt nur noch die Dokumentation fertig machen.|
|07.04|1.0.0|Heute haben wir die Dokumentation und den Lernbericht fertig gestellt.|

## 1 Informieren

### 1.1 Ihr Projekt

Unser Projekt beinhaltet einen Game-Triatlon.

Unser Projekt wird in Unreal Engine 5 programmiert und unser Ziel ist es, dass der Spieler in eine hohe Diversität von verschiedenen Genres befördert wird und der Gewinner sein muss. Wir möchten, dass wir dem Spieler ein spassiges Spiel programmieren und dass wir vieles dabei lernen. Das Spiel hat eine hohe Diversität und deshalb ist die Lernmenge ziemlich viel. Wir hoffen zu lernen, wie man Fahrzeuge programmiert oder wie man Menüs und die Levels verbindet.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 |Kann|Qualität |Als ein User möchte ich zwischen verschiedenen Charakteren auswählen können, damit ich einen Vorteil gegenüber anderen haben kann.|
| 1.2 |Kann|Qualität| Als User möchte ich, dass Charaktere verschiedene Stats haben, damit das Spiel nicht langweilig ist. |
|2|Kann|Qualität|Als User möchte ich zwischen verschiedenen Fahrzeugen auswählen können, damit ich meine Rennen fahren kann.|
|2.2|Kann|Qualität|Als User möchte ich Fahrzeuge, die unterschiedliche Stats haben, damit ich einen grösseren Spielspass habe.|
|3|Soll|Funktional|Als User möchte ich ein Rennspiel haben, damit das Spiel eine Diversität bietet.|
|4|Soll|Funktional|Als User möchte ich ein Platformer haben, damit das Spiel nicht immer gleich ist.|
|5|Soll|Funktional |Als User möchte ich ein Final spiel haben, damit dann entschieden wird, wer der Gewinner ist.|
|6|Soll|Funktional|Als User möchte ich ein Fighter-Spiel haben, damit noch mehr Diversität ins Spiel kommt. |
|7 |Soll|Funktional|Als User möchte ich einen Victory Screen haben, damit man weiss, wer der Gewinner ist.|
|8|Kann|Qualität|Als User möchte ich Tänze machen können, damit man mehr Spass am Spiel hat.|
|9|Kann|Rand|Als User möchte ich eine Währung erhalten, wenn ich ein Match spiele, damit ich eventuell andere Items kaufen kann.|
|10|Kann|Qualität|Als User möchte ich mit der erhaltenen Währung verschiedene Siegestänze kaufen können, damit ich meine Währung ausgeben kann.|
|11|Kann|Qualität|Als User möchte ich meine Platzierungen / Stats speichern können, damit ich rückblickend meine Siege und Niederlagen sehen kann.|
|12|Soll|Funktional| Als User möchte ich, dass die Hälfte der Spieler, die unter dem Durchschnitt sind, dass sie rausfliegen, damit es dann am Schluss einen Gewinner gibt.|  


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |  Spiel hat gestartet, Spieler ist im Auswahlsmenü | Spieler wählt Charakter   |  Mann wird weiter zur Auswahl gesendet |
| 1.2  |  Auswahlmenü            | Spieler begutachtet die Statistiken der Charaktere        |  Spieler hat den passenden Charakter ausgewählt |
| 2.1  | Spieler hat Charakter ausgewählt und kann jetzt sein Fahrzeug auswählen | Spieler drückt beim Menü auf auswählen und wählt sein Fahrzeug aus.  |Das Rennen startet|
| 2.2  | Spieler sieht die Stats der Fahrzeuge|Spieler wählt Fahrzeug aus|Wird ins Spiel geschickt|
| 3.1 |Spieler hat Charakter und Fahrzeug ausgewählt|Startet das Spiel|Rennen beginnt|
| 3.2 |Rennen hat begonnen|Spieler gibt Inputs|Auto bewegt sich|
| 4.1 | Autorennen vorbei | 1 zufällige Strecke wird ausgewählt | Strecke wird geladen
| 4.2 | Strecke wurde geladen | - | Spieler spawnen auf einer Plattform
| 4.3 |  Rennen hat gestartet | - | Alle Hindernisse bewegen sich
| 4.4 | Rennen hat gestartet | - | AI nimmt oft, aber nicht immer den richtigen Weg
| 4.5 | Spieler bewegen sich | landen auf Plattform | bleiben auf der Plattform
| 4.6 | Spieler bewegen sich | Hindernis trifft sie | fallen runter
| 5.1 |Platformer ist vorbei|-|Final Spiel startet |
| 6.1 | Platformer vorbei | - | Map wird geladen |
| 6.2 | Map eingeladen | - | Spieler werden eingespawnt |
| 6.3 |  Spieler wurden eingespawnt | - | Kampf startet |
| 6.4 | Kampf hat gestartet | Spieler schlagt gegner | AI verliert leben |
| 6.5 | Spieler wurde geschlagen | - | Spieler verliert leben |
| 6.6 | AI ha fast kein leben mehr | Spieler schlagt AI | AI fällt um |
| 6.7 | Spieler hat gewonnen | - | Winscreen |
| 7.1 |Das Spiel ist vorbei | -| Der Gewinner sieht man beim Victory Screen| 
| 8.1 |User ist im Spiel |Drückt einen Knopf |Charakter macht einen Tanz |
| 9.1 | User hat ein Spiel beendet|- |Erhält eine Währung |
| 12.1 |Ein Level wurde beendet|-|Die Hälfte der Leute die unter dem Durschnitt sind fliegen raus.|

### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/111044215/220884451-ef174a16-bc8f-478c-9ecb-6e63aaeb1b4e.png)
![image](https://user-images.githubusercontent.com/111044215/220884507-5a6fd6b7-0d04-4fcd-bae3-4229723a6579.png)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 09.03 | Mirhan | Menü wird erstellt | 75 Minuten |
| 1.B | 09.03 | Mirhan | Charaktere werden eingefügt | 65 Minuten |
| 1.B | 16.03 | Mirhan | Charaktere haben eigene Stats, die man sehen kann | 45 Minuten|
| 2.A | 16.03 | Mirhan | Fahrzeuge sind auch auf dem Menü zusehen | 45 Minuten |
| 2.B | 16.03 | Mirhan | Auf dem Menü sind Stats der Fahrzeuge zu sehen | 45 Minuten |
| 3.A | 9.03. | Jan Frey | Das Auto kann Fahren | 135min |
| 3.B | 9.03. | Jan Frey | Das Auto hat realistische Physics | 90min |
|3.C||16.03|Jan Frey|Die Map ist ertsellt|100Min|
| 3.D | 16.03. | Jan Frey | Spieler kann in Auto ein und Aussteiugen | 45min |
| 3.E | 16.03. | Jan Frey | Verschiedene Autos mit verschiedenen Stats | 90min |
| 4.A | 23.03. | Nicola | Random Map Selector | 45min |
| 4.B | 09.03. | Nicola | Plattformer Maps | 135min |
| 4.C | 16.03. | Nicola |  Bewegende Hindernisse | 135min |
| 4.D | 23.03. | Nicola | Nicht konsistente AI | 135min |
| 4.E | 09.03. | Nicola | Lande Physik | 65min |
| 4.F | 16.03. | Nicola | Hitbox Physik | 70min |
| 6.A | 02.03 | Benas | Charakter Importieren und Bewegung implementieren | 20 min | 
| 6.B | 02.03 | Benas | Charakter Animationen | 45min |
| 6.C | 02.03 | Benas | Charakter Animationen verlängert, springen | 25min |
| 6.D | 09.03 | Benas | Mini GUI implementation | 45min |
| 6.E | 09.03 | Benas | AI erstellen und modell fertigstellen | 90min |
| 6.F | 09.03 | Benas | AI intelligentes Laufen implementieren | 45min |
| 6.G | 16.03 | Benas | Verschiedene attacken implementieren | 45min |
| 6.H | 16.03 | Benas | Animationen zu attacken implementieren | 45min |
| 6.I | 16.03 | Benas | AI verschiedene attackenwahl | 45min |
| 6.J | 23.03 | Benas | Level design | 90min |
| 6.K | 23.03 | Benas | Fertigmachen | 45min |
| 7.A | 23.03. | Mirhan | Der VictoryScreen muss angezeigt werden | 90 Minuten |
| 12.A | 23.03 | Mirhan | Der Durchschnitt der Spieler die unter dem Durchschnitt liegen fliegen raus | 60 Minuten |
| 0.A | 23.03. | Alle | Projekte zusammenfügen | 90min |
| 0.B | 30.03. | Nicola | Powerpoint | 45min |

## 3 Entscheiden


Wir haben grösstenteils das gemacht, was wir vor hatten. Wir hatten uns sehr viel vorgenommen und ein paar Sachen haben wir nicht so gut hingekriegt wie wir es wollten. Manche mussten wir auch weg lassen, da wir zu wenig Zeit hatten, um es auch noch hinzu zufügen und andere waren auch nicht nötig, da sie schon in der Software vorhanden waren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 09.03 |  Mirhan  | 75 minuten      |   100 minuten  |
|1. B  | 09.03 |  Mirhan  | 65 minuten      |   90 minuten  |
| 4.B  | 09.03 |  Nicola  | 135 minuten     |   135 minuten |
| 4.C  | 09.03 |  Nicola  | 135 minuten     |   90 minuten  |
| 4.B  | 16.03 |  Nicola  | 135 minuten     |   45 minuten  |
| 4.C  | 16.03 |  Nicola  | 135 minuten     |   135 minuten |
| 4.C  | 23.03 |  Nicola  | 135 minuten     |   90 minuten  |
| abc  | 29.03 |  Nicola  | 45 minuten      |   45 minuten  |
| 4.A  | 16.03 |  -  | 45 minuten | - |
| 4.E  | 16.03 |  -  | 65 minuten | - |
| 4.F  | 16.03 |  -  | 70 minuten | - |
|3.A|16.03|Jan Frey|135|210 min |
|3.B|09.03|Jan Frey|90 min|200 min|
|3.C|23.03|Jan Frey|100 min|300 min|
|6.A|02.03|Benas|20min|45min|
|6.B|02.03|Benas|45min|45min|
|6.C|02.03|Benas|25min|10min|
|6.D|09.03|Benas|45min|45min|
|6.E|09.03|Benas|90min|135min|
|6.F|09.03|Benas|45min|45min|
|6.G|16.03|Benas|45min|45min|
|6.H|16.03|Benas|45min|60min|
|6.I|16.03|Benas|45min|90min|

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
