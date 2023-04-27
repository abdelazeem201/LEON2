# LEON2 / LEON2-FT
The LEON2 is a synthesisable VHDL model of a 32-bit processor conforming to the IEEE-1754 (SPARC V8) architecture. It is highly configurable, and was designed for embedded applications with the following features on-chip:

* 5-stage integer pipeline
* separate instruction and data caches
* hardware multiplier and divider
* memory management unit
* interrupt controller
* debug support unit with trace buffer
* two 24-bit timers
* two UARTs
* power-down function
* watchdog
* 16-bit I/O port
* Flexible memory controller

The LEON2 is based on an AMBA AHB/APB bus architecture, so new modules can easily be added to extend its functionality. The processor can be implemented in both FPGA and ASIC technologies.
![LEON2_architecture_diagram_pillars](https://user-images.githubusercontent.com/58098260/234860188-788758e4-7e9e-4170-a6c1-d350c634f176.jpg)


The LEON2-FT design is an extension of the basic LEON2 model including advanced fault-tolerance features to withstand arbitrary single-event upset (SEU) errors without loss of data. The fault-tolerance is provided at design (VHDL) level, and does not require an SEU-hard semiconductor process, nor a custom cell library or special back-end tools. Atmel has manufactured an ASIC version of the LEON2-FT in the ATH18RHA rad hard process, available through their catalogue as part number AT697F. The AT697F is qualified according to QML-Q.

*Availability:*

The LEON2-FT VHDL IP core is available from ESA directly, under special licensing conditions. Please refer to the LEON2-FT IP Core webpage on the ESA IP Cores website for more information on licensing the LEON2-FT model.
The LEON2 (non-FT) model is no longer maintained. It is superceded by LEON2-FT, and the subsequently released LEON models (LEON3, LEON4).
The ASIC implementation of the LEON2-FT is available from Atmel,as part number AT697F.

![GR740_next-generation_microprocessor_card_medium](https://user-images.githubusercontent.com/58098260/234861085-d22a4587-087d-4bdc-8f9e-63e46ea97212.jpg)
