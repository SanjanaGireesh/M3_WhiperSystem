# WIPER CONTROL SYSTEM
# Introduction
These days, even non-luxury compact and family cars are available with rain-sensing wipers. These systems utilize an LED sensor, fitted between the windshield and rearview mirror, to detect the amount of rain or snow falling on the windshield.There are a number of infrared light-emitting diodes (LEDs) and a central photodiode which make up the “rain sense” portion of the system.The invisible light emitted by the LEDs is reflected by the windshield onto the photo sensor. Therefore the more moisture there is on the windshield, the less light the sensor receives. This information is subsequently relayed to a computer control unit, which then adjusts the intermittent wiper delay intervals of the accordingly.The wetter it gets, the faster the rain sensing wipers work to help give you a clear view of what's in front of you. When the system senses drier conditions, such as when the vehicle is stopped at a red light and the rain is falling less intensely, the wipers will gradually slow down before switching themselves off when no longer needed.
# Objectives
The automated rain wiper system is used to detect rainfall and activate automobile rain wiper automatically without driver interaction. The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation. The few seconds that a driver takes their attention off the road to adjust a knob while driving in poor weather conditions could potentially lead to car accidents.The system uses a combination of impedance and rain sensor to detect rain and its intensity. The system contains a controller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals The aim of this project is to help reduce accidents that happen as a result of the driver intending to clean the windscreen when rain is falling thereby taking the attention of the driver off the road when he or she is switching on and off the wiper. In rainy days we suffer from the act of sprinkling of water on the front glass of our wheeler. While driving, when drivers cannot see visibly on-road vehicles they try operating the wiper on glass manually, at times switching on and off intermittently and this distraction might cause vehicle accident. If we apply any kind of sensor on glass which senses the act of sprinkling water, by automation, the wiper will be operating automatically. When the water hit the sensor, it will send a signal to the system thus triggering the wiper motor. Once the sensor does not detect any water, the wiper will stop. This will reduce the human interface that has been stated earlier. An addition to this invention is that the wiper automatically push up from the windscreen when the engine is shut off.
#  About the project WCS
## Description
 This Project is an _Wiper control (WCS) system_,a wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions. It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.
## Features
1) A wiper speed control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.
2) The control system includes a rain sensor (30) detecting rain conditions to produce . an analog signal having an amplitude depending upon the detected rain conditions.
## Identifying features
1) When the button is pressed once the car will start (_Ignition key postion at ACC_)
2) When the button is pressed again the wiper will start(_Wiper On_)
3) When the button is pressed again the wiper will off(_Wiper Off_)
4) When the button is pressed thrice the car will stop(_Ignition key position at Lock_)

## State of art
  The main focus point is seeing the wiper control of the car and also seeing the seep of the wiper system in the car. Now this two features are explained in these project.
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
## Wipers are frozen or snowed on to the windshield
Your windshield wipers don't weight very much so its easy for heavy wet snow to weight them down or cause them to freeze onto the windshield.
## Wipers aren't fastened in properly
If you don't put your windshield wiper blades on properly, they won't be able to function.
## Wipers have torn blades
Your windshield wiper blades are made of rubber that's meant to handle water and sometimes ice. Faced with anything solid, these rubber blades can rip easily causing your wipers not to work. Causes of Broken Windshield Wipers.
 # 5W's and 1'H
 ## WHAT
 Wiper Control System (WCS)
## WHERE
 During driving in heavy rain, out side the car.
## WHEN
When the weather condition is bad (like in rain and snow) the wiper is activate and clean the car window, commonly used during rainy season and when there is unwanted dust in windshield.
## WHY
For cleaning the wind shield from unwanted dust and mist.
## WHO
Who is driving or controlling the car
## HOW
When we on the wiper switch it gets activated.
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


    
