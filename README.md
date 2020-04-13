# Marlin-DiscoEasy200
Firmware for Dagoma DiscoEasy 200 based on https://www.lesimprimantes3d.fr/forum/topic/10887-sticky-derni%C3%A8re-version-marlin-pour-discoeasy-200 and used with the head created by Z122.

This my personal setup but could be useful for others.

* No heatbed
* No Rod T8 Trapezoidal
* Z122 head: https://www.thingiverse.com/thing:2478810
* Changes made with the help of https://www.lesimprimantes3d.fr/forum/topic/12542-discoeasy-et-concepts-z122-la-solution-parfaite/
* Screen display with estimated time
  * I copied the file _duration_t.h_ and _status_screen_DOGM.h_ from https://www.lesimprimantes3d.fr/forum/topic/10887-sticky-derni%C3%A8re-version-marlin-pour-discoeasy-200/?do=findComment&comment=240652

# Requirement

You must change the cabling. Follow the explanation located here:

https://www.iot-experiments.com/dagoma-discoeasy200/ (Marlin v1.1.8 + original cabling -- not the one did by Dagoma) 

# Issue

Improvement for the move and probe on the plate need to be done since the head is different from the original one.
