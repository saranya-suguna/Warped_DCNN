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




