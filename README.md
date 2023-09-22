# FrSky-Ethos-Helicopter-Templates
Staging Repository for Ethos Helicopter Templates
The templates will be officially hosted on https://ethos.frsky-rc.com, but intermediate updates and pre-release templates/documentation will be staged here to prevent excessive updates to the main Ethos download page.


Document Purpose:
This document, as well as the other associated documentation, is intended to explain the flybarless helicopter model template library download, available from https://ethos.frsky-rc.com.    All model templates are made for flybarless helicopter use and there are several different models of varying complexities from basic to rather complex.  These are template models.  They are not fully configured and require some setup by the user which is described in the applicable document when needed for each model. 

While attempts have been made to ensure the model templates are as universal as possible between Ethos radios, FBL units, receivers, etc., it is not possible to make 100% sure they are and, in some cases, unexpected model reactions or movement resulting in personal or property damage are possible. 

You, as the user, must ensure proper safety procedures are followed when using any of these model templates.  Remove all blades, including tail blades, from the model for initial setup and testing.  Alternatively (or in addition), completely unplug the motor from the ESC or use a separate RX pack to power up the servos, receiver, and flybarless unit during initial setup.

All model templates were created in Ethos 1.4.9 and you must have at least 1.4.9 installed on your radio to use them.  They will occasionally be updated to take advantage of features in later Ethos versions and to bring them up to date.  Additional templates may be added if it’s seen as necessary or largely requested to do so.

These model templates assume standard FrSky basic channel assignments and typical channel assignments for Rescue and Bank/Setup selection.  The channel assignments used by all helicopter model templates are:
1. Aileron
2. Elevator
3. Throttle
4. Rudder
5. Gyro Gain
6. Collective
7. Setup/Bank Selection
8. Rescue Mode Activation

The channel directions are as per Ethos defaults so some reversal in the radio may be necessary for your FBL unit to see the correct control directions.  This is best done in Model Settings > Outputs (“Invert” Setting)

Because most people these days do not use a normal mode, and instead opt for three idle ups, only the basic model (BasicHeli1.bin) has a normal mode.  BasicHeli2 and above all have three idle ups instead.  If you want to use a more advanced template but also want to still have a normal mode, refer to the BasicHeli1 model and its setup for normal mode and copy it over to the template you want to use.

Each template is unique and there are levels: Basic, Intermediate, Advanced.  For the most part, the more advanced you go, you will have all the features from the previous templates plus some new ones.  Any unused features can be deleted/removed to reduce clutter and avoid wasting channels.

Each model file has its own documentation .pdf file.  The documents are named according to the name of the model file (e.g. BasicHeli1.bin and BasicHeli1.pdf)

A short summary of each model template and its name can be found on the following page.

BasicHeli1.bin
Very basic helicopter model with normal mode.  Simplest of setups while still being easy to customize to use your preferred switches.  Optimized for throttle governor use (whether Flybarless or ESC governor) but will also work with ungoverned models with some small changes.  It does not have bank/setup switching for FBL units or Rescue Mode.  Gyro gain (Ch5) is on the Mode switch, allowing you to have different gain settings for Normal, IU1, and IU2.
BasicHeli2.bin
Identical to BasicHeli1 except that that there is no normal mode.  When you flip out of throttle hold, the heli will immediately begin to spool up.  Simplest of setups while still being easy to customize to use your preferred switches.  Optimized for throttle governor use (whether Flybarless or ESC governor) but will also work with ungoverned models with some small changes.  It does not have bank/setup switching for FBL units or Rescue Mode.  Gyro gain (Ch5) is on the Mode switch, allowing you to have different gain settings for IU1, IU2, and IU3.
InterHeli1.bin
Identical to BasicHeli2 except that it also adds Setup/Bank Selection and Rescue into the mix.  Easy to customize to use your preferred switches by having the main functions tied to flight modes.  Optimized for throttle governor use (whether Flybarless or ESC governor) but will also work with ungoverned models with some small changes. Gyro gain (Ch5) is on the Mode switch, allowing you to have different gain settings for IU1, IU2, and IU3.
InterHeli2.bin
Identical to InterHeli1 except it adds settings adjustment for supported flybarless systems.  Easy to customize to use your preferred switches by having the main functions tied to flight modes.  Optimized for throttle governor use (whether Flybarless or ESC governor) but will also work with ungoverned models with some small changes. Gyro gain (Ch5) is on the Mode switch, allowing you to have different gain settings for IU1, IU2, and IU3.



Model templates and documentation created by Keith W.  This all took a long time to write, I hope it is helpful.  


The best place to get extra help with these templates (and to help anyone else who sees the discussion in the future) is on the associated HeliFreak thread:


Please also be aware of the lengthy Ethos user manuals which can answer many of your questions already, available for download on the FrSky ETHOS Community Feedback GitHub.
https://github.com/FrSkyRC/ETHOS-Feedback-Community/tree/main/doc
