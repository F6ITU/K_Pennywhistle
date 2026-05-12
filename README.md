# K_Pennywhistle

**K\_Pennywhistle**


A 20W HF amplifier by KE9H

Pennywhistle is a linear amplifier based on a pair of Mitsubishi FET (RD16HHF1 or RD15HVF1) that was originally used to boost the output power of the very first SDRs using the Hermes board.

Marketed as a kit by the TAPR, this amplifier—which is very easy to build—has long been out of production. 

In the meantime, numerous variations have emerged, notably the famous G6ALU, which was used in Picastar transceivers. 

This same amplifier is also integrated into the filter board of the Anan 100 series and serves as  driver for the RD100HHF1 output stage. 

Why build such a clone in 2026 ?

* Because this design is proven and has been built in the thousands
* To complete the collection of OpenHPSDR board clones already available on this GitHub repository
* Because it can deliver either 4 to 7 W with RD06HVF1 transistors or 15 to 20 W in its original version—power levels perfectly suited for driving a higher-power amplifier (Munin 1 to 4 series, Munin 100, Munin 400...)
* Because it can easily complement a "barefoot" SDR outputting 0.5 to 1 W 
* And because it is also compatible with the Ajax pre-driver module

It should be added that, technically speaking, it would be preferable to build a push-pull circuit using LDMOS transistors, such as the AFT05MS003... but the void left by the closure of NXP’s production facilities for high-frequency transistors and the resulting component shortage mean that a return—even a temporary one—to older technologies is far from unreasonable. 

Finally, this amplifier is probably one of the simplest circuits available, allowing beginners to tackle building a linear amplifier without spending a fortune. 

This project is licensed under the TAPR Open Hardware License and is the result of the work of Graham Haddock KE9H 

It's design has been made using Kicad 10 opensource EDA.

All building and tuning instructions could be found in the original Pennywhistle documentation (https://github.com/TAPR/OpenHPSDR-SVN/blob/master/PennyWhistle/Documentation/PennyWhistle%20Manual%20V1.2.pdf) 
