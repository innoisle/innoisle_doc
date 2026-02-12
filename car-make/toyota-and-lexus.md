---
description: What do you need for Honda vehicles
---

# Toyota & Lexus

### Notice:

Comma released a new update for their official branch 0.9.7. SDSU will no longer be supported in the official openpilot.

**If you would like to continue to use SDSU, please switch to SunnyPilot or FrogPilot.**

**Please see the SDSU page for details:**&#x20;

{% embed url="https://docs.innoisle.com/beartech/sdsu-description-and-installation-guide" %}

### Vehicles require SDSU + Pedal

#### What is needed:

1. [SDSU](../beartech/sdsu-description-and-installation-guide.md)
2. [Pedal](../beartech/comma-pedal-description-and-installation-guide.md)
3. [Splitter](../beartech/obd-power-and-splitter-description.md) (only if you have an RJ45 Comma Power connected)
4. [Harness box](../beartech/harness-and-harness-box-description.md) (To connect the pedal, you will need a harness box with rj45 port)

#### Why do you need both SDSU and Pedal:

You will use openpilot longitudinal control instead of Toyota TSS-P ACC

Your vehicle needs to have ACC (so that you will have the DSU port that connects SDSU)

[SDSU](../beartech/sdsu-description-and-installation-guide.md) helps openpilot to gain longitudinal control. This will allow your openpilot the ability to accelerate from 20mph and slow down to 0mph. **SDSU will enable experimental mode.**

[Pedal](../beartech/comma-pedal-description-and-installation-guide.md) covers the acceleration from 0mph to 20mph

#### Toyota:

* Toyota Avalon 2016-2021
* Toyota Avalon Hybrid 2019-2021
* Toyota Corolla 2017-2019
* Toyota Highlander (and Hybird) 2017-2019
* Toyota Prius 2016-2020  (Pedal Optional: Pedal only helps in lowering the power draw in a standstill on Prius)
* Toyota Prius Prime 2017-2020  (Pedal Optional: Pedal only helps in lowering the power draw in a standstill on Prius)
* Toyota Prius V 2017
* Toyota Rav4 (and Hybird) 2016-2018
* Toyota Sienna 2018-2020
* 2019 Toyota Kluger (Highlander name in Australia)
* Toyota CHR Thailand version 2019 (with standard DSU)



#### **Lexus:**

* Lexus ES (and Hybird) 2017-2018
* Lexus CT Hybrid 2017-2018
* Lexus NX (and Hybird) 2018-2019
* Lexus RX (and Hybird) 2016-2019
* Lexus IS (200T) 2017-2020&#x20;
* Lexus RC 2018-2021 not verified, but should work
* Lexus GS 2016-2020 not verified, but should work
*
* For Lexus vehicles, **add a pedal** if you encounter either of the occasions:&#x20;
* 0-25mph acceleration still requires you to step on your gas pedal
* The sng hack in the fork you use does not work for 0-25mph

***

### Vehicles require SDSU ONLY

#### What is needed:

1. [SDSU](../beartech/sdsu-description-and-installation-guide.md)

#### Toyota:

* Toyota RAV4 Hybrid&#x20;
* Toyota Highlander&#x20;
* Most of the Toyota Hybrid Vehicles requires SDSU only

***

### Vehicles require CANfilter ONLY (NO SDSU, NO Pedal)

#### What is needed:

1. CANfilter (still under development)

#### Toyota:

* Toyota Camry
* Toyota CHR
* Toyota RAV4 2024

### How to identify which version of harness box is needed:

1. If you have a harness box with rj45 port - you DO NOT need another harness box to use pedal
2. If have a harness box purchased from Comma, with no rj45 port - you will need a 2x9 pin box
3. If you plan to purchase the harness + box (GM only) from me, then it is 2x13 pin box
4. If you purchased a used harness with no box, please DM me the picture of your harness. (the old ones before 2024 June are 2x13 pin)
5. If you purchased a customized harness for Tesla, you will need a 2x13 pin box
