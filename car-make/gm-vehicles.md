---
description: What do you need for GM vehicles
---

# GM Vehicles

### Vehicles require Pedal and GM harness set

\*\* Pedal firmware for Bolt vehicles is still updating regularly. DFU key is highly recommended for a bolt pedal.

#### What is needed:

1. [Pedal](../beartech/comma-pedal-description-and-installation-guide.md)
2. [Harness & Harness box](../beartech/harness-and-harness-box-description.md) (To connect the pedal, you will need a harness box with rj45 port)

#### GM:&#x20;

* Chevy Bolt EV with and without ACC (before 2022)
* Chevy Bolt EV without ACC after 2022
* Chevy Bolt EUV with and without ACC (before 2022)
* Chevy Bolt EUV without ACC after 2022
* Chevy Volt without ACC, with LKAS\
  (For Volt without ACC, without LKAS, you will need to flash your car and use comma's OBD harness)

### How to identify which version of harness box is needed:

1. If you have a harness box with rj45 port - you DO NOT need another harness box to use pedal
2. If have a harness box purchased from Comma, with no rj45 port - you will need a 2x9 pin box
3. If you plan to purchase the harness + box (GM only) from me, then it is 2x13 pin box
4. If you purchased a used harness with no box, please DM me the picture of your harness. (the old ones before 2024 June are 2x13 pin)
5. If you purchased a customized harness for Tesla, you will need a 2x13 pin box

#### What else do you need:

* An ethernet cable
  * For smaller cars, 11ft in length or more&#x20;
  * Please avoid flat noodle cable

***

### Vehicles require GM Harness & Harness box

#### What is needed:

1. [Harness & Harness box](../beartech/harness-and-harness-box-description.md) (To connect the pedal, you will need a harness box with rj45 port)

#### GM:&#x20;

* Chevy High Country
* Chevy Silverado
* GMC Sierra with ACC, 2020, 2021
* Chevy Suburban
* Chevy Equinox
* Chevy Malibu without ACC
* Cadillac XT5 2018, 2021
* &#x20;(some other Cadillac models may apply too)

***

### Vehicles require ASCM Harness Plus & Harness box

ASCM Harness Plus is for steering control \
The "Plus" means it is ready to use with SASCM Module for Openpilot Longitudinal control.&#x20;

**Please make sure your vehicle has ASCM harness connection point to proceed**

Please find more detailed information: [ASCM](../beartech/ascm-harness-plus.md)&#x20;

#### What is needed:

1. [ASCM](../beartech/ascm-harness-plus.md) Harness

#### GM:&#x20;

* Chevy Volt (2018-2019)  （with Adaptive Cruise Control）- _pedal optional for start from stop_
* Acadia Denali （2018）
* Chevy Malibu (Before 2018)
* Regal TourX&#x20;
* Cadillac ELR (2014) - _Possibly work_
* Cadillac Escalade (2017-2020)  （with Adaptive Cruise Control） - _Possibly work_
* Cadillac Escalade ESV (2019-2020)  （with Adaptive Cruise Control） - _Possibly work_

***

### Vehicles require SDGM Harness & Harness box

For steering control

**Please make sure your vehicle has SDGM harness connection point to proceed**\
(Usually behind OBD port, if not, please check the back of your trunk)\
Please find more detailed information: [SDGM Harness](../beartech/sdgm-harness.md)

#### What is needed:

1. [SDGM Harness](../beartech/sdgm-harness.md)



**Supported vehicles:**

**Your vehicle HAS to have LKAS to support SDGM.**&#x20;

**(If your car make is listed, but the year is different. SDGM might work if you have ACC or lane keep.)**

**SDGM A:**

* Buick Enclave (2019)
* Buick Baby Enclave (CN)
* Chevy Volt (2019)
* Cadillac XT4 (2023)
* Chevy Traverse  (2022, 2023)
* Chevy Malibu XL 2019

**SDGM B:**

* Cadillac XT6
* Chevy Blazer 2022, 2025

***

### Vehicles require SASCM&#x20;

For speed control and to retain AEB.

If you use SASCM, you will need the ASCM Harness Plus.

**Please make sure your vehicle has SASCM connection point to proceed**\
Please find more detailed information: [SASCM](../beartech/sascm.md)

#### What is needed:

1. [SASCM](../beartech/sascm.md)

#### GM:&#x20;

* Chevy Volt (2016-2017)  （with Adaptive Cruise Control）
* Chevy Volt (2018-2019) （with Adaptive Cruise Control）- _pedal optional for start from stop_
* Acadia Denali （2018）
* Buick Enclave
* Cadillac XT4
* Chevy Traverse  (2022-2023)
* Buick Baby Enclave&#x20;
* Cadillac XT5
* Cadillac XT6&#x20;
* Chevy Malibu XL



#### More information regarding GM vehicles  - Comma Wiki for GM

{% embed url="https://github.com/commaai/openpilot/wiki/GM" %}

**GM Bolt Installation Guide**&#x20;

[https://docs.google.com/document/u/0/d/1-MPeSlzj-705sbGkDHYGqSl7sVDFSFTqGrebiH0gNfY/mobilebasic#h.1tvlrgmmu9ao](https://docs.google.com/document/u/0/d/1-MPeSlzj-705sbGkDHYGqSl7sVDFSFTqGrebiH0gNfY/mobilebasic#h.1tvlrgmmu9ao)
