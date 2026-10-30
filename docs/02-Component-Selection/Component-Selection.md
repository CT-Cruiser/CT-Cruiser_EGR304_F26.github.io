---
title: Component Selection
---


Here is informaiton regarding the rationale for selecting the components that will be put in my subsystem board. 

*Table 1: Flow Sensing Resistor*

**Photoresistor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](MFG_PDV-P8103_sml(200x200).webp)<br>Option 1.<br> PDV-P8103 Photoresistor <br>$0.77/each<br>[link to product](https://www.digikey.com/en/products/detail/advanced-photonix/PDV-P8103/480610)                 | \* Inexpensive<br>\* Accepts 5 Volts <br>\* Rated resistance rate is desirable                                               | \* Might Have trouble getting to work with resistive amp  |
| ![](NORPS-12_sml.jpg)<br>\* Option 2. <br>\* NORPS-12 Photoresistor <br>\* $2.46/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/advanced-photonix/NORPS-12/5039796) | \* Reliable <br>\* Two-leaded package  | \* More expensive                                                        |
| ![](TO-18-Photocell_sml.jpg)<br>\* Option 3. <br>\* NSL-5110 Photoresistor <br>\* $3.19/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/advanced-photonix/NSL-5110/5039795) | \* Resistance Values are desriable <br>\* Wide operating temperature  | \* Most Expensive                                                       |

**Choice:** Option 1: PDV-P8103 Photoresistor

**Rationale:** This photo sensor has desirable resistance values for the application. It is also the least expensive option on digikey, since cost is a concern for this project.  

 

 *Table 2: DC Linear Regulator Component Selection*

**DC Linear Regulator**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](786138.jpg)<br>Option 1.<br> LM7805 <br>$2.25/each<br>[link to product](https://www.jameco.com/z/LM7805CT-National-Semiconductor-IC-LM7805CT-5V-1A-Positive-Voltage-Regulator-40C-125C-Temp-_786138.html)                 | \* Voltage is desirable                                               | \* Not as effecient |
| ![](S786138.jpg)<br>\* Option 2. <br>\* LM7905 Linear Regulator <br>\* $1.72/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM7905CT-NOPB/6349) | \* 5v regulator <br>\* No external components to set voltage <br> | \* Negative output                    |
| ![](488~369C-01~D,DT~2_sml(200x200).webp)<br>\* Option 3. <br>\* MC78M05BDTRKG Linear Regulator <br>\* $0.47/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/onsemi/MC78M05BDTRKG/919369) | \* Least Expensive <br>\* Output voltage is fixed  | \* Surface Mount Design                                                      |


**Choice:** Option 1: LM7805 Linear Regulator

**Rationale:** This liner regulator is a through-hole design and doesn't need external circuitry (except conditioning capicitors) to output 5v DC. 


*Table 3: Op Amp*

**Op Amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](mcp6006.webp)<br>Option 1.<br> MCP 6006 Op Amp <br>$0.21/each<br>[link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6006T-E-OT/13985876)                 | \* Rail to Rail output                                               | \* Only One Op Amp <br>\* Surface Mount Design |
| ![](mcp6004.jpg)<br>\* Option 2. <br>\* MCP6004 Op Amp <br>\* $0.60/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060) | \* Contains 4 Op-Amps <br>\* Inexpensive <br> | \* Can only handle 5v                    |
| ![](STMOPAMP.webp)<br>\* Option 3. <br>\* LM358DT Op Amp  <br>\* $0.21/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/LM358DT/591693) | \* Inexpensive <br>\* 2 Op Amps  | \* Surface Mount Design                                                      |


**Choice:** Option 2: MCP 6004 Op Amp

**Rationale:** This Op Amp chip comes with our kit, and is more than adequate for the application. 
## Power Budget 

