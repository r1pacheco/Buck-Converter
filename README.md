# Buck-Converter

This buck converter uses a simple switcher, LM2576SX,to hold a steady 3.3V output with the a
certain configuration. My board uses this switch along with schottky diode and an inductor to 
limit a linear range of voltage pass. We have high input voltage (between 12V and 16V) so we
opt for screw terminal input, but use molex outpit pins for the lower voltage output as the
load for this board is a ESP8266 wifi MC that has molex input pins for power.

--------------------------------------PARTS---------------------------------------
Simple Switcher:
https://www.digikey.ca/en/products/detail/texas-instruments/LM2576SX-3-3-NOPB/366792

Diode:
https://www.digikey.ca/en/products/detail/nexperia-usa-inc/BAT760115/1232134

Inductor:
https://www.digikey.ca/en/products/detail/bourns-inc/SRR1806-221M/1129809

Capacitors:
(100uF) https://www.digikey.ca/en/products/detail/nichicon/UWX1C101MCL1GB/589846

(330uF) https://www.digikey.ca/en/products/detail/nichicon/UWT1C331MNL1GS/589921