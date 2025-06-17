# Didactic plant - Food Industry prototype

This repository contains all files related to the Food Industry prototype, which is used as a didactic plant for teaching Discrete Event Systems (DES) at the University.

## Overview

![DiagramaProcesso](https://github.com/user-attachments/assets/c0f4e49f-f655-417e-a9c4-25ce678d64ac)

The Food Industry prototype is designed to showcase a simulated industrial process involving various components:

## Features
- **Tank R:** Water reservoir.
- **Tank M:** Where the Cleaning, Grinding, Pasteurization and Drying processes take place.
- **Tank F:** Where the Fermentation, Mixing and Cooking processes take place.
- **Agitators:** Acts in the Cleaning, Mixing and Fermentation processes.
- **Mixer or Bottom Paddle:** Acts in the Mixing process.
- **Exhaust/Ventilation Fan:** In the Grinding process, it rotates to the right and acts as an exhaust fan. In the Drying process, it rotates to the left and acts as a ventilation fan.
- **Grinder:** Acts in the Grinding process.
- **Heaters:** Acts in the Fermentation, Pasteurization and Cooking processes.
- **Collers:** Acts in the Fermentation and Pasteurization processes.
- **Water Pumps:** Responsible for filling and emptying the tanks in all processes.

  
## Events 
|EVENT |DESCRIPTION                                            |TYPE           |
|------|-------------------------------------------------------|---------------|
|LAgF  |Turn On Agitator of Tank F                             |Controlable    |
|DAgF  |Turn Off Agitator of Tank F                            |Non Controlable|
|LAgM  |Turn On Agitator of Tank M                             |Controlable    |
|DAgM  |Turn Off Agitator of Tank M                            |Non Controlable|
|AferF |Turn On Heater to Fermentation Temperature in Tank F   |Controlable    |
|DAferF|Turn Off Heater to Fermentation Temperature in Tank F  |Non Controlable|
|ApasF |Turn On Heater to Pasteurization Temperature in Tank F |Controlable    |
|DApasF|Turn Off Heater to Pasteurization Temperature in Tank F|Non Controlable|
|AferM |Turn On Heater to Fermentation Temperature in Tank M   |Controlable    |
|DAferM|Turn Off Heater to Fermentation Temperature in Tank M  |Non Controlable|
|ApasM |Turn On Heater to Pasteurization Temperature in Tank M |Controlable    |
|DApasM|Turn Off Heater to Pasteurization Temperature in Tank M|Non Controlable|
|LbFM  |Turn On Pump FM (pumps water from Tank F to Tank M)    |Controlable    |
|DbFM  |Turn Off Pump FM (pumps water from Tank F to Tank M)   |Non Controlable|
|LbFR  |Turn On Pump FR (pumps water from Tank F to Tank R)    |Controlable    |
|DbFR  |Turn Off Pump FR (pumps water from Tank F to Tank R)   |Non Controlable|
|LbMF  |Turn On Pump MF (pumps water from Tank M to Tank F)    |Controlable    |
|DbMF  |Turn Off Pump MF (pumps water from Tank M to Tank F)   |Non Controlable|
|LbMR  |Turn On Pump MR (pumps water from Tank M to Tank R)    |Controlable    |
|DbMR  |Turn Off Pump MR (pumps water from Tank M to Tank R)   |Non Controlable|
|LbRF  |Turn On Pump RF (pumps water from Tank R to Tank F)    |Controlable    |
|DbRF  |Turn Off Pump RF (pumps water from Tank R to Tank F)   |Non Controlable|
|LbRM  |Turn On Pump RM (pumps water from Tank R to Tank M)    |Controlable    |
|DbRM  |Turn Off Pump RM (pumps water from Tank R to Tank M)   |Non Controlable|
|Gdir  |Rotate Right (Turns on the Exhaust Fan)                |Controlable    |
|Dexa  |Turn Off Exhaust Fan                                   |Non Controlable|
|Gesq  |Rotate Left (Turns on the Ventilation Fan)             |Controlable    |
|Dven  |Turn Off Ventilation Fan                               |Non Controlable|
|Lmis  |Turn On Mixer (or Bottom Paddle)                       |Controlable    |
|Dmis  |Turn Off Mixer (or Bottom Paddle)                      |Non Controlable|
|Lmoe  |Turn On Grinder                                        |Controlable    |
|Dmoe  |Turn Off Grinder                                       |Non Controlable|
|LResF |Turn On Cooler of Tank F                               |Controlable    |
|DResF |Turn Off Cooler of Tank F                              |Non Controlable|
|LResM |Turn On Cooler of Tank M                               |Controlable    |
|DResM |Turn Off Cooler of Tank M                              |Non Controlable|
|MF    |Medium Level in Tank F                                 |Non Controlable|
|HF    |High Level in Tank F                                   |Non Controlable|
|LF    |Low Level in Tank F                                    |Non Controlable|
|MM    |Medium Level in Tank M                                 |Non Controlable|
|HM    |High Level in Tank M (HIGH)                            |Non Controlable|
|LM    |Low Level in Tank M (LOW)                              |Non Controlable|
|MR    |Medium Level in Tank R                                 |Non Controlable|
|HR    |High Level in Tank R (HIGH)                            |Non Controlable|
|LR    |Low Level in Tank R (LOW)                              |Non Controlable|
|FF    |Cold Temperature in Tank F                             |Non Controlable|
|QferF |Hot: Temperature of Fermentation in Tank F             |Non Controlable|
|QpasF |Hot: Temperature of Pasteurization in Tank F           |Non Controlable|
|FM    |Cold Temperature in Tank M                             |Non Controlable|
|QferM |Hot: Temperature of Fermentation in Tank M             |Non Controlable|
|QpasM |Hot: Temperature of Pasteurization in Tank M           |Non Controlable|



## Contributions
Contributions to the Food Industry prototype project are welcome. If you have suggestions for improvements, bug fixes, or new features, feel free to submit a pull request following the contribution guidelines outlined in the repository.

## Demo Video
Check out the demo video below to see the Food Industry prototype in action:

[Plant Demo](https://www.youtube.com/watch?v=4ZmwFEM_V7I)

## Author
- **Name:** Letícia Maia Silva Araújo
- **Email:** leticiamaiaaraujo@hotmail.com
