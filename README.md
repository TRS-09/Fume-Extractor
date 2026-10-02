# Fume-Extractor

It is a small and portable fume extractor which uses a fan and a carbon filter to remove fumes and airborne particles from a work area.

The project was carried out in two versions, the second of which featured improvements in airflow, noise reduction, filtration arrangement, and speed control.

## Version 1

The initial version made use of a small direct current motor together with specially 3D-printed fan blades.

The fan was constructed having more blades and a steeper blade angle in order to place a greater emphasis on static pressure rather than on maximum airflow, the aim being to assist in pushing the air through the carbon filter.

### V1 Power and control

* 2 × AA batteries
* Two available speeds
* Full speed
* Reduced speed using a resistor

The resistor offered a simple method of reducing motor speed, even though this approach gave only limited control and caused some power to be wasted in the form of heat.

### V1 Filter

The carbon filter was placed back of the fan.

However, when the filter was put directly behind the fan the airflow became turbulent and less uniform. The special fan also made more noise than was desired.

## Version 2

In the second version the airflow path and the electronics were redesigned in order to improve the entire system.

A fan with a diameter of 120 mm was used in place of the custom motor and fan assembly since the bigger fan delivered a smoother flow of air and was quieter when operating.

The carbon filter was transferred to the front of the extractor so that the fan could draw the air through the filter rather than forcing turbulent air directly into it.

### V2 Power and control

Version 2 uses:

* Rechargeable lithium-ion battery
* 120 mm PC fan
* PWM speed controller
* Carbon filter

Instead of having only two fixed speeds, the fan speed can be continuously adjusted by means of the PWM controller.

This also prevents the power losses that occur when a resistor is used to control the speed of the motor.

## Design changes

| Feature        | Version 1                        | Version 2               |
| -------------- | -------------------------------- | ----------------------- |
| Fan            | Custom 3D-printed fan            | 120 mm PC fan           |
| Airflow        | Higher pressure, more turbulence | Smoother airflow        |
| Filter         | Behind fan                       | In front of fan         |
| Power          | 2 × AA                           | Rechargeable Li-ion     |
| Speed control  | Resistor                         | PWM                     |
| Speed settings | 2                                | Continuously adjustable |
| Noise          | Higher                           | Lower                   |

## Design considerations

The initial version was employed in order to experiment with the geometry of the fan blades and the static pressure. The aim was to increase the pressure available for pushing the air through the filter by increasing the number of blades and their angle.

The initial version was tested and it was found that both the position of the filter and the fan's design had a significant effect on airflow.

Version 2 therefore aimed at producing a smoother airflow path while reducing noise and enhancing control.

## CAD

The housing and its components were designed with the aid of CAD and then 3D printed in order to produce the physical extractor.

Because of its modular design, the fan and filter can be taken out and put in again.

## Main features

* Portable design
* Carbon filtration
* 120 mm fan
* Rechargeable battery
* PWM speed control
* Adjustable fan speed
* 3D-printed housing
* Two design iterations
* Improved airflow compared with V1
* Reduced noise compared with V1
