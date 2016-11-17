# AirBeamBREATHE
Hardware Flash Code for AirBeam Controller Data Format for BREATHE

Steps to Re-Flash the AirBeam for new data format:

1) Download Arduino: https://www.arduino.cc/en/Main/Software

2) Open Arduino software on your computer

3) Download this code onto your desktop

4) In Arduino, go to File-->Open-->Open this code from the folder you downloaded it to 

5) Plug the Airbeam into your computer using the USB cable, and turn the device on. Allow the device set up to automatically run and install drivers

6) In Arduino, go to Tools-->Board-->Choose Arduino Leonardo as your current board type

7) In Arduino, go to Tools-->Port-->Choose the COM port that says (Arduino Leonardo) next to it. This is your AirBeam's port

8) In Arduino, go to Sketch-->Upload, and upload the code here onto your AirBeam's Arduino Leonardo board

9) Once uploaded, the command prompt should read "Successful"

10) The AirBeam is now uploaded with the latest firmware, go to your BREATHE app, pair with the AirBeam on the smartwatch (hit "Yes" when it asks if the pair code ID is correct), and then check https://www.breatheplatform.com/portal/sensor?id=8 to see if the AirBeam data is uploading to the UCLA cloud server.
