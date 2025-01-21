## JAPAN SERVO KP39HM2-025

![image of a stepper motor](https://github.com/ChronicMechatronic/Stepper-motor-benchmarking/blob/main/JAPAN%20SERVO%20KP39HM2-025/(3)%20JAPAN%20SERVO%20KP39HM2-025.jpg)

This motor is difficult. Apparently, it came from a 5 1/4-inch disk drive, so it must be quite old at this point - which explains why it was actually unipolar in its stock configuration. I disassembled mine and wired both sides of the center tap in each coil in parallel to reduce total phase resistance and inductance for use in a bipolar configuration. It's not quite the usual unipolar-to-bipolar mod, so here's an image for illustration:
![improved unipolar-to-bipolar wiring configuration](https://github.com/ChronicMechatronic/Stepper-motor-benchmarking/blob/main/JAPAN%20SERVO%20KP39HM2-025/Improved%20unipolar-to-bipolar%20mod.png)

Given that I ran my tests after doing these modifications to the motor, all the data you see here will obviously only apply to models of this stepper that underwent the same treatment (which I don't recommend doing, btw, as it turned out the air gap between the rotor and stator is only like 0.1mm all around, which means it's basically impossible to reassemble the motor without the rotor scraping against the stator laminations unless you have some very specific alignment tools at your disposal. That's something I didn't mention in the video.)

Through trial & error I determined an appropriate operating current for my modified motor to be 0.23A, which is surprisingly close to the 0.2A I saw specified on some websites I found.
Here are links to everything I found online about this motor:

 - Forum post from 2003 mentioning the 5 1/4-inch disk drive: https://forum.nutsvolts.com/viewtopic.php?t=4466
 - The broken product page listing voltage and current: http://us.100y.com.tw/PNoInfo/9743.htm
 - Another product page confirming that info: https://www.yoycart.com/Product/544148608932/

There are also exported PDF versions for each of these sites as a backup in case any of them goes down in the future.

Intellectual property rights for any graphics and logos depicted in screenshots of those sites obviously go to their respective site owners and are not part of this open-source repository, as I have no rights to distribute these myself. (in other words, stating the obvious to make sure I cover my ass for legal purposes here: the fact that I'm sharing screenshots with these logos and graphics in them in a CC-BY-SA-4.0 repository doesn't mean the license extends to those graphics)

I originally planned to use this motor in a 3D printer, so I made a pretty detailed CAD model for it. I included the .STEP file here, but you can also download it from my GrabCAD:
 - https://grabcad.com/library/nema-16-stepper-motor-kp39hm2-025-1
