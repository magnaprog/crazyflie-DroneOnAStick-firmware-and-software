# Crazyflie DroneOnAStick Firmware and Software

This repository contains the firmware and software for the Crazyflie DroneOnAStick project. The project involves custom modifications to the Crazyflie firmware to support advanced control algorithms and research applications.

## Repository Structure

- `/src`: Contains the source code files, including the modified `stabilizer.c` and `controller.c`.
- `/include`: Header files defining the interfaces and data structures used across the firmware.
- `/simulink`: Generated C code from Simulink models, ready for integration.
- `/scripts`: Helper scripts for compiling, flashing, and testing the firmware.
- `/docs`: Documentation on the firmware architecture, modification guidelines, and testing procedures.

## Getting Started

### Prerequisites

- [Crazyflie 2.1](https://www.bitcraze.io/products/crazyflie-2-1/)
- [Crazyflie Client](https://github.com/bitcraze/crazyflie-clients-python)
- [Crazyflie Firmware](https://github.com/bitcraze/crazyflie-firmware)
- [Simulink](https://www.mathworks.com/products/simulink.html)
- [MATLAB](https://www.mathworks.com/products/matlab.html)

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/magnaprog/crazyflie-DroneOnAStick-firmware-and-software.git
    cd crazyflie-DroneOnAStick-firmware-and-software
    ```

2. Follow the compilation and flashing instructions in the `/docs` directory.

### Usage

- Modify the firmware source code as needed and compile using the provided scripts.
- Flash the modified firmware onto the Crazyflie using the `cfloader`.
- Test and validate the firmware using HIL and field testing protocols.


## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Contact

For support and further information, please use the issue tracker on GitHub.
