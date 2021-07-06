# Hilfe

Eine ausführliche Hilfe zum Last Survivor Bot.
Wörter in <> diesen Klammern sind zwingend erforderlich, in [] diesen Klammern müssen nicht geschrieben werden.
Solltes du Wörter haben die aus mehreren Wörtern bestehen müssen diese in "" Anführungszeichen geschrieben werden.
Beispiel: Das Item `Stein` kann so geschrieben werden. Sollte es aber `schwerer Stein` sein muss dieses so geschrieben werden `"schwerer Stein"`

## Hilfe für Spieler

### Charakter `.char`

- `.char info` - Mit diesem Befehl kannst du dir Informationen wie Name, Kontostand und Aktivität zu deinen Charkateren anschauen.
- `.char select <Charaktername>` - Solltest du mehrere Charaktere kannst du hiermit bestimmen welcher dein aktiver ist. Von dem aktiven wir dann z.B. beim bezahlen Geld abgezogen. In der Info siehst du welcher Charakter aktiv ist. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.

### Geld `.money`

- `.money info` - Mit diesem Befehl kannst du dir Informationen wie Name, Kontostand und Aktivität zu deinen Charkateren anschauen.
- `.money pay <Charaktername des Empfängers> <Geldmenge>` - Um einen anderen Charakter zu bezahlen kannst das mit diesem Befehl machen. Als erstes musst du den Charakter angeben an wen du zahlen willst und dann wie viel Geld. Das Geld wird von dem Konto von deinem aktiven Charakter abgezogen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.

### Looting `.loot`

- `.loot [Ort]` - Um nach Items zu suchen musst du diesen Befehl eingeben. Wenn kein Ort angegeben wird, wird allgemein gesucht und alle Items gefunden werden. Wenn ein Ort angegeben wurde, wird speziell Items für diesen Ort gefunden. Mögliche Orte müssen irgendwo auf dem Discord stehen.

### Inventar `.inv`

- `.inv show [Sortierung]` - Mit diesem Befehl kannst du dir in deinem Inventar anzeigen welche Items du wie oft hast. Ohne Sortierung werden die Items in der Reihenfolge angezeigt wie du sie gefunden hast. Du kannst aber auch nach `name` oder `anzahl` sortieren.

### Items `.item`

- `.item use <Itemname> [Anzahl]` - Benutze im RP ein Item oder wird einfach ein paar Items weg. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item use "Stein" 4`
- `.item trade <Charaktername> <Itemname> [Anzahl]` - Um einem anderen Charakter ein Item zu geben kannst du diesen Befehl nutzen. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item trade Fabiii "Stein" 4`

### Crafting `.craft`

- `.craft <Itemname>` - Mit diesem Befehl kannst du aus Items die du in deinem Inventar hast ein neues Item herstellen. Bsp.: `. craft "Tür"`
- `.craft show` - Hier kannst du eine Liste sehen aller möglichen Items sehen die hergestellt werden.

### Handeln mit Händler `.trade`

- `.trade show` - Hier werden die Angebote vom Händler angezeigt. Es gibt eine Kategorie für den Verkauf und eine für den Ankauf.
- `.trade buy <Itemname>` - Mit diesem Befehl kauft man ein Item von dem Händler. Du musst dafür sorgen, dass du genug Geld auf dem Konto hast. Es kann immer nur ein Item aufeinmal gekauft werden.
- `.trade sell <Itemname>` - Mit diesem Befehl kannst du ein Item aus deinem Inventar an den Händler verkaufen. Es kann immer nur ein Item aufeinmal verkauft werden.

## Hilfe für das Team

### Charakter `.char`

- `.char new <Name> <getaggter Spieler>` - Um einem Spieler einen neuen Charakter zu erstellen benutzt du diesen Befehl. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.char new Fabiii @itsFabiii`
- `.char kill <Charaktername>` - Falls ein Charakter stirbt oder nicht mehr gespielt wird kann er mit diesem Befehl gelöscht werden. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.char kill Fabiii`
- `.char show <getaggter Spieler>` - Um die Charaktere eines Spieler zu sehen kannst du das mit diesem Charakter machen. Bsp.: `.char show @itsFabiii`

### Geld `.money`

- `.money give <Charaktername> <Geldmenge>` - Füge einem Charakter diese Geldmenge zu seinem aktuellen Kontostand hinzu. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.money give Fabiii 1000`
- `.money set <Charaktername> <Geldmenge>` - Setzte den Kontostand auf die angegebene Geldmenge. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.money set Fabiii 5000` 

### Items `.item`

