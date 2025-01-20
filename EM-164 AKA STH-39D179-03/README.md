## EM-164 / STH-39D179-03

![image of a stepper motor](https://github.com/ChronicMechatronic/Stepper-motor-benchmarking/blob/main/EM-164%20AKA%20STH-39D179-03/(4)%20EM-164.jpg)

The provenance of this stepper is a mystery - as is pretty much the entire motor. I found no reference whatsoever to this stepper motor, not even an image of an exact match, which is kind of surprising. What I do know is that it used to be unipolar - I disassembled mine and wired both sides of the center tap in each coil in parallel to reduce total phase resistance and inductance for use in a bipolar configuration. It's not quite the usual unipolar-to-bipolar mod, so here's an image for illustration:
[improved unipolar-to-bipolar wiring configuration](link)

Prior to this modification, the phase resistance used to be about 5.8Ω, which was halved to around 2.9Ω, a fairly common value for bipolar stepper motors. 
Seeing as this would've rendered all existing electrical specifications irrelevant anyway, the fact that I didn't find anything about this motor online wasn't a big problem - I simply determined a new appropriate operating current via trial and error. The current at which the stepper heated up to no more than 70°C at a room temperature of 20°C was 0.74 Amperes. The 70°C temperature limit was picked rather arbitrarily; the actual maximum operating temperature would be more like 80°C, as that's where the neodymium magnets start to degrade, so 70°C leaves some room for error. 

Given that I ran my tests after doing these modifications to the motor, all the data you see here will obviously only apply to models of this stepper that underwent the same treatment (which I don't recommend doing, btw, as it turned out the air gap between the rotor and stator is only like 0.1mm all around, which means it's basically impossible to reassemble the motor without the rotor scraping against the stator laminations unless you have some very specific alignment tools at your disposal. That's something I didn't mention in the video.)
