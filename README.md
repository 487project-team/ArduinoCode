# ArduinoCode
loadcell_calibration.ino is used to set the sensitivity of the load cell sensor. This value is stored in the force.ino program.
force.ino is used to control the linear actuator and read the load cell sensor. 
  + The Raspberry Pi sends a two-byte command to the Arduino Nano with the force limitation and linear actuator command.
  + The Arduino Nano sends a one-byte + indetermined number for force reading to the Raspberry Pi.
