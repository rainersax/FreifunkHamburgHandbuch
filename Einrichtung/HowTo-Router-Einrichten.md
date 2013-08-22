# Freifunk Hamburg Router einrichten
### Schritt für Schritt Anleitung

## Einleitung
Das Einrichten des Routers ist ganz einfach und Du benötigst keine technischen Kenntnisse. Wenn du dieser Anleitung folgst kann eigentlich nichts schiefgehen.

Diese Anleitung erklärt Schritt für Schritt wie's geht. Wenn du fertig bist ist läuft das Freifunk WLAN und ist für Alle in der Nähe als offenes WLAN mit der SSID "hamburg.freifunk.net" zu sehen.

Dein Router sollte das Freifunk Betriebssystem bereits installiert haben. Ob das so ist, erfährst du von dem Freifunker, von dem du das Gerät bekommen hast.
Wenn dein Router noch nicht das Freifunk-Betriebssystem installiert hat, findest du hier eine Schritt für Schritt Anleitung.

## Router einrichten

### 1. Freifunk-Router mit dem Computer verbinden
![Dein Router](./img/dein_router.png "Das ist dein Router")

Bitte schließe deinen Router (1) (Die Antenne (2) kannst du jetzt oder auch später aufschrauben.) an eine Steckdose an - Das Kabel dazu ist dabei (3). Verbinde dann den Router mit dem beiliegenden grauen LAN-Kabel (4) mit Deinem Computer. 

Stecke dafür das Kabel in eine der gelben Buchsen (die blaue brauchst du später).
![Gelbe Buchse](./img/gelbe_buchse.png "Steck deinen Router für die Einrichtung hier ein")

### 2. Konfiguration starten
Jetzt kannst du den Router einfach über den Browser konfigurieren. 

Dazu rufst du in deinen Browser folgende Adresse auf: __<http://192.168.1.1>__

Dein Browserfenster müsste nun so aussehen – Folge hier dem Link "Knoten neu einrichten". Er führt dich durch die Schritte des Einrichtungsprozesses:
![Start](./img/start.png "So geht's los")

### 3. Passwort vergeben
Als erstes legst du ein Passwort fest.

*TODO: Wann brauch ich das Password wieder? Muss das erklärt werden?*

![Passwort](./img/password.png "Nimm ein gutes Passwort")

Tipp: Du kommst jederzeit durch Drücken der QSS-Taste wieder in meinen Configmode und kannst Einstellungen ändern.

*TODO: Wo soll das hin? Das scheint die falsche Stelle zu sein*

### 4. Namen vergeben
Als nächstes musst du deinem Router einen Namen geben.

*TODO: Empfehlungen zum Namen. Brauchen wir überhaupt eine*

*TODO: Warum? Wo wird der denn benötigt?*

![Name](./img/name_start.png "Such dir einen Namen aus")

### 5. Optionen 
Im nächsten Schritt kannst du noch zwei Optionen zur Funktionsweise deines Routers festlegen. Dies sind:

![](./img/mesh_start.png "")

#### 1. Mesh
Damit dein Router sich mit anderen Routern in der Umgebung verbinden kann (meshing), musst du diesen Haken setzen. Wir empfehlen dies zu tun – daher kommt ja schließlich die Magie von Freifunk.

![](./img/mesh_select.png "")

#### 2. Bandbreitenbegrenzung
Wenn du einen einen einen einigermaßen normalen Internet-Anschluss hast, brauchst du die Begrenzung nicht aktivieren. Dein Router wird im alltäglichen Betrieb nicht mehr als 6MBit/s benutzen. Unsere Empfehlung ist deshalb die Begrenzung nicht zu ativieren.

### 6. Dein Schlüssel
Klick wieder auf weiter und nun bekommst Du einen Schlüssel:

![VPN Schlüssel](./img/key.png "Der VPN Schlüssel deines Routers")

Diesen Schlüssel musst Du dir aufschreiben! Du kannst ihn zusätzlich in die Zwischenablage kopieren – du brauchst ihn später zur Registrierung deines Routers auf der Freifunk Knoten-Karte, aber dazu später mehr.

### 7. Abschließen und Einstellungen speichern
Dein Router ist nun fast fertig eingerichtet. Klick nur noch einmal auf weiter. Damit die Einstellungen gespeichert werden, musst du den Router neu starten. Klick dazu einfach auf „Jetzt Neustarten“

![](./img/restart.png "")

Nach dem Neustart sieht dein Browserscreen so aus. Obwohl es aussieht wie eine Fehlermeldung, ist es genau wie es sein soll.

![](./img/reboot_comment.png "")

### 8. Router anschließen
Nun kannst du den Router ans Internet anschließen. Dazu musst du  das WLAN-Kabel auf der Rückseite deines Routers umstecken: Bisher hattest du das Kabel in der gelben Buchse. Jetzt muss es in die blaue. Verbinde dann noch das Kabel mit deinem bestehenden Router und dein neuer Freifunk Router ist am Netz. 

![Blaue Buchse](./img/blaue_buchse.png "Steck deinen Router hier für den laufenden Betrieb ein")

