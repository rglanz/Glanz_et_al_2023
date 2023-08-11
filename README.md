# Glanz_et_al_2023

[![DOI](https://zenodo.org/badge/586313842.svg)](https://zenodo.org/badge/latestdoi/586313842)

Matlab files for eight P8 and eight P12 rat pups are included. See [Glanz et al., 2021](https://www.jneurosci.org/content/41/32/6905/tab-article-info) for data collection details.

**Data included:**
* pupId: name assigned to pup [*string*]
* pupAge: postnatal age of pup, in days [*int*]
* Units: spike timestamps (in seconds) for each unit [*non-scalar structure of doubles*]
* Behavior: structure containing mixed datatypes...
  * Behavior.limbPosition: pixel value of each limb feature (elbow, wrist, digits) per video frame [*double*]
  * Behavior.twitchTimestamps: onset of each twitch, in seconds [*double*]
  * Behavior.wakeMovementTimestamps: onset of each wake movement, in seconds [*double*]
  * Behavior.sleepWakeStateTimestamps: onset of active sleep (AS) or wake (W) state, in seconds [*double*]
  
