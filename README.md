## Arrow Everest Board RISC-V Designs

This repository contains Libero projects for the following soft core RISC-V processors:
* MIV_RV32
* MIV_RV32IMA_L1_AHB * 
* MIV_RV32IMA_L1_AXI * 
* MIV_RV32IMAF_L1_AHB *

\*Legacy cores. MIV_RV32 recommended for new designs

FlashPro Express projects containing pre-generated programming files are also available for each of the designs.

To download or clone the repository:

    $ git clone https://github.com/RISCV-on-Microsemi-FPGA/Arrow-Everest-Board.git

    $ Running from the zipped sources
    1. Download the zipped sources via the "Code" button using "Download Zip" button
    2. Unzip the sources


# Libero Projects
The Libero_Projects folder contains sample Mi-V Libero designs for Libero v2021.1. Libero projects for older Libero releases can be downloaded from their [tags](https://github.com/RISCV-on-Microsemi-FPGA/Arrow-Everest-Board/releases) in this repository.

## Design Features
The Libero designs include the following features:
* A soft RISC-V [processor](https://github.com/RISCV-on-Microsemi-FPGA/CPUs)
* A RISC-V debug block allowing on-target debug using SoftConsole
* The operating frequency of the design is 50MHz
* Target memory is SRAM (32kB)
* User peripherals: 2 Timers, UART, 2 GPIO Inputs and 4 GPIO Outputs (GPIOs use fixed configs for simplicity and better resource utilization)

## Target Hardware
Details of the Arrow-Everest-Board and it's features can be found:
* [EVEREST-DEV-BOARD](https://www.microsemi.com/existing-parts/parts/143998) (MPF300TS_ES)

# FlashPro Express
The FlashPro_Express_Projects folder contains the pre-generated programming files, which can be downloaded directly to the target board using FlashPro Express.

# Design Tools
The following design tools are required.

## Libero SoC v2021.1
[Libero SoC](https://www.microsemi.com/products/fpga-soc/design-resources/design-software/libero-soc#downloads) is Microsemi's FPGA design software.

## FlashPro Express
[FlashPro Express](http://www.microsemi.com/products/fpga-soc/design-resources/programming/flashpro#software) is Microsemi's Programming and debug tool. It is included in the Libero SoC software and is also
available as a standalone application. Please note, that if Libero SoC is already on your system, you do not need
the standalone version.

## SoftConsole
[SoftConsole](https://www.microsemi.com/product-directory/design-tools/4879-softconsole) is Microsemi’s free software development environment facilitating the rapid development of bare-metal and RTOS based C/C++ software for Microsemi CPU and SoC based FPGAs. It provides development and debug support for all Microsemi SoC FPGAs and 32-bit soft IP CPUs. SoftConsole can be downloaded.
