# Gesture-controlled-Robot-Army-with-NRF24L01-
Arduino Robot Army: Control 4 Robots Simultaneously Using One MPU6050 Transmitter &amp; NRF24L01
In this project, we are going to build an Arduino-based Robot Army using NRF24L01 wireless transceiver modules. Instead of controlling each robot individually, we'll use one transmitter to broadcast movement commands to all four robots simultaneously.
The transmitter uses an MPU6050 accelerometer and gyroscope to detect hand movements and tilts. An Arduino Nano processes these movements and sends commands wirelessly using an NRF24L01 module. Each robot has its own Arduino Nano, NRF24L01 receiver and motor driver.
