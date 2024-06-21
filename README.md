# pco_edge42_cl
Python device adaptor: PCO.edge 4.2 CamLink sCMOS camera.
## Quick start:
- Install the 'Camlink' interface drivers, then install 'Camware' to test the camera and get the latest
.dll files "SC2_Cam.dll" and "sc2_cl_me4.dll" (versions included here). Put the .dll files in the 
directory with "pco_edge42_cl.py" and run the script (requires Python and numpy).

![social_preview](https://github.com/amsikking/pco_edge42_cl/blob/main/social_preview.png)

## Details:
- The adaptor reveals a minimal API from the extensive PCO SDK by following the 'typical implementation'
for a series of .dll calls for camera setup, image acquisition and tidy up.
- See the '\_\_main__' block at the bottom of "pco_edge42_cl.py" for some typical ways to interact with a
stand alone camera or "pco_edge42_cl_external_trigger_example.py" for an example of high speed external
triggering (a very useful mode for ultra fast synchronization in a multi-device/microscope system).
