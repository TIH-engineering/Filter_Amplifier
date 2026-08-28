# Filter_Amplifier

[![release](https://img.shields.io/github/v/release/TIH-engineering/Filter_Amplifier?label=release)](https://github.com/TIH-engineering/Filter_Amplifier/releases)
[![Build](https://github.com/TIH-engineering/Filter_Amplifier/actions/workflows/build.yml/badge.svg)](https://github.com/TIH-engineering/Filter_Amplifier/actions/workflows/build.yml)
![Hardware](https://img.shields.io/badge/Hardware-KiCad-blue)
![License](https://img.shields.io/badge/License-CC--BY--NC--SA--4.0-lightgrey)

## 🔌 Leiterplattenbeschreibung

Die Leiterplatte **Filter_Amplifier** dient zur praktischen Untersuchung von **aktiven Filtern und Operationsverstärkerschaltungen**. Sie wurde insbesondere für Laborübungen im Bereich Elektronik und Messtechnik entwickelt.

Die Schaltung besteht aus zwei hintereinander geschalteten Operationsverstärkerstufen mit einem **LM358**. Durch unterschiedliche Jumperstellungen können verschiedene Schaltungsvarianten realisiert und messtechnisch untersucht werden.

Folgende Betriebsarten sind vorgesehen:

- **nichtinvertierende Verstärkerschaltung**
- **Tiefpass 1. Ordnung**
- **Tiefpass 2. Ordnung**
- **Hochpass 1. Ordnung**
- **Hochpass 2. Ordnung**
- Untersuchung des Einflusses einer **kapazitiven Last** auf die Stabilität des Operationsverstärkers

Für die Filterschaltungen sind unterschiedliche Widerstands- und Kondensatorwerte vorgesehen. Dadurch können verschiedene Grenzfrequenzen eingestellt und deren Einfluss auf den Frequenzgang untersucht werden.

Ein- und Ausgang stehen über Koaxialanschlüsse zur Verfügung, sodass die Schaltung beispielsweise mit **Funktionsgenerator und Oszilloskop** vermessen werden kann. Die konfigurierbare Struktur ermöglicht insbesondere die experimentelle Untersuchung von **Verstärkung, Grenzfrequenz, Amplitudengang, Phasengang und Stabilität**.

> **Einsatzgebiet:** Laborübungen und Unterricht im Bereich Operationsverstärker, aktive Filter und Frequenzgangmessung

---

## 📥 Downloads

| Datei | Beschreibung |
|---|---|
| 📄 [Schaltplan (PDF)](../../releases/latest/download/schematic.pdf) | Schaltplan der Leiterplatte |
| 🖨️ [Leiterplatte (PDF)](../../releases/latest/download/pcb.pdf) | Leiterplattenansicht als PDF |
| 🔩 [Bohrplan (PDF)](../../releases/latest/download/drill.pdf) | Bohrdaten / Bohrplan |
| 📋 [Stückliste (Excel)](../../releases/latest/download/bom.xlsx) | Bill of Materials |
| 🌐 [Interactive BOM](../../releases/latest/download/ibom.html) | Interaktive Bestückungsansicht |
| 📦 [Fertigungsdaten](../../releases/latest/download/kicad.zip) | Gerber- und Bohrdaten |
| 🧊 [STEP-Modell](../../releases/latest/download/pcb.step) | 3D-Modell der Leiterplatte |

Die Dateien werden automatisch durch den Release-Workflow erzeugt.

---

## 🖥️ Leiterplatte

### Vorschau

| Oberseite | Unterseite |
|:---:|:---:|
| ![PCB Top](../../releases/latest/download/top.kicad.thumbnail.png) | ![PCB Bottom](../../releases/latest/download/bottom.kicad.thumbnail.png) |

### Oberseite

![PCB Top](../../releases/latest/download/top.kicad.png)

### Unterseite

![PCB Bottom](../../releases/latest/download/bottom.kicad.png)

---

## ℹ️ Projektinformationen

| Eigenschaft | Wert |
|---|---|
| **Projekt** | Filter_Amplifier |
| **Software** | KiCad 10 |
| **Repository** | TIH-engineering/Filter_Amplifier |
| **Autor** | TIH |
| **Lizenz** | CC BY-NC-SA 4.0 |

---

## 🗂️ Repository-Struktur

```text
.
├── .github/
│   └── workflows/       # GitHub Actions
├── .kibot/              # KiBot-Konfiguration
├── pcb/
│   ├── lib/             # Projektspezifische Bibliotheken
│   └── ...              # KiCad-Projektdateien
├── .gitignore
├── LICENSE
└── README.md