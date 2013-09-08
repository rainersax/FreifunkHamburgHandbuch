![Freifunk.Hamburg.net](./img/Ffhh_logo-06.png)![Freifunk.Hamburg.net](./img/Schriftzug.png)

# Freifunk Hamburg Router einrichten

## Einleitung
Für die Einrichtung des Routers werden keine technischen Kenntnisse benötigt. Wenn du dieser Anleitung Schritt für Schritt folgst, kann eigentlich nichts schiefgehen. Wenn du fertig bist, läuft das Freifunk WLAN und ist für alle in der Nähe als offenes WLAN mit der SSID "hamburg.freifunk.net" zu sehen.

Dein Router sollte das Freifunk Betriebssystem bereits installiert haben. Ob das so ist, erfährst du von dem Freifunker, von dem du das Gerät bekommen hast.
Wenn dein Router noch nicht das Freifunk-Betriebssystem installiert hat, findest du [hier](http://hamburg.freifunk.net/?page_id=80#anleitungen) eine Schritt-für-Schritt-Anleitung.

## Router einrichten

### 1. Freifunk-Router mit dem Computer verbinden
![Dein Router](./img/dein_router.png "Das ist dein Router")

_Deinem Router (1) liegen mindestens eine Antenne (2), ein Steckernetzteil (3) und ein LAN-Kabel (4) bei._

Bitte schraube zuerst die Antenne(n) auf die Gewindestecker des Routers. Schließe danach den Router mit dem Steckernetzteil an eine Steckdose an. Verbinde dann den Router mit dem beiliegenden LAN-Kabel (4) mit Deinem Computer. Stecke es dabei am Router in eine gelbe Buchse.

![Gelbe Buchse](./img/gelbe_buchse.png "Steck deinen Router für die Einrichtung hier ein")

_Anmerkung: Derzeit unterstützt Freifunk Hamburg zwei unterschiedliche Router, den TL-WR741ND und den TL-WR842ND. Beide sind von TP-Link. Der oben abgebildete ist das kleinere Model und hat eine Antenne. Der andere hat ein wenig mehr Leistung und zwei Antennen. Die Einrichtung ist für beide gleich. Es ist also egal welchen du hast. Falls Du ein anderes Routermodel in den Händen hältst, wie z.B. den TL-WR841ND, kann es sein, dass Du das Kabel in die blaue Buchse stecken musst, um eine Verbindung zu bekommen._


### 2. Konfiguration starten
Jetzt kannst du den Router einfach über den Browser konfigurieren. 

Dazu rufst du in deinem Browser folgende Adresse auf: 

__<http://192.168.1.1>__

Dein Browserfenster müsste nun aussehen, wie im folgenden Bild. Folge dem Link "Knoten neu einrichten". Er führt dich durch die Schritte des Einrichtungsdialogs.
![Start](./img/start.png "So geht's los")

### 3. Passwort
Als erstes legst du ein Passwort fest.

![Passwort](./img/password.png "Nimm ein gutes Passwort")

Das Passwort brauchst du, um dich später wieder an deinem Router anzumelden. Dies ist beispielsweise nötig, wenn du das Freifunk-Betriebssystem (Firmware) auf dem Router aktualisieren willst. Schreib es dir also besser irgendwo auf.

### 4. Name
Als Nächstes musst du deinem Router einen Namen geben. Nimm einfach einen, der dir gefällt und der vielleicht ein wenig über den Standort des Routers aussagt. z.B. HumanistLab_0.
Bitte achte darauf, dass keine Leerzeichen im Namen erlaubt sind. Wenn du ein Leerzeichen brauchst, verwende einfach einen Unterstrich "_".

Dieser Name wird später noch einmal benötigt. Am besten öffnest du jetzt einen Texteditor und kopierst ihn dort hinein.

![Name](./img/name_start.png "Such dir einen Namen aus")

### 5. Optionen 
Im nächsten Schritt kannst du noch zwei Optionen zur Funktionsweise deines Routers festlegen. Diese sind:

![Options](./img/mesh_start.png "Lege die Optionen fest")

#### 1. Mesh-VPN
Setze diesen Haken, um eine verschlüsselte Verbindung über deinen Internet-Router zum Freifunk-Server herzustellen. Wir empfehlen, dies zu tun.
Der Freifunk-Server verbindet deinen Freifunk-Router mit dem Internet und dem Teil des Freifunk-Netzes, der nicht über WLAN erreicht wird.
Wenn diese Option nicht aktiviert wird, kann der Router nur mit den Routern kommunizieren, die er direkt oder indirekt per WLAN oder über andere Router mit aktivierter Option erreicht. Der Zugang zum Internet ist dann nur möglich, wenn mindestens bei einem der erreichbaren Router die Option aktiviert ist.

![Mesh](./img/mesh_select.png "strongly recommended")

#### 2. Bandbreitenbegrenzung
Wenn du einen normalen Internet-Anschluss hast, brauchst du die Begrenzung nicht zu aktivieren. Dein Router wird im alltäglichen Betrieb nicht allzuviel von deiner Bandbreite in Anspruch nehmen. Unsere Empfehlung ist deshalb, die Begrenzung nicht zu aktivieren.
Solltest du aber trotzdem eine Begrenzung eintragen wollen, setze den Haken "Banbreitenbegrenzung aktivieren?" und trage in die beiden Felder darunter die gewünschten Limits ein. Die Minimalwerte sind 1000 im oberen und 100 im unteren Feld.

### 6. Dein VPN-Schlüssel
Klick wieder auf weiter. Nun bekommst Du einen VPN-Schlüssel angezeigt, der später zur Registrierung deines Routers im Freifunk-Netz gebraucht wird. Kopier ihn am besten ebenfalls in den Texteditor.

![VPN Schlüssel](./img/key.png "Der VPN Schlüssel deines Routers")

### 7. Abschließen und Einstellungen speichern
Dein Router ist nun fast fertig eingerichtet. Klick noch einmal auf weiter. Klicke danach auf „Jetzt Neustarten“, um die Einstellungen zu speichern. Der Router startet daraufhin neu.

![restart](./img/restart.png "Starte neu")

Nach dem Neustart sieht dein Browserfenster aus, wie im folgenden Bild. Die angezeigte Fehlermeldung kannst du gefahrlos ignorieren.

![not an error](./img/reboot_comment.png "diese Meldung sagt: PRIMA!")

### 8. Router anschließen
Nun kannst du den Router ans Internet anschließen. Dazu musst du das LAN-Kabel auf der Rückseite deines Routers umstecken: Bisher hattest du das Kabel in der gelben Buchse. Jetzt muss es in die blaue. Verbinde dann noch das andere Ende des Kabels mit deinem Internet-Router und dein neuer Freifunk-Router ist am Netz.

![Blaue Buchse](./img/blaue_buchse.png "Steck deinen Router hier für den laufenden Betrieb ein")

Alternativ kannst du deinen Router auch nur zum Meshing verwenden. Dazu muss allerdings mindestens ein anderer Freifunk-Router in WLAN-Reichweite sein. Wenn einer der Router in dem Mesh-Netzwerk eine Internet-Verbindung hat, wird diese mit deinem Router geteilt. Das ist auch gut, aber wir empfehlen trotzdem den Freifunk-Router an deinen Internet-Router anzuschließen, wenn dir das möglich ist. Nur so teilst du deine Bandbreite mit anderen.

## Router im Netz registrieren
Nun musst du nur noch deinen Router über folgendes Formular im Freifunk-Netz anmelden:

__<http://freifunk-gw01.hamburg.ccc.de:8080/>__

Was die einzelnen Felder bedeuten und wie sie auszufüllen sind, wird im Folgenden erklärt.
![node info](./img/knoten_comment.png "Bitte ausfüllen") 

### 1. Name
Gib hier den Namen an, den du vorhin während der Einrichtung in Schritt 4 vergeben hast. Unter diesem Namen ist dein Router bei Freifunk zu sehen.

### 2. VPN-Schlüssel
Trage hier den VPN-Schlüssel ein, der während der Einrichtung in Schritt 6 angezeigt wurde.

### 3. MAC-Adresse angeben
Als nächstes brauchst du die MAC-Adresse von der Unterseite des Routers. Die MAC-Adresse ist eine eindeutige Identifikationsnummer die der Hersteller für jedes Gerät vergibt.

Wenn du sie in das Formular eingibst, füge bitte nach jedem zweiten Buchstaben einen Doppelpunkt hinzu. Leider schreibt der Hersteller die MAC-Adresse ohne Doppelpunkte.
Schreib also:
0A:F3:45:… anstatt 0AF345…

![MAC-Adresse](./img/router_rueckseite_MAC.png "Die MAC-Adresse auf der Rückseite")

### 4. Kontakt – Nickname / Name
Unter diesem Kontakt wird dich Freifunk nur selten ansprechen. Z.B. wenn ein wichtiges Update des Freifunk-Betriebssystems für deinen Router verfügbar ist.

### 5. Kontakt – E-Mail Adresse
Wie unter 4 gesagt, wird dich Freifunk unter dieser E-Mail nur selten ansprechen. Kein Spam – versprochen.

### 6. Koordinaten des Knotens
Wenn du die Geo-Koordinaten des Standorts deines Routers hier einträgst, ist er auf der Karte der Zugangspunkte zu sehen. So können alle feststellen, wo überall Freifunk verfügbar ist. Diese Angabe ist freiwillig, aber empfohlen.

Die Geo-Koordinaten des Standorts zu ermitteln, ist ganz einfach:
Geh auf die [Karte der Freifunk-Zugangspunkte](http://knotenkarte.de).
Dein Browserfenster sollte dann ungefähr so aussehen:
![Knotenkarte](./img/karte1.png "Finde deinen Standort auf der Karte")

Zoome nun zu dem Ort, an dem du den Router aufstellen willst. Klicke dann auf den Button „Koordinaten beim nächsten Klick zeigen“ (1) und nachfolgend auf den gewählten Ort (2).
![Koordinaten ermitteln](./img/karte2_getcoordinates.png "Ermittele die Koordinaten des Router-Standorts")

In dem daraufhin erscheinenden kleinen Fenster werden nun dessen Geo-Koordinaten angezeigt. Kopiere sie in das Formularfeld.
![Koordinaten](./img/karte2_confirm.png "Kopiere die Koordinaten")

## Formular Abschicken
Wenn das Formular fertig ausgefüllt ist, schicke es mit einem Klick auf „Knoten eintragen“ ab. Wenn Alles geklappt hat müsste dein Browserfenster ähnlich aussehen, wie im folgenden Bild. Damit ist die Registrierung abgeschlossen und du kannst deinen Freifunk-Router nun in Betrieb nehmen.
![fertig](./img/fertig.png "Nun ist dein Router angemeldet")

Nach wenigen Minuten sollte der Router auf der Karte an der von dir angegebenen Position zu sehen sein. Wenn ein grüner Punkt angezeigt wird, ist alles in Ordnung und dein Router ist am Netz. Wenn zusätzlich noch eine Verbindungslinie zu einem anderen Knoten zu sehen ist, dann mesht dein Router mit einem anderen.  
![Karte mit Router](./img/karte_fertig.png "Dein Router ist nun auf der Karte zu sehen")

Jetzt hast du's geschafft. Klopf dir auf die Schultern, freu dich und verbreite die Botschaft von Freifunk weiter. 

## Fragen?
Solltest du Fragen oder Probleme haben oder Einträge deines Knoten ändern wollen, schreibe gerne an 

__<kontakt@hamburg.freifunk.net>__!

## Noch ein wichtiger Hinweis zum Schluss 
Das Freifunk-Netz wird in die Niederlande getunnelt. Das kann bedeuten, dass dich Facebook, Googlemail, etc. warnen, du seist im Ausland. Erschrick nicht, obwohl in machen Warnungen von „Hackerangriffen“ etc. die Rede ist. Das ist ganz normal und es soll auch so sein. Diese Maßnahme dient dem Schutz vor der Störerhaftung.

[![Licence: Public Domain](http://creativecommons.org/images/deed/nolaw.png)](http://creativecommons.org/publicdomain/zero/1.0/)
