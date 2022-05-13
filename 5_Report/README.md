# Introduction
These days, even non-luxury compact and family cars are available with rain-sensing wipers. These systems utilize an LED sensor, fitted between the windshield and rearview mirror, to detect the amount of rain or snow falling on the windshield.There are a number of infrared light-emitting diodes (LEDs) and a central photodiode which make up the “rain sense” portion of the system.The invisible light emitted by the LEDs is reflected by the windshield onto the photo sensor. Therefore the more moisture there is on the windshield, the less light the sensor receives. This information is subsequently relayed to a computer control unit, which then adjusts the intermittent wiper delay intervals of the accordingly.The wetter it gets, the faster the rain sensing wipers work to help give you a clear view of what's in front of you. When the system senses drier conditions, such as when the vehicle is stopped at a red light and the rain is falling less intensely, the wipers will gradually slow down before switching themselves off when no longer needed.
# Objectives
The automated rain wiper system is used to detect rainfall and activate automobile rain wiper automatically without driver interaction. The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation. The few seconds that a driver takes their attention off the road to adjust a knob while driving in poor weather conditions could potentially lead to car accidents.The system uses a combination of impedance and rain sensor to detect rain and its intensity. The system contains a controller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals The aim of this project is to help reduce accidents that happen as a result of the driver intending to clean the windscreen when rain is falling thereby taking the attention of the driver off the road when he or she is switching on and off the wiper. In rainy days we suffer from the act of sprinkling of water on the front glass of our wheeler. While driving, when drivers cannot see visibly on-road vehicles they try operating the wiper on glass manually, at times switching on and off intermittently and this distraction might cause vehicle accident. If we apply any kind of sensor on glass which senses the act of sprinkling water, by automation, the wiper will be operating automatically. When the water hit the sensor, it will send a signal to the system thus triggering the wiper motor. Once the sensor does not detect any water, the wiper will stop. This will reduce the human interface that has been stated earlier. An addition to this invention is that the wiper automatically push up from the windscreen when the engine is shut off.
# Features
A wiper speed control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions. The control system includes a rain sensor (30) detecting rain conditions to produce . an analog signal having an amplitude depending upon the detected rain conditions.
# Swot Analysis
# Strength
1) Whenever the water hit a dedicated sensor that located on windscreen, it will send a signal to move on the wiper motor. Once water is not detected by sensor, the wiper will automatically stop. This will help the driver to give more concentration and reduce the car accident probability.
2) It helps in saving money by switching off the irrigation system when it rains. This saves money by cutting off bills on electricity consumption.
3) It extends life of rain sensor based systems such as car wiper, irrigation systems by running them only when it is necessary.
4) Rain sensors help save water during rain events and hence water is available during summer and emergency applications such as firefighting etc.
5) Operating principle is very easy.
6) It consumes less power for operation.
7) Installation of rain sensor based systems are very much simple.
8) Individual rain sensor costs very less.
# Weakness
1) The rain sensor based system functions when water falls on the sensor directly.
2) The cost of overall system increases as additional components are needed along with rain sensor.
3) In order to avoid false detection of rain, it requires rain sensors to take decision after few minutes.
# Opportunities
Windshield wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum.
# Threats
# Wipers are frozen or snowed on to the windshield
Your windshield wipers don't weight very much so its easy for heavy wet snow to weight them down or cause them to freeze onto the windshield.
# Wipers aren't fastened in properly
If you don't put your windshield wiper blades on properly, they won't be able to function.
# Wipers have torn blades
Your windshield wiper blades are made of rubber that's meant to handle water and sometimes ice. Faced with anything solid, these rubber blades can rip easily causing your wipers not to work. Causes of Broken Windshield Wipers.
 # 4W's and 1'H
# WHERE
 During driving in heavy rain.
# WHEN
Commonly used during rainy season and when there is unwanted dust in windshield.
# WHY
For cleaning the wind shield from unwanted dust and mist.
# HOW
When we on the wiper switch it gets activated.

# ENGINE ON STATE
![Red Led ON](https://user-images.githubusercontent.com/101441389/168270659-510526cf-8bf6-4916-afe9-c947d4dfa916.png)

# WIPER SPEED IS LOW
![Orange Led ON](https://user-images.githubusercontent.com/101441389/168272110-ba6bdba7-3601-4577-b324-2eb865077862.png)

# WIPER SPEED IS MODERATE
![Green Led ON](https://user-images.githubusercontent.com/101441389/168272380-5c7a8fdb-6ac8-4f0e-b39d-12fd36c119da.png)

# WIPER SPEED IS HIGH
![BLUE LED ON](https://user-images.githubusercontent.com/101441389/168272740-47d01034-eca2-412c-bf74-62f5edad61d9.PNG)

# ENGINE OFF STATE
![Wiper OFF State](https://user-images.githubusercontent.com/101441389/168271807-83ca6e24-7ec2-4a6d-917b-81b59797b88d.PNG)

# Advantages
1) Optimal wiping performance
2) Enhanced driver comfort 
3) Reduced noise from wiper operation
4) Improved visibility
5) Vehicle design freedom 
6) space occupancy in plenum area significantly reduced
7) Wiper arm/blade protection - from potential sources of damage e.g. snow block.
8) Easy blade replacement
9) 'service' position facilitates blade replacement.
# Disadvantages
While rain sensors are generally a good idea, they're not usually necessary in extremely arid environments that receive relatively small amounts of precipitation. In this case, a sensor would have little or no value.
# Detail requirements
# High Level Requirements
 
 1) HLR_1 - Systic Timers(Internal Timers)
 2) HLR_2 - Light Emitting Diode(Blue, Green, Orange)
 3) HLR_3 - On/Off Switch(Red)
