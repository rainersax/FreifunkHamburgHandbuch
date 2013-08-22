#  Freifunk Hamburg Router Firmware einspielen
### Schnell–Anleitung


![](./img/TP_link_firmware_confirm.png "")
![](./img/TP_link_firmware_file.png "")
![](./img/TP_link_firmware.png "")
![](./img/TP_link_start.png "")
![](./img/TP_link_upgrade_progress.png "")

## Einleitung
Das Einrichten des Routers ist ganz einfach und Du benötigst keine technischen Kenntnisse. Wenn du dieser Anleitung folgst kann eigentlich nichts schiefgehen.

Diese Anleitung erklärt Schritt für Schritt wie's geht. Wenn du fertig bist ist läuft das Freifunk WLAN und kann von Allen unter 
hamburg.freifunk.net erreicht werden.

Dein Router sollte das Freifunk Betriebssystem bereits installiert haben. Ob das so ist, erfährst du von dem Freifunker, von dem du das Gerät bekommen hast.
Wenn dein Router noch nicht das Freifunk-Betriebssystem installiert hat, findest du hier die Anleitung wie du es installierst.

## Router anschließen
### 1. Freifunk-Router mit dem Computer verbinden
Bitte schließe deinen Router an eine Stekckdose an - Das Kabel dazu ist dabei. Verbinde dann den Router mit dem beiliegenden grauen LAN-Kabel mit Deinem Computer. Stecke dafür das Kabel in eine der gelben Buchsen (die blaue brauchst du später). Vergiss nicht den Router einzuschalten.
TODO Bild einfügen.

### 2. Konfiguration starten
Jetzt kannst du den Router einfach über den Browser konfigurieren. Dazu rufst du in deinen Browser folgende Adresse auf: 
<http://192.168.1.0>

Als erstes wirst du nach Username und Password gefragt - ab Werk ist das "admin" und "admin". 
Nach dem Login müsste das Browserfenster nun so aussehen:
TODO Bild einfügen

Folge hier dem Link "Knoten neu einrichten". Er führt dich durch die Schritte des Einrichtungsprozesses.

### 3. Passwort vergeben
Als erstes legst du ein Passwort fest.
TODO: Wann brauch ich das? 

![Passwort](./password.jpg "Nimm ein gutes Passwort")

### 4. Namen vergeben
ALs nächstes musst du deinem Router einen Namen geben.
TODO: Warum? Wo eird der denn benötigt?
![Name](./name.jpg "Such dir einen Namen aus")

Nimm am Besten einen Namen, der …
TODO: Empfehlungen zum Namen
TODO: Entscheiden ob das weg kann
	Wichtig: Du kommst jederzeit durch Drücken der QSS-Taste wieder in meinen Configmode und kannst Einstellungen ändern.

### 5. Optionen 
#### Mesh
#### Bandbreitenbegrenzung
Wenn du einen einen einen einigermaßen normalen Internetanschluss hast, brauchst du die Begrenzung nicht aktivieren.

### 6. Dein Schlüssel
Nun bekommst Du einen Schlüssel:
![Schlüssel](./schluessel.jpg)
Diesen Schlüssel musst Du dir aufschreiben! Du kannst ihn zusätzlich in die Zwischenablage kopieren!

### 7. Abschließen und Einstellungen speichern
Noch einmal auf Weiter und auf „Jetzt Neustarten“ und ich starte neu und bin fast bereit...




Wichtig: Wenn ich keine anderen Freifunk-Knoten sehe, kann ich nicht „meshen“ und das Freifunk-Netz vergrößern. Ich brauche in diesem Fall eine Internetverbindung um ein Teil des Freifunk-Netzes zu werden – Bitte schließe mich mit einem Lankabel an Deinen Heimrouter an - 
Wichtig: benutze dafür nur meine blaue Buchse und NICHT eine meiner gelben Buchsen!

## Router im Netz registrieren
Nun musst Du mich über dieses Formular mit dem Freifunk-Netz bekannt machen:
<http://freifunk-gw01.hamburg.ccc.de:8080/>
![Registrieren](./foemular.jpg)


Hier trägst Du nun meinen Namen, meinen Schlüssel, meine MAC-Adresse (steht unten auf meinem Gehäuse), Deinen Namen und eine E-Mail-Adresse. Außerdem kannst Du meinen Standort eintragen – so kann man mich leichter finden :-) 

Unter http://freifunk-gw01.hamburg.ccc.de/ffhhmap/geomap.html, mit der Option „Koordinaten beim nächsten Klick zeigen“ findest Du die Koordinaten meines zukünftigen Standortes.
Dann kannst Du mich eintragen und ich werde ein Teil des Netzes – habe ein bisschen Geduld,
es kann manchmal ein bisschen dauern.

## Fertig!

Nach wenigen Minuten sollte der Router auf der Karte an der von dir angegebenen Position zu sehen sein. Wenn ein grüner 

Solltest Du Fragen oder Probleme haben oder Einträge deines Knoten ändern wollen,
schreibe gerne an <kontakt@hamburg.freifunk.net>!

Ein wichtiger Hinweis: Als Schutz gegen die Störerhaftung wird das Freifunk-Netz in die Niederlande getunnelt. Das kann bedeuten, dass Dich Facebook, Googlemail, etc. warnen, Du seist im Ausland.

Erschrick bitte nicht – in machen Warnungen ist von „Hackerangriffen“ etc. die Rede.  

[![Licence: Public Domain](http://creativecommons.org/images/deed/nolaw.png)](http://creativecommons.org/publicdomain/zero/1.0/)