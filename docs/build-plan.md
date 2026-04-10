# Build Plan 

## Ziel 

Der Aufbau erfolgt Schritt für Schritt nach funktionalen Baugruppen, damit jede Einheit einzeln getestet werden kann. 

## Reihenfolge 

1. Clock: Taktsignal
2. Registers: Register
3. ALU (Arithmetic Logic Unit): Recheneinheit
4. RAM (Random Access Memory): Arbeitsspeicher 
5. Program Counter: Befehlszähler
6. Instruction Register: Befehlsregister
7. Control Logic: Steuereinheit
8. Output Register: Ausgaberegister 
9. Gesamttest


## Phase 1: Clock 

Ziel: 
- Taktgenerator verstehen 
- Manuell und automatisch takten
- Clock-Signal sichtbar machen 

Aufgaben: 
- NE555-Timer aufbauen
- Astabilen Takt testen
- Manuellen Taster für Single Step ergänzen
- LED zu Anzeige des Clock Signals nutzen 

Erfolgskriterium: 
- Die Clock läuft stabil 
- Single Step funktioniert kontrolliert 


## Phase 2: Registers 

Ziel:
- Daten Speichern und über den Bus ausgeben

Aufgaben: 
- A-Register aufbauen 
- B-Register aufbauen
- Load- und Output-Verhalten testen
- LEDs zur Zustandsanzeige verwenden 

Erfolgskriterium: 
- Werte lassen sich korrrekt laden und ausgeben 

## Phase 3: ALU 

Ziel: 
- Addition und Subtraktion nachvollziehen 

Aufgaben: 
- ALU mit 74LS181 integrieren 
- Verbindung zu A- und B-Register herstellen 
- Flags beobachten 
- Beispielrechnungen testen 

Erfolgskriterium: 
- Rechenoperatoren liefern reproduzierbare Ergebnisse 

## Phase 4: RAM 

Ziel: 
- Daten und Programme speichen 

Aufgaben: 
- RAM-Modul aufbauen 
- Adressierung testen 
- Schreiben und Lesen prüfen 

Erfolgskriterium: 
- Daten können zuverlässig gespeichert und gelsen werden 

## Phase 5: Programm Counter 

Ziel: 
- Befehlsadressen automatisch durchlaufen 

Aufgaben: 
- Counter aufbauen 
- Inkrement testen 
- Reset-Verhalten prüfen 

Erfolskriterium: 
- Adressen werden korrekt hochgezählt 

## Phase 6: Instuction Register 

Ziel: 
- Aktuellen Befehl halten und dekodieren 

Aufgaben: 
- Instruction Register aufbauen 
- Eingehende Daten Übernehmen 
- Ausgabe an Steuerlogik prüfen 

Erfolgskriterium: 
- Befehle werden stabil übernommen 

## Phase 7: Control Logic 

Ziel: 
- Steuerung aller Baugruppen 

Aufgaben: 
- EEPROMs vorbereiten 
- Kontrollsignale definieren 
- Mikrocode schrittweise testen 

Erfolgskriterium: 
- Steuerleitungen verhalten sich passend zum Befehl 

## Phase 8 

Ziel: 
- Ergebnisse sichtbar machen 

Aufgaben: 
- Output Register aufbauen 
- Anzeigeeinheit verbinden 
- Zahlen auf 7-Segment testen

Erfolgskriterium: 
- Ergebnisse werden korrekt dargestellt 

## Phase 9: Gesamttest 

Ziel: 
- Gesamtsystem als 8-Bit-Computer testen 

Aufgaben: 
- Module vverbinden 
- Einfaches Programm laden
- Ablauf vollständig testen 
- Fehler dokumentieren 

Erfolgskriterium: 
- Einfaches Programm läuft reproduzierbar durch 

## Notizen 

Während jeder Phase dokumentieren: 
- Schaltplan-Änderungen 
- Fehlerbilder 
- funktionierende Tests 
- offene Probleme 

