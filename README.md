# Micromouse_SIDER
 Maze-solving Robot Micromouse. The project in collaboration with Embedded Aplication Technology Society (EATS) and CSULB Institute of Electronic and Electronical Engineering (IEEE). 

# Main Component List
Main Processor: STM32F411CEU6 (Thinking combine with ESP32 for maze solving algorithm for SIDER V2)\n
Driver: Pololu DRV8833 Dual Driver\n
Motor: Polulu Brushed DC Motor Gearmotor 590 RPM 1.3W Incremental 6V (54.45 Gear Reduction Ratio = 617.4 CPR)\n
IMU: MPU6050\n
Sensor: Time of Flight VL53L0X QT

# Current Mouse Configuration
TIM2 + TIME5: Encoder Velocity Calculation Counter\n
TIM3 + TIM4: PWM Motor Signal Generation (Aiming for 20MHz for now)\n
\n
Last Updated: 11/14/2024\n
