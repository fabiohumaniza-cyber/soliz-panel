# De Olho na Pele: research panel, 2,197 unseen images

This repository holds only the panel page (`index.html`) and the run data (`saida_virgens_v110_en.json`). The engine code is not here. Images load from the public ISIC Archive (all CC-0); no image is hosted here.

- Pre-registration: https://doi.org/10.5281/zenodo.23966486 (all versions: https://doi.org/10.5281/zenodo.23966485)
- Sealed result: `RESULTADO_VIRGENS_V110_LACRADO.jsonl`, SHA-256 1dfcc467bf4a2cb41de76ff8cb3f82e2d808a8fd9729853b709c76357cb2adb7
- Dice was computed against the IMA++ reference masks (Zenodo 10.5281/zenodo.14201692, CC BY-NC-ND 4.0). The masks themselves are not shown or redistributed here.
- Size classes in the panel use the area of the rule contour (refused images: no contour). Apart from the Dice, no number in the panel depends on the reference masks.
- The panel shows the numbers of the run and recomputes nothing. The work queues, physician actions and chat are a fictitious demonstration: nothing is sent.
