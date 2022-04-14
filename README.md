 
## Session 1 (Motivation and preparation)

* Why this workshop ? how it helps translating to stm !
* why is the arduino data sheet so good yet very samll and simple 
* What is the Arduino framework and what it does ?
* What is HAL and how it makes code 1) portable and 2)small and less complex
* How the platform makes things so easy?
* What it hides and what problems it causes ?
    * Servo + SW serial
    * digitalWrite() overhead
    * interrupt ocasional overhead
    * When you have a new module without an arduino library, or u are using another MCU, what will you do ?
    * Why Servo.write(180) works? how the heck ?
    * Why digital write works !!!!
* How digital write works? what are gpio registers? datasheet walkthrough, and blinky program ! + oscilloscope analysis

## Session 2/3 (Reinveting the wheel 'Servo.h')
* how servos work
* digitalWrite() Delay() PWM for testing it it is real ?
* WHats the problem ? :: blocking !!!
* timer interrupts
* how to generate PWM with exact timings and for any pin !!! (reinventing the AnalogWrite)
* What are timers ? datasheet walkthrough
* timer code and testing (on scope if possible as well)
* reinveting the servo lib "myServo.h" with just a bunch of functions !


## Session 4/5/6 (From IDE to TextEditor + terminal !)
* under the hood of setup() and loop()
* the compilation process
* compiling a program
* avrdude + bootloader + usb to tty chip 
* linking "servo.c" + path of "servo.h"
* make (automating the compilation upload process)
* now you have your ide !!!
* note about the arduino setup code and how it enables certain functions


## session 7 (Things to checkout in the datasheet, moving to STM ,Resources, the different paths of embedded)
