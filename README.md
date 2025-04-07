# AC-Switch-Blink-Project
Arduino Nano Mains Control Switch.
By: Javier.
https://sites.google.com/view/b-eng-jarl/home

Based in Arduino example: 01-Basics/Blink:
  Successful implementation results in a blinking domestic light bulb at a 0.5Hz frequency with 50% duty cycle.

Design considerations:
  G1. Nominal topology shall operate with mains 127VAC @ 60Hz.
  G2. Mains load may operate solely with positive polarity peak voltage (Vp).
  G3. Mains switching is purely boolean.

Benefits:
  B1. 97.5% enhance in mains power consumption compared to triac & optocoupled switching topologies.
  B2. Enhanced safety beneficial to user and control equipment via optocoupling as per corresponding isolation rating (e.g. 5000V).
  B3. Full AC to DC integration to embedded control systems (e.g. Arduino, Atmel, Microchip, among other C-based).
  B4. Off-the-shelf viability down to component level.
  B5. Stand-alone solution, does not require USB connectivity to peripheral PCs or devices to operate.

Topology description:
  D1. AC switching topology is to integrate with control chip/board as per schematic: "20250407 - SCH - AC Switch 'Blink' Project.pdf"

Further reading/research media:
  FR1. Simon Monk, Electronics Cookbook. Published by O'Reilly Media, Inc.
  FR2. Paul Scherz, Simon Monk. Practical Electronics for Inventors, Fourth Edition, 4th Edition. Published by McGraw-Hill Education TAB. e-ISBN 978-1-25-958755-9.
  FR3. ARDUINO. Arduino Nano Reference Manual. SKU: A000005.
  FR4. ARDUINO. Arduino Nano Wiring Schematic. https://www.arduino.cc/en/uploads/Main/Arduino_Nano-Rev3.2-SCH.pdf.
  FR5. TEXAS INSTRUMENTS. LM1117. Sheet No.: SNOS412Q – FEBRUARY 2000 – REVISED JANUARY 2023.
  FR6. SHARP. PC817XxNSZ1B Series. Sheet No.: OP18002EN.
  FR7. ATMEL. ATMega328p. Sheet No.: 7810D-AVR-01/15.
  FR8. INFINEON. IRFP250NPbF. Sheet No.: Rev. 2.1, 2024-10-08.
