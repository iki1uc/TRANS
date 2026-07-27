# TRANS – Höhe (H)

## ID-System
TRANS arbeitet mit der ID **H** (Höhe).  
Diese ID ist ein 1‑Zeichen‑Schlüssel und wird als TMP‑Speicherpfad genutzt:

`TMP/H/<slot>.json`

## Albertus Orbit Engine C
TRANS nutzt die Orbit‑Engine C, die automatisch:

- 3×3 Slots (1–9)
- VAR-Slots (V1–V9)
- Meta-Slot (X)
- Orbit-Slot (∞)

durchläuft und ausweicht, wenn ein Slot besetzt ist.

## Slot-Finder
TRANS verwendet:

`ALBERTUS_FIND_SLOT(H, busy)`

Die Engine wählt automatisch den nächsten freien Slot.

## RESPO_H – Höhen-Interpretation
RESPO interpretiert TMP-Daten als Höhenmatrix.

## BEN_H – Höhen-Bewertung
BEN bewertet die Höhenstruktur des aktiven TMP-Slots.

## AI-H – Höhen-Steueralgorithmus
Der AI-Algorithmus steuert den Höhenorbit und entscheidet,
wie RESPO/BEN-Daten weiterverwendet werden.

## Zweck
TRANS bildet die Höhenachse des Systems.
