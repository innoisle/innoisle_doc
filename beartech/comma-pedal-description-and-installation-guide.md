---
description: 'Join our discord at: https://discord.innoisle.com/'
icon: goal-net
---

# Comma Pedal Description and Installation Guide

## Where to buy

Link to my Store: [https://shop.tlbb.ca/products/comma-pedal-non-customizable-toyota-honda-gm-vw-benz](https://shop.tlbb.ca/products/comma-pedal-non-customizable-toyota-honda-gm-vw-benz)

Link to my Etsy Store: [https://www.etsy.com/ca/listing/952895642/openpilot-comma-pedal-toyota-honda-gm-vw](https://www.etsy.com/ca/listing/952895642/openpilot-comma-pedal-toyota-honda-gm-vw)

Link to RetroPilot Store: [https://shop.retropilot.org/product/pedal/](https://shop.retropilot.org/product/pedal/)

***

### Update:

Firmware updated - For 2017-2021 Chevy bolt users, if you had  "propulsion error" using the pedal, please flash an updated software for your pedal. A dfu key is required for flashing. Pedal purchased after 2025-01-01 already has the up-to-date firmware

## Product Description

Comma Pedal is created and open-sourced by CommaAI to support cars to accelerate with no stop-and-go capability.&#x20;

For complete detail, please read this article:&#x20;

{% embed url="https://github.com/commaai/openpilot/wiki/comma-pedal" %}

All the electronic components from innoisle on this device are AEC-Q100 & AEC-Q200 qualified. All the connecting parts are from original equipment manufacturers. Assembled in Canada. 3D printed case with ASA automotive grade and UV resistant plastic.

## Notice

Comma released a new update for their new harness box in July 2024 . There is no more RJ45 port from the harness box and therefore, pedal is not supported by the new Comma harness box.

I have released my harness box; please choose the correct one for purchase.

There are two versions, 2x9 pin (new version by comma) and 2x13 pin (old version by comma). Please check your harness before ordering.

If you need the individual harness box, you can find it at : [https://shop.tlbb.ca/products/openpilot-harness-box-v1-2x13-pin-and-v2-2x9-pin-with-rj-45-port](https://shop.tlbb.ca/products/openpilot-harness-box-v1-2x13-pin-and-v2-2x9-pin-with-rj-45-port)

**A Splitter is needed if you are using OBD power (you will need an OBD power with RJ45 port).**

\*Pedals will not be refunded for the issue of using the wrong splitter.

#### How to identify which version of harness box is needed:

1. If you have a harness box with rj45 port - you DO NOT need another harness box to use pedal
2. If have a harness box purchased from Comma, with no rj45 port - you will need a 2x9 pin box
3. If you plan to purchase the harness + box (GM only) from me, then it is 2x13 pin box
4. If you purchased a used harness with no box, please DM me the picture of your harness. (the old ones before 2024 June are 2x13 pin)
5. If you purchased a customized harness for Tesla, you will need a 2x13 pin box

#### What else do you need:

* An ethernet cable
  * For smaller cars, 11ft in length or more&#x20;
  * Please avoid flat noodle cable
  * At least CAT6 cable is recommended
  * CAT8 cable couble be too thick and too hard to hide
  * There is a discussion about the ethernet cable under #customer service in the discord channel. Several tested cables were confirmed to work. Please search "ethernet" under that channel.

## **Currently supported vehicles**

#### GM:&#x20;

* Chevy Bolt EV
* Chevy Bolt EUV
* Chevy Volt without ACC
* Opel Ampera E (Same as Bolt, but in Europe)

#### Toyota:

* Toyota Avalon 2016-2021
* Toyota Avalon Hybrid 2019-2021
* Toyota Corolla 2017-2019
* Toyota Rav4 2016-2018
* Toyota Prius 2016-2020  (Pedal Optional: Pedal only helps in lowering the power draw in a stand still on Prius)
* Toyota Prius Prime 2017-2020  (Pedal Optional: Pedal only helps in lowering the power draw in a stand still on Prius)

**Lexus:**

* Lexus ES350 (and hybird)  2017-2018 (pedal optional)
* Lexus CT Hybird 2017-2018 (pedal optional)
* Lexus NX  (and hybird) 2018-2019 (pedal optional)
* Lexus RX  (and hybird) 2016-2019 (pedal optional)

#### Honda:&#x20;

* Honda CRV 2015-2016
* Honda Ridgeline 2017-2025
* Honda Pilot 2016-2022
* Honda Odyssey 2018-2020
* Honda Passport 2019-2023
* Honda HRV 2019-2022
* Honda Civic 2016-2018
* Honda Clarity 2016-2020
* Honda Fit 2018-2020
* Honda Freed 2020
* Honda Accord
* Honda Clarity

#### Acura:&#x20;

* Acura ILX 2016-2022
* Acura RDX 2016-2018

#### Volkswagen:&#x20;

* VW PQ platform&#x20;

**Tesla**:&#x20;

* Tesla Pre-AP



**Other Make and Models we customized before (but unsure about software compatibility, mainly for development use)**

* BMW 535i 2014 - ready for testing
* Cadillac XT5 (need brake booster for braking)
* Cadillac XT4 - ongoing testing
* 2019 Cadillac Escalade ESV - ongoing testing
* GMC Yukon - ongoing testing
* Toyota Yaris 2009 - ongoing testing
* Hyundai Elantra N 2022 - compatible

***

## Installation Guide

#### Toyota:&#x20;

For installation, Jason Moreau made a wonderful video on how to install my Smart DSU and Pedal on his Rav4. He used our older version pedal and SDSU, but the installation method is similar. Please refer to his video:&#x20;

\*\*In this video, pedal was connected to SDSU through RJ45 port, which is WRONG.

Pedal HAS TO connect to harness box (therefore the harness box must have an rj45 port)

{% embed url="https://www.youtube.com/watch?v=ftkKeD9NGl4" %}

Or you can refer to Kevin's video on installing the pedal on Toyota. All installation processes are similar for different vehicles.&#x20;

{% embed url="https://www.youtube.com/watch?v=OxEhBRE1znE&ab_channel=Wocsor" %}

#### Chevy Bolt:&#x20;

{% embed url="https://www.youtube.com/watch?v=R7yDL2SDtaY" %}

{% embed url="http://www.youtube.com/watch?v=5D21wzCcycE" %}

#### Gmc sierra

{% embed url="https://youtu.be/Pel4LKiNiY0?si=ES4Vy6jukafYy4CK" %}

## **Warning:**

Comma Pedal only adds support to your car to accelerate from the start. It does not enable your car to stop to zero.\
For braking to stop, it will be handled by your comma device. Please refer to Openpilot's source code.\
The Wiring is the cross-type showed in the product description. The listing will not guaranty working for your car.\
Please confirm that the wiring fits your car before purchase.\
This product is only rated for off-road use.\
Any accident or damage caused by this product is at the buyer's own risk.
