# Warped_DCNN
Identifying warped disk galaxies in Pan-STARRS and Euclid images using deep learning

This repository contains the catalogue of newly predicted galaxies, best-performing model weights, a demo notebook for loading the model weight to make prediction.


## Contents

High-confidence predictions (p ≥ 0.85)

    Panstarrs_Highconf_Warp.csv
    Panstarrs_Highconf_Nonwarp.csv
    Euclid_Highconf_Warp.csv
    Euclid_Highconf_Nonwarp.csv
    Lists of new galaxy predictions where the model predicted a class with probability ≥ 0.85.

Lower-confidence predictions (p < 0.85)

    Panstarrs_Lowconf_Warp.csv
    Panstarrs_Lowconf_Nonwarp.csv
    Euclid_Lowconf_Warp.csv
    Euclid_Lowconf_Nonwarp.csv
    Predictions where the model probability for the predicted class is below 0.85.

Model weights

    Best_model_link.txt — Link containing the best-performing trained model.

Demo notebook

    prediction_code_FITS.ipynb — Demonstrates loading the above model and generating predictions for new galaxy images.


## Columns / Fields

### The PanSTARRS predicted sample share the following columns :

    Obj_name — user defined id
    PGC — PGC name (Unique identification number linked to the HyperLeda database)
    EGIPS — Edge-on galaxies in the Pan-STARRS survey designation 
    RAJ2000 — Right ascension (J2000) (ra) 
    DEJ2000 — Declination (J2000) (dec)
    Coord — Coordinates in the sexagesimal format 
    max_prob: Model's predicted probability for the reported class.

### The Euclid predicted sample share the following columns :

    Obj_name — user defined id
    right_ascension
    declination
    max_prob: Model's predicted probability for the reported class.
    

## Contact

For more information, please contact: Saranya Suguna J — saranya.suguna5@gmail.com




