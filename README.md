# L.A. Liivimaa atlase DDA analüüsis kasutatud kontrollpunktid

# Ground control points for Mellin's Atlas of Livonia

This repository contains ground control point (GCP) files used for the geometric distortion analysis of the Estonian sheets of Ludwig August Mellin's *Atlas von Liefland*.

The files are intended for use with the Differential Distortion Analysis workflow described by Claeys Boùùaert et al. (2016).

## Files

The repository contains ten tab-delimited text files:

| File | Sheet |
|---|---|
| `gcps_sheet01.txt` | Harjumaa |
| `gcps_sheet02.txt` | Läänemaa |
| `gcps_sheet03.txt` | Paide |
| `gcps_sheet04.txt` | Paldiski |
| `gcps_sheet05.txt` | Pärnumaa |
| `gcps_sheet06.txt` | Saaremaa |
| `gcps_sheet07.txt` | Tartumaa |
| `gcps_sheet08.txt` | Viljandimaa |
| `gcps_sheet09.txt` | Virumaa |
| `gcps_sheet10.txt` | Võrumaa |

## Data format

Each file contains one ground control point pair per line. The files have no header.

Column order:

```text
x_in    y_in    X_EST97    Y_EST97
