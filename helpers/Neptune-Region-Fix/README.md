# Neptune Region Fix

A flex pcb to help fix the region issue.

See Service bulletin CSB\_NEP\_001

![NeptuneRegionFix]

It should align up with the pin 81 on IC6 to GND on the EXT Header.

I made the flex long, so it can be held done with something as it is quite small otherwise.

##Flex PCB Production

When adding gerbers to your PCB Manufacturer, please choose the flex pcb option and add a note that you want to cut across the pads.

Otherwise they may ask you to change the gerber.

The current flex [Gerber][NeptuneRegionFixGerber] was produced to JLCPCB Specifications.

[NeptuneRegionFix]: https://raw.githubusercontent.com/Board-Folk/Neptune/master/helpers/Neptune-Region-Fix/images/Nep_Region_Fix.jpg

[NeptuneRegionFixGerber]: https://raw.githubusercontent.com/Board-Folk/Neptune/master/helpers/Neptune-Region-Fix/production/Neptune-Region-Fix.zip