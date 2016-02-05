## Narrow Classic Flight Controller
The Classic Narrow is an experimental flight controller designed to pilot Quadcopters using 7mm-8.5mm brushed motors. It features an Atmel Atmega 32u4 processor, MPU6050 Gyro/Accelerometer,  built in 9.5A ESCs, and a built in Bind button for easy binding.
### Narrow Classic Example Picture
(JMPR build pictured - Latest build uses tactile switches in place of jumpers)

![Classic Narrow](/docs/assets/images/Classic-Side-USB.jpg "Classic-Narrow")

#### Narrow Classic Specs
* MultiWii compatible
* Atmel Atmega 32u4 micro controller
* MPU6050 accelerometer/gyro sensor unit
* 4x 9.5A brushed ESCs (MOSFETS) - 2oz copper layers recommended
* Integrated USB port (side access)
* Serial connection for external DSM2/DSMX sat receiver (e.g. Spektrum SAT, OrangeRx R100 or Lemon RX)
* Alternate PPM connection for external receiver - Pin pulled out - untested
* Hardware bind button for easy binding
* Motor connections are at the corners for easy orientation with reduced wiring
* Dimensions:  31x25mm
* Direct operation from an single cell 3.7V Lipo battery
* 5V and 3.3V buck/boost regulators (5V out can be used to power accessories)
* Buzzer out on pin D8
* Single Sided - all components on the top layer

#### Build Files and Resources:

Schematic, board design, and part list ➜ ![Narrow Classic 5V ZIP](https://github.com/HumbleOne/Flight-Controllers/blob/master/Flight-Controllers/Classic/Classic-Narrow-5V-SIDE-USB.zip?raw=true "Classic Narrow 5V ZIP") 

This bare board can be made at ➜ [OSHpark] (https://oshpark.com/shared_projects/2qDJlrGR "OSHPARK Narrow Classic")

Stencils can be made at ➜ [OSHStencils] (https://www.oshstencils.com/ "OSHStencils")

_**THESE FILES ARE BEING PROVIDED ''AS IS'' WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES.**_