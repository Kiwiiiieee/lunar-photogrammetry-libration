# Lunar Photogrammetry and Optical Libration

*Individual project · AE 451 · Izmir University of Economics · May 2026*

![Measured lunar features](figures/libration.png)

## Engineering question
What is the Moon's optical libration on a given night, determined from a single telescopic image?

## Approach
- 126 surface features measured in AstroImageJ on a FITS image (13 April 2023) and matched to Virtual Moon Atlas coordinates.
- Eight plate constants fitted by least squares (Kopal and Carder), with parallax corrections.

## Results
- Libration in longitude −3.182° and latitude +7.049°.

## Validation
Compared with the ephemeris: deviations of 0.48° and 0.45°.

## Repository contents
- `notebooks/`: Wolfram Language Jupyter notebooks (outputs saved, so results display directly on GitHub)
- `report/`: written report (PDF)
- `figures/`: key figures

## How to run
The notebooks use the Wolfram Language kernel for Jupyter (WolframLanguageForJupyter, Wolfram Engine or Mathematica 14).

The notebook imports measurement files (.dat/.txt) from local folders; add them to a data/ folder and update the paths to re-run.

## Credits
This project was completed on a course notebook framework by **Prof. Fabrizio Pinto** (Izmir University of Economics), released under CC BY 4.0. The completed notebook, results and written report in this repository are my own work.

## License
CC BY 4.0, consistent with the original course material. Please credit both Prof. Fabrizio Pinto and Kaoutar Ammara.

---
Kaoutar Ammara · Aerospace Engineer · [GitHub](https://github.com/Kiwiiiieee) · [LinkedIn](https://linkedin.com/in/kaoutar-ammara)
