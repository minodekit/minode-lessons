## Lesson 03-03 Optical control lamp

- Duration: 10 minutes
- Difficulty: Beginner

### Introduction

This lesson we'll learn how to use the Light sensor. The Light sensor can be used to sensor the ambient light. We can use the ambient light level to adjust the RGB LED brightness.



> NOTE
>
> Please make sure the dial switch on the Light sensor should be switched to "A"

### Materials

| Item | Component           | Quantity |
| ---- | ------------------- | -------- |
| 1    | Micro:bit           | 1        |
| 2    | Connect Board       | 1        |
| 3    | RGB LED module      | 1        |
| 3    | Light Sensor module | 1        |
| 4    | USB Micro-B Cable   | 2        |
| 5    | E-brick Cable       | 1        |

### Electronic Circuit

First we need to build the electroic circuit.

> **TODO**
>
> [Software Team] Insert the electronic picture

![dfsd](./_image/lesson-03-01/electronic_circuit.png)

| Sensor Module ID | Connect Board Connector ID | Micro:bit Pin ID | Signal Type |
| ---------------- | -------------------------- | ---------------- | ----------- |
| RGB-LED#1        | D15                        | pin15/pin16      | Digital IO  |
| Light Sensor#1   | A0                         | pin0             | Analog IO   |

### Create Code

#### Step 1: Get the ambient light level

 ![dfsd](./_image/lesson-03-03/get-light-level.png)

There're total 5 ambient light levels with one being the highest level and five being the lowest level.

#### Step 2: Optical control lamp

 ![dfsd](./_image/lesson-03-03/on-light-change.png)

### Interaction

> **TODO**
>
> [Software Team] Add a vedio

### What next

> **TODO**
>
> [Software Team] Add exercise

### Reference

- [Potentiometer](https://en.wikipedia.org/wiki/Potentiometer)
