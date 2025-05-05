# EPWW ADDS

Custom EuroScope setup for the Warsaw FIR (EPWW), crafted for VATSIM controllers operating within the Polish vACC. This repository includes sector files, profiles, and display settings optimized for both radar and tower operations.

## Get started
### 1. **Download or Clone** this repository:
```bash
git clone https://github.com/Bartek-M/EPWW_ADDS.git
```

### 2. **Move the Folder**:
Place the entire `EPWW_ADDS/` folder **next to your EuroScope executable**, in the same directory where the `Sounds/` folder is located.
This ensures proper access to shared resources like sound alerts.
```
EuroScope/
├── EuroScope.exe
├── Sounds/
├── EPWW_ADDS/
```

### 3. **Install Font (once)**:
- Open `EuroScope.ttf` and click **Install**.

### 4. **Launch EuroScope**:
- When prompted, load either `Poland ACC.prf` or `Poland TWR.prf`.

#

### When new AIRAC comes out:

- Download necessary files from either [Polish vACC ATC Resources](https://cv.plvacc.pl/atcresources) or [GitHub](https://github.com/Bartek-M/EPWW_ADDS)

- Replace `.sct` and `.ese` files with the same base names - `EPWW-Sector`

- Replace all files at `EPWW/ICAO/` and `EPWW/NavData/`

> **NOTE:** After initial setup, **EuroScope** won't ask for loading sector files again thanks to same naming.