# Low Level Requirements

 1) LLR_1 - Arm Processor
 2) LLR_2 -  STM32 Bit
 3) LLR_3  - Qemu Microcontroller
# Exploring STM32F407 Discovery Board
The main purpose of this project is to get an insight into the STM32F407 Discovery Board, which is an ARM Cortex M4 based Microcontroller. As I started working on STM32F07 Discovery Board, initially it was difficult and confusing to understand and program this microcontroller because understanding internal structures and working of the microcontroller using datasheet of STM32F407VGT MCU is difficult especially if one is a beginner.
# Figure 1 : STM32F407 Discovery Board
![STM32F407 Discovery Board](https://user-images.githubusercontent.com/101441389/167889559-56e8ccad-7419-470f-80b9-ab31101be18c.PNG)
# NVIC(Nested vectored interrupt controller)
Interrupts are a common feature supported by almost all microcontrollers. They are typically generated by hardware, for example peripherals or external input pins. When a peripheral or hardware needs service from the processor, this will lead to changes in program flow control outside the normal programmed sequence. Typically, the following sequences would occur:

1) The peripheral asserts an interrupt request to the processor.
2) The currently running task is suspended by the processor.
3) The processor executes an Interrupt Service Routine (ISR) to service the peripheral, and optionally the interrupt request is cleared by software if needed.
4) The processor resumes the previously suspended task. For every interrupt there must be a program associated with it. When an interrupt occurs, this program is executed to perform certain service for the interrupt. This program is usually named as Interrupt Service Routine (ISR) or interrupt handler.
 
![NVIC](https://user-images.githubusercontent.com/101441389/167892509-aed11f6b-5d49-48d7-8152-0cc503bbc96d.PNG)
As the above figure shows every Cortex-M4 processor provides a Nested Vectored Interrupt Controller (NVIC) for interrupt handling. NVIC facilitates low-latency exception and interrupts handling, controls power management and implements System Control Registers. The NVIC and the processor core interface are closely coupled, which enables low latency to interrupt processing and efficient processing of late arriving interrupts.

For this microcontroller, the NVIC receives interrupt requests from various sources. In addition to interrupt requests, ther are some other events which need servicing. They are called “exceptions” (which are MCU internally generated). For Cortex-M4 processor, exceptions include resets, software interrupts and hardware interrupts. Each exception has an associated 32-bit vector that stores the memory location where the ISR that handles the exception is located. These vectors are stored in ROM at the beginning of memory. As explained earlier Vector table holds the location of ISR. The Cortex-M4 NVIC supports up to 240 interrupt requests (IRQs), a non-maskable interrupt (NMI), a SysTick timer interrupt and a number of system exceptions. Most of these IRQs are generated by peripherals such as timers, GPIO ports and communication interfaces such as UARTs.
# Overview of STM32F407VGT6 Microcontroller
The STM32F407 Discovery board uses STM32F407VGT6 Microcontroller which has ARM Cortex-M4F Processor, which is capable of running upto 168Mhz. This MCU has many peripherals such as GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART ect. The processor and peripherals talk via BUS-Interface. There are three busses available :-

1) I-BUS (Instruction Bus)
2) D-BUS (Data Bus)
3) S-BUS (System Bus)
# I-BUS
  This bus connects the Instruction bus of the Cortex®-M4 with FPU(Floating point unit) core to the BusMatrix. This bus is used by the core to fetch instructions. The target of this bus is a memory containing code (internal Flash memory/SRAM or external memories through the FSMC/FMC).

# D-BUS 
This bus connects the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM data RAM to the BusMatrix. This bus is used by the core for literal load and debug access. The target of this bus is a memory containing code or data (internal Flash memory or external memories through the FSMC/FMC).

# S-BUS 
This bus connects the system bus of the Cortex®-M4 with FPU core to a BusMatrix. This bus is used to access data located in a peripheral or in SRAM. Instructions may also be fetched on this bus (less efficient than ICode). The targets of this bus are the internal SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the external memories through the FSMC/FMC.

