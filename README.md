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


x_in    y_in    X_EST97    Y_EST97

Source maps

The map sheets used for this dataset are from the Library of Congress digitized copy of Mellin's atlas:

Ludwig August Mellin, Atlas von Liefland, oder von den beyden Gouvernementern u. Herzogthümern Lief- und Ehstland, und der Provinz Oesel.

Library of Congress, Copy 1:
https://www.loc.gov/resource/g7022lm.gct00143/?st=gallery

The Library of Congress record includes several copies of the atlas. This dataset refers to Copy 1.

Methodological reference

The control points were prepared for Differential Distortion Analysis, following the approach described in:

Claeys Boùùaert, M., De Baets, B., Vervust, S., Neutens, T., De Maeyer, P., & Van de Weghe, N. (2016). Computation and visualisation of the accuracy of old maps using differential distortion analysis. International Journal of Geographical Information Science, 30(7), 1255–1280. https://doi.org/10.1080/13658816.2015.1127377

The original MATLAB/Octave implementation of the method is available here:
https://github.com/mclaeysb/distortionAnalysis
