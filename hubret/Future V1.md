Something like https://www.amazon.ca/MEAN-WELL-RD-35A-Supply-Output/dp/B00FRBN2CK to power both a computer (arduino/rpi) and the pump. 5v out goes to the computer, and 12v out powers the pump.

I think a IRLZ44N MOSFET each to switch the pump and the fans.

Possible temperature sensor locations:
G1/4 sensor on the second pump inlet
G1/4 sensor on a T-joint at both ends of the radiator
Temperature probe or combo temp/humidity sensor inside the bed

Still need a case solution to house everything.

Might modify the potentiometer on the bottom of the vario to be spinnable by fingers, since its a pain to go under and try to adjust it with a screwdriver, and im not quite sure about mounting the pump and reservoir sideways.

The tachy wire can be plugged into the computer.

Ideally, the computer is a raspberry pi so that it can easily/more rapidly (in terms of setup) write sensor data to an onboard webserver or push sensor data to an api.

# Corrosion/bio

I don't think bioactivity is a huge concern, though I want to make it a lot easier to flush out all the water in the system, since over time the distilled water will have dissolved some of the metal inside the loop. The radiator and the reservoir are both aluminum, I'm pretty sure the faceplate of the pump is aluminum (the rotor of the pump is plastic), and the barbs are copper.

Maybe a T joint in the intake port of the pump that can hoo k up to a bottle of water for flushing.