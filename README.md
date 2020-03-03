# UWESSNAEWEEN

*Uwe soll sich nicht ärgern. Wir entwickeln etwas neues.*

<img width="200" src="assets/media/CurrentSignCropped.png">&emsp;&emsp;&emsp;
<img width="300" src="assets/media/DoorSign.svg">

## Problembeschreibung

Uwe muss immer wenn sich die Belegung der Räume ändert, die Türschilder ändern. Das ist ein aufwendiger nerviger Prozess.

Beim Besprechungsraum wäre es schön, wenn man sehen könnte wann und für wen der Raum in den nächsten Stunden reserviert ist. Bei einer laufenden Besprechung wäre es schön, wenn man sehen könnte welche Mitarbeiter gerade in der Besprechung sind, falls man jemanden sucht.

Insgesamt haben wir bei SEKAS ca. 20 Türschilder.

## Mögliche Lösung

EInk-Displays an/neben den Türen. Die Displays sollten

* Batteriebetrieben sein (Lebensdauer 1 Jahr tbd.)
* Eine übersichtliche Seite mit Informationen zum Raum anzeigen
* Sich über WiFi regelmäßig aktualisierte Informationen beschaffen
* Ein formschönes Gehäusedesign haben
* Die Aktualisierungen sollten zentral gemanaged werden
* Updateintervalle sollten variabel sein (Einfluss auf Lebensdauer)

*Ganz grobe BOM-Kosten*:

* 800x600 6" EInk Display 2 Color: 36$
* 800x448 5.83" EInk Display 3 Color: 40$
* Driver Board (off the shelf): 8$
* Total BOM: ~60$

## Projekitphasen

### Klärung SEKAS-Beteiligung

* Budget Material
* Bestellwesen
* Bereitstellung von Räumlichkeiten
* Beretistellung von Pizza
* Versicherung, Haftung

### Teambildung

* Wer hat Lust mitzumachen?
* Wer kann welche Fähigkeiten einbringen?
* Wer kann wie viel Zeit einbringen?
* Wer kann welche Rollen übernehmen?
* Wer möchte am Ende auch Exemplare für zu Hause?

### Skills

* Firmware-Entwicklung
* Backend-Entwicklung
* EE-Design
* Board-Layout
* Mechanisches Design
* Supply-Chain
* Fertigung (Löten, Mechanischer Zusammenbau)
* Industrial Design
* PM

### Anforderungsdefinition

* Was soll auf den Türschildern dargestellt werden?
* Was sind die Anforderungen bzgl. Updaterate?
* Was sind die Anforderrungen bzgl. Batterielebensdauer?
* Was ist der Kostenrahmen?

### Machbarkeitsuntersuchung

* Sind die Ziele bezüglich Lebensdauer der Batterien machbar?
* Wie hoch sind die Materialkosten ungefähr (BOM, pro Schild)
* Wie klein bekommen wir die Steuerungslogik

### Platformauswahl

* Welchen Prozessor verwenden wir?
* Was für eine Entwicklungsplattform nutzen wir?
* Nutzen wir eine IoT-Platform oder fangen wir erst mal mit den Basics an?

### Hardware Design

* Leiterplattendesign
* Gehäusedesign
* Batteriefach
* Aufhängung

### Hardware Prototyp

* Handfertigung einer Leiterplatte oder Bestellung über ein Board-House
* Bestückung
* Gehäusefertigung (3D-Print)
* Iterationen

### Software Design und Implementierung

Parallel zu Hardware-Prototyp

* Firmware
* Backend
* Iterationen

### Produktion

* Bestellung Leiterplatten
* Bestückung (in-House / Auftragsfertigung?)
* Programming (Firmware aufspielen)
* Gehäuse (Injection Mold / 3D Print)
* Endmontage

### Deployment

* Anbringen an den Türen
* Installation / Rollout Backend Software

## Links

### Beispielprojekt ESP8266 Light Strip

https://github.com/pbininda/ESP8266LightStrip


<img width="500" src="https://raw.githubusercontent.com/pbininda/ESP8266LightStrip/master/doc/assets/devsystem-perspective.jpg">

### Waveshare E-Ink Displays

https://www.waveshare.com/product/displays/e-paper/epaper-1.htm

€38.84 für "raw display"

<img width="500" src="https://www.waveshare.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/5/_/5.83inch-e-paper-b-1.jpg">

49.95 für "display mit HAT"

<img width="500" src="https://www.waveshare.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/5/_/5.83inch-e-paper-hat-b-1.jpg">


### ESP8266 Bei Mouser

https://www.mouser.de/Embedded-Solutions/Wireless-RF-Modules/WiFi-Modules-80211/_/N-6l7qa?Keyword=esp8266&FS=True

https://www.mouser.de/ProductDetail/Espressif-Systems/ESP-WROOM-02D-4MB?qs=sGAEpiMZZMsRr7brxAGoXSSUPDSAjAiVMDdZTQMS1OoLsk1Mo9acAg%3D%3D


Einzel-Stückpreis €2,88

<img width="300" src="https://www.mouser.de/images/espressifsystems/hd/ESP-WROOM-02D_t.jpg">

### ESP8266 Bei Ali Express

https://de.aliexpress.com/item/32641565241.html

Einzel-Stückpreis €1,08

<img width="300" src="https://ae01.alicdn.com/kf/HTB17wx_DQKWBuNjy1zjq6AOypXar/1PCS-Esp8266-WiFi-serie-von-modell-ESP-12-ESP-12F-esp12F-esp12-authentizit-t-garantiert-I74.jpg">


### Boards


5 Boards: $2.00

Shipping:
* $6 (7-10 Werktage)
* $21 (DHL Express, 2-3 Werktage)


https://jlcpcb.com/


### Die Konkurenz

https://www.digitales-tuerschild.de/1_12_Digitale_Tuerschilder.php

<img src="https://www.digitales-tuerschild.de/img/7_4_zoll_batterie_funk_tuerschild_kunststof_metallfront.jpg">

https://shop.kindermann.de/erp/webshop/navigationPath/100000.Produkte/117250.Raumbuchung/105055.Doorsigns

<img src="https://shop.kindermann.de/erp/KCO/avs/5/5002/5002000201/04_Bilder/5002000201_300x300px_1.jpg">

https://shop.kindermann.de/erp/KCO/avs/Katalogseiten/2019/Katalog_60+61+62.pdf

* Doorsign e-Ink 7,4 Zoll schwarz/weiß/rot €179,00


* e-Ink Wireless Accesspoint €625,00
* Netzteil für e-Ink Accesspoint €35,00
* Wandhalterung aus Edelstahl €25,00