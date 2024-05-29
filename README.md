# Envirosensing HAT PCB Design Group Project (EEE3088F)

## Design Team

- Ethan Morris (MRRETH003)
- Ethan Meknassi (MKNETH002)
- Moutloatsi Setlogelo (STLMOU001)

## Project Overview

Our project involves designing a proximity sensor surveillance device using a HAT (Hardware Attached on Top) powered by either a microcontroller or a battery. The HAT utilizes a PIR motion sensor to detect the presence of a person or animal, triggering a buzzer to sound an alert. Detection logs are stored and can be accessed by the user.

## Hardware Requirements

To operate this device, you will need the following hardware:
- **Power Source**: Either an STM32000 microcontroller or an 18650 battery.
- **USB Cable**: Male USB A to Male Micro USB B Cable for data retrieval.
- **Computer**: For data retrieval and battery charging.

## Hardware Setup

### Microcontroller Power Setup
1. Place the microcontroller under the device using the inner set of connectors.
2. Connect the 5V pin of the microcontroller to pin "J3" on the device. Pin "J3" is the leftmost pin on the third row of connectors when the device is in its default position (buzzer at the top left).

### Battery Power Setup
1. Insert the 18650 battery into the battery holder.
2. Connect the USB to Micro USB cable to the device and your computer for data retrieval or battery charging. The battery should be placed in the position indicated by the red rectangle in the attached picture.

## Basic Operating Instructions

1. Power on the device using the battery.
2. Create movement close to the device (e.g., wave your hand 5-10 cm away from the device). The buzzer should beep, indicating the device is operational.
3. To retrieve the detection log, connect the device to a computer using the USB to Micro USB cable.

## License

The license information for this project can be found in the Git repository.

[Project Repository](https://gitlab.com/mrreth003/envirosensing-hat/-/tree/main/)

Kind Regards,

Ethan Morris, Ethan Meknassi, and Moutloatsi Setlogelo