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

- `.money show` - Mit diesem Befehl kannst du dir Informationen wie Name, Kontostand und Aktivität zu deinen Charkateren anschauen.
- `.money pay <Charaktername des Empfängers> <Geldmenge>` - Um einen anderen Charakter zu bezahlen kannst das mit diesem Befehl machen. Als erstes musst du den Charakter angeben an wen du zahlen willst und dann wie viel Geld. Das Geld wird von dem Konto von deinem aktiven Charakter abgezogen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.

### Looting `.loot`

- `.loot` - Um nach Items zu suchen musst du diesen Befehl eingeben. Du findest dann zufällig ein Item in deiner Umgebung. Du kannst nur 10 mal pro Stunde den Befehl nutzen.

### Inventar `.inventory`

- `.inventory show [Sortierung]` - Mit diesem Befehl kannst du dir in deinem Inventar anzeigen welche Items du wie oft hast. Ohne Sortierung werden die Items in der Reihenfolge angezeigt wie du sie gefunden hast. Du kannst aber auch nach `name` oder `anzahl` sortieren.

### Items `.item`

- `.item use <Itemname> [Anzahl]` - Benutze im RP ein Item oder wird einfach ein paar Items weg. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item use "Stein" 4`
- `.item trade <Charaktername> <Itemname> [Anzahl]` - Um einem anderen Charakter ein Item zu geben kannst du diesen Befehl nutzen. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item trade Fabiii "Stein" 4`

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
- `.item show [Sortierung]` - Hier können alle Items mit Wahrscheinlichkeit angezeigt werden die bereits exestieren. Ohne Sortierung werden die Items in der Reihenfolge angezeigt wie sie erstellt wurden. Mit `name` oder `prozent` kann man alphabetisch nach dem Namen oder aufsteigend nach der Wahrscheinlichkeit sortieren.
- `.item name <aktueller Name> <neuer Name>` - Mit diesem Befehl kann man ein Item ganz einfach umbennen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.
- `.item prozent <Name> <neue Wahrscheinlichkeit>` - Mit diesem Befehl kann die Wahrscheinlichkeit eines Items geändert werden. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt.
- `.item give <Charaktername> <Item> [Anzahl]` - Wenn man einem Charakter eine Item geben möchte. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item give Fabiii "Stein" 10`
- `.item remove <Charaktername> <Item> [Anzahl]` - Wenn man einem Charakter eine Item wegnehmen möchte. Wenn keine Anzahl angegeben wird, wird einfach 1. Item genommen. Auf Anführungszeichen achten wenn es sich um mehrere Wörter im Namen handelt. Bsp.: `.item remove Fabiii "Stein" 4`
- `.item search <Itemname>` - Mit diesem Befehl kann nach Items gesucht werden. Sollte man nicht den genauen Namen kennen so können Wildcarts benutzt werden. `%` um nach beliebigen anderen Buchstaben oder Wörtern zu suchen. Bsp.: `.item search "%Stein%"` (Um das Ergebniss zu sehen probiere es einfach aus :D)

# Changelog

Alle bemerkenswerten Änderungen an diesem Projekt werden in dieser Datei dokumentiert.


# Released

## 0.3.0[12.06.2021]

#### Item `.item`
Das Team kann jetzt nach Items suchen um nicht mehr die ganze Liste nach einem bestimmten Item zu durchsuchen.

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

## 1.0.0 [kein Datum]

#### Looting
Das Lootingsystem soll überarbeitet werden und abhänging von Orten sein. Zudem soll beim Looting eine Geschwindigkeit gewählt werden, bei dem abhäning der Zeit besseres Loot gefunden werden kann.
Auch sollen besondere Dropevents hinzugefügt werden, die vom Team gedroppt werden können.

#### Items
Ein Craftingsystem soll hinzugefügt werden mit dem aus einzelnen Items neue Items gebaut werden können.

#### Handelssystem
Ein System mit dem Spieler untereinander aber auch mit verschiedenen Händlern Items traden können.

#### Base Building
INFOS FOLGEN

#### Webpage
Eine Webseite über die Infos zu Charakteren und Inventaren angezeigt werden soll.


