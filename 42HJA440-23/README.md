## 42HJA440-23 (unknown manufacturer)

![image of a stepper motor]()

This stepper motor is a total mystery - it looks about as generic as things can get, and the total lack of identifying features other than the part number stamped on the back makes it all the more intriguing to me. But probably it's just another clone of a clone. I'll certainly work fine for a 3D printer or something, with a microstepping performance on par with that of most other modern Chinese low-cost steppers. Since I didn't find a concrete current rating, I theoretically should've established a new one through actual testing, but seeing as these NEMA 17s are all so similar, I basically just guesstimated a value that felt right. Taking the relatively low phase resistance of only 1.5Ω into account, I went with 1.64A, which is definitely as arbitrary as it is to be taken with a grain of salt. In continuous use, I would probably run this motor closer to 1.5A or less, depending on how hot it gets. If you happen to have one of these, please run your own tests; even something simple with an A4988 like I did in the video will easily give you a much more reliable reference and prevent anything from being damaged. That said, I needed a baseline for my testing and couldn't spend another day letting stepper motors run idle in the basement.

Here some of the search results that sounded the most relevant, though none of them is actually referring to this model as far as I can tell:

 - https://www.made-in-china.com/showroom/seaweedtan/product-detailzMAEstGCaZRr/China-42mm-Stepper-Motor-for-Lighting-Equipment-42HJA440-20-.html
 - https://www.ubuy.fr/en/catalog/product/view/id/12983460/s/dp-cinkco-nema-17-stepper-motor-2phase-17-bipolar
 - https://www.machineto.com/textile-printing-equipment-stepper-motor-10238961

There are also exported PDF versions for each of these sites as a backup in case any of them goes down in the future.

Intellectual property rights for any graphics and logos depicted in screenshots of those sites obviously go to their respective site owners and are not part of this open-source repository, as I have no rights to distribute these myself. (in other words, stating the obvious to make sure I cover my ass for legal purposes here: the fact that I'm sharing screenshots with these logos and graphics in them in a CC-BY-SA-4.0 repository doesn't mean the license extends to those graphics)