- `.item new <Name> <Wahrscheinlichkeit>` - Um ein neues Item anzulegen kannst du das mit diesem Befehl machen. Itemnamen sind einmalig und dürfen nich mehrmals vorkommen. Die Wahrscheinlichkeit gibt an wie wahrscheinlich es ist dieses Item zu finden. Die Wahrscheinlichkeit pro Item ist auf 100 limitiert. Bsp.: `.items new Messer 5`
- `.item delete <Name>` - Es können über diesem Befehl Items wieder komplett aus dem System gelöscht werden. Vorsicht es werden logischerweise auch aus allen Items gelöscht. Ein weiter Hinweis kommt nicht. Bsp.: `.items delete Messer`
- `.item show [Sortierung]` - Hier können alle Items mit Wahrscheinlichkeit angezeigt werden die bereits exestieren. Ohne Sortierung werden die Items in der Reihenfolge angezeigt wie sie erstellt wurden. Mit `name` oder `prozent` kann man alphabetisch nach dem Namen oder aufsteigend nach der Wahrscheinlichkeit sortieren.
- `.item name <aktueller Name> <neuer Name>` - Mit diesem Befehl kann man ein Item ganz einfach umbennen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.
- `.item chance <Name> <neue Wahrscheinlichkeit>` - Mit diesem Befehl kann die Wahrscheinlichkeit eines Items geändert werden. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.
- `.item give <Charaktername> <Item> [Anzahl]` - Wenn man einem Charakter eine Item geben möchte. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item give Fabiii "Stein" 10`
- `.item take <Charaktername> <Item> [Anzahl]` - Wenn man einem Charakter eine Item wegnehmen möchte. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item remove Fabiii "Stein" 4`
- `.item search <Name>` - Mit diesem Befehl kann nach Items gesucht werden. Sollte man nicht den genauen Namen kennen so können Wildcarts benutzt werden. `%` um nach beliebigen anderen Buchstaben oder Wörtern zu suchen. Bsp.: `.item search "%Stein%"` (Um das Ergebniss zu sehen probiere es einfach aus :D)

### Crafting `.craft`

- `.craft new <Herstellbares Item> <Benötigtes Item> <Anzahl>` - Darüber können Rezepte zu Items hinzugefügt werden. Bsp.: `. craft new "Tür" "Holz" 4`
- `.craft remove <Herstellbares Item>` - Hier wird bei einem Rezept ein Item enfernt. Bsp.: `. craft remove "Tür"`

### Location `.loc`

- `.loc show [Ortsname]` - Ohne Ortsname wird eine Übersicht alle verfügbaren Orte angezeigt. Wenn ein Ort angegeben wird, wird eine Liste angezeigt aller Items die an diesem Ort gefunden werden können.
- `.loc new <Ortsname>` - Damit kann ein neuer Ort hinzugefügt werden Bsp.: `.loc new Polizei`
- `.loc rename <alter Name> <neuer Name>` - Damit kann ein bereits erstellter Ort umbennant werden. Bsp.: `.loc rename Polizei Polizeistation`
- `.loc delete <Ortsname>` - Damit kann ein neuer Ort wieder werden Bsp.: `.loc delete Polizei`
- `-loc additem <Ortsname> <Itemname> <Wahrscheinlichkeit>` - Wenn ein Ort erstellt wurde kann man mit diesem Befehl Items hinzugefügt werden, die an diesem Ort gefunden werden können. Es wird immer nur gefunden was über diesen Befehl hinzugefügt wurde. Bsp.: `.craft additem Polizei AK-47 20`
- `-loc additem <Ortsname> <Itemname>` - Damit kann ein Item wieder von einem Ort entfernt werden. So kann es nicht mehr an dem Ort gefunden werden. Bsp.: `.craft additem Polizei AK-47`

### Handeln mit Händler `.trade`

- `.tade additem <Itemname> <Anzahl> <Verkaufspreis> <Ankaufspreis>` - Mit diesem Befehl kann ein Item zum Händler hinzugefügt werden. Die Anzahl gibt an wie oft der Händler das Item verkauft. Der Verkaufspreis gibt an für wie viel Geld das Item verkauft wird. Wenn die Anzahl und der Verkaufspreis 0 ist wird das Item nur angekauft. Der Ankaufspreis gibt an für wie viel das Item angekauft wird. Wenn der Ankaufspreis 0 ist wird das Item nur verkauft.
- `.trade removeitem <Itemname>` - Mit diesem Befehl wird das Item aus dem Angebot des Händlers herausgenommen.
- `.trade list` - Hier werden die Angebote vom Händler angezeigt. Es gibt eine Kategorie für den Verkauf und eine für den Ankauf. Dieser Befehl funktionier auch wenn der Show Befehl der User deaktiviert wird.
-  `. trade enable` / `.trade disable` - Dieser Befehl aktiviert bzw. deaktiviert den Shop im Bot. Es werden die Befehle `.trade show`, `.trade buy` und `trade sell` aktiviert bzw. deaktivert.

# Changelog

