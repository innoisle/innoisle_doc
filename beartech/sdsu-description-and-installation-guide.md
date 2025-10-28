---
description: 'Join our discord at: https://discord.innoisle.com/'
icon: engine
---

# SDSU Description and Installation Guide

## Where to buy

Link to my Store: [https://shop.tlbb.ca/products/copy-of-c-sdsu-smartdsu-for-toyota-openpilot-2-day-rush](https://shop.tlbb.ca/products/copy-of-c-sdsu-smartdsu-for-toyota-openpilot-2-day-rush)

Link to my Etsy Store: [https://www.etsy.com/ca/listing/1505938755/sdsu-smartdsu-for-toyota-openpilot](https://www.etsy.com/ca/listing/1505938755/sdsu-smartdsu-for-toyota-openpilot)

Link to my Ebay: [https://www.ebay.ca/itm/185580845198](https://www.ebay.ca/itm/185580845198)

Link to Retropilot Store: [https://shop.retropilot.org/product/c-sdsu-smartdsu/](https://shop.retropilot.org/product/c-sdsu-smartdsu/)

## Product Description

SmartDSU enabling openpilot longitudinal control without removing AEB.

SDSU will enable your experimental mode.

For complete detail, please read this article:&#x20;

{% embed url="https://github.com/wocsor/panda/tree/smart_dsu" %}

All the electronic components from innoisle on this device are AEC-Q100 & AEC-Q200 qualified. All the connecting parts are from original equipment manufacturers. Assembled in Canada. 3D printed case with ASA automotive grade and UV resistant plastic.

## Notice

Comma released a new update for their official branch 0.9.7. SDSU will no longer be supported in the official openpilot.

**If you would like to continue to use SDSU, please switch to SunnyPilot or FrogPilot.**

See all available branches here:

{% embed url="https://bderkhan.com/comma-ai-openpilot/" %}

For comparison about which branch to use:

{% embed url="https://bderkhan.com/frogpilot-vs-sunnypilot/" %}

## **Currently support vehicle**

#### Toyota:

* Toyota Avalon 2016-2021
* Toyota Avalon Hybrid 2019-2021
* Toyota Corolla 2017-2019
* Toyota Highlander (and Hybird) 2017-2019
* Toyota Prius 2016-2020
* Toyota Prius Prime 2017-2020
* Toyota Prius V 2017
* Toyota Rav4 (and Hybird) 2016-2018
* Toyota Sienna 2018-2020
* 2019 Toyota Kluger (Highlander name in Australia)

**Lexus:**

* Lexus ES (and Hybird) 2017-2018
* Lexus CT Hybrid 2017-2018
* Lexus NX (and Hybird) 2018-2019
* Lexus RX (and Hybird) 2016-2019
* Lexus IS (200T) 2017-2019 - might work but not validated



## Installation Guide

If you are connecting BOTH a SDSU and a pedal on your vehicle, Pedal has to connect to the harness box. It does not connect to SDSU.

If you would like to add an OBD power, it will need to be connected through a splitter.

<figure><img src="../.gitbook/assets/Photo 2024-11-16, 08 37 43.png" alt=""><figcaption></figcaption></figure>

#### Toyota:&#x20;

For installation, Jason Moreau made a wonderful video on how to install my Smart DSU and Pedal on his Rav4. He used our older version of the pedal and SDSU, but the installation method is similar. Please refer to his video:&#x20;

\*\*In this video, pedal was connected to SDSU through RJ45 port, which is WRONG.

Pedal HAS TO connect to harness box (therefore the harness box must have an rj45 port)

{% embed url="https://www.youtube.com/watch?v=ftkKeD9NGl4" %}

## **Warning:**

SDSU only adds longitudinal control to your existing openpilot setup. The Wiring is as-is. The listing will not guarantee that it will work for your car. Please confirm that the wiring fits your car before purchase. This product is only rated for off-road use. Any accident or damage caused by this product is at the buyer's own risk.
