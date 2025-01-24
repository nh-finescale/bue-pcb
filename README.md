# bue-pcb
documentation of Bue pcb's

Using the Bahnübergang https://github.com/Kleinbahner/BUESte means you need a few pcb's. Which ones depened on your use case.

There are 4 pcb's available:
- **Bue-main**: main pcb for the processor etc: https://github.com/nh-finescale/bue-pcb/img/bue-v2.png
- **Bue-control** control boxes: https://github.com/nh-finescale/bue-pcb/img/BUE_Box-PCB.jpg
- **Bue-sensor** For detection sensors: https://github.com/nh-finescale/bue-pcb/img/bue-sensor.png
- **Bue-signal** For Büe signal to train https://github.com/nh-finescale/bue-pcb/img/BUE_Sig-PCB.jpg

At least 1 **Bue-main** and one **Bue-control** are needed to run the Bauhnuebergang and make the servo's run and the lights blink

The Bue-signal is suitable for a Bü0/Bü1 signal (see https://www.tf-ausbildung.de/SignalbuchOnline/buesignale.htm ) both in the modernized version without a control lamp and for the older version with a control lamp. Fot the older version the board has a switch and a battery holder to light the control lamp (led)

The configuration depends on your use case

# Use Cases

## case 1

this use case is for a locally manned crossing, no train detection is used. The crossing is started and stopped manually
![scenario 1](https://github.com/nh-finescale/bue-pcb/img/scenario-1.jpg)

pcb used are:
1 Bue-main
1 Bue-control
2 Bue-signal

## case 2

this use case is for a train operated crossing,  train detection is used. The crossing is started and stopped by the train, a manual override is possible using the control box
![scenario 1](https://github.com/nh-finescale/bue-pcb/img/scenario-2.jpg)

pcb used are:
1 Bue-main
2 Bue-control
2 Bue-Sensor
2 Bue-signal

## case 3

this use case is also for a train operated crossing,  train detection is used. The crossing is started and stopped by the train, a manual override for the detection is possible using the control box, there is no manual override to stop/start the crossing
![scenario 1](https://github.com/nh-finescale/bue-pcb/img/scenario-3.jpg)

pcb used are:
1 Bue-main
2 Bue-control
2 Bue-Sensor
2 Bue-signal

# Manuals
see https://github.com/Kleinbahner/BUESte?tab=readme-ov-file#manuals
