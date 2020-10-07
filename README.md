# ArduinoCode
loadcell_calibration.ino is used to set the calibration_factor (sensitivity) of the load cell sensor. This value is stored in the force.ino program.
force.ino is used to control the linear actuator and read the load cell sensor. 
  + The Raspberry Pi sends a two-byte command to the Arduino Nano with the force limitation and linear actuator command.
  + The Arduino Nano sends a one-byte + indetermined number for force reading to the Raspberry Pi.

First, prior to a lab session the TA will upload loadcell_calibration.ino onto the Arduino and determine the sensitivity value.

Second, the TA will upload force.ino (with the new calibration_factor value) onto the Arduino and close the Arduino IDE (programming application) to allow for the Raspberry Pi GUI to perform bidirectional serial communication.
