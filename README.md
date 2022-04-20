# IR Colour Sensor Array
By [https://github.com/VusumuziDube][Vusumuzi Dube]
Want to make An IR sensor array for a simple line following robot?
This is the tutorial for you!

## Introduction
This is my journey to create my first IR Sensor array and hopefully it will help you young line follower.

## Requirements
Before beginning let me quickly give the requirements of the sensor so we all know what the end result will be as well as why certain design choices were made.
From the problem description, and compatibility requirements we can discern that 

### Multi-Colour detection
the sensor should be able to distinquish between 4 line colours on a white background, In total the sensor should be able to defrientiate between 5 colours.
- <span style="color:black">Black ⚫</span>
- <span style="color:red">Red 🔴</span>
- <span style="color:green">Green 🟢</span>
- <span style="color:blue">Blue 🔵</span>
- <span style="color:white">White ⚪</span>

### 3.3V Outputs and Operation
Requires 3.3 output and idealy 3.3V input. 5V compatibility is recommended, however it should also work at 3.3V

## Parts List
| Checked |             Part            | Quantity |                   Description                  | Link |
|---------|:---------------------------:|----------|:----------------------------------------------:|------|
|         | IR Sensor                   | 3        | Photo Transistor / IR LED Pair                 | [https://www.robotics.org.za/ITR9909?tracking=vUaBcGVoiTrcysntIvEoMY8EaQc3nlEaAzJSIy7qZ7d9tucVpG1GYWE2hHAKGVYS][Here] |
|         | 100K $\Omega$ Potentiometer | 3        | For adjusting the gain of the photo transistor | [https://www.robotics.org.za/B104-100K?tracking=vUaBcGVoiTrcysntIvEoMY8EaQc3nlEaAzJSIy7qZ7d9tucVpG1GYWE2hHAKGVYS][Here] |
|         | 220 $\Omega$ Resistor       | 3        | Current limiting resistor for the IR LED       | [https://www.robotics.org.za/RES-220E-50?tracking=vUaBcGVoiTrcysntIvEoMY8EaQc3nlEaAzJSIy7qZ7d9tucVpG1GYWE2hHAKGVYS][Here] |
|         | N-Channel MOSFET            | 1        | To turn the LEDs on and off                    | [https://www.robotics.org.za/BS170-TO-92?tracking=vUaBcGVoiTrcysntIvEoMY8EaQc3nlEaAzJSIy7qZ7d9tucVpG1GYWE2hHAKGVYS][Here] |
|         | Protoboard* / Veroboard     | 1        | to solder your components to                   | [https://www.robotics.org.za/PROTO5070?tracking=vUaBcGVoiTrcysntIvEoMY8EaQc3nlEaAzJSIy7qZ7d9tucVpG1GYWE2hHAKGVYS][Here]
