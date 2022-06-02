# Powering the pump, fans, and computer

## Option A

Arcade power supply. Something like https://www.amazon.ca/MEAN-WELL-RD-35A-Supply-Output/dp/B00FRBN2CK to power both a computer (arduino/rpi) and the pump. 5v out goes to the computer, and 12v out powers the pump.

I think a IRLZ44N MOSFET to switch the pump during sleeping time, and 4 pin fans connected to the computer for temperature controlling.

Downside is that the power supply needs DIY wiring to be hooked up to 120v main, and will just kind of have loose wiring everywhere after hooking up the pump and fans.

## Option B

Get a cheap ATX PSU with the ATX 24 pin connector + a [breakout](https://www.amazon.ca/SUPERPLUS-Upgrade-Version-Benchtop-Breakout/dp/B07JLT314P?th=1) for 12v and 5v. At this point it would be identical to the arcade power supply, with the exception that you can plug it into the wall easily with a power cable. If the breakout also includes fan headers it will be even easier to wire the fans in.

# Sensors

Possible temperature sensor locations:
G1/4 sensor on the second pump inlet
G1/4 sensor on a T-joint at both ends of the radiator
Temperature probe or combo temp/humidity sensor inside the bed

The tachy wire can be plugged into the computer.

# Case/tactiles

Still need a case solution to house everything.

Might modify the potentiometer on the bottom of the vario to be spinnable by fingers, since its a pain to go under and try to adjust it with a screwdriver, and im not quite sure about mounting the pump and reservoir sideways.

# Computer

Ideally, the computer is a raspberry pi so that it can easily/more rapidly (in terms of setup) write sensor data to an onboard webserver or push sensor data to an api.

# Corrosion/bio

I don't think bioactivity is a huge concern, though I want to make it a lot easier to flush out all the water in the system, since over time the distilled water will have dissolved some of the metal inside the loop. The radiator and the reservoir are both aluminum, I'm pretty sure the faceplate of the pump is aluminum (the rotor of the pump is plastic), and the barbs are copper.

Maybe a T joint in the intake port of the pump that can hook up to a bottle of water for flushing.
