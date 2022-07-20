# Gotchas

- arctic p12 pwm pst does not have 0db mode anymore (meaning that the fan has a minimum speed and will not stop if pwm signal is low enough) which is a bummer
- The arduino PWM does not have the correct frequency to modulate fan speed. very very unfortunate
- The tacho wire from the fans need the voltage modified in order to get a correct reading. i think it needs to be pulled up

I think can still control fan speed using voltage control, so I might test the system with the fans running at a set speed
