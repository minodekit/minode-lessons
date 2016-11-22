## Lesson 3.5 Robot

- Duration: 10 minutes
- Difficulty: Beginner

### Introduction
Speaker

### Materials
| Item |     Component          | Quantity |
|--------|---------------------------|-------------|
|    1   | Micro:bit                   |        1      |
|    2   | Connect Board          |        1     |
|    3   | Speaker module       |        1     |
|    4   | DHT11 module         |        1     |
|    5   | PIR module               |        1     |
|    6   | Mini Fan module      |        1     |
|    7   | USB Micro-B Cable   |        2     |
|    8   | E-brick Cable            |        1     |

### Electronic Circuit
First we need to build the electroic circuit.
![dfsd](./image/lesson01-switch/electronic_circuit.png)

| Sensor Module ID | Connect Board Connector ID | Micro:bit Pin ID | Signal Type |
|------------------|----------------------------|------------------|---------------|
| Speaker#1        | A0                         | pin0               | Analog IO  |
| Mini Fan#1        | A1                         | pin1              | Analog IO  |
| PIR#1                | D13                       | pin13            | Digital IO   |
| DHT11#1          | D15                       | pin15            | Digital IO   |


### Create Code

#### Step 1: 添加获取温湿度的模块！
 ![dfsd](./image/lesson35-Project/button-dht11.png)
按下按键A可以获取当前的温湿度值。

#### Step 2: 温度控制风扇！
 ![dfsd](./image/lesson35-Project/button-dht-fan.png)
当温度大于一个设定的值（23摄氏度）的时候电机开始工作。

#### Step 3: 添加PIR模块！
 ![dfsd](./image/lesson35-Project/button-dht-fan-pir.png)
当人靠近的时候LED矩阵会显示一个笑脸。

#### Step 4: 添加警戒模式！
 ![dfsd](./image/lesson35-Project/guard.png)
警戒模式下当人靠近的时候LED矩阵会显示一个×的图形。

#### Step 4: 添加扬声器模块！
 ![dfsd](./image/lesson35-Project/speaker.png)
警戒模式下当人靠近的时候LED矩阵会显示一个×的图形,同时扬声器发出声音。

### Interaction

> TODO:Add a gif/video/pic

### What next
> 

### Reference
- 