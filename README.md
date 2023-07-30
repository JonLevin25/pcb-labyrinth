# Labyrinth PCB Board

A board made for Midburn projects (Labyrinth / Sangha).

This repo contains the Gerber file (defining the PCB circuitry), and the BOM (the Bill of Materials, defining the components needed )

# How to Order

## Main order - PCB

1. Go to [JLCPCB.com](https://jlcpcb.com/)
1. Create Account
1. Click Order Now in the top menu
1. Add Gerber file -> select the gerber zip
1. select the amount of boards you like (PCB Qty- 5/10/15 etc)
1. Most options should stay the same (2 layer board, 1 design, etc)
1. change the color if you like
1. Select PCB Assembly (assemble top side)
1. Click Next twice
1. Add BOM + CPL Files (the CSVs from this repo)
1. Click Process BOM and CPL
1. Confirm BOM
1. Confirm placement
1. Product description - Category Other/Other, enter whatever ("leds board" etc)
1. Save to cart
1. Finalize order + shipping from cart
1. Make sure to select coupon on checkout (theres always something)

## Other components

## Connectors

You'll need to solder connectors for your leds to work. Generally JST-SM connectors are used (the 3-pin variant for the most popular WS2812 strips).
You can find these on AliExpress

## PCB Power switch

The LEDs power switch used is not available in economic PCB assembly (which is much cheaper)
So I batch order them from LCSC.

You can order them here https://www.lcsc.com/product-detail/Slide-Switches_XKB-Connectivity-SS-12M11G5_C2879839.html

Or you can solder where the big switch would be instead, and the LEDs will always be on if the PCB is connected to power.