So instructions and data use I-bus and D-bus respectively, All the other peripheral uses System bus. The Cortex-M4 processor contains three external Advanced High-performance Bus (AHB)-Lite bus interface and one Advanced Peripheral Bus (APB) interface. The GPIOs are connected to AHB1 bus which has a maximum speed of 150Mhz and is divided into two buses as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The different peripherals such as SPI, UART, TIMERs, ADCs, DACs, etc are connected to either APB1/APB2 buses. And the AHB2(168Mhz max) is connected to Camera and USB OTG interfaces, AHB3 is connected to External memory controller.
# Clock
STM32F407VGT6 Micorcontroller has 3 main clock sources:

# Crystal Oscillator(HSE) 
This is external clock source which can be connected to MCU based on requirements. HSE standas fro High speed External. If you want to use HSE as system clock an external crystal oscillator(whose frequency must be in range 4 to 26Mhz ) has to be connected. In this board, the manufacturer has connected 8Mhz crystal.

# RC Oscillator (HSI) 
All modern MCU comes with internal RC Oscillator, which can be just activated to use. HSI stands for High Speed Internal .After Reset, by default HSI is used to provide a clock to MCU, which means by default MCU select HSI as the clock. This clock is internal to MCU and its value is 16Mhz in STM32F407 MCU. The HSI internal oscillator has the advantage of providing a clock at a low cost, as no external component is required to use this clock. It also has a faster start-up time than the external crystal oscillator however, frequency is less accurate when compared to the external crystal oscillator.

# PLL(Phase locked loop) 
It is also Implemented internally in MCU, it uses low frequency sources to generate high frequency clock (PLLCLK).The power of PLL lies in producing high-frequency clocks of various programmable range. By using PLL you can boost the HCLK(AHB) up to 168Mhz in STM32F4xx MCU. All the modern MCU has PLL. If you want to use MCU-buses at their maximum speed then we have to use PLL only. You have to feed either HSI or HSE to the PLL as input frequency. Then by using all PLL circuitry settings, it produces a PLL output clock in the range of 100's of Mhz. So to Run STM32F407 at its maximum frequency(168Hhz) you have to use PLL.

![clock tree](https://user-images.githubusercontent.com/101441389/167905521-69aa0066-bba5-41b4-8c67-6f5c32fb51f0.PNG)

From above clock tree we can see that HSI RC is 16Mhz internal Clock, and an external oscillator (4Mhz to 26Mhz) has to be connected to HSE input and PLL takes HSI/HSE as input to produce various other clocks. All 3 of these clock sources are given to SYSTEM CLOCK MULTIPLEXER where we can select clock source, Output of this MUX is SYSCLK(i.e, System Clock).

# SYSCLK 
This is the Main clock of MCU, using this other clocks are derived (Ex: Peripheral, Bus clocks ect). SYSCLK is given directly to Ethernet PTP Clock.
# HCLK 
HCLK is derived from SYSCLK with a Prescaler in between , which brings down the clock frequency. HCLK goes directly to AHB bus, core, memory and DMA. HCLK goes to Cortex System Timer with prescalar in between and HCLK goes directly to Cortex Processor (FCLK Cortex Clock).
# PCLK 
PCLK1 and PCLK2 are derived from HCLK, PCLK1 goes to APB1 peripheral clock and APB1 Timer Clock and PCLK2 goes to APB2 peripheral clock and APB2 Timer Clock.
By default MCU uses HSI (i.e internal RC Oscillator) as SYSCLK, Which means after reset HSI is used as SYSCLK Source. Before using any peripheral its clock should be enabled. Referring MUC Block Diagram, all different peripheral drives the clock from bus which it is connected. By default almost all the peripheral are deactive, which means there clocks are not enabled. RCC(Reset and clock Control) engine of MCU gives various registers to enable and disable various peripheral clocks. For more information refer RCC section of STM32F4xxx Reference Manual (RM0090).
# Clocking the MCU using External Crystal Oscillator
As explained before, you can connect (4 to 26Mhz) crystal oscillator to MCU. In STM32 board manufacturer has connected 8Mhz Crystal. Even though it is connected its useless as its disabled. Before using an external oscillator, we need to enable it by using RCC Clock Control Register(RCC_CR). Refer 7.3.1 RCC clock control register (RCC_CR). Bit 17 and 16 are HSERDY and HSE ON respectively
To enable HSE, HSEON bit is made 1, then you have to wait until the HSERDY flag becomes 1, which indicates the HSE oscillator is ready to use. It important to wait until HSERDY flag is set.
Now HSE is ready but it is not yet set as SYSCLK(System Clock).
So to set HSE as System clock, RCC clock configuration register (RCC_CFGR) is used. RCC clock configuration register (RCC_CFGR). Referring RCC_CFGR, bit 0 and 1 are used to switch system clock.

If Bit1:0 SW = 01, then HSE oscillator selected as the system clock .
Once we do this HSE will be used as a system clock.
