# Serverhandling Anleitung

## Allgemeine Informationen

### Die Server

* oben HV02, unten HV01.  
<img src="../img/serveransicht_komplett.JPEG" alt="image" width="64%">
<img src="../img/serveransicht_beschriftung.JPEG" alt="image" width="30%">

* Domäne: ``copr-gmbh.lab``

* Servertags  
<img src="../img/servicetags.jpg" alt="image" width="50%">

* MAC-Karten  
<img src="../img/mac_karten.jpg" alt="image" width="50%">

* Hyper-V Manager   
<img src="../img/hyperv_manager.JPEG" alt="image" width="100%">

---

### HV-O1

- CPU: Intel Xeon 8-Core E5640@2.67Ghz
  - L1-Cache: 512KB
  - L2-Cache: 2MB
  - L3-Cache: 24MB

- RAM: 120GB DIMM-DDR3@1333MHz

- Festplatten  
<img src="../img/HV01_festplatten.JPEG" alt="image" width="80%">

- Speicherplatz  
  ...

- Partitionen  
  ...

- Netzwerkverbindungen  
<img src="../img/HV01_netzwerkverbindungen.jpg" alt="image">

- Virtuelle Switches
<img src="../img/HV01_virtuelle_switches.JPEG" alt="image">

- Servermanager  
<img src="../img/HV01_servermanager.JPEG" alt="image" width="60%">

---

### HV-O2

- CPU: Intel Xeon 8-Core E5640@2.67Ghz
  - L1-Cache: 512KB
  - L2-Cache: 2MB
  - L3-Cache: 24MB

- RAM: 144GB DIMM-DDR3@1333MHz

- Festplatten  
<img src="../img/HV02_festplatten.JPEG" alt="image" width="80%">

- Speicherplatz  
<img src="../img/HV02_speicher.JPEG" alt="image" width="80%">

- Partitionen  
<img src="../img/HV02_partitionen.JPEG" alt="image" width="100%">

- Netzwerkverbindungen
<img src="../img/HV02_netzwerkverbindungen.JPEG" alt="image">

- Virtuelle Switches
<img src="../img/HV02_virtuelle_switches.JPEG" alt="image">

- Servermanager  
<img src="../img/HV02_servermanager.JPEG" alt="image" width="60%">

## Erste Schritte

- Einschalten der Server
  - ***Anfangen mit HV-01!*** Zuerst diesen Hochfahren, da HV-02 auf ihn abhängig ist.
  - Hauptschalter einschalten (1 = EIN | 0 = AUS)  
  <img src="../img/hauptschalter.jpg" alt="image" width="30%">

  - Hinter den Serverschrank begeben  
  <img src="../img/rückansicht_server.JPEG" alt="image" width="30%">

  - Den Tischverteiler anschalten  
  <img src="../img/tischverteiler.JPEG" alt="image" width="30%">

  - Anschaltknopf betätigen (zuerst HV01)  
  <img src="../img/anschaltknopf_aus.JPEG" alt="image" width="30%">
  <img src="../img/anschaltknopf_ein.JPEG" alt="image" width="30%">
  - die drei Kabel (VGA für Video, 2 USBs für Tastatur und Maus) anschließen
  
  - Warten, bis HV01 vollständig gebootet wurde (Windows Login Fenster)

  - den selben Prozess mit HV02 durchmachen

## Herunterfahren
  - Umgekehrte Reihenfolge als beim Hochfahren
  - ***Zuerst HV02 herunterfahren***, da dieser Server von HV01 abhängig ist.
  - Normaler Windows-Logout unten links. Es werden alle Prozesse gestoppt, dann wird Server heruntergefahren.
  <img src="../img/shutdown.JPEG" alt="image" width="80%">
  - Roten Schalter (Tischverteiler) hinten ausmachen
  - Hauptschalter abdrehen (?)
