# Task-1
# Project 1 - Receiving Images from Passing Weather Satellites using an SDR:
There are some satellites from which anyone can receive data about the weather or some science data and decode it for their own use. This project deals with the extraction of data from weather satellites (in this case NOAA and Meteor-M2 satellites) as audio signals and converting these audio signals into images. They used simple materials to build a double crosser antenna (because it is omnidirectional, it is easier to catch the signal). Using this they've recorded an audio signal when the satellite passed by. This audio signal is then resampled, demodulated and then decoded to produce an image. This image can be further processed for smoothening it, adding colors, etc. This is done using various softwares that are fairly easy to install.
 WHY Resampling? - The audio recorded by the SDR is too fast to decode and hence is resampled at lower speed
 DEMODULATION - The data received by the satellite is modulated to radio frequencies and is transmitted. So we need to demodulate it.

# Project 2 - 
