## TRONXY 42SHDC4080Z-25B

![image of a stepper motor](https://github.com/ChronicMechatronic/Stepper-motor-benchmarking/blob/main/TRONXY%2042SHDC4080Z-25B/(11)%20TRONXY%2042SHDC4080Z-25B.jpg)

This stepper motor is clearly from a TRONXY 3D printer, which is why I was all the more surprised by the fact that there was absolutely no info about it online. Ultimately I guess it's just another generic clone of an obscure Chinese stepper motor. Unfortunately, Tronxy also didn't bother to list any specs anywhere either, as the replacement steppers they sell on their website have a different part number altogether. They're called "SL42STH40" instead, so short of sending TRONXY an email asking about the specs (which I don't feel bold enough to do), we're basically on our own if we want specs for the 42SHDC... Or are we? With a bit of _imaginative_ reasoning, we can assume the SL42STH40 steppers they currently sell are very similar clones - after all, what are the odds they actually changed suppliers or specifications? Relatively low, is my gut feeling. Physically they look identical save for the label, which obviously doesn't say much. So since I needed a baseline current rating for my testing, I decided to just go with the same 1.8A current rating they claim for their current SL42STH motor. Though I'm honestly not sure whether to trust that rating either, despite the low 1.6Ω winding resistance suggesting this motor would indeed run at a higher current than its 3Ω NEMA 17 brethren. So in continuous use, I would probably run this motor closer to 1.5A or less, depending on how hot it gets. If you happen to have one of these, please run your own tests; even something simple with an A4988 like I did in the video will easily give you a much more reliable reference and prevent anything from being damaged. I just didn't have the time to spend another day letting stepper motors run idle in the basement.

That said, here are the few most relevant-looking search results I was able to come up with:

 - https://www.tronxy3d.com/collections/motor/products/sl42sth40-1684a-1-8a-78oz-in-42-stepper-motor
 - https://botland.store/flashforge-replacement-parts/18649-stepper-motor-42shdc1065z-19wt-200-steps-448v-08a-028nm-for-flashforge-adventurer-3-5904422362294.html
 - https://www.tronxy3d.com/products/tronxy-3d-printer-parts-sl42sth60-1684a-motor-with-1-5m-cable?variant=44347991228660
 - https://www.alibaba.com/product-detail/42SHDC3025-24B-stepper-motor-for-eco_1600961608090.html
 - https://french.alibaba.com/product-detail/CE-Approved-2-Phase-Stepper-1-62149025114.html

There are also exported PDF versions for some of these sites as a backup in case any of them goes down in the future.

Intellectual property rights for any graphics and logos depicted in screenshots of those sites obviously go to their respective site owners and are not part of this open-source repository, as I have no rights to distribute these myself. (in other words, stating the obvious to make sure I cover my ass for legal purposes here: the fact that I'm sharing screenshots with these logos and graphics in them in a CC-BY-SA-4.0 repository doesn't mean the license extends to those graphics)
