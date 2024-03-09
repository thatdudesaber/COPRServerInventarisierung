# Serverhandling Anleitung

## Allgemeine Informationen

### Die Server

oben HV02, unten HV01.  
<img src="../img/serveransicht_komplett.JPEG" alt="image" width="64%">
<img src="../img/serveransicht_beschriftung.JPEG" alt="image" width="30%">


### HV-O1

- CPU: Intel Xeon 8-Core E5640@2.67Ghz
  - L1-Cache: 512KB
  - L2-Cache: 2MB
  - L3-Cache: 24MB

- RAM: 120GB DIMM-DDR3@1333MHz

- Speicherplatz
  ...

- Netzwerkverbindungen  
<img src="../img/netzwerkverbindungen_HV01.jpg" alt="image">


### HV-O2

- CPU: Intel Xeon 8-Core E5640@2.67Ghz
  - L1-Cache: 512KB
  - L2-Cache: 2MB
  - L3-Cache: 24MB

- RAM: 144GB DIMM-DDR3@1333MHz

- Speicherplatz  
<img src="../img/speicher_HV02.JPEG" alt="image" width="80%">

- Netzwerkverbindungen
<img src="../img/netzwerkverbindungen_HV02.JPEG" alt="image">


## Erste Schritte

- Einschalten der Server
  - Hauptschalter einschalten (1 = EIN | 0 = AUS)
  <br>
  <img src="../img/hauptschalter.jpg" alt="image" width="30%">
  <br>

  - Hinter den Serverschrank begeben
  <br>
  <img src="../img/rückansicht_server.JPEG" alt="image" width="30%">
  <br>

  - Den Tischverteiler anschalten
  <br>
  <img src="../img/tischverteiler.JPEG" alt="image" width="30%">
  <br>

  - Anschaltknopf betätigen (zuerst HV01)
  <br>
  <img src="../img/anschaltknopf_aus.JPEG" alt="image" width="30%">
  <img src="../img/anschaltknopf_ein.JPEG" alt="image" width="30%">
  <br>
  - die drei Kabel (VGA für Video, 2 USBs für Tastatur und Maus) anschließen
  
  - Warten, bis HV01 vollständig gebootet wurde (Windows Login Fenster)

  - den selben Prozess mit HV02 durchmachen

  - Best Practices
    - Zuerst HV01 hochfahren, da HV02 auf diesen Server wartet
    - Beim Herunterfahren zuerst HV02 herunterfahren, da dieser Server von HV01 abhängig ist.

