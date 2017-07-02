=================================
ttn.ino is the code for sending package by the end device Arduino Uno.
Library used: https://github.com/abouillot/LoRa-LMIC-1.51

=================================
Clean_data contains the raw data measured in 4 routes(north route twice).
Payload can be used to recognise the different spot.

=================================
EWI_Measurement contains the raw data with SF7 and SF9 on floor 0,3,5,10,15,20(with payload 1,2,3,4,5,6) in EWI build, tu delft.
_7b means the nearest spot in each floor with SF7.
_9w means the farthest spot in each floor with SF9.