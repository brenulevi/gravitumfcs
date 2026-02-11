# Power Supply

## Overview

The power supply is a critical component of any electronic device, providing the necessary electrical energy to operate the device. It converts the input electrical power from a source into the appropriate voltage and current required by the device's internal components.

## Components

1. **INA219**: This is a current and power monitor that provides accurate measurements of current, voltage, and power. It is used to monitor the power consumption of the device and ensure it operates within safe limits.

2. **Battery**: The battery serves as the primary power source for the device, providing energy when the device is not connected to an external power source.

3. **TPS5430**: This is a step-down (buck) converter that efficiently converts the battery voltage (12V) to a lower voltage (5V), that 5v will power the camera module and radio receiver and enable the LDO to provide 3.3V. It ensures that the components receive a stable and regulated voltage supply, improving their performance and reliability.

4. **MIC26903**: This is another step-down converter that will be used to supply the servo motors with the necessary voltage and current. It ensures that the motors receive a stable power supply for optimal performance, isolating the power requirements of the motors from the rest of the system.

5. **LD39200**: This is a low-dropout (LDO) regulator that provides a stable output voltage (3.3V) with minimal dropout. It is used to power sensitive components that require a clean and stable voltage supply, such as the microcontroller and communication modules.

## Voltages

- **3.3v**: This voltage is used to power the microcontroller, sensors, and communication modules, ensuring they operate correctly and efficiently.

- **5v**: This voltage is used to supply additional components that require a higher voltage than 3.3V, such as camera module and radio receiver.

- **6v**: This voltage is specifically used to power the servo motors, providing them with the necessary energy to operate effectively.