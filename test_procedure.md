# DISCLAIMER
The tests are intended to capture data on the emissions of 3d printed filaments.
Please operate your machinery in a safe and healthy manner avoiding inhalation of fumes. 
I am not responsible or liable for injuries caused by this procedure.


# Setup Procedure
As follows:
* Connect BME688 in place and ensure power is delivered to the testing board (gantry mount stl is available in the files area)
* BME688 dev kit requires 24hrs to stabilize in the environment it's in. I anticipate this will not matter if it's heated or ambient. It's 'burn in' for the sensor, and only needs to happen once.

# Testing Procedure
## Record Normal Air (30 mins)
1) Ensure board is mounted securely
2) Heat chamber to ambient temperature (wait 30 minutes for chamber temps to stabilize)
3) Apply power to the sensor board being careful not to touch the sensors
4) The red light should be flashing every 2 seconds
5) Wait for 30 minutes to collect normal air data

## Record Sample (39 mins)
1) Press Button 1 (labelled S1) to mark the time of first sample
2) Print half of a 30mm Voron Cube in your filament of choice (my slicer predicts 8g in 39m) - we're aiming at 30 minutes of test data
3) Note, we're not aiming for a nice print. Just something to gather data
4) Press Button 2 (labelled S2) to mark the start of the next sample

## Re-Record Normal Air (30 mins)
1) The aim here is to remove any traces of test gas / plastic products
2) If you have a nice safe exhaust, please use it. Otherwise do what you can do a) evacuate the chamber whilst b) keeping your exposure to the hot nasty air down.
3) Open a window, run a fan, open the chamber doors
4) If you have a removable build plate, remove it with the part on it - being careful not to burn yourself and leave the room. These smells cant be good for your health. Alternatively, carefully remove the part
5) Whilst you're out of the room, prepare the chamber for another print. Remember our focus is to get normal air, so we dont yet want to heat the extruder, or put the build plate back on
  a) Remove your part from the build plate
  b) Preheat the build plate (but not the extruder yet)
7) Return after a few minutes to close the chamber doors once again so that the chamber air can heat up
8) Wait for 30 minutes to collect normal air data

## Re-record sample (39 mins)
1) Press Button 1 (labelled S1) to mark the time of the next sample
2) Re-fit the build plate, if it was removed. We dont want to add any more chemicals, so please dont use IPA or other solvents to clean the plate
3) Pre-heat the extruder to the printable temperature
4) Print half of a 30mm Voron Cube in your filament of choice (my slicer predicts 8g in 39m) - we're aiming at 30 minutes of test data
5) Note, we're not aiming for a nice print. Just something to gather data
6) Once the print has finished, disconnect the power from the dev board

Total Time: 2hrs 18mins + some faffing time.

All done, time to get the data into the software
