# V0 Filtered Exhaust

![Image](./images/filtered_exhaust.png) 

Voron 0 filtered exhaust solution that uses 6010 axial fan + the V2 BOM spec activated carbon filter. Cannot confidently comment on the efficacy of this solution in removing odors/particles, but the exhaust is pulled through 3 layers of the carbon filter. The exhaust requires cutting out a hole in the back panel.

## Variations:
Comes in 4 flavors:
1. `exhaust_body.stl`: base version
2. `exhaust_body_mosfet_mount.stl`: integrates a BME280 temperature/humidity sensor into one of the hexagons (*Note: might require supports for the sensor pocket cutout*)
3. `exhaust_fan_cover.stl`: integrates 4 pin magnetic pogo-pin connector for connecting accessories (lighting) to the tophat

## Required Parts:
* M3x16 BHCS (4x) for mounting
* M3 heatset insert (4x) for mounting fan
* Activated carbon filter - only 1 sheet required, cut equally into 4 squares with scissors (3 squares used at a time)
* 6010 Fan
* *Optional:* Mosfet module(for PWM fan control, since the SKR mini doesn't have many extra fan control headers)


## Installation Notes: 
* A 63x63 square hole (with 16mm fillets) is required to be cut into the back panel at the appropriate location, depending on where you mount the exhaust. See pictures below.
* 

## Configuration:
Connect:

Klipper config:

Usage:
SET_FAN_SPEED FAN=exhaust_fan SPEED=1.0

## Additional Images:
![Image](./images/filtered_exhaust.png) 

![Image](./images/filtered_exhaust.png) 

![Image](./images/filtered_exhaust.png) 

![Image](./images/filtered_exhaust.png) 