Alle bemerkenswerten Änderungen an diesem Projekt werden in dieser Datei dokumentiert.


# Released

## 1.0.1 [06.07.2021]

### Added

#### Orte `.loc`
Ein Befehl zum umbennenen von Orten wurde hinzugefüht.

### Changed

#### Items `.item`
Ein paar Fehler in den Antwortnachrichten wurden behoben.

## 1.0.0 [02.07.2021]

### Added

#### Crafting `.craft`
Es können jetzt Items hergestellt werden, die z.B. nicht gefunden werden können. Damit können Items in den Inventaren sinnvoller benutzt werden.

#### Orte `.loc`
Admins können hier neue Orte hinzugefügen und Items zu diesen hinzufügen die an diesem Ort gefunden werden können.

#### Items `.item`
Es wurde nun endlich ein Befehl hinzugefügt mit dem Items wieder gelöscht werden können.

### Changed

#### Looting `.loot`
Das Lootingsystem wurde aktualisiert. Es kann nun an bestimmten Orten, die eingerichtet wurden, gesucht werden. Dies gibt die Möglichkeit bestimmte Items basierend auf Orte gefunden werde. So ist die Wahrscheinlichkeit höher, dass kein Müll gefunden werden.

#### Inventar `.inv`
Der Befehl `.inventory` wurde aus Einfacheit in `.inv` umbenannt.

#### Geld `.money`
Der Befehl `.money show` wurde in `.money info` umbennant.

#### Hilfe `.help`
Die HIlfe wurde aktualisiert und sieht nun schöner aus.

#### Backend
Der Techniker wird nun bei Fehlern mit der Datenbank benachrichtigt.


## 0.3.0 [12.06.2021]

### Changed

#### Item `.item`
Das Team kann jetzt nach Items suchen um nicht mehr die ganze Liste nach einem bestimmten Item zu durchsuchen.

#### Backend
Der Bot irgnoriert jetzt Nachrichten von anderen Bots.

## 0.2.0 [10.06.2021]

### Added

#### Item `.item`
Nun können Spieler Items benutzen oder wegwerfen und Items mit anderen Spielern tauschen. Das Team kann nun Charakteren Items geben oder auch wegnehmen.

### Changed

#### Items `.items`
Der Befehl wurde von `.items` in `.item` umbenannt.

#### Looting `.loot`
Der Befehl kann jetzt nur noch 10 mal pro Stunde verwendet werden.

#### Hilfe
Dem Hilfetext wurde der Link zu dieser Seite hinzugefügt.

#### Backend
Das Bild, wenn jemand den Server betritt, wurde aktualisiert, dass der Text nun in 2 Zeilen steht. Damit bei langen Namen nichts abgeschnitten wird.

## 0.1.0 [07.06.2021]

### Added

#### Charakter `.char`
Ein Befehl mit dem vom Team neue Charaktere erstellt werden können, aber auch bestehende "getötet" werden können.
User können darüber Informatioen über ihre Charaktere sehen oder bei mehreren den aktiven Charakter wechseln.

#### Geld `.money`
Befehl mit dem andere Charaktere bezahlt werden können. Als Spieler bekommt man auch hier die Information über seine Charaktere.
Das Team kann Geld der Spieler bearbeiten oder ihnen neues Geld geben.

#### Looting `.loot`
Befehl mit dem momentan überall nach einem Zufallsprinzip gelootet werden kann.

#### Inventar `.inventory`
Über diesen Befehl können die Items die gelootet wurden eingesehen werden.

#### Items `.items`
Dieser Befehl ermögtlich dem Team vorhanden Iteams anzuschauen oder zu bearbeiten. Damit können aber auch neue Items hinzugefügt werden.

#### Hilfe
Eine Hilfe zu allen Befehlen.

#### Backend
Im Hintergrund werden Daten gesammelt für ein zukünftiges Levelsystem und die Aktivität.
Ein User wird beim betreten des Servers begrüßt und beim verlassen verabschiedet.
Daten und Charaktere werden beim verlassen gelöscht.


# Unreleased

## 2.0.0 [kein Datum]

#### Allgemein
Mit hoher Wahrscheinlichkeit werden `/` Befehle eingeführt. Diese vereinfachen deutlich den Gebrauch der Befehle.

#### Level UP System
Funktion bei der man für sein Charakter Erfahrung sammeln kann um verbesserungen für Befehle zu bekommen.

#### Webpage
Eine Webseite über die Infos zu Charakteren und Inventaren angezeigt werden soll.
Teammember können hier dann auch Items besser einsehen und bearbeiten und andere Info erhalten.

#### Backend
Die Art und Weise wie der Bot mit der Datenbank kommuniziert soll verändert werden.
Texte werden sollen in einer extra Datei gespeichert werden, damit diese leichter zu ändern sind.


