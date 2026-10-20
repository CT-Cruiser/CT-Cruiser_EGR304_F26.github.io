---
title: Component Selection
---


Here is informaiton regarding the rationale for selecting the components that will be put in my subsystem board. 

*Table 1: Flow Sensor component selection*

**Flow Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](MFG_314150005_sml.jpg)<br>Option 1.<br> 314150005 Flow Sensor <br>$9.50/each<br>[link to product](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/314150005/5488047)                 | \* Inexpensive<br>\* Accepts 5 Volts <br>\* Rated flow rate is desirable                                               | \* Requires MOSFET to interact with PIC <br>\* Connectors require 1/2 inch piping |
| ![](MFG_SLF3S-4000B-LIQUID-FLOW-SENSOR_sml.jpg)<br>\* Option 2. <br>\* SLF3S-4000B Liquid Flow Sensor <br>\* $191.87/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/sensirion-ag/SLF3S-4000B-LIQUID-FLOW-SENSOR/16579752) | \* Extremely Accurate <br>\* Communicates with I2C  | \* Very expensive <br>\* Flow might be too small                                                        |
| ![](SEN0216_sml(200x200).jpg)<br>\* Option 2. <br>\* SEN0216 Liquid Flow Sensor <br>\* $8.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0216/6579445) | \* Rated flow rate is desirable <br>\* Uses small 6mm ID piping  | \* Might not be as accurate                                                       |

**Choice:** Option 3: SEN0216 Liquid Flow Sensor

**Rationale:** This device uses a small ID tube which is better since we want to precisely control the amount we want to dispense. The amount of flow it is rated for should also be suitable. 

 

 *Table 2: Flow Sensor Switching Mosfet component selection*

**Switching Mosfet**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](1727~SOT23-3~~3_sml(200x200).webp)<br>Option 1.<br> Toshiba SSM3J36FS P-Channel Mosfet <br>$0.27/each<br>[link to product](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/SSM3J36FS-LF/2071880)                 | \* Voltage is desirable                                               | \* Requires a negative supply voltage |
| ![](264~2-2H1B~~3_sml(200x200).webp)<br>\* Option 2. <br>\* Nexperia 2N7002NXAKR N-Channel Mosfet <br>\* $0.14/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/nexperia-usa-inc/2N7002NXAKR/10416554) | \* N-Channel mosfet <br>\* Inexpensive <br> | \* Heat sensitive                     |
| ![](1727~SOT23-3~~3_sml(200x200).webp)<br>\* Option 3. Toshiba T2N7002AK N-Channel Mosfet <br>\*  <br>\* $0.17/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/toshiba-semiconductor-and-storage/T2N7002AK-LM/5298028) | \* Reputable manufacturer <br>\* Tried and true design  | \* More expensive                                                      |


**Choice:** Option 2: Nexperia 2N7002NXAKR N-Channel Mosfet

**Rationale:** This mosfet is best since it works within the limits of my proposed design as well as the price. 