![Freifunk.Hamburg.net](./img/Ffhh_logo-06.png)![Freifunk.Hamburg.net](./img/Schriftzug.png)

# Freifunk Hamburg Router Firmware einspielen
### Schritt für Schritt Anleitung
## Einleitung
Um einen Router als Freifunk Router zu nutzen ist es erforderlich dort das Freifunk Betriebssystem – die Freifunk Firmware – zu installieren.

Die Installation ist ganz einfach und Du benötigst keine technischen Kenntnisse. Wenn du dieser Anleitung folgst kann eigentlich nichts schiefgehen.
Los geht's!

## 1. Freifunk-Router mit dem Computer verbinden
![Dein Router](./img/dein_router.png "Das ist dein Router")

Bitte schließe deinen Router (1) (Die Antenne (2) kannst du jetzt oder auch später aufschrauben.) an eine Steckdose an - Das Kabel dazu ist dabei (3). Verbinde dann den Router mit dem beiliegenden grauen LAN-Kabel (4) mit Deinem Computer. 

Stecke dafür das Kabel in eine der gelben Buchsen (die blaue brauchst du später).
![Gelbe Buchse](./img/gelbe_buchse.png "Steck deinen Router für die Einrichtung hier ein")

## 2. Firmware runterladen
Derzeit gibt es die Hamburg Freifunk als fertigen Download für zwei verschiedene Router-Typen. 

Herauszufinden welche Firmware du brauchst ist ganz einfach:
Der Router-Typ (1) und die Hardware-Version (2) steht auf der Rückseite des Routers.

![Hardware-Version](./img/TP_link_version.png "Hardware-Version")

### TP-Link TL-WR741ND (der Router mit nur einer Antenne):

Die Freifunk Firmware für die __[Versionen 4.x](http://freifunk-gw01.hamburg.ccc.de/ffhh/openwrt-ar71xx-generic-tl-wr741nd-v4-squashfs-factory.bin)__

### TP-Link TL-WR842ND (der Router mit zwei Antennen)

Die Freifunk Firmware für die __[Versionen 1.x](http://freifunk-gw01.hamburg.ccc.de/ffhh/openwrt-ar71xx-generic-tl-wr842n-v1-squashfs-factory.bin)__ 

Wenn du einen anderen Router verwendest, oder wenn du eine ältere Version der genannten Router hast, kannst du unter [Firmware](http://hamburg.freifunk.net/?page_id=80#firmware) die entsprechende Version der Firmware laden.

## 3. Firmware einspielen
Jetzt kannst du den Router einfach über den Browser konfigurieren. 

Dazu rufst du in deinen Browser folgende Adresse auf: __<http://192.168.0.1>__

Bevor du weitermachst, musst du dich erst anmelden. Die wenig inspirierte Username / Passwort Kombination ist: __admin__ / __admin__

Dein Browserfenster müsste nun so aussehen – Folge hier dem Link "System Tools".

![TP-Link Konfiguration](./img/TP_link_start.png "Geh zu System Tools")

Als nächste wählst du aus dem Menü "Firmware Upgrade" (1). Danach kannst du die vorhin (in Schritt 2) geladene Datei zum Hochladen auswählen (2). Nach einem Klick auf "Upgrade" (3) beginnt der Prozess.

![System Tools - Upgrade Formware](./img/TP_link_firmware.png "Wähle die Freifunk Firmware und spiele sie ein")

Du musst noch einmal kurz bestätigen … 

![confirm](./img/TP_link_firmware_file.png "Einmal Bestätigen")

… und die Installation läuft.
Während die Installation läuft, zieh bitte auf keinen Fall den Stecker oder das Netzwerk-Kabel – denn dann ist dein Router hinüber. 

![progress](./img/TP_link_upgrade_progress.png "Die Installation läuft")

## 5. Abschluss 

Nachdem die Firmware fertig eingespielt ist, startet der Router neu. 

Dass der Router neu startet merkst du auch am Blinken der Lämpchen an deinem Router. Zuerst blinken alle Lämpchen wild, dann gehen sie aus. Wenn danach das Lämpchen mit dem Zahnrad gemütlich vor sich hin blinkt, ist der Router im Config-Mode angekommen.

Jetzt ist der Router nicht mehr unter der angegeben Adresse sichtbar und eine Fehlermeldung erscheint. 
Das ist gut so. Denn nun läuft nicht mehr die alte Firmware sondern die neue, tolle Freifunk Firmware auf deinem Router.

![Fehlermeldung](./img/TP_link_firmware_reboot_finished.png "Die alte Firmware ist weg - die neue läuft")

Als nächstes musst du deinen Router noch einrichten und im Freifunk Netz anmelden. Auch das ist ganz einfach. Eine Anleitung findest du unter [Anleitung Router einrichten](http://hamburg.freifunk.net/?page_id=80#anleitungen).

## Fragen?
Solltest Du Fragen oder Probleme haben oder Einträge deines Knoten ändern wollen, schreibe gerne an 

__<kontakt@hamburg.freifunk.net>__!

[![Licence: Public Domain](http://creativecommons.org/images/deed/nolaw.png)](http://creativecommons.org/publicdomain/zero/1.0/)