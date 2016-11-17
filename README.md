# AirBeamBREATHE
Hardware Flash Code for AirBeam Controller Data Format for BREATHE

Steps to Re-Flash the AirBeam for new data format:

1) Download Arduino software: https://www.arduino.cc/en/Main/Software

2) Open Arduino software on your computer

3) Download this code onto your desktop by pressing "Clone or Download" and then "Download Zip" in GitHub

4) Extract both zip files "DHT-sensor-library-master.zip" and "Airbeam.zip" onto your desktop

5) Double click on the "Airbeam.ino" file in the AirbeamBREATHE-master/Airbeam/Airbeam folder to open it in Arduino

6) In Arduino, go to Sketch-->Include Library-->Add .ZIP Libary--> Choose "Dekstop" folder, then "AirBeamBREATHE-master" folder and click on "DHT-sensor-library-master.zip"

7) Plug the Airbeam into your computer using the USB cable, and turn the device on. Allow the device set up to automatically run and install drivers

8) In Arduino, go to Tools-->Board-->Choose Arduino Leonardo as your current board type

9) In Arduino, go to Tools-->Port-->Choose the COM port that says (Arduino Leonardo) next to it. This is your AirBeam's port

10) In Arduino, go to Sketch-->Upload, and upload the code here onto your AirBeam's Arduino Leonardo board

11) Once uploaded, directly above the command prompt it should read "Done Uploading"

12) The AirBeam is now uploaded with the latest firmware, go to your BREATHE app, pair with the AirBeam on the smartwatch (hit "Yes" when it asks if the pair code ID is correct), and then check https://www.breatheplatform.com/portal/sensor?id=8 to see if the AirBeam data is uploading to the UCLA cloud server.
