# PocketSSD-21 — Kompakter USB 3.2 Gen2 NVMe Adapter

**Status: PCB-Design abgeschlossen — unbestückt**  
**Tool:** KiCad | **Layer:** 6-Layer | **Hersteller-ready:** Ja

---

## Projektbeschreibung

Kompakter USB 3.2 Gen2 zu NVMe M.2 Bridge-Adapter auf Basis des JMS583.
Designed für maximale Datenrate bei minimaler Baugröße. 
6-Layer-Stackup (JLC06161H-1080) für saubere Signalintegrität auf 
USB 3.2 Gen2 SuperSpeed+ und PCIe-Leiterbahnen.

**Besonderheiten:**
- USB 3.2 Gen2 (10 Gbit/s) über USB-C
- NVMe M.2 (PCIe Gen3 ×2) Unterstützung
- JMS583 Bridge-Controller
- Differentielle Paare mit kontrollierter Impedanz
- Kompaktes Format, direkt steckbar

---

## Hardware

| Komponente | Beschreibung |
|---|---|
| Bridge-Controller | JMS583 (USB 3.2 Gen2 ↔ PCIe Gen3 ×2) |
| Schnittstelle Host | USB-C (USB 3.2 Gen2, 10 Gbit/s) |
| Schnittstelle Storage | M.2 Key-M (NVMe, PCIe Gen3 ×2) |
| Stackup | 6-Layer (JLC06161H-1080) |
| Tool | KiCad |

---

## PCB

- 6-Layer Stackup für kontrollierte Impedanz
- Differentielle Paare (USB SS+/−, PCIe TX/RX) mit Längen-Matching
- Dedizierte GND-Planes zur Schirmung
- Hierarchisches Schematic über fünf Sheets

---

## Ausschlüsse

Portfolioprojekt — kein Serienprodukt, kein CE/EMV.

---

## Dateien in diesem Repository

- `/kicad/` — KiCad Projektdateien
- `/screenshots/` — PCB- und Schematic-Ansichten

---

> Entwickelt von [Shawn Schneider](https://tracelabs-pcb.de)  
> — PCB-Design & Lötservice, Wolfsburg
