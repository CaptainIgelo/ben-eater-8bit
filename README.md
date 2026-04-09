# Ben Eater 8-bit Breadboard Computer 

Vollständiger 8-bit Computer auf Breadboards nach Ben Eaters Anleitung.

## Projektstatus

| Phase | Status | Datum |
|-------|--------|-------|
| Planung | Fertig | 2026-04-09 |
| Teile Bestellung | Bestellt | 2026-04-09 | 
| Lieferung | Warten | Erwartet: 2026-04-16 |
| Inventur | Offen | - |
| Breadboard Setup | Offen | - |

## Lernziele 
- 8-Bit CPU-Architektur verstehen 
- 74LS TTL Logikschaltungen 
- Speicher (RAM/ROM) und Bus-Systeme 
- Clock- Generierung und Timing 
- Steuerlogik programmieren 

## Hardware Status 

### Bereits vorhanden (Fundoino Mega 2560 Starterkit)

- Arduino Mega 2560 R3 
- LEDs (rot, geld, grün, blau)
- Taster/Switches
- Wiederstände (verschiedene Werte)
- Breadboard Power Supply 

### Bestellt (vollständige Liste: doc/parts-list.md)

- 830-Punkte Breadboards 
- Verschiedene Typen 74LS ICs 
- 7-Segment Displays (rot) 
- 7447 Decoder und NE555 Timer ICs
- 28C16 EEPROM  
- 22awg solide Kabel 
- Kondenstatoren (verschiedener Art)

**Budget**: 147€ (Limit: 150€ (Ben-Eater kit: $350))


## Projektstruktur

```text
ben-eater-8bit/
├── README.md               # Projektübersicht 
├── bom.csv                 # Stückliste 
├── docs/                   
│   ├── parts-list.md       # Bestellte und geplante Teile 
│   ├── inventory.md        # Eingetroffene Teile prüfen 
│   ├── build-plan.md       # Aufbau und Reihenfolge 
│   └── notes.md            # Technische notizen 
├── images/             
│   ├── starter-kit/        # Fotos vom aktuellen Bestand
│   └── build-progress/     # Fotos vom Baufortschritt
├── notes/
│   └── 2026-04-09.md       # Tagesnotizen 
└── schematics/
    └── schematics.pdf      Schaltplände / Referenzen 
```

## Nächsten Schritte 

1. **Fotos vom Starter Kit** -> `images/starter-kit`
2. **Bestelllisten Erstellen** -> `docs/parts-list.md`
3. **Auf Teile Warten** -> Parallel Django API weiterentwickeln 

## Links 

- [Ben Eater Original](https://eater.net/8bit)
- [Portfolio](https://captianigelo.github.io/portfolio/)
- [Teileliste](docs/parts-list.md)

--- 
