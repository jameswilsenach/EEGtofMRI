# EEGtofMRI: ANN Learning of the Translation from EEG to fMRI-space

Motivation
===
This repository contains a template model on which I hope to expand for translating EEG to fMRI-BOLD signal during resting wakefulness (and possibly anaesthesia). Literature suggests some weak correlation between cortical fMRI and EEG and resting wakefulness at lower EEG frequency bands. Some increase increase in overall correlation may be expected during deep anaesthesia when EEG signal is dominated by low and medium frequency activity (so-called slow wave activity).

Overview
===
A basic simulation is included showing how EEG-like signal can be bandpass filtered, decomposed into power bands and pre-processsed by moving average to be used as features for training an EEG-to-fMRI translation ANN model.

References
===

[1.] Grooms, J. K., Thompson, G. J., Schwarb, H., Schumacher, E., Schmidt, R., Epstein, C., & Keilholz, S. D. (2012). Low-frequency EEG correlates of fMRI in the resting state. BMC neuroscience, 13(1), 1-2.

