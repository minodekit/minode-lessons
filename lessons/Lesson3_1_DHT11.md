## Lesson 3.1 获取当前的环境温度

- Duration: 10 minutes
- Difficulty: Beginner

### Introduction
DHT11温湿度传感器可以获取当前环境下的温度和湿度。

### Materials
| Item |     Component          | Quantity |
|------  |-------------------          |----------   |
|    1   | Micro:bit                   |        1      |
|    2   | Connect Board          |        1     |
|    3   | DHT11 module          |        1     |
|    4   | USB Micro-B Cable   |        2     |
|    5   | E-brick Cable            |        1     |

### Electronic Circuit
First we need to build the electroic circuit.
![dfsd](./image/lesson01-switch/electronic_circuit.png)

| Sensor Module ID | Connect Board Connector ID | Micro:bit Pin ID | Signal Type |
|------------------|----------------------------|------------------|-------------|
| DHT11#1        | D14                         | pin14             | Digital IO  |

### Create Code

#### Step 1: 
 ![dfsd](./image/lesson31-DHT11/button-get-temperature.png)
通过按下按键A获取当前的温度。

#### Step 2: 当DHT11的温度发生变化时提示！
 ![dfsd](./image/lesson31-DHT11/dht-event.png)
当检测到温度发生变化的时候，LED矩阵会显示数字1。

### Interaction

> TODO:Add a gif/video/pic

### What next
> 获取当前环境的湿度(华氏温度)。

### Reference
- 