Alternativ kannst du deinen Router auch nur zum Meshing verwenden. Dazu muss allerdings mindestens ein anderer Freifunk-Router in WLAN-Reichweite sein und du musst die entsprechende Option unter 5.1 gewählt haben. Wenn einer der Router in dem Mesh-Netzwerk eine Internet-Verbindung hat, wird diese mit deinem Router geteilt. Das ist gut, aber wir empfehlen trotzdem den Freifunk Router an deinen Router anzuschließen, wenn dir das möglich ist. Nur so teilst du deine Bandbreite mit anderen.

## Router im Netz registrieren
Nun musst Du mich über dieses Formular mit dem Freifunk-Netz bekannt machen:
_<http://freifunk-gw01.hamburg.ccc.de:8080/>_
![](./img/knoten_comment.png "")

Hier trägst Du nun meinen Namen, meinen Schlüssel, meine MAC-Adresse (steht unten auf meinem Gehäuse), Deinen Namen und eine E-Mail-Adresse. 

### 1. Name angeben
Gib hier noch einmal den Namen deines Routers an. Unter diesem Namen wird dein Router später auf der Freifunk Kontenkarte zu sehen sein. 

Bitte achte darauf, dass keine Leerzeichen im Namen erlaubt sind. Wenn du ein Leerzeichen brauchst, verwende einfach einen Unterstrich "_"

### 2. VPN Schlüssel
Trage hier den VPN Schlüssel ein, den du vorhin während der Einrichtung bekommen hast (s.o. Schritt 6)

### 3. MAC-Adresse angeben
Als nächstes brauchst du die MAC-Adresse deines Routers. Sie steht auf der Rückseite deines Routers. Die MAC-Adresse ist eine eindeutige Identifikationsnummer deines Routers.

![MAC-Adresse](./img/router_rueckseite_MAC.png "Die MAC-Adresse auf der Rückseite")

### 4. Kontakt – Nickname / Name
klar, oder?

*TODO: Wo taucht das überhaupt auf?*


### 5. Kontakt – E-Mail Adresse
…

*TODO: Wo taucht das überhaupt auf? Wo wird das benutzt?*

### 6. Koordinaten des Knotens
Wenn du den Standort deines Routers hier einträgst ist er auf der Karte der Zugangspunkte zu sehen – so können alle feststellen, wo überall Freifunk verfügbar ist. Diese Angabe ist freiwillig. Wir empfehlen aber sehr diese Angabe zu machen. 

Um den Standort deines anzugeben, musst du dessen Geo-Koordinaten hier eintragen. Der einfachste Weg diese Koordinaten zu bestimmen ist über die Karte der Freifunk Zugangspunkte. Die findest du hier: __http://hamburg.freifunk.net/?page_id=16__

Dein Browserfenster sollte dann ungefähr so aussehen.
![](./img/karte1.png "")

Zoome nun am Besten zu dem Standort an dem du den Router aufstellen willst. Klicke dann auf den Button „Koordinaten beim nächsten Klick zeigen“ (1) und dann dorthin wo du den Router aufstellen willst (2).
![](./img/karte2_getcoordinates.png "")

In dem kleinen Fenster sind nun die Koordinaten des Standorts angegeben, auf den du gerade geklickt hast. Die Koordinaten kannst nun über die Zwischenablage in das Formularfeld kopieren.
![](./img/karte2_confirm.png "")

## Formular Abschicken
Wenn du das Formular fertig ausgefüllt hast, einfach abschicken. Wenn Alles geklappt hat müsste dein Browserfenster ungefähr so aussehen. Damit ist die Registrierung abgeschlossen und du kannst deinen Router nun in Betrieb nehmen.
![](./img/fertig.png "")

Nach wenigen Minuten sollte der Router auf der Karte an der von dir angegebenen Position zu sehen sein. Wenn ein grüner Punkt angezeigt wird, ist Alles in Ordnung und dein Router ist am Netz. Wenn zusätzlich noch eine Verbindungslinie zu einem anderen Knoten zu sehen ist, dann mesht dein Router mit einem anderen.  
![](./img/karte_fertig.png "")

Jetzt hast du's geschafft. Klopf dir auf die Schultern, freu dich und verbreite die Botschaft von Freifunk weiter. 

## Fragen?
Solltest Du Fragen oder Probleme haben oder Einträge deines Knoten ändern wollen, schreibe gerne an 

__<kontakt@hamburg.freifunk.net>__!

## Noch ein wichtiger Hinweis zu Schluss 
Das Freifunk-Netz wird in die Niederlande getunnelt. Das kann bedeuten, dass dich Facebook, Googlemail, etc. warnen, du seist im Ausland. Erschrick nicht, obwohl in machen Warnungen von „Hackerangriffen“ etc. die Rede ist. Das ist ganz normal und es soll auch so sein, denn diese Maßnahme ist notwendig Als Schutz gegen die Störerhaftung.

[![Licence: Public Domain](http://creativecommons.org/images/deed/nolaw.png)](http://creativecommons.org/publicdomain/zero/1.0/)