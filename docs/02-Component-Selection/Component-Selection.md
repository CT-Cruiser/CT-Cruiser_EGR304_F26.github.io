---
title: Component Selection
---


Here is informaiton regarding the rationale for selecting the components that will be put in my subsystem board. 

*Table 1: Flow Sensor component selection*

**Flow Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](MFG_PDV-P8103_sml(200x200).webp)<br>Option 1.<br> PDV-P8103 Photoresistor <br>$0.77/each<br>[link to product](https://www.digikey.com/en/products/detail/advanced-photonix/PDV-P8103/480610)                 | \* Inexpensive<br>\* Accepts 5 Volts <br>\* Rated resistance rate is desirable                                               | \* Might Have trouble getting to work with resistive amp  |
| ![](NORPS-12_sml.jpg)<br>\* Option 2. <br>\* NORPS-12 Photoresistor <br>\* $2.46/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/advanced-photonix/NORPS-12/5039796) | \* Reliable <br>\* Two-leaded package  | \* More expensive                                                        |
| ![](TO-18-Photocell_sml.jpg)<br>\* Option 3. <br>\* NSL-5110 Photoresistor <br>\* $3.19/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/advanced-photonix/NSL-5110/5039795) | \* Resistance Values are desriable <br>\* Wide operating temperature  | \* Most Expensive                                                       |

**Choice:** Option 1: PDV-P8103 Photoresistor

**Rationale:** This photo sensor has desirable resistance values for the application. It is also the least expensive option on digikey, since cost is a concern for this project.  

 

 *Table 2: Flow Sensor Switching Mosfet component selection*

**Switching Mosfet**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](1727~SOT23-3~~3_sml(200x200).webp)<br>Option 1.<br> Toshiba SSM3J36FS P-Channel Mosfet <br>$0.27/each<br>[link to product](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/SSM3J36FS-LF/2071880)                 | \* Voltage is desirable                                               | \* Requires a negative supply voltage |
| ![](264~2-2H1B~~3_sml(200x200).webp)<br>\* Option 2. <br>\* Nexperia 2N7002NXAKR N-Channel Mosfet <br>\* $0.14/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/nexperia-usa-inc/2N7002NXAKR/10416554) | \* N-Channel mosfet <br>\* Inexpensive <br> | \* Heat sensitive                     |
| ![](1727~SOT23-3~~3_sml(200x200).webp)<br>\* Option 3. Toshiba T2N7002AK N-Channel Mosfet <br>\*  <br>\* $0.17/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/T2N7002AK-LM/5298028) | \* Reputable manufacturer <br>\* Tried and true design  | \* More expensive                                                      |


**Choice:** Option 2: Nexperia 2N7002NXAKR N-Channel Mosfet

**Rationale:** This mosfet is best since it works within the limits of my proposed design as well as the price. 

## Power Budget 

