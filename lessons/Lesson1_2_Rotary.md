## Lesson 1.2 手动调节灯的亮度--Rotary的使用

- Duration: 10 minutes
- Difficulty: Beginner

### Introduction
RGB灯的亮度可以通过调节RGB三个灰度值的大小来设置。

### Materials
| Item |     Component          | Quantity |
|------  |-------------------          |----------    |
|    1   | Micro:bit                   |        1      |
|    2   | Connect Board          |        1     |
|    3   | RGB LED module      |        1     |
|    3   | Rotary LED module  |        1      |
|    4   | USB Micro-B Cable   |        2     |
|    5   | E-brick Cable            |        1     |

### Electronic Circuit
First we need to build the electroic circuit.
![dfsd](./image/lesson01-switch/electronic_circuit.png)

| Sensor Module ID | Connect Board Connector ID | Micro:bit Pin ID | Signal Type |
|------------------|----------------------------|------------------|-------------|
| RGB-LED#1        | D15                         | pin15/pin16             | Digital IO  |
| Rotary#1        | A0                         | pin0             | Analog IO  |

### Create Code

#### Step 1: 通过按键调节RGB灯的亮度!
 ![dfsd](./image/lesson02-Rotary/button_light.png)
通过按键A控制RGB灯的亮度，一共有5档，循环控制灯的亮度。

#### Step 2: RGB亮度自动变化！
 ![dfsd](./image/lesson02-Rotary/light_change.png)
RGB灯每隔一秒钟切换一种亮度，从最亮到最暗一共四个档位，依次循环。

#### Step 3: 获取电位器旋转的百分比!
![dfsd](./image/lesson02-Rotary/get_rotary_percentage.png)
这种方法可以获取当前电位器旋转的百分比并显示出来，这个方法会返回0到100的值。

#### Step 4: 通过旋转电位器来调节灯的亮度！
 ![dfsd](./image/lesson02-Rotary/on-rotary-change.png)

### Interaction

> TODO:Add a gif/video/pic

### What next
> 实现按键A控制RGB灯的亮度变高，按键B控制灯的亮度变低。

### Reference
- [Potentiometer](https://en.wikipedia.org/wiki/Potentiometer)
