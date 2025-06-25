# 🚁 QuadPilot-FC – STM32F411-Based Quadcopter Flight Controller

QuadPilot-FC is a compact, custom-built quadcopter flight controller based on the **STM32F411 Blackpill** board. It uses the **INAV configurator** for real-time tuning and configuration, and integrates sensors like **MPU6050**, **ADXL345**, **BM280**, and **HMC5883** for precise flight stabilization and environmental awareness. The hardware is built using a **zero PCB layout**, making it highly space-efficient and ideal for lightweight UAVs.

---

## 🛠️ Features

- ✅ STM32F411 Blackpill flight controller
- ✅ INAV-compatible firmware and configuration
- ✅ Sensor suite: MPU6050 (gyro/accel), ADXL345 (accel), BM280 (barometer), HMC5883 (magnetometer)
- ✅ PID-based control loop for smooth and stable flight
- ✅ Zero PCB design with direct sensor and ESC connections
- ✅ Minimalistic and lightweight hardware footprint

---

## 🧩 Hardware Used

| Component         | Specification                          |
|------------------|------------------------------------------|
| MCU              | STM32F411CEU6 (Blackpill)                |
| IMU              | MPU6050 (Gyroscope + Accelerometer)      |
| Accelerometer    | ADXL345 (High-precision 3-axis accel)    |
| Barometer        | BM280 (Altitude & pressure sensing)      |
| Magnetometer     | HMC5883 (Compass/heading detection)      |
| ESCs             | BLHeli-S / Compatible 30A ESCs           |
| Motors           | 2205 2300KV Brushless Motors             |
| Battery          | 3S/4S LiPo                               |
| Frame            | 250mm Carbon Fiber (Custom/DIY)          |
| Receiver         | FlySky / FrSky (PPM/SBUS Input)          |

---

## 📸 Preview

<p align="center">
  <img src="images/flight_controller_layout.png" width="600"/>
  <br>
  <i>Zero PCB layout of STM32F411 and sensor suite</i>
</p>

---

## 📚 Documentation

- **[INAV Configurator](https://github.com/iNavFlight/inav-configurator)**
- **[STM32F411 Datasheet](https://www.st.com/resource/en/datasheet/stm32f411ce.pdf)**
- **[MPU6050 Register Map](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Register-Map1.pdf)**
- **[ADXL345 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/adxl345.pdf)**
- **[BM280 Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme280-ds002.pdf)**
- **[HMC5883 Datasheet](https://cdn.sparkfun.com/datasheets/Sensors/Magneto/HMC5883L.pdf)**

---

## 🤝 Contributors

> Designed and developed by [Hariharan S.](https://github.com/HariharanS-22)  
For any questions or collaboration ideas, feel free to reach out!

---

## ⚖️ License

This project is open-source under the MIT License. See `LICENSE` for more details.
