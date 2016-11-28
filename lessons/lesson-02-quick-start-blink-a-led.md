# Lesson 02 Quick Start - Blink a LED

- Duration: 5 minutes
- Difficulty: Beginner

## Introduction

Here is a quick start to help you getting start the kit. In this lesson, We'll show you how to use the sensor module step by step.

We'll implement a blinky led using the [Microsoft PXT](https://pxt.microbit.org).

## Materials

| Item | Component         | Quantity |
| ---- | ----------------- | -------- |
| 1    | Micro:bit         | 1        |
| 2    | Connect Board     | 1        |
| 3    | RGB LED module    | 1        |
| 4    | USB Micro-B Cable | 2        |
| 5    | E-brick Cable     | 1        |

## Electronic Circuit

First we need to build the electronic circuit.

> **TODO**
>
> [Software Team] Insert the electronic picture

![Electronic Circuit](./images/lesson01/car-indicators-electronic-circuit.png)

| Sensor Module ID | Connect Board Connector ID | Micro:bit Pin ID | Signal Type |
| ---------------- | -------------------------- | ---------------- | ----------- |
| RGB-LED#1        | D15                         | pin15/pin16             | Digital IO  |


## Create Code

### Step 1: Turn on it!

Let's start by turning on the LED.

Check 1-1: Go to microbit.co.uk to start a new project in the Microsoft Touch Develop editor. Call your new project ‘blink-led’.

> TODO
>
> [Software Team] Add your code here.

Check 1-2: Call the pins library to write a digital pin.

> TODO
>
> [Software Team] Add your code here.

### Step 2: Wait for a while then Turn it off

Then we turn off the LED after a while.

Check 2-1: Call pause function in the basic library to wait 500ms

> TODO
>
> [Software Team] Add your code here.

Check 2-2: Turn off it

> TODO
>
> [Software Team] Add your code here.

### Step 3: Multiple rounds

So far the LED on/off can only play once. Let’s fix that!

Check 3-1: Add a while loop at the start of your code

> TODO
>
> [Software Team] Add your code here.

Check 3-2: Click condition inside your while loop, and choose true so that it repeats forever.

> TODO
>
> [Software Team] Add your code here.

Check 3-3: Drag your code for waiting and displaying an LED inside your while loop.

> TODO
>
> [Software Team] Add your code here.

Check 3-4: Test your project.


## Interaction

> **TODO**
>
> [Software Team] Add a vedio


## What next?

Any challenge or task?


## Reference

- [Microsoft Touch Develop editor]()
- [Microsoft Block Editor source code / picture]()
- [Python source code]()
- [Hex file]()
- [Online code can be imported directly]()
- [RGB LED module - reference manual]()

