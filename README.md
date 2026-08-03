# TRANS — Höhe (H)

TRANS ist die Höhenachse des iki1uc‑Systems.  
Sie verbindet die oberen und unteren GEO‑Segmente und bildet die vertikale Rotation  
zwischen HY, PE, PER und den TMP‑Achsen.

TRANS ist die 4. Station im 9‑Stations‑System:

1. HY  
2. PE  
3. PER  
4. TRANS  
5. WARB  
6. KANAL  
7. TMP‑α  
8. TMP‑β  
9. TMP‑γ

---

## GEO‑Segmente

TRANS nutzt die rotierende GEO‑Sequenz:

◎ → 81 → ◆ → △


Diese Segmente stammen aus:

- geo-form-kompatibel-mit-3.csv  
- HY/PE/PER/WARB/KANAL/TMP‑Segment‑Matrix

Bedeutung:

- ◎ = Schließung  
- 81 = Raum  
- ◆ = Prüfung  
- △ = Funktion  

TRANS ist die **rotierende Prüfung im Raum**.

---

## Stellung im 3→9→81‑Frame

### Frame‑3  
TRANS nutzt die ersten drei rotierenden Symbole:

◎ → 81 → ◆


### Frame‑9  
TRANS ist die 4. Station im 9‑Stations‑System.

### Frame‑81  
TRANS belegt die 4. Zeile der 9×9‑Matrix.

---

## Kompatibilität

TRANS ist kompatibel mit:

- [HY](ca://s?q=HY_Station)  
- [PE](ca://s?q=PE_Station)  
- [PER](ca://s?q=PER_Station)  
- [TMP‑α](ca://s?q=TMP_alpha)  
- [TMP‑β](ca://s?q=TMP_beta)

TRANS ist inkompatibel mit:

- [WARB](ca://s?q=WARB_Station)  
- [KANAL](ca://s?q=KANAL_Station)  
- [TMP‑γ](ca://s?q=TMP_gamma)

---

## ANT — Höhenachse

TRANS/ANT.md zeigt die vertikale Rotationsform:

◉
↗   ↘
3     9
↘   ↗
◎
Dies ist die Höhen‑Schließung, die TRANS definiert.

---

## Systemachsen

TRANS nutzt vier Systemachsen:

- sys.in.json — Eingang  
- sys.out.json — Ausgang  
- sys.scale.json — Skalierung  
- sys.hdf.json — Höhen‑Daten‑Frame  

TRANS ist die rotierende Verbindung zwischen IN → OUT → SCALE → HDF.

---

## CSV‑Stellungen

TRANS nutzt:

- repo-id-3.csv — 3er‑Stellung  
- repo-id-6.csv — 6er‑Stellung  

TRANS ist die 3er‑Rotation innerhalb der 6er‑Achse.

---

## Dateien

- README.md — diese Datei  
- GEO.md — TRANS‑GEO‑Segmente  
- ANT.md — Höhenachse  
- ID.html — Stations‑Identität  
- index.html — System‑Loader  
- repo-id-3.csv — 3er‑Stellung  
- repo-id-6.csv — 6er‑Stellung  
- sys.in.json — Eingang  
- sys.out.json — Ausgang  
- sys.scale.json — Skalierung  
- sys.hdf.json — Höhen‑Daten‑Frame  

---

## Fazit

TRANS ist vollständig definiert:

- klare GEO‑Segmente  
- klare ANT‑Achse  
- klare Systemachsen  
- klare Kompatibilität  
- klare 9×9‑Stellung  
- klare TMP‑Bezüge  
- klare CSV‑Integration  

TRANS ist die vertikale Rotationsachse des iki1uc‑Systems.
