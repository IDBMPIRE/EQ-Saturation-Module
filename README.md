# EQ Saturation Module
In the files above I have included the Max MSP file for my software emulation (7MU009) and photo documentation of my hardware device(7MU007).

The Max patch for 7MU009 is based on a hardware unit I am currently developing and have developed for 7MU007 the software version is in a basic form as it is still at a developmental stage.

The overall goal is to take audio signal and apply the process of saturation, An Equiliser has been implemented in order to sculp the signal going into the saturation/distortion process.

The hardware version incorporates a preamp, Shelving EQ, saturation module (overdrive) and a vactrol-style compression module (still in development) and a final output amplification stage, this is mirrored in software 

The hardware version runs from a low voltage power supply (9–15v), and five modules have been created (Preamp,EQ & Overdrive). The vactrol compression element is still in development stages on breadboard and the final amplification stage is yet to be built as it is just a duplication of the first initial pre amplification module. Included in this Github repository are the hardware schematics of all the elements utilised for the hardware unit. Housing has not yet been accomplished as all modules are not complete and I am currently developing a mini internal patch-bay system to allow changes in signal flow throughout the hardware unit.

Also included are the hardware schematics of all the elements utilised for the hardware unit.

Housing has not yet been accomplished as all modules are not complete and im currently developing a mini internal patchbay system to allow changes in signal flow throughout the hardware unit.

The software version is still as basic stages of development, as I want to finish the hardware version first in order to mirror and better certain elements in the software domain.

I have created a six band equiliser that feeds an overdrive module, in comparison to the hardware version which has a two band shelving style equiliser, this decision was made due to not getting the desired sonic qualities whilst working on the hardware version, I wanted to evaluate if the character wanted was achievable using software over hardware. 

Max MSP was my choice of software due to its tools and layout, I found it easier to create the neccesary elements needed to experiement with my concept, and I found its presentation mode very helpful when trying to test practicality and remove clutter in order to stay organised.

There are a multitude of similar software plugins that exist in the world of audio but the main concept I found interesting was a newer plugin from Waves Audio called the CLA Mix Down, it is (typically) used on the mix bus to shape the overall tone and character of the mix. It has two faders for equilisation (low and high) a compression stage which can be stwitched between two different styles of compression and finally it has a drive stage meant to emulate driving the faders harder into the mix console (Youtube,2017). To me this was simply Eq,Compression and saturation and this is why I took an interest in developing something similar.

The hardware version is has similarities with many things from individual guitar pedals (Fire,2017) to full hardware equipment i.e. channel strips, mixing consoles etc (insync,2007).

My interest in building a hardware version grew specifically when learning that guitar pedals could be used as outboard gear in conjuction with a reamping box and a di box,so I began to piece together a concept that could work as a instrumentation channel strip whilst recording (like a rack mounted guitar pedal) or as a piece of outboard hardware for mix purposes.

So far ive been able to make a lot of progress with my hardware version and I am working towards presenting a fully working rack mounted piece of outboard gear with a software version for comparison sake and also to utilise for further developments to my hardware version.


References

Fire, T. (2017). 16 Guitar Effects Pedals Every Guitar Player MUST Have. [online] TrueFire Blog. Available at: http://truefire.com/blog/guitar-gear/16-guitar-effects-pedals-you-must-have/ [Accessed 9 Jul. 2018].

inSync. (2007). Mixing Console - inSync. [online] Available at: https://www.sweetwater.com/insync/mixing-console/ [Accessed 9 Jul. 2018].

Youtube (2017). Waves - CLA MixDown - Mixing With Mike Plugin of the Week. [video] Available at: https://www.youtube.com/watch?v=yPSz7_i8qAY&t=1s&frags=pl%2Cwn [Accessed 9 Jul. 2018].
