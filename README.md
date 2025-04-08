# AC-Switch-Blink-Project
<p>Arduino Nano Mains Control Switch.</p>
<p>By: Javier. https://sites.google.com/view/b-eng-jarl/home</p>
<br></br>
<p>Based in Arduino example: 01-Basics/Blink:</p>
<p>Successful implementation results in a blinking domestic light bulb at a 0.5Hz frequency with 50% duty cycle.</p>
![Uploading VAC Blink.GIF…]()

<br></br>
<p>Topology Schematic:</p>
<p>Note: components are to be dimensioned to suite AC switching application and local component availability</p>
<p>glad to advise under request</p>
![20250407 - SCH - AC Switch 'Blink' Project](https://github.com/user-attachments/assets/28d0a585-1d72-4d4e-9d7c-bf1834e645e3)


<br></br>
<p>Design considerations:</p>
<p>G1. Nominal topology shall operate with mains 127VAC @ 60Hz.</p>
<p>G2. Mains load may operate solely with positive polarity peak voltage (Vp).</p>
<p>G3. Mains switching is purely boolean.</p>
<br></br>
<p>Benefits:</p>
<p>B1. 97.5% enhance in mains power consumption compared to triac &amp; optocoupled switching topologies.</p>  
<p>B2. Enhanced safety beneficial to user and control equipment via optocoupling as per corresponding isolation rating (e.g. 5000V).</p>
<p>B3. Full AC to DC integration to embedded control systems (e.g. Arduino, Atmel, Microchip, among other C-based).</p>
<p>B4. Off-the-shelf viability down to component level.</p>
<p>B5. Stand-alone solution, does not require USB connectivity to peripheral PCs or devices to operate.</p>
<br></br>
<p>Topology description:</p>
<p>D1. AC switching topology is to integrate with control chip/board as per ...</p>
<br></br>
<p>Further reading/research media:</p>
<p>FR1. Simon Monk, Electronics Cookbook. Published by O'Reilly Media, Inc.</p>
<p>FR2. Paul Scherz, Simon Monk. Practical Electronics for Inventors, Fourth Edition, 4th Edition. Published by McGraw-Hill Education TAB. e-ISBN 978-1-25-958755-9.</p>
<p>FR3. ARDUINO. Arduino Nano Reference Manual. SKU: A000005.</p>
<p>FR4. ARDUINO. Arduino Nano Wiring Schematic. https://www.arduino.cc/en/uploads/Main/Arduino_Nano-Rev3.2-SCH.pdf.</p>
<p>FR5. TEXAS INSTRUMENTS. LM1117. Sheet No.: SNOS412Q &ndash; FEBRUARY 2000 &ndash; REVISED JANUARY 2023.</p>
<p>FR6. SHARP. PC817XxNSZ1B Series. Sheet No.: OP18002EN.</p>
<p>FR7. ATMEL. ATMega328p. Sheet No.: 7810D-AVR-01/15.</p>
<p>FR8. INFINEON. IRFP250NPbF. Sheet No.: Rev. 2.1, 2024-10-08.</p>
