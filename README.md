# Marlin-DiscoEasy200
Firmware for Dagoma DiscoEasy 200 based on https://www.lesimprimantes3d.fr/forum/topic/10887-sticky-derni%C3%A8re-version-marlin-pour-discoeasy-200 and used with the head created by Z122.

This my personal setup but could be useful for others.

* No heatbed
* No Rod T8 Trapezoidal
* Z122 head: https://www.thingiverse.com/thing:2478810
* Z122 faces (front/back): https://www.thingiverse.com/thing:3309864
  * I keep the motor at the front so the firmware has been change (_#define INVERT_Y_DIR true_)
* Changes made with the help of https://www.lesimprimantes3d.fr/forum/topic/12542-discoeasy-et-concepts-z122-la-solution-parfaite/
* Screen display with estimated time
  * I copied the file _duration_t.h_ and _status_screen_DOGM.h_ from https://www.lesimprimantes3d.fr/forum/topic/10887-sticky-derni%C3%A8re-version-marlin-pour-discoeasy-200/?do=findComment&comment=240652

# Requirement

You must change the cabling. Follow the explanation located here:

https://www.iot-experiments.com/dagoma-discoeasy200/ (Marlin v1.1.8 + original cabling -- not the one did by Dagoma) 

# Issue

Update November 2020: I changed some values in order to center the noze. It's not perfect but there is no need to do some modification on the slicer.

## Outdated

Improvement for the move and probe on the plate need to be done since the head is different from the original one.

This point is directely adressed in the slicer (Simplify3D with the modification of the _Origin offset_, x=9, y=16)
