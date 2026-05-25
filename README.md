# PowerBox

This project is an all in one power solution for something like a cyber deck.

# Components

PowerBox has 7 main compoments:
1. A usbc port with a pd sink controller to request 12v as the when fully loaded the ciruit can pull up to 36W!!
2. 2x Buck DC-DC convertors (TPS54620)
3. 2x Ideal diode ciruits (done as when the usb power is present I switch off the buck that is supplied by the batteries so the poor batt charger doesn't blow up. This creates a situation where the buck can see negative volts which it is not rated for hense the diode)
4. I made a bms circuit with the DW01A a very common bmc controller chip
5. An A 2S balance charger using the BQ2588RGER that can do 2A yippe


