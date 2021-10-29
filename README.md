# ZMPT101B-3.3V-ADC
 ZMPT101B based module enhanced for use with 3.3V assymetric ADC
The common module based on ZMPT101B current transformer uses the same tension reference for powering the OpAmps and offsetting the output signal.
Due to the output voltage swing the full operation range cannot be used which severly limits the resolution of the module when operating in the range of 0-3.3 V.
As a solution to this problem I proposed the use of different input pins for the offset voltage and the positive rail voltage. which allows us to benefit from the linear range of 5V operation while using offset appropriate for the 3.3V ADC.
Care should be taken with the amplification ratio to not exceed the save range of the ADC.

this repository includes the gerber files of the module in addition to the schematic and the KiCad project files. 